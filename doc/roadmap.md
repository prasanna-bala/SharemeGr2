# RoadMap 

## Login component

create login.js component
import google login ,image ,icon 

## tailwild
Updated the tailwind.css

## Login component 
create api in the Google cloud
create project id and token 

## .env 
create .env file
Add 
    React token,sanity token and project id 

## Client.js


- creation of user item in the local storage whith response.profileObj as data
- destructuring of the google response as name, googleId, imageUrl
- 

import sanity client ,sanity images
export client builder,Url

## sanity 
Manage sanity and launch sanity localhost
create project id and token 

Assign the sanity projectid and token  to the variable in .env file.js

## login.js components

import client 

## home
link userProfile, client, logo, pins and userQuery
create component pins in container, folders utils with file userQuery

-const userQuery for recov datas of user

-pins
    create components feed, createPin and pinDetail
    link components navbar, search, feed, pinDetail and createPin
    this component allow of recov categories in search for stand out pictures corresponding
    add button dark and + inside for create new pin
    when click in particular pin, this attach the detail of this pin


## sidebar & navbar
create components sidebar and navbar and link sidebar in page Home

-sidebar
    add categories, add if navbar is active or not
    add fonctionnality of close navbar when click in cross or click in link

- navbar
    add components search and input search in page navbar
    add name and picture of profile in bottom of navbar

## feed
create component feed and spinner
import the layout masonry for the images
import spinner for chargement of more images and if no image

## Pin
    in image, add button save, button delete, link description and button upload

## CreatePin
    add as a form for add a new pin with: 
        - place where click for add image in upload
        - input for add title
        - input for add about
        - input for add ddescription / link
        - select for category
        - button for save the pin
    
## PinDetail
    When click in the pin,
    see all informations of the pine :
        - in top: the image
        - the button for download at left and at right the link or description
        - the title and about 
        - the user who added the pin
        - add component comment:
            - attach input for add comment
            - the user who added a comment

## UserProfile
    attach all informations for a user
        - add a banner with a image of the user, the name of the user
        - attach pins than the user added
    the user of this profile can delete an image he has added

## search
    - add the functionnality of search a pin
    - can search pin letter by letter
