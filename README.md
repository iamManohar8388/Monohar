Import a key file from Jenkins-CI to enable installation from the package:

[ec2-user ~]$ sudo rpm --import https://pkg.jenkins.io/redhat-stable/jenkins.io.key
[ec2-user ~]$ sudo yum upgrade
Install Java:

[ec2-user ~]$ sudo amazon-linux-extras install java-openjdk11 -y
