# ContainerDemo
Steps to get docker image:</br>
<b>1. Create directory for application</b>
<code>mkdir PollService</code>
2. Clone repository of app (docker image)
sudo git clone https://github.com/rmestre/ContainerDemo.git PollService/
3. Build docker image
docker build -t myapp .
4. Run docker container with newly created image
docker run -t -d -p 5004:5004 myapp 
5. That's it you can see your app at localhost:5004 (localhost on host machine i.e. linux vm)
