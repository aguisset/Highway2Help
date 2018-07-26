Author: Abdoul W. GUISSET - Julien LAFARGUE

Development of a secure application to assist Alzheimer suffering patients and their helper.

----

How it works:

The application has two different login permissions: one for patient and one for the helper. The patient wear an connected object which monitors in real time his deplacement. Those data are stored in a FTP remote along with the PHP scripts.

This application use PHP scripts to login/register and parse the data gather from the connected object to finally put it into use it in a decision tree.

The ID3 algorithm written in PHP is used for the decision tree.

Input: 
	- Data from connected object
	- Results from a form

Output:
	- A number that indicates if the user is depressed or not
	
To run the project, download the repository and make sure that you have the corresponding Gradle version!

If any problems, comments don't hesitate to label an issue.
