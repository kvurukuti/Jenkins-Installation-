# Jenkins-Installation in AWS Linux Machine:

1. sudo yum update –y

2. sudo wget -O /etc/yum.repos.d/jenkins.repo https://pkg.jenkins.io/redhat-stable/jenkins.repo

3. sudo rpm --import https://pkg.jenkins.io/redhat-stable/jenkins.io.key

4. sudo yum upgrade

5. sudo amazon-linux-extras install java-openjdk11 -y

6. sudo yum install jenkins -y

7. sudo systemctl enable jenkins

8. sudo systemctl start jenkins

9. sudo systemctl status jenkins


Jenkins-Installation in Ubuntu Linux Machine:

1. sudo apt update

2. sudo apt install openjdk-11-jre

3. java -version

4. curl -fsSL https://pkg.jenkins.io/debian/jenkins.io.key | sudo tee /usr/share/keyrings/jenkins-keyring.asc > /dev/null

5. echo deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc] https://pkg.jenkins.io/debian binary/ | sudo tee /etc/apt/sources.list.d/jenkins.list > /dev/null

6. sudo apt-get update

7. sudo apt-get install jenkins

8.sudo systemctl enable jenkins

9. sudo systemctl start jenkins

10. sudo systemctl status jenkins



