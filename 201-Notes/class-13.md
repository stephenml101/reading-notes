# Notes

## Things I want to know more about:

[Local Storage and How To Use It On Websites](https://www.smashingmagazine.com/2010/10/local-storage-and-how-to-use-it/)

1. Why would a developer use local storage for a web application?

- The main problem with HTTP as the main transport layer of the Web is that it is stateless. This means that when you use an application and then close it, its state will be reset the next time you open it. If you close an application on your desktop and re-open it, its most recent state is restored.

2. What information should not be stored in local storage?

- Information on a user.

3. Local storage can store what type of data? How would you convert it to that type before storing?

- One annoying shortcoming of local storage is that you can only store strings in the different keys. This means that when you have an object, it will not be stored the right way.

- You can work around this by using the native JSON.stringify() and JSON.parse() methods

[“The Past, Present, and Future of Local Storage for Web Applications”](http://diveinto.html5doctor.com/storage.html)
