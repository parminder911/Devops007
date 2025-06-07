# Jenkins-DevOps-Demo




#Jenkins-DevOps-Demo 🚀

#Overview

This repository showcases a DevOps project where I set up and configured Jenkins to automate a simple pipeline. The pipeline executes a basic echo command to print "Devops project on Jenkins". This project demonstrates my understanding of CI/CD concepts, Jenkins configuration, and automation in a DevOps environment.



Project Setup

#Tools Used





Jenkins: For creating and running the CI/CD pipeline.



Java (JDK-17): Required to run Jenkins.



Maven: Configured in Jenkins for future builds.



Node.js: Configured in Jenkins for potential JavaScript projects.



Windows 11: Operating system used for this setup.

Jenkins Configuration





#Installed Jenkins:





Downloaded the jenkins.war file and ran it using Java 17.



Command used: "C:\Program Files\Java\jdk-17\bin\java" -jar D:\Softwares\Devops\jenkins.war



Accessed Jenkins at http://localhost:8080 and completed the initial setup (unlocked Jenkins, installed plugins).



Configured Tools in Jenkins:





Added paths for:





Node.js: For JavaScript-based projects.



Maven: For Java-based builds.



JDK-17: Specified the path to Java 17 (C:\Program Files\Java\jdk-17).



Created a Pipeline:





Created a new freestyle project named 1stMaven-Projeect.



Added a build step to execute a Windows batch command: echo "Devops project on Jenkins".



Ran the pipeline and verified the output.



Pipeline Output

Here’s the output from the Jenkins pipeline:

Started by user Parminderjit
Running as SYSTEM
Building in workspace C:\Users\Devloper\.jenkins\workspace\1stMaven-Projeect
[1stMaven-Projeect] $ cmd /c call C:\Users\Devloper\AppData\Local\Temp\jenkins17020598188466420744.bat

C:\Users\Devloper\.jenkins\workspace\1stMaven-Projeect>echo "Devops project on Jenkins" 
"Devops project on Jenkins"

C:\Users\Devloper\.jenkins\workspace\1stMaven-Projeect>exit 0 
Finished: SUCCESS

![image](https://github.com/user-attachments/assets/252c99f4-8c87-485b-a3bf-cf59bda3d171)

Jenkins Dashboard



Screenshot of the Jenkins dashboard showing the project list.

Pipeline Configuration



![image](https://github.com/user-attachments/assets/04611765-6fde-4cde-8097-a0defee7b3e5)


Pipeline Output



Screenshot of the console output showing the successful run.



What I Learned

Through this project, I gained hands-on experience in:





Jenkins Setup: Installing and running Jenkins using a .war file on Windows.



Java Version Management: Managing multiple Java versions (Java 23, 21, and 17) on the same system and specifying the correct version for Jenkins.



Tool Configuration: Configuring Node.js, Maven, and JDK in Jenkins for future builds.



CI/CD Basics: Creating a simple pipeline to automate a task (echo command) and understanding the build process in Jenkins.



Problem-Solving: Troubleshooting Java version compatibility issues and ensuring Jenkins runs smoothly.



Next Steps





Expand the pipeline to build and test a Maven-based Java project.



Integrate a Node.js project to demonstrate JavaScript automation.



Add more complex stages like unit testing, deployment, and notifications.



Explore Jenkins plugins for advanced features (e.g., Git integration, Slack notifications).



How to Run This Project





Install Java 17:





Download JDK 17 from Adoptium.



Install and verify: C:\Program Files\Java\jdk-17\bin\java -version.



#Install Jenkins:





Download jenkins.war from Jenkins.io.



Run: "C:\Program Files\Java\jdk-17\bin\java" -jar jenkins.war.



Configure Jenkins:





Access http://localhost:8080, unlock Jenkins, and install recommended plugins.



Configure tools (Node.js, Maven, JDK-17) in Manage Jenkins > Global Tool Configuration.



Create a Pipeline:





Create a freestyle project.



Add a build step (Windows batch command): echo "Devops project on Jenkins".



Run the pipeline and check the output.



About Me

I’m Parminderjit, an aspiring DevOps engineer passionate about automation, CI/CD, and cloud technologies. This project is part of my journey to build practical DevOps skills. Connect with me on LinkedIn to discuss opportunities!
