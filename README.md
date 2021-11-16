# Bookmark App!

This project was made by: Marco De Los Santos (Backend), J. Mitchell Paoletti (Frontend), & Donovan Gallaway (Styling and SCRUM Master)

## Technologies 

The backend was put together with Express.

## About the Site

This site allows users to bookmark their favorite site and will link them to it right from the main page! This also allows users to edit their bookmarks and add & remove bookmarks. 


### Pages & Routing Table


| Method      | Route | About     |
| :---        |    :----:   |          ---: |
| Get      | "/bookmarks" (Index)       | Shows all user's bookmarks   |
| Put   | "/bookmarks" (create)        | Route for adding a new bookmark      |
| Post   | "/bookmarks/:id"        | Route for updating bookmark data      |
| Delete   | "/bookmarks/:id"       | Route for deleting a bookmark       |


## Challenges

Backend was smooth, save for deployment. We had forgotten to actually declare DATABASE_URL at one point which caused some deployment headaches, but otherwise it was fine!
