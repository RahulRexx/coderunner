# coderunner


Routes 

/ - Form to submit code

/submit -post route

 
files:<br>
problem link -https://www.spoj.com/problems/MAXWOODS/ <br>
editorial.cpp -sample program  <br>
in.txt - input file <br>
req.txt - expected output <br>



using docker 

1. docker build -t coderunner . <br>
2. docker run -p 49160:8080 -d coderunner . <br>