# YOUR PROJECT TITLE
#### Video Demo:  <https://youtu.be/Qz7wligW_WA>
#### Description: So here i have tried to make a sort of e-library where different people
#### from my community and nearby places can access books for free
#### I remember growing up and liking books and i also remember myself from stop buying these books due to #### their price. I feel this software can solve all these problems as this provides an easy way to look #### at books and get them. By sharing these books we as a community can enjot different sorts of #### #### literature(including the poor and less privilaged). We can act as a family and even allow different #### people with common interest to meet. So lets jump into the code
#### app.py: This is the main flask application and specifies different routes and allows for manipulation #### of data , along with performance od checks. Firthermore this allows us to connect to a dataase and 
#### allows easy access of data. This has all neccessary routes and connects the webapp in a way
#### database.db: This is the main sql database and consists of tables with user information and that of
#### books; instead of using a foreign key one can access values of 1 table from another using username
#### as all usernames are unique
#### test.db, trial.db: These are test files made to ret sql functions and try to debug them
#### static: This consists of all images and css used in the file
####  style.css: consisits of stylings of the webpage and is responsible for a centralised size and other a
#### aesthetics
#### templates: consists of all html pages which provide the webapp ther looks
#### browse.html : This file handles function related to browsing and looking at books, here i
#### have used an api to get book covers
#### forgot.html: this is recover password page and asks for username and later connect to app whuch sends
#### otp with mail
####  get_books.html: this is the page where the community can add books
####  index.html: this is the homepage of the website and consists of animations and basic features of ####website this introduces users to the webapp and its purpose
#### layout.html: this is the layout for the entire page and sets up the page and the nav bar
####  login.html: this is the login page of the site and uses post methos to send info
####  message.html: this displays a custom message on screen using jinga
####   new_password: here we can enter the new password incase we forgot it that is after veryfing
#### our credentials using an otp generated with random
#### register.html: this the registrsation page
####   remove.html: this page allows the owner of that book to remove 5har book from the webapp's database
####    rent.html: this is the opp of remove and adds a book to the webpage
####    verify: this is the otp verificarion screen