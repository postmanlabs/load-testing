### From this blog post: Don’t get TechCrunched: [performance testing for your HTTP APIs](https://medium.com/postman-engineering/dont-get-techcrunched-performance-testing-for-your-http-apis-3196e40f6b70)
Using AWS Lambda to run concurrent functions with Newman

### Get Started
Install dependencies

    $ npm install

Run script from the command line   

    $ node loadTest.js

Your Postman collection can be exported as a JSON file and run from your local file system, as in this example here. Alternatively, you can use the [Postman API](https://docs.api.getpostman.com/) to access the latest version of your collection. The second approach is recommended if you plan to update the collection more frequently.

The handler function is defined in `index.js` if you're uploading this script to AWS Lambda. Zip up the required files and dependencies.

    $ node run zip


---
[Example script](https://github.com/postmanlabs/newman/blob/develop/examples/parallel-collection-runs.js) is taken from the [Newman open source project](https://github.com/postmanlabs/newman).
