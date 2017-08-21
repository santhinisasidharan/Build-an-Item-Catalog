# Build-an-Item-Catalog
This website is made as a part of project 4 of Udacity full stack nanodegree program. This project creates a web application that provides a list of items within a variety of categories in a Restuarant menu as well as provide a user registration and authentication system. Registered users will have the ability to post, edit and delete their own items.

## Pre-requisites
- Python 3
- Vagrant
- Virtualbox
- Google developer account
 Follow [these instructions to install the virtual machine](https://classroom.udacity.com/nanodegrees/nd004/parts/8d3e23e1-9ab6-47eb-b4f3-d5dc7ef27bf0/modules/bc51d967-cb21-46f4-90ea-caf73439dc59/lessons/5475ecd6-cfdb-4418-85a2-f2583074c08d/concepts/14c72fe3-e3fe-4959-9c4b-467cf5b7c3a0).We're using tools called Vagrant and VirtualBox to install and manage the VM. This will give you the PostgreSQL database and support software needed for this project.

## How to run the application?

- Install Vagrant and VirtualBox
- Click on the green color button on repository to clone or download the git repository to your computer.
- Unpack the zip file.
- Open terminal, navigate to the directory and launch the Vagrant VM (vagrant up)
- Run vagrant ssh
- Navigate to RestaurantMenuApplication.py
- Run your application within the VM (python Build-an-item-Catalog/RestaurantMenuApplication.py)
- Access and test your application by visiting http://localhost:5000 locally
- Close the application with 'ctrl+c'
