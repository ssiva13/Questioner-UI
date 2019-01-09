# Questioner-api
It is a crowd-sourcing platform for meetup questions. Questioner helps the meetup organizer prioritize questions to be answered. Other users can vote on asked questions and they bubble to the top or bottom of the log.

## Prerequisites
- Python 3.6.7 
- Postman


## Installation
1. Clone this repository :

	```
    $ git clone https://github.com/ssiva13/Questioner-API.git
    ```

2. CD into the project folder on your machine

	```
    $ cd Questioner-API
    ```

3. Create a virtual environment

    ```
    $ python3 -m venv venv
    ```

4. Activate the virtual environment

	```
    $ source venv/bin/activate
    ```

5. Install the dependencies from the requirements file

	```
    $ pip3 install -r requirements.txt
    $ pip3 install python-dotenv
    ```

6. Run the application

    ```
    python3 run.py
    ```

## Testing API endpoint

| Endpoint                            				| HTTP Verb   | Functionality           			    |
| ---------------------------------------------------- | ----------- | ------------------------------------------ |    
| /api/v1/meetups                  				| POST        | Create a meetup record     			    |
| /api/v1/meetups/<meetup_id>          				| GET         | Fetch a specific meetup record   		    |
| /api/v1/meeetups/upcoming/          		 		| GET         | Fetch all upcoming meetup records          |
| /api/v1/questions                				| POST        | Create a question for a specific meetup    |
| /api/v1/questions/<question_id>/upvote			| PATCH       | Up-vote a specific question        	    |
| /api/v1/questions/<question_id>/downvote			| PATCH       | Down-vote a specific question       	    |
| /api/v1/add_meetups/<meetup_id>/rsvps   			| POST        | Create a question for a specific meetup    |
--------------------------------------------------------------------------------------------------------------------

## Authors
Simon Siva - [Simon Siva](https://github.com/ssiva13)

## License


## Acknowledgement
-Andela Workshops
-Team 1 members
-NBO36
