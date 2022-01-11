node 
{
    
 def mavenHome = tool name: "maven 3.8.4"
 
 stage('checkoutCode')
 {
 git branch: 'development', credentialsId: '57232088-2c1f-46bc-88ab-6123fd9c6160', url: 'https://github.com/mss-ec-apps-autogroup/maven-web-application.git'
 }
/*	
 stage('Build'){
 sh "${mavenHome}/bin/mvn clean package"
 }
 
 stage('ExecuteSonarQubeReport'){
 sh "${mavenHome}/bin/mvn clean sonar:sonar"
 }

 stage('UploadArtifactNexus'){
 sh "${mavenHome}/bin/mvn clean deploy"  
 }
 
 stage('DevelopingTomcat'){
 sshagent(['94e97b6e-75d2-4262-8add-44cb4ae4d6cc']) {
    sh "scp -o StrictHostKeyChecking=no target/maven-web-application.war ec2-user@3.110.32.14:/opt/apache-tomcat-9.0.56/webapps/"
	}
 }
 
 stage('sendNotifications'){
     emailext body: '''Build over..

regards 
vamsi reddy''', subject: 'Build over', to: 'rvamshi666@gmail.com'
 }
 */
 
}
