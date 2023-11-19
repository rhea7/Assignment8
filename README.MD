## Description:
The application now features Message Bussing and Commands patterns to decouple the presentation layer from the application logic. Commands represent operations, while the Message Bus routes them to the appropriate handlers.

## Dependencies:
This version depends on Flask and SQLAlchemy, along with the base Barky bookmarking application.

## Instructions:
To run the modified application:

Verify Python 3.6+ and pip are installed on your system.
Clone the repository and navigate to the application directory.
Install required dependencies with pip install -r requirements.txt.
Execute python app.py to start the Flask server.
Message Bussing and Commands:
The Message Bus serves as the central point for command dispatching, with handlers for each command type encapsulating the business logic. This architecture enhances maintainability and scalability.

## Testing:
Execute the tests with python -m unittest discover. Tests will validate that the Message Bus correctly handles command routing and execution, aligning with the expected behaviors defined in the service contracts.