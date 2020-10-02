<h1 align="center"><b>Getting Started With Jenkins</b></h1>

<p align="center">
  <img src="img/Installation of Jenkins & Simple job/jenkins.png" height=300 width=500>
</p>

<p><b><h2>Jenkins</h2> It is a DevOps tool for Continous Integration and Delivery. It is written in Java with its plugins built for Integration purposes. It is Open Source and so available to all the developers they can collaborate easily. </p>

<p><h2>Features:</h2>
<ul>
<li>Easy Configuration</li>
<li>Easy Installation</li>
<li>Available Plugins</li>
<li>Extensible</li>
<li>Easy Distribution</li>
<li>Free Open Source</li>
</ul>

<p><b>Let’s get started by installing Jenkins.
In this tutorial, I will be using Windows OS.

As Jenkins is written in Java, we need to install Java. Go to this link and install JDK for your system: https://www.oracle.com/in/java/technologies/javase/javase-jdk8-downloads.html
<img src="img/Installation of Jenkins & Simple job/1jdk.PNG" height=300>


Let’s copy the location of our JDK as we will need this to set environments variables.
<img src="img/Installation of Jenkins & Simple job/2 jdk in folder.PNG" height=300>

We will add variable as JAVA_HOME and the provide location of the JDK folder.
<img src="img/Installation of Jenkins & Simple job/3 java home env setup.PNG" height=300> 	 


We will check if java is available by typing the command: “java -version” 
<img src="img/Installation of Jenkins & Simple job/4 cmd java installed.PNG" height=300>

Now, let’s move and download Jenkins
https://www.jenkins.io/download/ I have downloaded jenkins.war file
<img src="img/Installation of Jenkins & Simple job/5 download jenkins.PNG" height=300>



Now, you can see that jenkins.war file has been downloaded.
<img src="img/Installation of Jenkins & Simple job/6 jenkinswar file.PNG" height=100>






Now, we will run Jenkins by command: “java -jar jenkins.war”
<img src="img/Installation of Jenkins & Simple job/'7 java start using cli.PNG" height=300>





Move to your browser and type “localhost:8080”. You will see a screen like this. Here, the password asked is available in the location provided in your local machine.
Just go to that location and paste the password here. 
<img src="img/Installation of Jenkins & Simple job/8 passowrd required.PNG" height=300>








Click on install suggested Plugins
<img src="img/Installation of Jenkins & Simple job/9 cusomize jenkins.PNG" height=300>




Jenkins will download all required plugins.
<img src="img/Installation of Jenkins & Simple job/9.1 plugins.PNG" height=300>





Reset your credentials.
<img src="img/Installation of Jenkins & Simple job/9.2 id pass.PNG" height=300>




Now, you are ready to play with Jenkins.
<img src="img/Installation of Jenkins & Simple job/9.3 ready jenkins.PNG" height=300>


Enter Your credentials here to console.
<img src="img/Installation of Jenkins & Simple job/10.PNG" height=300>





You will be having no projects for the first time.
On the left side you can see various features of Jenkins, eg; New Item, People, Build History, Manage Jenkins, etc.
<img src="img/Installation of Jenkins & Simple job/11.PNG" height=300>







Let’s have a walkthrough Jenkins and its features.
In new items, you can see various type of projects can be made in Jenkins.
<img src="img/Installation of Jenkins & Simple job/13.PNG" height=300>




Inside people, you can see all the members you have created and edit their accessibility.
<img src="img/Installation of Jenkins & Simple job/14.PNG" height=300>









Inside Build History, you can check all the build done by you and their sta
<img src="img/Installation of Jenkins & Simple job/15.PNG" height=300>





Inside, Manage Jenkins you can check for System Configuration and security
<img src="img/Installation of Jenkins & Simple job/16.PNG" height=300>


In system configuration, inside plugins, you can check for various plugins
<img src="img/Installation of Jenkins & Simple job/16.1.PNG" height=300>

Status Information, Troubleshooting, and Tools and Actions.
<img src="img/Installation of Jenkins & Simple job/17.PNG" height=300>









Simple Project

In this project, we will just make Jenkins open cmd and run an echo command with the message of Simple Project 1 and build it.







Click on New Item >> Name the project as “Simple Project 1”  >> take the project as Freestyle Project. 
<img src="img/Installation of Jenkins & Simple job/18.1.PNG" height=300>









You can configure the project: 
<img src="img/Installation of Jenkins & Simple job/Simple Project 1 Config [Jenkins]-1.jpg" height=700>
<img src="img/Installation of Jenkins & Simple job/Simple Project 1 Config [Jenkins]-2.jpg" height=700>

You can build the project by clicking the Build Now and then it will start building the project automatically.
<img src="img/Installation of Jenkins & Simple job/ 18.2.PNG" height=300>

You can see that project has built easily.
<img src="img/Installation of Jenkins & Simple job/ 18.3.PNG" height=300>

That’s all! For this module. We will continue learning more cool features of Jenkins in next module.

</p>