# Offline Messaging API

## API Usage Scenario

- Users should be able to create an account and log-in
- Users should be able to message each other, as far as they know a username of each other
- Users should be able to access all their previous messages
- User should be able to block another user
- Users should be able to access activity logs (login, invalid login, etc)
- Critical errors should not be exposed to users and all errors should be recorded

## API Technical Requirements

- It should be designed using RESTful architecture
- Code should be written according to some common standard/convention
- It should be testable with minimum 5% test coverage

## Notes

- Any data storage solution can be used
- Postman can be used for API test automation
- Front-end client development is not a requirement

## Optional

- Authentication / Authorization can be implemented using any available OpenId / OAuth service provider or self-hosted
- API can be integrated with some available IM client
- API can be deployed to some cloud provider like GCP, AWS, Azure, etc
