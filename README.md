About
Easy!Appointments is a highly customizable web application that allows customers to book appointments with you via a sophisticated web interface. Moreover, it provides the ability to sync your data with Google Calendar so you can use them with other services. It is an open source project that you can download and install even for commercial use. Easy!Appointments will run smoothly with your existing website as it can be installed in a single folder of the server and of course share an existing database.

Features
The application is designed to be flexible enough so that it can handle any enterprise work flow.

Customers and appointments management.
Services and providers organization.
Working plan and booking rules.
Google Calendar synchronization.
Email notifications system.
Self hosted installation.
Translated user interface.
User community support.
Setup
To clone and run this application, you'll need Git, Node.js (which comes with npm) and Composer installed on your computer. From your command line:

# Clone this repository
$ git clone https://github.com/elmahico7/easyappointments-modified.git

# Go into the repository
$ cd easyappointments

# Install dependencies
$ npm install && composer install

# Start the file watcher
$ npm start
Note: If you're using Linux Bash for Windows, see this guide or use node from the command prompt.

You can build the files by running npm run build. This command will bundle everything to a build directory.

Installation
You will need to perform the following steps to install the application on your server:

Make sure that your server has Apache/Nginx, PHP and MySQL installed.
Create a new database (or use an existing one).
Copy the "easyappointments" source folder on your server.
Make sure that the "storage" directory is writable.
Rename the "config-sample.php" file to "config.php" and update its contents based on your environment.
Open the browser on the Easy!Appointments URL and follow the installation guide.
That's it! You can now use Easy!Appointments at your will.

You will find the latest release at easyappointments.org. If you have problems installing or configuring the application visit the official support group. You can also report problems on the issues page and help the development progress.

License
Code Licensed Under GPL v3.0 | Content Under CC BY 3.0

