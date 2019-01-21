# dotnet-api-crud
Simple CRUD to test some implementation on dotnet core

## Getting Started

```
- docker-compose up
- dotnet run
```

## List All
* **GET** - https://localhost:5001/api/v1/person

## Find by Id
* **GET** - https://localhost:5001/api/v1/person/1

## Create
* **POST** - https://localhost:5001/api/v1/person
```
Body
{
  "FirstName": "Ricardo",
  "LastName": "Georgel",
  "Address": "Some Address", 
  "Gender": "Male"
}
```

## Update
* **PUT** - https://localhost:5001/api/v1/person
```
Body
{
  "Id": 1,
  "FirstName": "Ricardo",
  "LastName": "Georgel",
  "Address": "Some Address", 
  "Gender": "Male"
}
```

## Delete
* **DELETE** - https://localhost:5001/api/v1/person/1





