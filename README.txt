Step 1: Connect to to the mongodb database, with mongod in the command line, alternatively utilize mongodb compass to setup the connection necessary for the functionality of the web application.

Step 2: For the sample data, open up mongodb compass and import the provided JSON files located inside the "db" folder to their appropriate collections, the names of the JSON files should aid in assigning the file to the collection. First import the connection using the Profdex.json to setup such, then import each json file for the data respective to the collections.

Step 3: Through the command prompt, navigate to the respective directory of the web application (i.e. through "cd" commands in windows) until the surface level has been reached, where folders such as db, views, public, etc. shall be "visible".

Step 4: Run the program through "npm start" in the respective command prompt and go to http://localhost:3000/ in your browser to view and navigate through the webpage upon successful execution of the steps.

Extra: For POST functionalities like creating reviews, editing your "about me" or profile, commenting on reviews, and consequently replying to comments, one must have an account foremost where the lack of such will redirect the user to the login/register page upon an attempt to execute any of the said functionalities have been made. 

Extra: The search bar accepts the full name of the professor with only a single space in between the first and last name, without any excess characters and spaces. Upon incorrect inputs for a professor name (i.e. input does not align with any professor in the database), the user shall be redirected to the homepage where a list of all the professors shall be displayed for the user to find a professor that they may potentially have misremembered or forgotten.
