#使用JDK8环境作为基础镜像
FROM java:8

#拷贝文件并且重命名
COPY build/libs/bob-0.0.1-SNAPSHOT.jar bob.jar

# 指定容器需要映射到主机的端口
EXPOSE 8081

#容器启动时执行的指令
ENTRYPOINT [ "java", "-jar", "/bob.jar"]