
###### jenkins
docker exec -it jenkins bash # 交互
cat /var/lib/jenkins/secrets/initialAdminPassword # 看初始密码

docker exec jenkins-lts cat /var/jenkins_home/secrets/initialAdminPassword # 直接看初始密码

docker-compose logs -ft jenkins # 看日志