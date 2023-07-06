# samplewebapp
# ci/cd pipeline for webapp on local machine.
softwares and tools used : Git , Java , Tomcat , Jenkins , Ant.
> Download Git and Java and install in your system.

![1 JAVA DOWNLOAD](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/c079aff0-9987-4cde-8e37-c3696dbbcd74)

> Configure Java in Environment Variables and System Variables as shown below.
> 
![2 JAVA CONFIGURE_ENV VARIABLE](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/2cc017dd-4553-41c3-8869-ee253085fbdd)
![3 JAVA CONFIGURE_SYSTEM VARIABLE](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/53e7e418-1b5b-403e-9bcc-2c0603bf895b)

> Now Go to Bin folder of Java Installed Path and Copy the path.
> 
![4](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/c402750e-c9de-4572-b826-5e9bdd2665b4)

> Edit Environment varibale and click on path and paste the bin path into it.
> 
![5  PATH](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/80623819-3baf-48d9-bdc3-bf443da7ef44)

> Check your installation and configuration of java.
> 
![6 CHECK JAVA](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/a7b2cf44-5f76-4c92-9262-56d8f097ad45)

> Now Downlaod Jenkins .war file from Jenkins offficial website.
> 
![7 JENKINS WAR DOWNLOAD](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/55dc1a48-e024-4640-8f71-eed4004ce48e)

> Download Tomcat windows service installer from tomcat official webite.

 ![8 TOMCAL DOWNLOAD](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/3435fb76-fff7-47e1-bb41-9094e5af9cc8)

 > While Tomcat installation keep default username and password i.e. admin - admin

![9 TOMCAT INSTALLATION_USER](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/d3d35560-0f4f-41cc-b6d6-7ec05a88dbfb)

> Open the Browser and type localhost:8080 and enter, it will ask for username and password , Put the default one and login to the homepage.

![10 SIGNIN TO TOMCAT AT LOCALHOST 8080 WITH USER](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/b88d2eb9-2559-4248-bfb4-2130a2055104)

> Go to C drive and make a folder called "JENKINSHOME"

![11  JENKINS HOME FOLDER IN C DRIVE](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/82c2b97c-c66a-4e84-bb45-27bc668cb9ce)

> Now Configure Jenkins in Environment Variables.
![12 SET JENKINS PATH IN ENV VARIABLE](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/bb17802e-275a-4902-a599-61c2daeaff69)

> Go to search button on task bar and search for Tomacat Monitor. Click to open it.

![14  CLICK ON MONITOR TOMCAT](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/895552b6-ccef-4592-a9a0-6cf59a80ad89)

> Now Select startup style to Automatic and start the tomcat service.

![13 AFETR RESTART CLICK ON TOMCAT MONITOR AND MAKE IT TO AUTOMATIC AND START THE PROCESS](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/f8ae6e24-4f5f-4680-9798-1cf25c492989)

> Go to Tomcat Homepage and click on manager app. It will ask for user credentials.

![15 CLICK ON MANAGER APP_IT ASK FOR USER](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/c3e43c84-9750-429d-bd02-1be789d325fc)

> Put the credentials and enter into tomcat web application manager.

![16 ENTER TO TOMCAT WEB APPLICATION MANAGER](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/b3c70452-bf06-4b68-a709-e9a1e0d9a85c)

> Put jenkins.war file into the webapps folder which is present in the tomcat installation directory.

![17 NOW PASTE JENKINS WAR IN THE ADDRESS BELOW](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/656eabe5-233d-4abc-bb24-b4e9aaa44f14)

> After this jenkins will show up in Tomcat web application manmager.

![18 JENKINS WILL SHOW UP IN TOMCAT](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/29c49101-f747-4af0-b91a-547fd5550f9f)

> Start the jenkins Service as shown.

![19 START JENKINS SERVICE](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/849706ae-1994-4514-8e74-028dfa6e4b0d)

> Enter localhost:8080/jenkins to enter Jenkins homapage.

![20 LOGIN TO JENKINS HOMEPAGE](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/6bb0ea7d-79b7-4651-aaae-276c02c2caf2)

> Goto the path as shown in the homwpage of Jenkins to find its login password.

![21 COPY THE PASSWORD PATH AND CHECK THE PATH](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/13b330d1-f251-4b3c-9539-fef7dc4146bb)

> In the Secret folder there is Initialadminpassword file. open it with Notepad or Notepad ++ to check the password.

![22 OPEN THIS SECRETS WITH NOTEPAD OR NOTEPAD++](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/1c60ec61-fbc4-4284-bcbf-3c5754aab2ad)

> Copy and paste this password to unlock jenkins and enter.

![23 COPY AND PASTE THE PASSWORD TO LOGIN](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/1e881292-4d72-4649-ac61-a93540c32d52)

> In the customize section click on " select plugins to install " in order to install plugins manually as per our need.

![24 SELECT THE SECOND OPTION TO INSTALL PLUGINS YOURSELF](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/a980f5bf-0692-45ae-95a1-8f7fa5c16921)

> Create username and password.

![25 CREATE USERNAME AND PASSWORD](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/e83f3c71-7784-43f7-8bcd-faa35392fdf7)

> Configure the url for jenkins.

![26 CONFIGURE URL AS PER YOUR COMFORT](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/26402c18-9810-4a4f-afee-909dd57c64d3)

> Now Download Apache Ant (ant.apache .org/bindownload.cgi)

![28 DOWNLOAD ANT BIN ZIP](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/bdd476bb-86c1-41cd-a1a1-469260fa3e60)

> Extract the .zip file into C drive.

![29 EXTRACT THE FILE PASTE IT TO C DRIVE](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/17d4285f-04a6-4a2c-bf44-048c932b927a)

> Configure Ant into the Environment Variable and configure the path also.

![30 CONFIGURE ANT_ENV VARIABLE](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/adc95717-aacf-416c-bc50-9adc593d9134)
![31 CONFIGURE PATH](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/780e0dfe-7019-42e4-a07b-6622b7043b76)

> Download the sample webapp from the address mentioned.

![34 DOWNLOAD SAMPLE WEBAPP](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/cb97f7da-4c45-4ad6-a619-52c1a698db20)

> Clone the webapp to your git directory.

![35 CLONE THE WEBAPP TO YOUR GIT DIRECTORY](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/a3d99b7d-682a-471e-9207-a260ac919e05)

> 4 jobs to be made in jenkins.
> a. Gitpull
> b. Build and code review
> c. Unit Test
> d. Deploy

> Create 1st Job to Pull Code from github. steps are as follows.
> Go to manage jenkins >> Manage Plugins >> search and select "github" >> Select install without restart and save.

![38 GITHUB PLUGIN TO BE INSTALL WITHOUT RESTART](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/d817eae3-1de5-4572-baef-c1db1133bc84)

> Create first job as <githubpull> under freestyle project.

![39 CREATE FIRST JOB-GITHUBPULL AS FREESTYLE](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/d261ccf6-50e3-46b6-bcff-5b2a99fd2211)

> In General Tab go to Advance and put the path under custom workspace.

![40 GOTO ADVANCE_CUSTOM WORKSPACE](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/9963131b-5123-4f2f-89e1-d21f07f74fc0)

> Under Source code management mention the Git url where the sample webapp is stored.

![41 SOURCE CODE MANAGEMENT](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/427b0356-6c75-4044-bba6-3f7ad90e6a81)


> Now install another plugin called "warning next generation" & "Ant-Build tool"

![42 INSTALL ANOTHER PLUGIN_WARNING NEXT GENERATION](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/9ca7d852-ea03-4574-9bcd-d2b984e73364)
![43 ANT _BUILD TOOL PLUGIN](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/dd6b8ad4-49d2-4ef5-953a-6888ddb90075)

> Create the second job as <buildandcodereview> and configure the advance option and source code managemnt option same as we set path in 1st Job.

![44 CREATE SECOND JOB AS BUIULD AND CODE REVIEW](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/90ac7434-5430-4d43-ad5a-192b43aacd60)
![45 SAME BOTH PATH IS TO CONFIGURE AS IN JOB 1](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/da942bd3-4886-4adc-bc65-7e39e34e8cfc)

> Go to option "Add build steps" and select "invoke Ant"

![46 NOW CONFIGURE BUILD TRIGGER](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/1557445c-0db8-4c35-8533-71e728609e31)

> Then Go to "Add post build action and select "record compiler warnings and static analysis results".

![47 POST BUILD ACTION](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/81f9a777-b46c-4844-bbde-af41ab65ca13)

> Select "Checkstyle" in tools options and configure as below.

![48 CHECKSTYLE](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/1183e413-b75c-48a3-a9aa-f4d07bf975c6)

> For the third job we need a plugin called " Junit Realtime test reporter "

. install without restart.

![50 JUNIT REALTIME PLUGIN INSTALLATION](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/66a61cdb-ddd2-4626-a0b0-e2283d89ca8a)


> Its time to create the 3rd Job <unit test> as fresstyle project.

![51 NEW JOB AS UNIT TEST AS FREESTYLE PROJECT](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/967b9e5c-c430-4247-838c-57a22e99798c)

> Configuration of custome directory and source code managemnet path same as prior 2 jobs.

![52 JOB CONFIGURATON](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/cdf1633e-0545-4f8b-acd1-64755cce638f)
![53 SOURCE CODE Path conFIG](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/20ca5fda-c470-464d-b26d-ad83f4b24df8)

> Select build as "Invoke Ant" and target as Junit.

![54 CONFIG BUILD TRIGGER](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/e1b2af58-754c-49f8-8a02-33de7fbf7edc)

> Add post build action as " Publish Junit test result report".

![55 POST BUILD ACTION](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/b19d1d17-24fa-4c6b-8503-84ffd66fe20c)

> Configure Post Build action as below.

![56 POST BUILD ACTION TAKE FILENAME FROM GIT](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/ac5d2371-33b7-46cf-84c6-f9ecad84ce5b)

> If we need to change the Tomcat Port number we can do it going inside the installation directory of tomcat and under "conf" folder ther is a file called server. Edit it with Notepad or Notepad++

![57 GO TO THIS LOCATION AND EDIT WITH NOTEPAD](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/3e5be4d9-1599-496c-8f19-21a8abfb0474)

> Change the port number as shown and save the file.

![58 CHANGE THE PORT NUMBER OF TOMCAT_8080 TO 8090](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/36051f56-8219-4711-af48-718301b9493f)

> Now in the same conf folder there is a file called "tomcat users. Open it with Notepad++

![59 OPEN TOMCAT USERS WITH NOTEPAD](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/a33bb875-93b6-48b2-be6f-54208ba65b3e)

> In the line number 22 add "manager-script,admin" and save it.

![60 EDIT AND ADD THIS](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/3900ae15-4fae-4fbd-bba9-dda1735cdd9d)

> Now for the 4th and last job we have to install another plug-in called " Deploy to Container ". Install without restart.

![62 INSTALL PLUGIN DEPLOY TO CONTAINER](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/243b4fd4-1427-4326-8269-8e0743f40828)

> Create the 4th job as "deploy" under freestyle.

![63 CREATE 4TH JOB NAME DEPLOY AS FREESTYLE PROJECT](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/06696c33-19da-4700-9104-20f19d6ce8bf)

> Configure the custom directory and source code managemnt path same as prior jobs.

![64 CONFIGURE 4TH JOB CUSTOM WORKSPACE](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/397c8eba-08b3-40f9-8742-9d255e4e30f2)

![65 ENTER SOURCE CODE GIT](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/2f4325dd-3c8c-4ac3-85a7-86c6235782f4)

> Select "invoke Ant" in build option and set "war" as Target.

![66 BUILD WITH ANT](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/790379d5-8cae-42c8-a5b7-275ad418e4c7)

> Under Post build action select "Deploy war/ear to a container" and type " **/*.war " inside the War/ear files.

![67 POST BUILD ACTION](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/f3d69901-6f34-41a4-befc-eab5d9827c87)

> Enter "samplewebapp" under context path and Select Tomcat Version inside the Container option and also put the credentials as "Jenkins".

![68 SELECT CONTAINER WITH TOMACAT VERSION AND CREDENTIALS AS JENKINS](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/413b2a9b-eeaa-499e-8e35-5edb3afdd363)

> Add credentials as Jenkins username and password .

![69 PUT JENKINS USERNAME AND PASSWORD ADMIN ADMIN](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/e6d6d104-37a4-4848-ae1f-2f83c86e1259)

>  Under Credentials select "Admin" and mention the changed tomcat URL.

![70 ADD CREDENTIALS TO ADMIN AND TOMCAT URL THEN SAVE](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/87c8eab2-346e-45bb-82bc-e2c260d7cdbf)

> After All these configuration close the jenkins page and restart the tomcat service.

![71 RESTART TOMCAT SERVICE](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/a8680819-8307-4566-bd02-b05636dba485)


> After the creation and configuration of these 4 Jenkins Jobs now its time to build pipeline and fo this we need to install anothe plugin in Jenkins called " Build pipeline ".

![73 NOW INSTALL ANOTHER PLUGIN CALLED BUILD PIPELINE](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/898bfd13-9cc9-49f7-85c8-ba8cf0513c02)

> Now Go to 1st Job created as <githubpull> and configure it going to "Build Environment" tab. Under Post build Actions select "Project to build" and mention the second job name "buildcodeandreview".

![74 CONFIGURE POST BUILD ACTION AS BUILD OTHER PROJECT AND SEARCH FOR NEXT JOB AND SAVE](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/b8031342-e6b0-4e35-a094-4b4a7b7b4f20)

> Similarly Go to 2nd Job and Configure the Post build action as Job 1.

![75 CONFIGURE SECOND JOB TO INVOKE THE THIRD JOB](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/04291ffd-aeb7-40a0-976b-24ccb5efa265)

> Same as under the Job <unittest>.

![76 CONFIGURE 3RD JOB TO INVOKE 4TH JOB](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/ce187757-72d9-4c31-8c34-5b2d0cea1979)

> After finishing this all restart the tomcat service.

![77 RESTART TOMCAT SERVICE AGAIN](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/ef7788b6-898f-407b-a0c6-a429257f1f77)

> Now Login to jenkins.

![78 LOGIN TO JENKINS AGAIN](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/b72e9f71-c5f8-41bb-8450-2a57c2853083)

> Go to the Dashboard and click on + sign.

![79 NOW CLICK ON + SIGN TO CRAETE A NEW JOB AS CREATE PIPELINE](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/2d356ea6-fa11-49d1-8181-9216a8fddc09)

> Create "new view" as <complete pipeline> and select "Buils pipeline view".

![80 NEW VIEW SELECT BUILD PIPELINE](https://github.com/howdycloudyarsh/samplewebapp/assets/133496386/11bd56f6-4f07-4593-b814-788f9fe2c2f7)













