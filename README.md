# CS361Microservice

Process to request data:
1. Connect to socket and send message with the line "Profile Request"
2. Microservice will receive line and open file dialogue box for user.

Process to receive data:
1. After sending "Profile Request", wait for user to select photos. Once they have, a response will be send through the socket. 
2. The first line given by the socket will be the number of images that the socket is sending.
3. The next lines will be the file paths to those images.

![image](https://user-images.githubusercontent.com/92469515/218640769-d7780d86-f2ce-4839-a0bc-6ccb573a14db.png)
