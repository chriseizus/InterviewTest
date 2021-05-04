# Welcome to GNE test!


Requirements:

 1.  use Python (FastAPI library) to create a backend rest api endpoint.

       > 1. Get Method
       > 2. you can use any url definition you want
       > 3. returning a json object which is the hard coded content as data.json (in the same repo as this readme.md) as well as http code 200
       > 4. The Json object must follow the hierarchy structure but the data details may be flexible (pay attention to the array hierarchy)
       > 5. Using pydantic library to validate the json payload

 2. use Angular to create a frontend to present the json format, please follow the rules:
    
       > 1.  use a separated http service to get data from backend
       > 2.  present the data to the frontend component
       > 3.  use data table to present the data
       > 4.  the table has to be nested as row-expand details view since the data arrays in the requirement are nested
       > 5.  the row items from the array must be able to change order using any method in the frontend
       > 6.  please implement actions that you can change the content of any value inside the table
       > 7.  provide a submit button that can call the backend POST method to save the modified table content

 3.  Create a backend api endpoint to accept POST method that frontend submitted

       > the json payload in the request body must be saved to a file on the backend server folder

 4.  To simplify, authentication is not required for any rest API call.
 5.  The frontend datatable design can be flexible but consider the best user experience first.
 6.  Please use flask-restful to implement backend python rest API
 7.  you must use ng-zorro angular library for frontend implementation
