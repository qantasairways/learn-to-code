# learn-to-code

With these kind of tools there can be some issues around code injection as this is fundermentally the requirment. i.e. inject the code I write into this page. However this implementation provides an interactive editor within a web page with the following features:

- Users can not change the code stored on the site. All changes are stored in localStorage on their browser. LocalStorage is namespaced by domain and browers protect the content of one domain from accessing data stored by another domain.
- The code in the editor can be coppied to the right hand portion of the screen and runs within an isolated iframe with no access to the rest of the page.
- There is no way to inject any code on the page that can be persisted in a link that could be sent to someone.
- The download option saves a static html file as a normal download.

In other words the page has completely static content appart from what is stored in each users browser localStorage facility.