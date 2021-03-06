# Note Taker

---

## Description

This simple note taking application allows you to save notes with a title and plain text. Powered by ExpressJS, the Note Taker app makes creating, viewing, and deleting notes easy.

    * The application frontend has already been created, it's your job to build the backend and connect the two.

    * The following HTML routes should be created:

      * GET `/notes` - Should return the `notes.html` file.

      * GET `*` - Should return the `index.html` file

    * The application should have a `db.json` file on the backend that will be used to store and retrieve notes using the `fs` module.

    * The following API routes should be created:

      * GET `/api/notes` - Should read the `db.json` file and return all saved notes as JSON.

      * POST `/api/notes` - Should receive a new note to save on the request body, add it to the `db.json` file, and then return the new note to the client.

      * DELETE `/api/notes/:id` - Should receive a query parameter containing the id of a note to delete. This means you'll need to find a way to give each note a unique `id` when it's saved. In order to delete a note, you'll need to read all notes from the `db.json` file, remove the note with the given `id` property, and then rewrite the notes to the `db.json` file.

---

## User Story

    AS A user, I want to be able to write and save notes

    I WANT to be able to delete notes I've written before

    SO THAT I can organize my thoughts and keep track of tasks I need to complete

---

## Visuals
![image](https://user-images.githubusercontent.com/27812373/179432181-bed2dbd9-678d-4075-a843-dffdb651be48.png)
![image](https://user-images.githubusercontent.com/27812373/179432208-60751be0-64cd-4420-a561-7cf46b460606.png)
![image](https://user-images.githubusercontent.com/27812373/179432292-e024ab20-04ac-4a1b-b341-bebce0192163.png)


---

## Deployed Link:
https://damp-inlet-25580.herokuapp.com/
---

## Built With
* [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
* [NodeJS](https://nodejs.org/)
* Node Packages:
    * [Express](https://www.npmjs.com/package/express)

---

## Contact Information
  * GitHub Username: (https://github.com/mherring11)
