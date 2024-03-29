-> What is Emmet?
 
   Emmet (formerly Zen Coding) is a set of plug-ins for text editors that allows for high-speed coding and editing in HTML, XML, XSLT, and other structured code formats via content assist.

 -> Difference between a Library and Framework?

 A library performs specific, well-defined operations.

A framework is a skeleton where the application defines the "meat" of the operation by filling out the skeleton. The skeleton still has code to link up the parts but the most important work is done by the application.

Examples of libraries: Network protocols, compression, image manipulation, string utilities, regular expression evaluation, math. Operations are self-contained.

Examples of frameworks: Web application system, Plug-in manager, GUI system. The framework defines the concept but the application defines the fundamental functionality that end-users care about.

-> What is CDN? Why do we use it?
    A Content Delivery Network (CDN) is a geographically distributed group of servers that work together to provide fast delivery of Internet content.

-> Why is React known as React?
     The name "React" was chosen because it is meant to help developers build user interfaces that are fast and responsive, or "reactive." The library was designed to "react" to changes in data. With React, developers can create, combine, and reuse components (or blocks) to make beautiful, interactive web pages. A component is a mixture of HTML and JavaScript that captures all of the logic required to display a small section of a larger UI. Each of these components can be built up into successively complex parts of an app.

-> What is crossorigin in script tag?
    The crossorigin attribute sets the mode of the request to an HTTP CORS Request.
    Web pages often make requests to load resources on other servers. Here is where CORS comes in.
    A cross-origin request is a request for a resource (e.g. style sheets, iframes, images, fonts, or scripts) from another domain.
    CORS is used to manage cross-origin requests.
    CORS stands for Cross-Origin Resource Sharing, and is a mechanism that allows resources on a web page to be requested from another domain outside their own 
    domain. It defines a way of how a browser and server can interact to determine whether it is safe to allow the cross-origin request. CORS allows servers to 
    specify who can access the assets on the server, among many other things.


-> What is diference between React and ReactDOM?
    
   React: React is a javascript library, designed for building better user interfaces.
   React-DOM: React-DOM is a complimentary library to React which glues React to the browser DOM.
   In a nutshell, Whenever we use component, classes, elements, etc. We’re using React and whenever we use methods like render() or findDOMNode() we’re using React-DOM.

 Why did the React team decide to split React and React-DOM into two different libraries?

 Because React-DOM binds the idea of React to a web browser. And ideally, React has nothing to do with a browser or web for that matter. That’s why we’re seeing tools and frameworks like React-Native, React-Three being developed. These tools and frameworks don’t use React-DOM, but they do in fact use the idea behind React.


## What is difference between react.development.js and react.production.js files via CDN?
     
     react.development.js - More developer friendly, readable, will take more size. 
     react.production.js - Minified code that is not developer friendly as it focused on decreasing in file size, code efficiency.
