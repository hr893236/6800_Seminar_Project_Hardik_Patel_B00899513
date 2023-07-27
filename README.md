# 6800_Seminar_Project_Hardik_Patel_B00899513

7	CODE AND DEMO
This chapter attempts to deliver the demonstrations of the project within limitations of the documentation. Though sufficient figures and text has been provided to comprehend the moderate understanding of pragmatism of the project.
7.1	Code
Code can be found on below git link, use the pull request [27].
https://github.com/hr893236/6800_Seminar_Project_Hardik_Patel_B00899513.git
7.2	Demonstration
This section is advantageous in case of acquiring how to setup and run the project. For the ease of demonstration single system mode is selected. Below are the steps to setup and run the project. 
7.2.1	Environment
Code is split into four directories inside seminar-project directory. First thing to do is setup the dropbox free account and generate access token and add it into config/config.json file as shown in Figure 7.1 below.
 
Figure 7.1 Dropbox Access Token Add

7.2.2	Setting python path for config module
Add config module path under the variable PYTHONPATH show as below in Figure 7.2.
 
Figure 7.2 Edit PYTHONPATH Variable

7.2.3	Install Python Libraries
Simply go to seminar-project and find the file requirements.txt and run below command to install required libraries to run the code successfully. 
“pip3 install -r requirements.txt”
7.2.4	Run Server and client
Jump to seminar-project/server and run server.py, after which run the client.py at seminar-project/client location. Below Figure 7.3 and 7.4 contains output logs for both.
 
Figure 7.3 Client Terminal

 
Figure 7.4 Server Terminal

7.2.5	Outcome
On the client side two new files should be created – client_data.json and client.log. As for server, five new files should be created – server_data.json, summary.json, statistics.txt, distribution.txt, and server.log. Review below figures 7.5 to 7.9
 
Figure 7.5 Server Output Files

 
Figure 7.6 Client Output Files

 
Figure 7.7 client_data.json Sneak Peek

 
Figure 7.8 statistics.txt Sneak Peek

 
Figure 7.9 distributions.txt Sneak Peek

7.2.6	Upload Files
Go to seminar-project/upload path and execute upload.py which will upload the output files to dropbox for remote access. This program runs in loop with time interval of 3 minutes by default but can be changed though config module editing. Review Figure 7.10 and 7.11.

 
Figure 7.10 Dropbox Upload

 
Figure 7.11 Dropbox Upload

7.3	Summary
Concerning the installation and execution of the project, this chapter have covered all the details and steps. Next chapter brings end to this adventure as we do conclude and provide recommendations for the further enhancements.
