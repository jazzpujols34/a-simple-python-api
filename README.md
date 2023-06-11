# Simple API App

This is a simple API application developed using Flask. It currently supports two endpoints, /get-user/<user_id> for retrieving user information and /create-user for creating a new user.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

## Prerequisites

The project requires Python3 and Flask. Make sure you have them installed on your system. If not, follow the instructions here to install Python and then install Flask using pip:

```
pip install flask
```

## Installation

Clone this repository to your local machine using:

```
git clone https://github.com/jazzpujols34/a-simple-python-api.git
```

(Replace 'username' with your actual GitHub username)

## Navigate to the project directory:

```
cd simple-api-app
```

Run the application:

```
python main.py
```

The app will be served at http://127.0.0.1:5000/.

## Usage

The application currently supports the following API endpoints:

### GET /get-user/<user_id>

This route is used to retrieve user information. Replace <user_id> with the actual user id.

You can also pass an optional extra query parameter to this route to receive additional user information. Here is an example:

```
http://127.0.0.1:5000/get-user/1?extra=someExtraInfo
```

###POST /create-user

This route is used to create a new user. Send a POST request with a JSON body containing the user details.

Here is an example using curl:

```
curl -X POST -H "Content-Type: application/json" -d '{"user_id":"1", "name":"John Doe", "email":"john.doe@example.com"}' http://127.0.0.1:5000/create-user
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Contact

If you have any questions, feel free to contact me.