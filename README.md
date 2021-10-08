# Fullstack Helsinki 2021 Part 3 Note App Separate Repo for Heroku

### *This repo for the finalized version of the Note App along with the main fs-hel21-sup Repo are supplemental course work, and are not to be submitted as for-credit exercises.*

----

Location of Notes App: https://whispering-spire-37046.herokuapp.com/

Location of JSON API Server: https://whispering-spire-37046.herokuapp.com/api/notes


* fs-hel21-part3 is the backend Node Express Server for the frontend React Application located at ...codegrunt/fs-hel21-sup/part2/notes
* Use the build:ui, deploy, and deploy:full scripts located at this repo to depoly the app after making changes to the frontend there.
* app.use(express.static('build')) serves the index.html file and static resources from build folder to *http://localhost:3001*
* All requests to the (relative) /api/notes routes are handled on this server
  

-cz 10/8/2021