# KUT-MSA-Design-Pattern-2

http://naver.me/GYcse7UL

https://drive.google.com/drive/folders/1eBNixcIilwmFxQZ6nSFsL3ZXxoLilGZR?usp=sharing

### Lab environment settings

1. VirtualBox
2. VirtualBox Host Key on VM (ctrl+alt)
3. Setting Network(NatNetwork)
   192.168.15.0/24
4. Import VirtualBox image(Dockersvr.ova)
5. user1, 1234
6. Connect after installing Putty
   localhost:22
7. Install Visual Studio Code
8. Install Extensions (Spring Boot Extension Pack, Docker, Java, YML, Maven...)
9. Connect to Remote SSH


### Multple Projects on Visual Studio Code

         <?xml version="1.0" encoding="UTF-8"?>
         <project xmlns="http://maven.apache.org/POM/4.0.0" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
         	xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 https://maven.apache.org/xsd/maven-4.0.0.xsd">
         	<modelVersion>4.0.0</modelVersion>
         
           <groupId>co.kr.ideacube</groupId>
           <artifactId>springboot-microservices</artifactId>
           <version>1.0</version>
           <name>springboot-microservices</name>
           <packaging>pom</packaging>
         
         	<parent>
         		<groupId>org.springframework.boot</groupId>
         		<artifactId>spring-boot-starter-parent</artifactId>
         		<version>3.2.4</version>
         		<relativePath/>
         	</parent>
         
           <properties>
             <project.build.sourceEncoding>UTF-8</project.build.sourceEncoding>
             <maven.compiler.source>17</maven.compiler.source>
             <maven.compiler.target>17</maven.compiler.target>    
           </properties>
             
           <modules>
             <module>...</module>
               ....
           </modules>
         </project>
