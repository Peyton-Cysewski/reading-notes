# Reading 13

## Local Storage for Web Applications
Local storage is the storage on your local machine. Any application you run will have access too your computer's memory to keep information to access later. Web browsers were not originally designed for this use. They were eventually afforded a few KB of data as cookies, but that would slow down https requests even though it wasn't enough space to do anything particularly useful.

With HTML5 and the use of the DOM, 'storage events' were added so that data would be stored locally as strings and wouldn't need to be sent as https requests. This allows the speed of the internet to be maintained, security with localized information, and a lot more storage that can be allotted for use by browswers.

Each origin is allotted 5MB (as of 2011). To use the storage, use an event listener/hander to manipalte data from the 'localStorage' object.




#### [Home](README.md)