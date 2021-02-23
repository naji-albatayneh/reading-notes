[**Back**](https://naji-albatayneh.github.io/reading-notes)

# Local Storage for Web Applications

- **On the on hand, cookies can be used for persistent local storage of small amounts of data, where they are included with every HTTP request, thereby slowing down the web application by needlessly transmitting the same data over and over. In addition, they are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL). Furthermore, they are limited to about 4 KB of data, which is enough to slow down your application, but not enough to be terribly useful.**

- **On the other hand, we indeed require a lot of storage space on the client that persists beyond a page refresh and isn’t transmitted to the server.**

- **This has been introduced by `HTML5` which provides a `standardized API`, implemented `natively` and consistently in `multiple browsers`, without having to rely on `third-party plugins`. However, before HTML5 there were multiple ways to store user data but they all are `unsatisfactory` enough.**

- **HTML5 Storage is a way for web pages to store `named key-value pairs` `locally`, within the client web browser. This data persists even after you navigate away from the web site, close your browser tab, exit your browser. Unlike cookies, this data is never `transmitted` to the remote web server (unless you go out of your way to send it manually). Unlike all previous attempts at providing persistent local storage, it is implemented natively in web browsers, so it is available even when third-party browser plugins are not.**

- **From JavaScript code, we can access HTML5 Storage through the `localStorage object` on the `global window object`. Before we can use it, we should detect whether the browser supports it or not by using `Modernizr`.**

- **We can use `JSON` to `stringify` objects in a format that can be stored in a local storage.**
- Ex.: `JSON.stringify(object or array);`

- **We can use `JSON` to `parse` values stored in a local storage to object format that can be used in javascript.**
- Ex.: `JSON.parse(key from the local storage);`

- **We can use `localStorage.setItem('key','value')` to store a pair of key-value format.**

- **We can use `localStorage.getItem('key')` to get the value of the key.**

________________________________________________________
##### Naji A. Albatayneh | Ph.D (IT) | Faculty of Computing and Informatics, Multimedia University, Cyberjaya, Selangor, Malaysia

###### Mobile: +60-143-473374 , +962-786-324328 | E-mail: naji.albatayneh@gmail.com

###### Let's Connect on [LinkedIn](https://www.linkedin.com/in/naji-a-albatayneh/) | [Github](https://github.com/naji-albatayneh) | [Facebook](https://web.facebook.com/naji.albatayneh/)
