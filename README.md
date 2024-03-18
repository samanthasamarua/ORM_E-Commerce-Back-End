# 13 Object-Relational Mapping (ORM): E-Commerce Back End

## Project Task

Internet retail, also known as **e-commerce**, plays a significant role within the electronics industry, as it empowers businesses and consumers alike to conveniently engage in online buying and selling of electronic products. In the latest available data from 2021, the industry in the United States alone was estimated to have generated the substantial amount of US$2.54 trillion, according to the United Nations Conference on Trade and Development. E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. Due to the prevalence of these platforms, developers should understand the fundamental architecture of e-commerce sites.

Your task is to build the back end for an e-commerce site by modifying starter code. You’ll configure a working Express.js API to use Sequelize to interact with a MySQL database.

Because this application won’t be deployed, you’ll also need to provide a link to a walkthrough video that demonstrates its functionality and all of the acceptance criteria being met. You’ll need to submit a link to the video and add it to the readme of your project.

## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```md
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```
### Usage:

To access the application, follow instructions below:

1. Clone the repository (link below)
2. Estalish Databse Setup: Project requires a database connections and will require user to add MYSQL 2 credentials in environmental variable file (.env)
3. Open Integrated Terminal
4. Type npm I to install all the dependencies:
    "dotenv": "^8.2.0",
    "express": "^4.17.1",
    "mysql2": "^2.1.0",
    "sequelize": "^5.21.7"
5. Source database by typing in mysql -u root -p and enter password. This is followed by SOURCE db/schema.sql
6. seed the database by exiting msql and typing in "npm run seed"
7. Run the server by typing in "npm run watch nodemon"
8. Navigate to Insomnia and test the routes. Refer to the walkthrough video for reference.

### GitHub Repository:

Link: https://github.com/samanthasamarua/ORM_E-Commerce-Back-End

### Walkthrough Video:

Link: https://drive.google.com/file/d/1t0duhyN481H4-9HSlzvZuduiGk7a30mn/view


