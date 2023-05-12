# JavaDatabaseConnectivity
## Installing Apache Tomcat
Make sure Java JDK and JRE as well as Oracle Database is already installed in your system.  
You need to switch to administrator from the default user to avoid multiple permissions.  
> Open cmd as administrator and run command, net user administrator /active:yes  
> Install Apache Tomcat from the official website according the system specifications.  
> While installing, you need to change HTTP/1.1 Connector Port from 8080 to 8888 (or anything) because Oracle's default port is 8080. So, it will result in collision.  

## Launching Apache Tomcat
> Open 'Monitor Tomcat' from start menu.  
> You can start/stop from the navigation bar.  
> Open the browser and go to address, localhost:8888  

## Thin Driver Setup
> copy ojdbc14_g.jar from C:\oraclexe\app\oracle\product\10.2.0\server\jdbc\lib and paste it to the directory where you're working i.e. where your Java programs are present.  
> Open cmd from the working directory and execute the following command, jar xvf ojdbc14_g.jar  