# Assigment1
SpringBootApplication

It is basically a CRUD based spring Application which allows connection from multiple databases via different sources i.e. 
MongoDb
Sql

once the request is sent via Postman it adds the data to their alloted data source

Sample Data:
{
  "firstName":"khushi",
  "lastName":"new",
  "email":"helloo@abc.com",

  "courses":[
      {
          "name":"docker",
          "description":"helo",
          "email":""
      },
      {
          "name":"kuber",
          "description":"khuhuhu",
          "email":""
      }
      ]

}


Here the main data of the student is stored in an SQl database whereas the course data in the mongoDb collection.

Similarly data can be added, deleted and updated in both the databases from a single application.
