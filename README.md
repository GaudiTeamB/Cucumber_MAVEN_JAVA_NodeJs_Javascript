# Cucumber_MAVEN_JAVA_NodeJs_Javascript

Cucumber - Implementing Tests in JAVA using MAVEN Dependencies

1) To  test The Time Measurement Response Front End app using Cucumber(MAVEN) in JAVA, the CucumberTest.jar file has to be unziped under the "%userprofile%/workspace" folder. 

Then you have to open the Java Eclipse IDE to run the Test. But before running the Test, make sure the decompressed CucumberTest folder is included under the user's Workspace folder, assuming JAVA eclipse has already been installed in your machine. If that isn´t the case, to install JAVA eclipse go to the following website: https://www.eclipse.org/downloads/download.php?file=/oomph/epp/neon/R2a/eclipse-inst-win64.exe

2)To install and configure MAVEN, which is the required JAVA framework that includes the dependencies for Cucumber, go to this tutorial and folow the instructions. They provide an outstanding step by step example for beginners; https://www.tutorialspoint.com/cucumber/index.htm

*************************  Cucumber with Javascript and NodesJS ********************************
Prerequisites:
　
1) Git should be installed. If it's not, go to this website to download it, https://git-scm.com/download/win
　
2) nodes and npm sould be installed. In case you need to download nodes(In this case the "nodes_module" folder doesn´t exist), go to this website and then click on window installer, https://nodejs.org/en/download/current/
　
3) the Gulp Server should be installed and configured. In case you need to install it, follow these instructions:
　
   a) Install webpack and gulp: npm install webpack gulp -g 
      b) Download this repsitory from https://github.com/GaudiTeamB/gb-front-end-time-measurent.
      c)) Run: npm install 
      d) Open a command line and run gulp: >gulp 
      e) Open a second command line and run gulp server >gulp server 
      f) You will be able to connect to http://localhost:8080 and see the site.
      g) Press CTRL C and when promted for Yes/No, enter "Yes"
　
 4) Unzip the Cucumber_NodesJS zip file in your Desktop and go to the Cucumber_NodesJS folder
 5) from the DOS Command Prompt, run the command npm install(make sure the package.json file exists). After executing npm install, a folder called nodes_module
   should have been created in the current directory
 
----------------------------------- HOW TO RUN THIS TEST ----------------------------------------
　
Once the prerequisites metnioned above are met, to run the tests, all you have to do is execute the Run_Cucumber_NodesJS.vbs file located under the Cucumber_NodeJS folder.
　
if you have any questions, ask Cris.
