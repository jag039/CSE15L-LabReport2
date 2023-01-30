# Lab Report 2
Jesus Gonzalez - CSE 15L - A17425808 - Jan 29, 2023

---
## String Server
The folowing is the code creating the web server that keeps track of a single string that gets added to by incoming requests.

The request should look like this `/add-message?s=<string>`.

The request results in concatenating a new line containing the string after = to the running string, and then respond with the entire string so far.
![Image](StringServer.png)



