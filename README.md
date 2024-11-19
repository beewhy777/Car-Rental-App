

# A Car Rental App with GUI
- App Designed and Developed By: Adebayo Onajoko
- Programming Language Used: Python (Jupyter Notebook Environment)
- Python Libraries Used for building the App: Pandas and Tkinter

Brief Description of the Application:
=====================================
This application is a Car Rental App that was designed to get the amount to be paid to rent a car.
The ability to get the cost of renting a car is made possible by utilizing Pandas library to read from the mycar.xlsx (worksheet of available cars) that has four columns for car brand, model, year and the price per hour to rent the different cars.
The App was developed using Python language in Jupyter Notebook and the Tkinter library was used for the App GUI.

The original look of the App can be seen in the screenshot below:
<p align = "center">
<img src= "https://i.imgur.com/PRRvPJG.png",width="50",height ="50",alt="Original Look"/)
<br/>
</p>

The Steps for using the Car Rental App:
===========================================
To understand how the app functions, select a car brand of “Toyota”, choose the “Sienna” model and the year 2020 ,3 hours of rental, and check the radio button of the comprehensive insurance as a case study.                                                                                                 
 To get the price of the above case study, Click on the "SHOW PRICE” button.
The look of the App after clicking on the " SHOW PRICE” button is shown in the screenshot below:
<p align = "center">
<img src= "https://i.imgur.com/6m1V3zb.png",width="50",height ="50",alt="Before Clicking CONVERT"/)      
<br/>
</p>
In order to get value of a different order - choose a different brand, model, year and number of hours   
and then click the "SHOW PRICE" button or you just click on the "CLEAR" button which clears all the present inputs and the App is then ready for a new set of inputs.

Exception handling feature of the App:
======================================
In addition to reducing the likelihood of errors by having most of the input boxes accept only allowed values through the use of drop-down boxes, the App is also equipped with exception handling features which enables the App to catch exceptions such as entering a non-numerical value into the “No of Hours” box or not selecting an insurance option.							              If a value that is not valid is entered into “No of Hours” box or one fails to select an insurance option,the App would trigger an error message as shown in the screenshot below:

<p align = "center">
<img src= "https://i.imgur.com/0YLCVLC.png ",width="50",height ="50",alt="Invalid or Incomplete Values"/)
<br/>
</p>

Final word on the use of the App:
=================================
It should be noted that the App can only be replicated in its full capacity if the Jupyter Notebook file, the excel worksheet (mycar.xlsx) and all the necessary image files are all in the same directory.The excel sheet can be tailored to include the brand of cars you have in your company,model,year and rental cost per hour for each car.
Also, you can carefully examine the python code and tweak the code to suit your company needs and policy.
