# Assignment II - Module 03 - Git And Jenkins

### Make sur to have the jenkins-cli.jar plugin binary by downloading it from the `Jenkins CLI` in the `Manage Jenkins` and make it available in your PATH

## Follow the below steps in order to import and test the project with your own jenkins instance

### First, download the config file from present in the root of the project: `assignmentII_maven_project_config.xml`  

### To Create/import the Job, run one of the following command depending of the way yoiu setup up your server

```sh
java -jar jenkins-cli.jar -s <your server url> create-job <NEW_JOB_NAME> < assignmentII_maven_project_config.xml
# OR
java -jar jenkins-cli.jar -s <your server url> -auth username:password create-job <NEW_JOB_NAME>  < assignmentII_maven_project_config.xml
```

*********************************************
*********************************************
That's All! You should see your newly created job/project in the jenkins Dashboard.
*********************************************
*********************************************
