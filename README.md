# ContainerDemo
Steps to get docker image:</br>
<b>1. Create directory for application</b></br>
<code>mkdir PollService</code></br>
<b>2. Clone repository of app (docker image)</b></br>
sudo git clone https://github.com/rmestre/ContainerDemo.git PollService/</br>
<b>3. Build docker image</b></br>
docker build -t myapp .</br>
<b>4. Run docker container with newly created image</b></br>
docker run -t -d -p 5004:5004 myapp </br>
<b>5. That's it you can see your app at localhost:5004 (localhost on host machine i.e. linux vm)</b>
