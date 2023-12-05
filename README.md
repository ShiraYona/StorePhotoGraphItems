# Welcome to my Shop for photography accessories store
# How to use my project:
In order to run this project you need:
DB- SQL server. 
VS 2022 version (and on). 
.net 6 (and on).

For creating the DB, you can use code-first abilities. All what you need is: 
Open your package manager console, 
Write: 
add-migration [DataBaseName]
and then:
Update-DataBase. 

And the DB is ready for use!

# about my project:
The project represents a Shop for photography accessories. It includes a login page, when the user gets an option of registering in case of new user. After a successfuly login, you  getting into the store. In the store page you can add products to your cart, that is saved in the session storage. There is an option of filtering the products that you see using category, words from product description, minimum price or maximum price as parameters. You can click and go to your cart page, where you can see your cart, remove products from it, and save your order, and you can update youre details. 
my project in .net6,wrriten by web API .net core and follows the REST architecture principles.
i used SQL server database.
i used ORM of Entity Framework by database first.

i have maintained password strength using the nuget package zxcvbn-core.
the struct's project made from layers who connect between them with Dependency Injections, in order to earn  the advantages of the DI as making the application more encapsulated and flexible,
Enables parallel development, decoupling between the class and its dependencies.
i used Asynchronous function for adding Scalability.
i have a swagger that describes our project structure, if you want to, you can use it by the rout:"localhost:[PORT NUMBER]/swagger" and see everything documented neatly.

i used DTO's layer for in order of preventing circular dependency.

the project maps the objects using package AutoMapper.
i used configuration files for savig sensitive and unconstant data.
i keeped on logging. the Logger send  an email if exception or error accures
i also created middlewares for Handling errors and Raiting. 


MiddleWares: I wrote 2  middleWares for the project, 
one that puts each request details in the DB -Raiting, 
and another which is in charge on error handling, as is written beneath.

Validation and error handling: I used entity validation. The errors are written to the log, and the user gets just an internal error.


Wishing you a pleasant and useful use
                                     
                 Shira







