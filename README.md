This project demonstrates authentation in ejs using JWTs and employs several packages to do the job. Namely they are:
1. jsonwebtoken
2. bcrypt
3. cookie-parser


It is uses express as the server and mongoose and the client to talk to mongodb database.

The project does the following:
1. User is able to sign up and if there were any errors in signing up then they are shown on the screen.
2. Once signed up a jwt token is added as a cookie.
3. User is able to login and if there were any errors in logging in then they are shown on the screen.
4. Once logged in a jwt token is added as a cookie.
5. Cookie lifetime is of 3 days.
6. Logged in user can see their email on the navigation bar.
7. Only logged in users can view the /smoothies page which lists out all the smoothies present in the imaginary smoothie shop.

   
