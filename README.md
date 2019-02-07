# Politico


Politico is a platform which both the politicians and citizens can use. It enables citizens give their mandate to politicians running for different government offices while building trust in the process through transparency. 



Getting started
--------------------
1. Clone this repository
```
https://github.com/exdus/Politico
```

2. Navigate to the cloned repository

Pre-requisites
----------------------
1. Python3
2. Flask
3. Postman

Installation
---------------------------------
1. Create a virtual environment
```
    virtualenv -p python3 venv
```

2. Activate the virtual environment
```
    source venv/bin/activate
```

3. Switch to 'develop' branch
```
    git checkout develop
```

4. Install requirements
```
    pip install -r requirements.txt
```

Run the application
---------------------------------
```
    python3 run.py
```
Test the following api endpoints using postman
-----------------------------------------------

| Endpoint | Functionality |
----------|---------------
/api/v1/party             | POST    | Create a party record
/api/v1/party/<party_id>  | GET     |Fetch a specific party record
/api/v1/party/<party_id>  | PATCH     |Edit a given party record
/api/v1/party/<party_id>  | DELETE  |delete a specific party record
/api/v1/parties           | GET	    |Fetch all party records
/api/v1/office            | POST	|Create a political office 
/api/v1/ office/<office_id>/|GET    | get specific office details
/api/v1/ offices          | GET	    |View all political offices
/api/v1/signup            | POST    |sign up for an account
/api/v1/signin            | GET     |sign into the api


	
Contributors
-----------------------------
Bunei



Acknowledgements
--------------------------------
#nbo-37
Andela community
