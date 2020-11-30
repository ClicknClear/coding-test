## ClicknClear Coding Test
V3 – 30/11/2020

Included in this repo is a file “tracks.json”
The file contains a JSON object with the following structure:

```
{
  "tracks": [
  {
    "id": 1,
    "title": "A Song",
    "artist": "Famous Singer"
  },
  {
    "id": 2,
    "title": "Another Song",
    "artist": “Famous Band"
  }]
}
```

Write an application that serves a REST API allowing a client to query the contents of this file, as well as a basic web client to display the data.

The API should support the following endpoints:
- Given a track id return the associated track details.
- Given an artist name return the details of the associated tracks

**Notes:**
Please write the API using NodeJS, using a framework such as Express or Fastify.

Please provide a ReactJS web client to demonstrate how the API should be called and data should be displayed. Incorporation of a widget toolkit such as Bootstrap or Material UI is encouraged.

Please use TypeScript for each portion of this exercise. You may use any other dependencies or libraries you wish. Write the code in a professional manner as if it were something you were submitting for code review rather than as a toy exercise.

The solution should be simple to build and run, such as simply using npm run. Please commit the exercise to a GIT repository and provide a link to the repository when finished.

The exercise will be evaluated on:
- Correct use of TypeScript
- Code structure
- Grasp of modern coding practices such as ES6
- Performance of application
- Any obvious bugs in the code
