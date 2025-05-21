# spotify-api-test-newman

After creating the collection in Postman, the below steps needs to be followed for using Newman
npm install -g newman
npm install --save-dev newman newman-reporter-html
newman run .\spotify-demo.postman_collection.json -r cli,html --reporter-html-export output.html


![Screenshot 2025-05-21 163705](https://github.com/user-attachments/assets/356f3261-54aa-4ca5-81bd-d11729fbd280)
