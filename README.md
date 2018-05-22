#Udacity-Item-catalog-Project
 
 This is a python module that creates a website and JSON API for a list of items in a catalog. Each catagory displays their list of items and also provides user authentication using Google and Facebook. Registered users will have ability to edit and delete their own items. This application uses Flask,SQL Alchemy, JQuery,CSS, Javascript, and OAuth2 to create Item catalog website.

Setting up OAuth 2.0

You will need to signup for a google account and set up a client id and secret.
Visit http://console.developers.google.com for google setup.
Also for facebook : developers.facebook.com/apps




Steps to run this project :

Go to your vagrant environment and ssh into the virtual machine by using the following commands :

$ vagrant up
$ vagrant ssh
Once you have logged into your VM, use the follow command to enter the directory containing the project :

$ cd /vagrant/catalog
Once your in the directory run the following commands to initialise and populate the Database :

$ python database_setup.python
$ python catalogwithusers.py

Once you have run the above commands successfully, you should see a catalogwithusers.db named file in your local directory /catalog

Run the following command to run the app :

$ python project.py

References http://discussions.udacity.com/
