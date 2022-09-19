
# e-commerce Back End (ORM)  


## Table of Contents
- [Description](#description)
- [Video](#Walkthroug_Video)
  


## Description  

e-commerce Back End is a simple app that allows to interact with sequelize to perform queries to a SQL database using HTTP requests. The app consist of a database of three main tables; products, categories and tags; additionaly it has a productTag table wich is going to help to establist a relation ship between products and tags given that there is a relationship many to many between these two tables. The different queries allow the user to perform CRUD operations.  


VIES TABLE CONTENTS

Using GET HTTP requests the user can view the content of the whole tables or specifying an id. The tables will show its content and the content related of other tables.

CREATE / UPDATE CONTENTS

Using POST AND PUT HTTP request the user is able to either create or modify a table record. For these operations the usere must pass the content of the new record in JSON format. For the PUT method, the user is required to specify the id of the record that will be updated.


DELETE CONTENTS

Using DELETE HTTP reuqests, the user is able to delete a specific record of the table chosen in the route. The user must sepcify the id of the record that will be deleted.


## Walkthrough Video
Please refer to the following vide for more details of the code and app functionality.

[Walkthroug Code and Application: ](https://watch.screencastify.com/v/WRNb4COgJBHxflLhyBkq)
  
 

## Questions
Please refer to my GitHub profile for more information: https://github.com/Lalo79  
If you have questions, you can reach me via e-mail: lalo@mail.com   

