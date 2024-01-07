 [Important to Know] :
    Make sure to run the API seperately (In the seperate console or run it seperately) other-wise you may run into problems.
    or Just paste this in the console  [ >> python RestApi.py ] 

    You can Update and Delete the data via clicking on the Rows of Preview Window.

    To install requirments.txt   : >>  pip install -r requirements.txt
  
1 - IMPORT research.py
2 - Change /config.php accordingly.
3 - It is strongly advised that you add a Virtual Host to this project. 

For Demo

admin : user = admin@admin.com
	pass = admin@admin.com

faculty: user = atif.khattak@nu.edu.pk
	pass = atif.khattak@nu.edu.pk

student: user = safi@safi.com
	pass = safi@safi.com
+
├───App // Everything related to current application
│   ├─── Class // Holds all class definitions to fetch data as objects from database
│   ├─── Controllers // Contains controllers for all route operations and methods
│   ├─── Data // contains User's images
│   └─── Views // Contains Views for current application 
│       ├─── css
│       ├─── fonts
│       ├─── img
│       ├─── js
│       ├─── partials // Contains all repeated building blocks like head and foot etc.
├─── Core // Contains Framework's core classes like Database and Router definitions etc.
├─── Docs // Contains documentation
└─── vendor // Contains libraries included through Composer
