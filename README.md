assignment2
Cloud Computing 
Reyan Jaimon 
C1548408
DT228/3

YOUTUBE LINK VIDEO DEMO:

https://www.youtube.com/watch?v=zDku1n5mnRw

HOW TO RUN AND EXECUTE CMS:

# How app works

1. We clone the repo 

git clone https://github.com/c15487408/assignment2.git
2. we create virtual environment in Python2

`virtualenv venv`

3. we activate virtualenvironment

source venv/bin/activate

4. we install requirements

pip install -r requirements.txt

5. we run application 

python container-server.py

6. Mainly GET methods are implemented and delete methods for removing image 

images that have dependency cannot be erased without -f flag 

some examples:

`curl http://localhost:8080/images`

`curl http://localhost:8080/containers`

`curl http://localhost:8080/containers/<id>`

`curl http://localhost:8080/containers/<id>/logs`

`curl -X DELETE http://localhost:8080/images/<id>`
