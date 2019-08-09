## fetch-api-demo
Making server requests in JavaScript-based application is a common task. There are different ways of solving that task. Back in the day developers used the XMLHttpRequest (XHR) objects to interact with servers. For the first time it has been possible to retrieve data from a URL without having to do a full page refresh. This was one of the prerequisites to enable a web page to update just parts of the page without needed to do a full refresh.

However, using XMLHttpRequest has never felt very natural to JavaScript developers and has lead to code which is hard to read and understand. External libraries like jQuery or Axios have been trying to solve that problem and have provide better and cleaner server request APIs.

With the release of the Fetch API JavaScript has now build-in a much cleaner promised-based API which can be used to perform server request in an easy way without needing to use third-party libraries. 
