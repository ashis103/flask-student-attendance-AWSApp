**Please isnatll EC2 inistance with ubuntu and then install docker and docker compose.

copy all text to you notepad ....

https://docs.docker.com/compose/install/linux/**

If install docker and compose Please follow the below instruction in your AWS instance .

sudo service docker status
dcoker ps -a
dcoker ps

docker run hello-world

history
systemctl enable docker
docker ps -a
*** Please open Git bash CLI *****
run below GIT command .

git clone https://github.com/bongodev/flask-student-attendance-app.git
ls
cd flask-student-attendance-app/
ls
history
docker run -d mysql:latest
docker compose up --build -d

* **AWS Instance Inbound Rules : You need to allow 5000 ports .
**
* Now Please check https://IP:5000

