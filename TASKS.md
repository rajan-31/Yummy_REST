## TA Messages

1. .
   This is the code we created in today's class.
   What we want from your side is open it in your system go through it and try to understand whatever we taught you today in the class.
   try to understand the syntax and go through the annotations.
   Try to understand the logic.

Once you feel you are comfortable with this code snippet then try to create an api for Login in CustomerController and on successful login return "user logged in successfully" string.

Have any doubt? -> reach out to us 😊.

Please do it, you gonna need these things in interviews.

*Yummy_REST.zip*

2.
Hello everyone!
I hope all of you have reviewed the logic and looked at the code. Please try to implement the login code. Create an API for login that takes an email and password as input, and on successful login, returns the string: "User logged in successfully."

For this you will have to write a function definition in "Some file" to find a customer by email. Also please add some fields like Address, City, Pincode in the database for customer (Make necessary changes in all the files).

What we want from you is a Github repo. Make commits after each functionality (Like Create Customer, Login etc describe the commit in a proper message). Also its a good practice to make first commit right after initializing the project. Maybe we will be evaluating your codes on the basis of commits too. Try to do this by tomorrow evening after that I will post a new task for you guys.

Hi everyone.

So here is your next task. It might feel overwhelming but trust us its easy and we are providing you most of the code.

1. Encrypt the password in database before storing it.
2. Change login business logic so that we can match user entered password with password stored in database in encrypted format.
3. Implement logic to create JWT token and to return it when user logs in successfully.
4. Authenticate Jwt token in each api such as when user wants to retrieve their information, user wants to update their information or wants to delete their accounts.
5. Create API to delete user account and Update user details except email and password.

To implement these features take reference from my code. You guys will get encryption logic directly and jwt code directly from the attached zip folder.
I have made interceptors which I dont want you to make so ignore that code. To secure an API, what I want from you is, to take JWT token from the client request and create a common function which can validate the JWT token's authenticity and now whenever you wnat to secure a route you can directly call this common function and pass it the token coming from request and check whether the user is authenticated and authorized or not.

so in simple terms ---->
1. function to check whether jwt is valid or not
2. whenever you want to secure an api function, inside the function first you will call this jwt validation function and if jwt is correct you will perform the further business logic.

You will also have to import some dependencies in pom.xml file.
We are only securing the APIs or routes with JWT token which are necessary. Like a new customer want to create account on our website, so there is no need to secure it as a new user who is not in database cant have a JWT token, similarly for login api request we cant have JWT token, as a customer who has not logged in yet will not have any JWT token. Login API will return the JWT token on successful login.

Dont forget to make git commits 😊.

*ESDTestingProgram.zip*

3. .
   Task 2 for backend
   Complete this by the upcoming Saturday's frontend class. You will need these APIs to interact with frontend.
   Also, commit the changes to your repository.
   There is no frontend session on saturday, but complete this task by the weekend

*IMG-20241113-WA0001.jpg*
