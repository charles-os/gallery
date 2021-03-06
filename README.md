# Gllery Application
Application that display images and contains a database 

## Description

by **Charles Osoro**

The user can:

- Register to use the program
- Sign In to his/her profile
- Post images in the profile page
- Like the posted images
- Comment on the posted images

## Setup/Installation Requirements

### Prerequisites

- python3.6
- pip
- Virtual environment(virtual)

### Cloning and running

-Clone  the application using git clone(this copies the app onto your device). In terminal:

           git-clone https://github.com/charles-os/gallery.git
           cd Instagram

-Creating the virtual environment

           python3 -m venv --without-pip virtual
           source virtual/bin/env
           curl https://bootstrap.pypa.io/get-pip.py | python

-Installing Django and other Modules

           python3 -m pip install -r r< module needed >

- Run the application:

           python3.6 manage.py runserver

### Testing the Application

- To run the tests for the class files:

           python3.6 manage.py test

## Technologies Used

- Python 3.6
- Django
- HTML and CSS

## Behaviour driven development/ Specifications

| Behaviour               |       Sample Input       | Sample Output                                        |
| :---------------------- | :----------------------: | :--------------------------------------------------- |
| Sign Up required    |       On page load       | Registration form apperars                 |
| Registration            | Submit regitration form  | User creates an account and receives welcome email   |
| Subscription            | Submit subscription form | User receives email eb=very time there is a new post |
| Post an image          | 'image.jpeg' | Image is posted and appears on profile page |

## Support and contact details

For any questions, troubleshooting or contributions, find me on:

- Email: chaloo56@gmail.com

[MIT LICENSE](https://github.com/charles-os/gallery/blob/master/license)
Copyright (c) {2019}
