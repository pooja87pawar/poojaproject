
stage('Deploy to tomcat ')
{
steps{
sshagent(['3ac6ad91-1b4d-4629-a17b-78d32ed90fe1']) 
sh 'scp -o StrictHostKeyChecking=no */target/*.war ec2-user@172.31.46.4:/var/lib/tomcat/webapps'
}
}
