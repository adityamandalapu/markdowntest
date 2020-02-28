#                                         **OnBoarding Documentation**
---------

###Downloading and installing Eclipse


Download the eclipse going to the following [link](https://www.eclipse.org/downloads/)

please download the latest version of eclipse 
<p>
![new version of eclipse 2020](./tree/master/images/eclipse download.jpg)

### Downloading Java 8 JDK

Download the JAVA 8 JDK from the flowing [link](https://www.oracle.com/java/technologies/javase-jdk8-downloads.html) based on your operating system

please find the below image and click the desired 

![JAVA 8](./tree/master/images/java download.jpg)

### Downloading and Installing Maven
 
Download the maven 3.3+ from the following [link](https://maven.apache.org/download.cgi)

Downlaod the latest version of the Maven from the above link at the time of writing 3.6.x is the latest one as preovided below

![Maven download zip ](./tree/master/images/maven download.jpg)

Once The download is done extract the maven and place it in any of the local folder 

![Maven Extract](./tree/master/images/Maven Extract.jpg)

<p>
Once the extract is done go to the Environment variables to add the Maven to the path for us to run the Maven form command line

for the environment variables goto Control Panel -> System and Security -> System -> Advanced System settings -> **Environment Variables**

![Env variables](./tree/master/images/Env variables.jpg)

<br/>

![Env path](./images/env path.jpg)


Add the Maven home into the System Variables add the same path   

![Maven System Variables](./images/maven home.jpg)      
  
    
    
    
    
    
### Installing Google Formatter

Download the google formatter xml file from the following [link](https://github.com/google/styleguide/blob/gh-pages/eclipse-java-google-style.xml)     


In the eclipse go to the window -> preferences -> java -> code style -> formatter -> import -> add the xml file you saved on the local and hit apply      

    
![Google Formatter](../tree/master/images/formatter.jpg)      

          
![Google Formatter XML](./tree/master/images/formatter xml.jpg)      



### Git Flow in Eclipse

for git goto File -> import -> projects from git (with smart import) -> clone URI -> Enter credentials -> select branch -> hit finish


![Git prespective](./images/git import.jpg)   

![Git clone](./images/git clone.jpg)


![Git branches](./images/git branches.jpg)


<br/>
Here slect the branch you want to import intially here we are using the one feature branch to import to the local

![Git Branch select](./images/git branch select.jpg)


<br/>
Here slect the branch you want to import, here we are using the master branch to import to the local

![Git Location Destination ](./images/git local destination.jpg)   

<br/>

![Git  Final Import](./images/git final import.jpg)

The above steps would have imported the project to the local git successfully.  


<br/>
<br/>
<br/>

to commit the code right click on the project and hit commit, it should open a new window saying git staging

 <img alt ="git commit in eclipse" src="./images/git commite.jpg" width = 600)    />
 
 <br/>
 
 In the staging add the file you want to be pushed to the repository and enter the commit message and hit commit and push 
 
 <img alt ="commit screen" src="./images/git commit push.jpg" width = 600) />
 
 
 <br/>

### JUnit test in eclipse
 
 To run a JUNIT test right click on the testclass -> run as -> JUnit test
 
 
 <img alt ="JUnit test run" src = "./images/junit test.jpg" width = 600/>
 
 <br/>
 
 After running the test the output shows what test failed and passed along with failure trace.
 
 <img alt= "Junit Sucess " src="./images/test sucess.jpg" align="Auto" width = 700>
 <img alt= "Junit failure " src="./images/test sucess2.jpg" align="Auto" width = 700>
 
 <br/>
 <br/>
 
 
### Adding more required tools from Eclipse MarketPlace
 
 To goto the eclipse market place  goto Help -> Eclipse Marketplace
 
 The above will open a new windows and search for the following tools 
 
 * **EclEmma**
 * **Spring tools**
 
 <img alt ="" src ="" align= "" width =/>
 <img alt ="Elcipse market place" src ="./images/eclipse market.jpg" align= "Auto" width =500/>
 
 Search for the required tools and click install to add them to the eclipse
 <br/>
 
 <img alt ="EclEmma Tool" src ="./images/eclemma.jpg" align= "Auto" width = 500/>
 
### Eclipse Codecoverage using EclEmma

Once the EclEmma has been installed we will have a option to see coverage as in eclipse

right click on project -> coverage as -> JUnit test

<img alt ="Code coverage option location " src ="./images/coverage option.jpg" align= "Auto" width = 500/>
<br/>

when the coverage is run successfully it will show the percentage of the code our test has covered and it is highlighted in green and the code that hasn't covered is highlighted in red as shown in the below 


<img alt ="Coverage output" src ="./images/coverage output.jpg" align= "Auto" width = 700/>

<br/>

** The code coverage should cover atleast 70% of the code **
 
 
