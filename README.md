# Contract Directory

This is a class assignment for my Backend 2 class for the Fall 2023

To run this application you will need to type `node server.js` in the terminal. Then you will see three forms to add, update, and delete contacts. You can use Postman or Thunder client to interact with the api.

## Here are the instructions

### Assignment: Contact Directory

Create a web application using Express.js to manage a contact directory. The application should allow users to add, view, update, or delete contact information. All contact data should be stored in a local JSON file which will act as your database.

#### Requirements

### Setup

- Initialize a new Node.js project and install Express.js.
- Create a new JSON file named contacts.json to store contact information.

### Contact Schema

- Each contact should have the following information:
- Name (required)
- Phone Number (required)
- Email (required)
- Address (optional)

### API Endpoints

- Implement the following HTTP methods:
- GET to retrieve and display all contacts or a single contact by ID.
- POST to add a new contact.
- PUT or PATCH to update an existing contact by ID.
- DELETE to delete a contact by ID.

### Middleware Function

- Create a middleware function that validates the contact data before it reaches the endpoint handlers.
- The middleware should check that the name and phone number fields are provided and are of the correct data type.
- If the data is invalid, respond with an appropriate error message. If the data is valid, pass control to the next function in the stack.

### Validation

- (This can now be handled by the middleware function.)

### User Interface

- Create a simple front- end using HTML, CSS, and JavaScript to interact with your API.
- The UI should have forms for adding, updating, and deleting contacts.
- Display the list of contacts, and allow the user to click on a contact to view more details.

### Error Handling

- Implement error handling to manage cases where a contact does not exist, or the data provided is invalid.

### Documentation

- Include a README file in your project repository explaining how to run your project, and how to interact with the API.

### Submission

Submit the GitHub link of your project repository.
Ensure your repository is public, has a descriptive README, and is well- commented.
