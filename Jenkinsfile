//pipeline{
//    agent{
//        label 'docker'
//    }
//    stages{
//        stage('build Docker Image'){
//            steps{
//                script{
//                    sh 'docker build -t judyassem/docker-react -f Dockerfile.dev .'
//                }
//            }
//        }
//        stage('Run Tests'){
//            steps{
//                script{
//                    env.DOCKER_BUILDKIT = 1
//                    sh 'docker run -e CI=true judyassem/docker-react npm run test'
//                }
//            }
//        }
//    }
//}