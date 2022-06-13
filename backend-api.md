[← Back](README.md)

# Backend API

## ⚠️ Prerequisites

None.

## ⚙️ Technologies

You can use any technology to build REST APIs you are comfortable with. Preferred would be to use:

- C#
- ASP.NET Core
- Swashbuckle

If you plan to also work on the [Azure Backend Connect](backend-azure.md), please choose technologies for that an Azure Table Storage SDK exists.

## 🏋️‍♀️ Task

Imagine that you and your team are creating a new app for managing a shopping list. Each item is presented by a simple text which is the title.

The goal is to create an API that offers endpoints to manipulate a simple array of texts. The list itself shall be stored locally in memory. Endpoints are needed for:

1. Adding an item to the list
2. Removing an item from the list
3. Retrieving the complete current list as array

We want to use JSON as the format of data flowing in and out of the API.

## 🏃‍♀️ Steps

- Create a simple REST API project
- Configure a graphical API documentation (for example using “Swagger UI”)
- Implement the needed HTTP endpoints
- Test out the API

## 🤩 How can you wow us?

- Ensure that all methods are using the correct HTTP methods.
- Take care about the documentation of the API.
- Ensure that the list is retrieved sorted alphabetically.
- Ensure that items cannot be added if they already exist.
