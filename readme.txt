
��װdocker׼��������

yum install -y yum-utils device-mapper-persistent-data lvm2

yum-config-manager --add-repo  https://download.docker.com/linux/centos/docker-ce.repo

��װ���
yum install docker-ce
�鿴��װ�İ汾��
docker -v


����docker ���� ��docker exec -it 48d2691182f0 /bin/bash
��docker ���ص���������/usr/local/dockerĿ¼�£�
docker run -d -p 8081:8080 -v /usr/local/docker/v:/usr/local/tomcat/webapps --name tomcat tomcat 

docker-compose ��װ
yum install -y epel-release
yum install -y python-pip

pip install --upgrade pip
pip install --upgrade setuptools 

pip install docker-compose

docker-compose����
docker-compose up

��װgit:
yum install git

�ύgit��Ŀ
git add .

 
git commit -m  "update docker "

git push -u origin master
