java -jar (项目下不同环境打包的jar)xx.jar --spring.profiles.active=dev

nohup java -jar eureka-center-0.0.1-SNAPSHOT.jar --spring.profiles.active=prod-1 >eureka-1.log &
nohup java -jar eureka-center-0.0.1-SNAPSHOT.jar --spring.profiles.active=prod-2 >eureka-2.log &
ps -ef | grep eureka-center-0.0.1-SNAPSHOT.jar | grep -v grep

C:\Windows\System32\drivers\etc\hosts
127.0.0.1 eureka-center1
127.0.0.1 eureka-center2

/etc/hosts
在127.0.0.1后面  eureka-center1 eureka-center2
service network restart