# options.allowedHosts-0-non-empty-string-Error-Solution
Resolve for Invalid options object. Dev Server has been initialized using an options object that does not match the API schema


Delete "proxy": "http://localhost:YourPort" if added on Package.json

npm i http-proxy-middleware --save

Add this file setupProxy.js inside src in client side.

Now, run your app. 
