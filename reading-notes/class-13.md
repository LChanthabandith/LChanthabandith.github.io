# Readings

## Why would a developer use local storage for a web application?

The main problem with HTTP as the main transport layer of the Web is that it is stateless. This means that when you use an application and then close it, its state will be reset the next time you open it. If you close an application on your desktop and re-open it, its most recent state is restored. This is where *local storage* comes in. You would keep a key on the user’s computer and read it out when the user returns.

[Local Storage and How To Use It On Websites](https://www.smashingmagazine.com/2010/10/local-storage-and-how-to-use-it/)

## What information should not be stored in local storage?

Never store sensitive information in LocalStorage. This includes passwords, API Keys, authentication tokens like JWTs and financial information like credit card numbers, to name a few.

[Storing Data in the Browser with LocalStorage](https://stackabuse.com/storing-data-in-the-browser-with-localstorage/)

## Local storage can store what type of data? How would you convert it to that type before storing?\

You can only store strings in the different keys. This means that when you have an object, it will not be stored the right way. You can work around this by using the native `JSON.stringify()` and `JSON.parse()` methods.

[Local Storage and How To Use It On Websites](https://www.smashingmagazine.com/2010/10/local-storage-and-how-to-use-it/)
