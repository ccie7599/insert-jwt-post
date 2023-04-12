insert-jwt-post
======================

# About

Simple endpoint that-

-listens for POSTs via host:1880/api 
-signs a JWT (with claims set via parameters in the POST)
-Adds the JWT to a request and forwards the POST to another host.

Built to allow for JWT signing of POST requests into BQ.

Alternative- There is an alternative approach built into the application - a node.js package for google BQ that allows for BQ inserts via a Google Service Account credential. 

![image](https://user-images.githubusercontent.com/19197357/231475308-6dccb95b-bebe-43f0-882b-a10428b14fd1.png)

