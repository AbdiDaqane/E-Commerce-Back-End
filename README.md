## E-commerce Backend 


# User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

# Acceptance Criteria

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

# Description 

Server-side application for a e-commerce application to manage products. Build with ExpressJS and Sequelize.

# Usage

## Category API
- Get all categories: get /categories
- Get category by id: get /categories/:id
- Create new category: post /categories
- Update category by id: put /categories/:id
- Delete category by id: delete /categories/:id
## Product API
- Get all categories: get /products
- Get category by id: get /products/:id
- Create new category: post /products
- Update category by id: put /products/:id
- Delete category by id: delete /products/:id
## Tag API
- Get all categories: get /tags
- Get category by id: get /tags/:id
- Create new category: post /tags
- Update category by id: put /tags/:id
- Delete category by id: delete /tags/:id

# Licence
![badge](https://img.shields.io/badge/license-MIT-important)

# Link
https://drive.google.com/file/d/1yJdqHPbXbGDQMoNdLNMyWkIflcTv0lnY/view?usp=share_link
