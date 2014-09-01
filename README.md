Welcome to ClassStalker!

So you're in class and notice a cute girl. You think to yourself, "Wow, what a magnificent specimen."
You watch her the whole class and wonder to yourself, "What the hell is she doing at a school like this!?" 
Class drags on and is eventually dismissed.
You're off to your next class and what the... it's the same girl from before! 
Lightning DOES strike twice!
This program is designed to help/expedite the search in this magnificent beast's name.


"Scan through your classes and see people with similar schedules."




Remember to list python as variable value in your environment!
	Control Panel > System > Advanced System Settings
	In the Advanced tab: Environment Variables
	Under System Variables: Find/click on Path and hit the edit button 
	APPEND the something like the following to your Variable Value text field: ";C:\Python26;C:\Python26\Scripts" or wherever you saved your python installation directory. (Yes, I'm using v2.6)



Dependencies:
	Required:
		mechanize
		BeautifulSoup
		html2text
		easygui (for passwordbox)
	Recommended:
		pip (for easier installation of modules above)
		



PIP installation:
	Save this file to somewhere accessible: https://bootstrap.pypa.io/get-pip.py
	With command prompt point to the destination that has the .py file above.
	Execute "python get-pip.py"

	
Module installation(s):
	Now that PIP is installed, modules can be installed from the command line from running:
		pip install mechanize
		pip install beautifulsoup4
		pip install html2text 
		pip install http://easygui.sourceforge.net/download/version_0.96/easygui_version_0.96.tar.gz


Updates that this project will undergo:
	Inclusion of tarballs, zips, binary exe and source files to ensure module(s) installation.
	Detailed error checking of login failure (currently: crummy exception thrown)
	Argument Handling to surpass prompts
	Won't be limited to 12 courses. (arrays will be created dynamically)
	
Execution:
	With pyhton listed as an evironment variable, classStalker can be run from the command line after pointing to the files destination (or running the run.bat) with the following:
		python classStalker.py



I apologize for the ugly easygui passwordbox that was implemented. I included the import for getpass and have the functional code stubbed out for users whom wish to use that instead. My reasoning was that when used in IDLE or similar IDEs, the password is echoed.
If you wish to use getpass instead of easy box, change the following:

Line 55    "print "Password: ""                                           can be deleted or stubbed  
Line 56    "password = passwordbox("Password: ")"                         can be deleted or stubbed  
Line 58	   "#password = getpass.getpass() #-> echos pass with IDLE"       to      "password = getpass.getpass()" or unstub the first #






Follow me on twitter @zweed4u
	
