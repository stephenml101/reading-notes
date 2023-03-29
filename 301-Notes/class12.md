# CRUD Notes

[Status Codes Based On REST Methods](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)

1. In your own words, describe what each group of status code represents:

- 100’s = The header part has been received
- 200’s = Success! Their request was accepted
- 300’s = This area isn't accepted, you should go here.
- 400’s = I can't do that at all
- 500’s = There's too much data! ERROR ERROR!

2. What is a status code 202?

- This code tells the client that the request was valid, but its processing will finish sometime in the future.

3. What is a status code 308?

- This tells the client to use another URL to access the resource and not use the current URL anymore.

4. What code would you use if an update didn’t return data to a client?

- 204 No Content

5. What code would you use if a resource used to exist but no longer does?

- 410

6. What is the ‘Forbidden’ status code?

- 403

[Build A REST API With Node.js, Express, & MongoDB - Quick](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw)

1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?

- So that it pulls from our local database

2. What is middleware?

- A software that allows different applications to communicate with each other.

3. What does app.use(express.json()) do?

- Let's our server accept json. Parses. 

4. What does the /:id mean in a route?

- Alllows us to have an endpoint that will have access to everything typed after it.

5. What is the difference between PUT and PATCH?

- PUT updates everything every time something new is added, but PATCH allows the info to get partially updated based off of input received.

6. How do you make a default value in a schema?

- Create a variable so that we can set objects in the schema with default values

7. What does a 500 error status code mean?

- The server encountered an unexpected condition that prevented request fulfillment.

8. What is the difference between a status 200 and a status 201?

- 200 means that the request was successfully received and processed. 201 means the request was successful, and resource  was created.