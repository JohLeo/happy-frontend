### Project Happy Thoughts Frontend - https://happy-mongo-api-jl.netlify.app

**✓ The brief**\
The goal was to build a database, an API and a frontend with react for a Twitter like app, but with more positivity given the name from Technigo - Happy Thougts.

The app has three main functionalities - adding thoughts, listing thoughts, and toggling a 'like' status.

The project was a great opportunity to work on my backend and React skills and bring together the different parts of React and working with fetching and posting to an API. It also included building the backend with Schemas and setting up the API using MongoDB, MongoDB Atlas, Google Cloud and POSTMAN.

Must-haves:\
✔️ The API should implement the given routes exactly.

✔️  The GET /thoughts endpoint should only return 20 results, ordered by createdAt in descending    order.

✔️  The API should validate user input and return appropriate errors if the input is invalid.

✔️  In the POST /thoughts endpoint to create a new thought, if the input was invalid and the API is returning errors, it should set the response status to 400 (bad request).

✔️  The endpoint to add hearts to a thought should return an appropriate error if the thought was not found.

✔️  Follow a given design as close as possible.

✔️  List the most recent thoughts at the top and older thoughts at the bottom (sorted).

✔️  Show the content of the message and how many likes the thoughts have received.

✔️  Have a form to post new thoughts.

✔️  Implement a heart button to send likes on a thought.


**🏔️ The problem**\

Started by looking and understandinig the data structure of the api we've used earlier.
Then tested the endpoints (GET, POST, PATCH) through Postman. 
Had some issues with the PATCH request and needed to look through naming for frontend vs api to solve the issue. Really liked this project since it gave me a good understanding on the correlation between back- and frontend.

**View it live**\

Deployed frontend: https://happy-mongo-api-jl.netlify.app  
Deployed backend: https://project-happy-thoughts-api-7b7pldp75q-lz.a.run.app
