*Please read the **test plan** for further details*

# SimpleUnitTestProject
A simple Selenium c# unit test project with ASP.NET MVC
# Repo link ==> https://dev.azure.com/hmandiv/_git/MVCLifecycle

# Objective
A Test driven development process using Red, Green, Refactor and repeat cycles. 
Build a Automated Selenium test framework with selenium webdriver and check if the input box
components of the form in the home page of the web application works the way it is
supposed to. 

The integration test checks that when the form is filled correctly and the
submit button is pressed, the web site redirects the user to the correct destination. 

For this tests project, the system test checks if the user can bypass the form fill up process or not
to reach the Success page. As the function of the web application is to have a user fill out
a form and only upon successful completion of the form the user can get redirected to a
success page. 

The scope of this project is very limited, the only web browser it will be
tested on will be Chrome version 74.0.3729.169 (official build)(64-bit).(Therefore the
chrome webdriver used in selenium will be chrome driver version 74.0.3729.6). All the
tests are run against the production website for this project, as my development, staging
and production sites will basically be the same.
