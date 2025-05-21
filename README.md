# spotify-api-test-newman

After creating the collection in Postman, the below steps needs to be followed for using Newman
npm install -g newman
npm install --save-dev newman newman-reporter-html
newman run .\spotify-demo.postman_collection.json -r cli,html --reporter-html-export output.html


![Screenshot 2025-05-21 154017](https://github.com/user-attachments/assets/0e9d82e7-36ab-4ed5-9196-ad2df06cf054)