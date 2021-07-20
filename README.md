# A simple demo how to configure a very basic pwa (progressive web application)

This project is to demo the very basics of pwa  

### How to configure 

1) web server:  

we use node lite-server (package.json)

2) configuation:  see manifest.json

3) register service worker 

at main.js navigator.serviceWorker.register('./sw.js')

4) cache essential resources 

at sw.js cache.addAll(filesToCache);

   
### How to test 

1) start web server 

2) chrome at localhost:3000

3) at developer console, disconnect network 

4) refresh at chrome, the page is still accessible 


