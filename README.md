## Data Reliability Module For NOKIA 
---
## Dependecies
	-You must Have Java installed 
	-You must install Mysql 									
	-You must set the password and username in your mysql server to 
		username : root												
		Password : ""											
	-If you have extracted the Zip please make sure that all the 	
	 	files are arranged in the same folder if not please do it	
	  	manually												
---

## Instructions																 
	First Of all after extracting the zip file run either the Launch.sh or .bat 
	(for windows) this will run the application .				     
	Put the path of the folder that contains the xml.gz files when asked .							
	Then the module will run through the files and do his work after finishing 
	the process , a message containing 	the execution time will appear then you 
	have to choose if you want to print the results to the console or to 	 
	pass the result to the dashboard .													 
		-> If you choose the console then the result will be automatically printed 
		and the application will finish   
		-> If you choose the dashboard then several details will be available 
		(See the screenshots):				 
			->The first interface displays each BTS with the number of mesurments sent (%)			 
			->The button "Switch" gives you the possibility to switch the view 			 
			->The button "TreeView" is available when you are in the NE -> %measurments
			modeand it gives you the opportunity to visualize the tree of elements 
			extracted from the files 			
			->The "Save Results" button creates an output folder (if not exists) in 
			the same folder as the module this directory will contain the log file 
			(the result of the application) and then it will be added to the database.
			->The "Load Results" button gives you the possibility to load a log file
			using the date in the same format as mentioned in the text field of the View .					
---	

## Contributors
- Hasbi Hamza <hamza.hasbi@gmail.com> 

---
## LICENSE

Licenced under the [Apache License 2.0] (./LICENSE.md)

