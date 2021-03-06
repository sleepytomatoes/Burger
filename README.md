# Eat Da Burger

# Table of Contents
1. [Project Description](#description)
2. [Usage](#usage)
3. [Dependencies](#dependencies)
4. [References](#references)
5. [Github](#gitcontact)

## Project Description <a name="description"></a>
On the surface, this application allows the user to add burgers to a database.  The user can then manipulate that data to delete burgers or change the status of the burger to available or devoured. This modularized application utilizes the MVC paradigm.  Within the View layer express-handlebars is implemented as a template engine for HTML.  Within the Model layer we've utilized an ORM (burger.js) to implement reusable queries to retrieve/send data via MySQL Workbench.  Within the Controller level burger_controller.js handles client-side routes, interacts with the Model and delivers dynamic content via the View layer.
![screenshot](/images/appimage.jpeg) 


## Usage <a name="usage"></a>
From the command line, 
'npm run start'
In the browser: localhost:8080

## Dependencies <a name="dependencies"></a>
This application utilizes MySQL Workbench and requires the following npm packages:
- express
- express-handlebars
- mysql 

## References <a name="references"></a>
Cats App [CatsApp]](https://richmond.bootcampcontent.com/Richmond-Boot-Camp/ur-rich-fsf-pt-11-2020-u-c/tree/master/13-MVC/01-Activities/17-CatsApp)

## Github <a name="gitcontact"></a>
Github username: [sleepytomatoes](https://github.com/sleepytomatoes) 
Email: shaunadunn1@gmail.com
