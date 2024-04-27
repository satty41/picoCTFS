GET aHEAD 

Description:

Find the flag being held on this server to get ahead of the competition https://lnkd.in/g4Aw_yvq

HINTS:
1. Maybe you have more than 2 choices
2. Check out tools like Burpsuite to modify your requests and look at the responses

SOLUTION:-
Access the given URL in browser and capture request/response using Burp Suite tool.
We can notice only 2 buttons present in the application which changes color of the page on click.
Click on the both buttons and analyze all captured traffics till now in the tool, however nothing looks interesting.
Challenge name i.e. “Get aHEAD” seems to be a hint as HEAD is one of the known HTTP method which we can try in any of the captured request. Change method from GET to HEAD and generate response.
It can be noticed that Flag value is revealed in the response.
Challenge Solved. Thanks.. 😊 

hashtag#Hacking hashtag#ctf hashtag#picoctf hashtag#cybersecurity
