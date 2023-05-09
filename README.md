# Milestone2
A. Requests through this microservice are done through local text files. To do a call to this service your program will write to the loginRequest.txt with the format "username,password". The microservice will read this from this file and then compare the read string to the saved logins in the users.txt file. If a match is found the microservice will return True if not False in the loginResponse.txt file. For the createAccount service, you will have to write to the file createRequest.txt with a string in the format "username,password". From here the createAccount microservice will read from this file and add the new username and password to the users.txt file. For all of these requests to the microservice make sure in your program to delete what you wrote to the files so as to not get multiple responses.

B. To receive the request from the microservice you will have to read from the loginResponse.txt file after sending a request. It will have either True or False printed into the file. True will mean the login was correct False will mean the login was incorrect. From here you can choose whether to allow the user to access the account.

#Can access image of UML diagram from this link:
C.![uml](https://user-images.githubusercontent.com/129989916/236993640-ad6ba691-c3c6-4eb9-ba58-7c848f65c8cf.PNG)


