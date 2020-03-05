# wizeline-qa-backend-challenge

this is the code to run the tests
`newman run "OsirisVilla_GraphqlWorkshop.postman_collection.json" --environment "QA.postman_environment.json"`

And this is including the html report 
`newman run "OsirisVilla_GraphqlWorkshop.postman_collection.json" --environment "QA.postman_environment.json" -r htmlextra`

I also added 2 extra requests, `deleteProject` and `getDeletedProject`
First one to delete the current project and reset the data
Second one to be sure the project was deleted

I let the html report of my last run in the newman folder if you want to check it
