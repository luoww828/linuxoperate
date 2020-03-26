
安装docker准备工作：

yum install -y yum-utils device-mapper-persistent-data lvm2

yum-config-manager --add-repo  https://download.docker.com/linux/centos/docker-ce.repo

安装命令：
yum install docker-ce
查看安装的版本：
docker -v


进入docker 容器 ：docker exec -it 48d2691182f0 /bin/bash
把docker 挂载到宿主机的/usr/local/docker目录下：
docker run -d -p 8081:8080 -v /usr/local/docker/v:/usr/local/tomcat/webapps --name tomcat tomcat 

docker-compose 安装
yum install -y epel-release
yum install -y python-pip

pip install --upgrade pip
pip install --upgrade setuptools 

pip install docker-compose

docker-compose启动
docker-compose up

安装git:
yum install git

提交git项目
git add .

 
git commit -m  "update docker "

git push -u origin master
