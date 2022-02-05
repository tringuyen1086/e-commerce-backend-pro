# E-commerce Back End

### Description

Development of the back end for an e-commerce site using Express.js API, configured to use sequelize to interact with a MySQL database.

### Built With

- [x] Express.js
- [x] MySQL
- [x] Sequelize

### Instruction:

To get started clone this repository using
<br>

```terminal
git clone git@github.com:tringuyen1086/e-commerce-backend-pro.git
```

Both Node.js and MySQL must be installed on your computer.

Install dependencies

```terminal
npm install
```

```terminal
npm install express sequelize mysql2
```

Open up MySQL shell and input

```terminal
source db/schema.sql
```

and

```terminal
use ecommerce_db
```

Then quit MySQL shell and input the following in your terminal

```terminal
npm run seed
```

to start running application simply input

```terminal
npm start
```

Open up Insomnia core to GET, POST, PUT and DELETE from different routes.

### User Story

> AS A manager at an internet retail company  
> I WANT a back end for my e-commerce website that uses the latest technologies  
> SO THAT my company can compete with other e-commerce companies

### Acceptance Criteria

> GIVEN a functional Express.js API  
> WHEN I add my database name, MySQL username, and MySQL password to an environment variable file  
> THEN I am able to connect to a database using Sequelize  
> WHEN I enter schema and seed commands  
> THEN a development database is created and is seeded with test data  
> WHEN I enter the command to invoke the application  
> THEN my server is started and the Sequelize models are synced to the MySQL database  
> WHEN I open API GET routes in Insomnia Core for categories, products, or tags  
> THEN the data for each of these routes is displayed in a formatted JSON  
> WHEN I test API POST, PUT, and DELETE routes in Insomnia Core  
> THEN I am able to successfully create, update, and delete data in my database

## Project Visual

### From assignment:

![13-orm-homework-demo-01](https://user-images.githubusercontent.com/77648727/115477536-fa67cc80-a1f8-11eb-97e0-f35a8c902d4f.gif)

### See Video Demo

Demo - Creating the schema from the MySQL shell & Seeding the database from the command line & Starting the application's server
[here](https://vimeo.com/673955318/9211c46f06)


https://user-images.githubusercontent.com/71200950/152658231-13292479-0ccb-49c6-81a4-90c606cbf7ae.mp4



Demo - GET routes for all categories, all products, and all tags being tested in Insomnia
[here](https://vimeo.com/673959538/af3fe5989d)



https://user-images.githubusercontent.com/71200950/152658240-800caf46-861d-49d7-ba8f-7f8d0cd6f9dc.mp4



Demo - Get routes fro a single category, a single product, and a single tag being tested in Insomnia
[here](https://vimeo.com/673962576/5250389ea9)



https://user-images.githubusercontent.com/71200950/152658243-14c549bc-22f5-4f5a-93fb-abb98cdfcaac.mp4


Demo - POST, PUT, and DELETE routes for categories, products, and tags being tested in Insomnia
[here](https://vimeo.com/673983538/e0608b8c3d)


https://user-images.githubusercontent.com/71200950/152658342-99b67755-dfda-4102-9654-aecdf77c9d7b.mp4



## References

- [x] [MySQL2 Documentation](https://www.npmjs.com/package/mysql2)
- [x] [Sequelize Documentation](https://sequelize.org/v5/)
