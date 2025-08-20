## Installing Jenkins

1.sudo apt update  
2.sudo apt install openjdk-21-jdk -y  
3.sudo wget -O /usr/share/keyrings/jenkins-keyring.asc https://pkg.jenkins.io/debian-stable/jenkins.io-2023.key  
4.echo "deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc]" https://pkg.jenkins.io/debian-stable binary/ | sudo tee /etc/apt/sources.list.d/jenkins.list > /dev/null  
5.sudo apt update  
6.sudo apt install jenkins -y  

