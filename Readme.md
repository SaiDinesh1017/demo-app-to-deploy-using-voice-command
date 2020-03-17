# About this Project

### Project Description
Demo application which is deployed using jenkins through voice command

### To Run Jenkins using Docker 
Once the local jenkins setup is done it will create a config folder and saves all the history of Jenkins. 
This helps saving our jenkins history. No need to maintain jenkins instance locally running continuously.
The config folder backs up your history and will be used during restart
```
./script_to_run_jenkins.sh
Go to --> http://localhost:8080 to login your local jenkins instance
```
### Jenkins file configuration
```
Use Jenkins file in the classpath to configure your Jenkins Job to deploy the application in PCF
```

### Pre-Requisites before running Jenkins Job
* You have create credentials in your Jenkins to access github and PCF

### Future enhancements
* Either by using microsoft bot sdk or by other frame works will create a process
to deploy the app using voice commands
