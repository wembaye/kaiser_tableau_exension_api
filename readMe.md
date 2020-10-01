# Demo for filtering range data set using tableau extension api 

This is a simple demo to show how to use tableau extension api when working with our web application. Here I integraged my web application with tableau dashboard inorder to filter a rande of data set by date. I used superstore data set across European countries. More specifically, I filtered sales by European super stores by date. 

The following are the steps to perform the task.

# Step 1: 
sign in to your glitch account if you have one, otherwise, sign up in order to create project in glitch. Use the link below for this procedure.
https://glitch.com/

# Step 2:
Open a new project in glitch. After you sign in, on the top rigt corner, you will find new project feature on the left side of your profile account.

Click it and it will ask you to choose a template and which I personally prefer the first choice from the list. After that it will open new project with three most importance files such as script.js, style.css and index.html. You can copy and past mine which I have it here. And you can edit them to suit your preferences as well. 

Add a new file trex file in the project using New File button found on the top left corner. Similarly, I have added mine with file name MyExtension.trex. You can sill use it but make sure you change the URL under source-location tag based on the server you run your project. There is show button in the top right corner. Click it, and choose open in new window and take the new opened window URL and put it in the url under source location tag of your own.

N.B: keep the url of your windon where your application is running for later use in the tableau dashboard. 


# Step 3:
Go to tableau online (https://sso.online.tableau.com/public/idp/SSO) and open an account.

Once, you sign in, Go to settings on the bottom left corner. Click extension tap and add the url that you kept from step 2.

Uploading data set: Go to create tap under Home. Click worksheet and it will take you to connect to data page. Click files tap and you will see upload from computer tap. Go ahead and upload the excel file you saved in your local computer. You can use my exel data set which is avaiable here.
make sure the sheet name is the same as the name of file that you use in the script file where data filtering functions are getting executed. 

Drag and drop orders to the "Drag tables here section" once the excel file is uploaded. Put sales on the row and Date on the column area of the table.

creat a dashboard. Go to new dashboard tap in the botton left corner which is near the sheet name of the data set. Drag and drop the data set in the dashboard. Again drag and drop extension below the data set in the dashboard. You will see wizard with choose extension after that. Click my extension tap and navigate toward the location where you keep the trex file. Open the trex file and click allow to open in case it ask. You will see the project running in the dashboard.


# Step 4:
Go back to project you opened in step 2.

in the index.html file, we have two script files.

Use the first to write a function for filtering the data within any date range you wanted. See mine, which filters sales and show only between 2020 and 2019.

Use the second script to add the latest version of tableau extension. Use mine if that is the latest. Otherwise, refer to the tableau documention to find the new one.

# Step 5:

Finally, refresh the dashboard the you created in step 3. You will see the result.