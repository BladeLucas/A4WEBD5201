# README

This is the Readme document for Lab 4 of WEBD 5201, creating a CRUD application for Ruby on Rails.

This site contains minimal design and functionality. There is a main screen that displays each task with its name and
description in a card. Each task is divided into an individual card on screen. Below each card is the option to open
the task in a new window in order to edit or delete it. At the top of the page is a "login" and "new task" link. the
new task link brings you to a new page to create a new task, the login link brings you to the login screen. There is
also an error space below the login and new task button, where error messages will display when appropriate.

On the "New Task" screen, the interface is fairly straight forward. Enter the name of the task and the description and
press enter, you will be redirected to the "Show Task" screen and the task will be populated in a new card on the home
screen. There is also a button to return to the previous screen if you wish to cancel the creation process.

The "Login" screen is also straight forward. Enter your username and password in order to be authenticated and logged in.
The auhentication process currently serves no purpose, but it is there as an extra feature as outlined by the lab.

The "Show Task" screen allows you to see the full task, as well as additional options, such as deleting and editing the
task. If you choose to edit the task, you will be taken to a screen similar to the new task screen, where you can edit the
existing information of the task. When finished, hit "Update Taks" to submit, or "Back to Tasks" to cancel. "Destroy this task"
will do exactly as you would think, the task is instantly deleted.


Resources:
 - https://dev.to/kjdowns/creating-a-user-login-system-ruby-on-rails-2kl2