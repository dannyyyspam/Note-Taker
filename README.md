# Note Taker
Write, save, and delete notes! 

Deployed on [Heroku][1]! 

Front-end starter code from [Xandromus][2]

---
## UsagePull requests
><b>Add a note:</b> Fill in the title and body, then hit the floppy disk save icon.
>> You will see your note saved in the left side column.
>> 
>> Hitting the '+' instead if the floppy disk will send your note into oblivian 🧙‍ (won't fix)

> To view an existing note you simply click on it from the left coolumn.

> The '+' is for switching from viewing an existing note to creating a new one.

><b>Delete a note:</b> Hit the red trashcan icon on an existing note. (or the + on the one you're currently writing 🤦‍♂️)  

### Technical Jargon

This application uses an Express.js back-end to save and retrieve note data from a JSON file.

I wrote the back-end `JavaScript`, connected the front-end, and then deployed the application to Heroku.

> Application front end connects to an `Express.js` back end.

> Application back end stores notes with unique IDs in a `JSON` file.

> Application is deployed to `Heroku`.

---
## User Story
```
AS A small business owner
I WANT to be able to write and save notes
SO THAT I can organize my thoughts and keep track of tasks I need to complete
```

## Acceptance Criteria
```
GIVEN a note-taking application
WHEN I open the Note Taker
THEN I am presented with a landing page with a link to a notes page
WHEN I click on the link to the notes page
THEN I am presented with a page with existing notes listed in the left-hand column, plus empty fields to enter a new note title and the note’s text in the right-hand column
WHEN I enter a new note title and the note’s text
THEN a Save icon appears in the navigation at the top of the page
WHEN I click on the Save icon
THEN the new note I have entered is saved and appears in the left-hand column with the other existing notes
WHEN I click on an existing note in the list in the left-hand column
THEN that note appears in the right-hand column
WHEN I click on the Write icon in the navigation at the top of the page
THEN I am presented with empty fields to enter a new note title and the note’s text in the right-hand column
```

<br>

## Screenshots
|<center><b>homepage</b>|<center><b>notes page with no notes</b>|
-|-
![][3]|![][4]
|<center><b>notes page with one stored note and creating a new one</b>|<center><b>notes page with two stored notes. viewing a stored note</b>|
![][5]|![][6]

___

[1]:https://first-app-created.herokuapp.com/
[2]:https://github.com/coding-boot-camp/miniature-eureka
[3]:https://raw.githubusercontent.com/its-jefe/Note-Taker/main/images/1.png
[4]:https://raw.githubusercontent.com/its-jefe/Note-Taker/main/images/2.png
[5]:https://raw.githubusercontent.com/its-jefe/Note-Taker/main/images/3.png
[6]:https://raw.githubusercontent.com/its-jefe/Note-Taker/main/images/4.png