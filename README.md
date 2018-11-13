# Rest_Api
 The purpose of creating this "Rest_Api" application was to demonistrate the .net core 2 platform components to
 build Rest-Api application. What does this application? The application is designed to help manage different meetings. 
 When I decided to build this rest-api solution it shuld be cross-platform, rest architecture principles, separation of concerns principle
 and optimal designed. To achieve all this services I explored the Asp.Net Core 2 and Entity Framework Core 2. For validation I applied 
 FluentValidation library. The appliction folders structure are self explanatory. 
 How to create the Models and Repositories just follow the class libray structures. The rest-api solution will use a single page application (SPA) to render and create dynamic website, but for the moment the SPA solution is not implemented.     

Database generated by Entityframework are 
1. MeetingsSchemas table

![alt text](https://github.com/muluhai/Rest_Api/blob/master/MeetingSchema.API/Results_images/MeetingSchema-Table.png)
2. User table

![alt text](https://github.com/muluhai/Rest_Api/blob/master/MeetingSchema.API/Results_images/Uers-Table.png)
3. Participants table

![alt text](https://github.com/muluhai/Rest_Api/blob/master/MeetingSchema.API/Results_images/Participansts-table.png)

Testing the rest-api with postman

1. MeetingSchema-ApiController

![alt text](https://github.com/muluhai/Rest_Api/blob/master/MeetingSchema.API/Results_images/TestingSchemaControllerPostman.png)

2. User-ApiController

![alt text](https://github.com/muluhai/Rest_Api/blob/master/MeetingSchema.API/Results_images/TestingUserController.png)

3. Swagger

![alt text](https://github.com/muluhai/Rest_Api/blob/master/MeetingSchema.API/Results_images/swagger.png)

