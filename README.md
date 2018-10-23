# Flask-app
this app use Flask , sqlalchemy, to make an app that is used to showw restaurants menu that has been added by users

## Introduction
This is a python module that uses information of restaurants in  restaurantmenu.db:



### Functions in tray.py:
* **restaurants()** Connects to the  page identfay user using database and compare hashed passworthat show all restaurant in database .
* **editRestaurants(id):** used to edit restaurants in the data base.
* **restaurantMenu(restaurant_id):** used to show the menu of specefic restaurant.
* **newMenuItem(restaurant_id):** used to add new item in the menu.
* **editMenuItem(restaurant_id, menu_id):** sdit items in the menu and commited to the data base.
* **deleteMenuItem(restaurant_id, menu_id):** delet an item from the menu.
* **resraurantMenuJSON(restaurant_id):** create JASON API for the restaurants in the database  .
* **menuItemJSON(restaurant_id, menu_id):** create JASON API for menu items .
## Instructions
* To run this module succesfully make sure that you install:

*[python](https://www.python.org/downloads/)

*[sqlalchemy](https://www.sqlalchemy.org/download.html)

* or use 'pip install --user (liberary name )'
*in shell comand
## Recommended setup
* Install [vagrant](https://www.vagrantup.com/downloads.html) and [virtualbox](https://www.virtualbox.org/wiki/Downloads) 
* Clone the repository to your local machine:
  git clone [https://github.com/ebishbishy10/log-_analysis-udacity-project.git]
* Start the virtual machine
  From your terminal, inside the project directory, run the command `vagrant up`. This will cause Vagrant to download the Linux           operating   system and install it.
  When vagrant up is finished running, you will get your shell prompt back. At this point, you can run `vagrant ssh` to log in to your     newly installed Linux VM!
       directory, which is shared with your virtual machine.
* Setup Database
  To setup the database use the following command:
  `python database_setup.py;`
* Run Module
  `python project.py`
