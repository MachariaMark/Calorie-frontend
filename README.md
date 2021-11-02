## Calorie Counter <div dir="rtl">29.10.2021</div>
#### <div dir="rtl">By **The team**</div>

## Description

## Features

As a user of the web application you will be able to:

1. Sign up and log in

## Specifications
| Behavior            | Input                         | Output                        | 
| ------------------- | ----------------------------- | ----------------------------- |
| User visits the app and gets directed to the login page  | User logs in | Directed to the home page | 
If user has no account, they click on `sign up` | User signs up | User is redirected to the profile set up page |
|  Homepage loads | Click `` | User's taken to the alerts page| 
| Homepage loads | Click `` | User's redirected to a page where they can see uploaded posts and a button to post too | 
| Homepage loads | Click `` | User's redirected to a page where they can see health services | 
| Homepage loads | Click `` | User's redirected to a page where they can see uploaded businesses |
| Homepage loads | Click `` | User's redirected to a page where they can see posted authorities in the same neighbourhood |
| Homepage loads | User inputs in the search form and presses enter | Searched results show |


## Getting started
### Prerequisites


### Cloning
* In your terminal:
        
        $ git clone https://github.com/MachariaMark/Calorie-backend
        $ cd neighbourhood-watch

## Running the Application
* Install virtual environment using `$ python3.6 -m venv --without-pip virtual`
* Activate virtual environment using `$ source virtual/bin/activate`
* Download pip in our environment using `$ curl https://bootstrap.pypa.io/get-pip.py | python`
* Install all the dependencies from the requirements.txt file by running `python3.6 pip install -r requirements.txt`
* Create a database and edit the database configurations in `settings.py` to your own credentials.
* Make migrations

        $ python manage.py makemigrations watch
        $ python3.6 manage.py migrate 

* To run the application, in your terminal:

        $ python3.6 manage.py runserver
        
## Testing the Application
* To run the tests for the class file:

        $ python3.6 manage.py test watch
        
## Technologies Used
* Django

## Support and contact details
For feedback contact us through;
* 
* 

### License
[MITlicense](LICENSE) 2021 