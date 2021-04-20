# Read13

## “The Past, Present, and Future of Local Storage for Web Applications”

**What is HTML Web Storage?**
- With web storage, web applications can store data locally within the user's browser.
- Before HTML5, application data had to be stored in cookies, included in every server request. Web storage is more secure, and large amounts of data can be stored locally, without affecting website performance.

- Unlike cookies, the storage limit is far larger (at least 5MB) and information is never transferred to the server.

- Web storage is per origin (per domain and protocol). All pages, from one origin, can store and access the same data.

**HTML web storage provides two objects for storing data on the client**
- window.localStorage - stores data with no expiration date
- window.sessionStorage - stores data for one session 

**The localStorage Object**

The localStorage object stores the data with no expiration date. The data will not be deleted when the browser is closed, and will be available the next day, week, or year.

**The sessionStorage Object**

The sessionStorage object is equal to the localStorage object, except that it stores the data for only one session. The data is deleted when the user closes the specific browser tab.

[Go Back ](README.md)