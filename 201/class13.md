# Class 13 Reading Notes

## Local Storage and How To Use It On Websites

- The main problem with HTTP as the main transport layer of the Web is that it is stateless. This means that when you use an application and then close it, its state will be reset the next time you open it. If you close an application on your desktop and re-open it, its most recent state is restored.

- A cookie is a text file hosted on the user’s computer and connected to the domain that your website runs on. You can store information in them, read them out and delete them.

- You can also use sessionStorage instead of localStorage if you want the data to be maintained only until the browser window closes.

- Another use case is to store the state of interfaces. This could be as crude as storing the entire HTML or as clever as maintaining an object with the state of all of your widgets. 

## The Past, Present, and Future of Local Storage for Web Applications

- Persistent local storage is one of the areas where native client applications have held an advantage over web applications. For native applications, the operating system typically provides an abstraction layer for storing and retrieving application-specific data like preferences or runtime state. These values may be stored in the registry, INI files, XML files, or some other place according to platform convention. If your native client application needs local storage beyond key/value pairs, you can embed your own database, invent your own file format, or any number of other solutions.

### Things I want to know more about

- HTML5 Storage specification

- DOM Storage on Mozilla Developer Center

- Dojo Storage

- Web SQL Databases

#### Link to my github portfolio [https://github.com/jenniferlidotson](https://github.com/jenniferlidotson)
