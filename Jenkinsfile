pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building your project...'
                // Add build commands or scripts here
            }
        }

        stage('Deploy') {
            steps {
                
                    // Navigate to the deployment directory
                        // Copy files to the deployment directory
                        //sh 'cp -r * /var/www/dev/nodeapp'

                        //sh 'cd /var/www/dev/nodeapp'
                        // Check if the process is running
                        
                        // Stop the Node.js process (if running)
                        //sh 'sudo pkill -f "index.js"'
                        // Start the Node.js process using pm2
                       // sh 'nohup pm2 start index.js &'
            
                

                echo 'Running tests...'
                // Add test commands or scripts here
            }
        }
        stage('Docker image') {
            steps {
                sh 'docker rm -f nodecontainer2 || true'
                sh 'docker build . -t nodejs'
                
                sh 'docker run -d -p 5000:5000 --name nodecontainer2 nodejs'
                
            }
        }

        // Add more stages as needed
    }
}
