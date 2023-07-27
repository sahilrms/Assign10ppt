# Assignement 10 pre placement training: <br>
### here are the questions solved in the repository:<br>
**Q.1** Explain Middlewares in NodeJS ?<br>
**Q.2** Why use Express Over NodeJS ?<br>
**Q.3** What are REST API ?<br>
**Q.4** What is the use of MongoDB?<br>
**Q.5**  What is Mongoose and how does it relate to MongoDB?<br>
 **Q.6** Build a Server Using Http Module NodeJS with api endpoints for Getting Products Data<br>

      ‘/’ → send msg as “Welcome to Men & Women Dummy Data”<br>

     ‘/men’ → send 10 products data of men<br>

     ‘/women’ → send 10 products data of women<br>

     ‘/other’ → send response as page not found<br>
**Q.7**  Build a Server that Generate Random Number Using Express
‘/random’ → send random number in response {random:10}<br>
**Q.8** Create a Backend For Counter Web App with Api Endpoint for Managing Counter Using Express<br>

- ‘/’ → send counter data as {counter:counter} <br>
- `/increment` → increment counter by 1 and send in response latest data as {counter:counter} <br>
- `/decrement` → decrement counter by 1 and send in response latest data as {counter:counter} <br><br><br><br>
**Q.9** You are tasked with building the backend for a Todo web application. The application allows users to create, update, and delete tasks in their to-do list with Api Endpoint as mentioned below <br>

**`/`** -->  send all the todos which are created by user <br>

**`/add`** --> to create todo create a middleware to validate user providing all the mandatory input (task), if user doesn't provide task as input send resp as validation failed <br>

**`/update/:id`**  --> to update todo with Todo Id, after updating send resp as {msg:"todo update successfully",data:allTodos} <br>

**`/delete/:id`** -->  to update todo with Todo id, after deleting send resp as {msg:"todo deleted",data:allTodos}
