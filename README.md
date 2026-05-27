# Lab8-Starter

Names: Iban Rosales

https://iirosales.github.io/Lab8_Starter/

**How are graceful degradation and service workers related?**

Graceful degradation basically allows a website to not break when encountering basic functionality failures, such as older browser, slow/no internet, database connection loss, etc. And service workers supports this concept of graceful degradation by intercepting network requests and serving cached assets. An example will be if the user loses connection to the internet, instead of the application crashing completely, it will "degrade" itself into an offline mode, with although more limited functionality, still usable. 
