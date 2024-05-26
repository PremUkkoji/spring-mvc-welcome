# Ant + Spring MVC and WAR file example

1. Build project with `ant`
2. `helloproject.war` file will be generated inside targert folder
3. Run Project
   - `brew install tomcat@9`
   - `brew services start tomcat@9`
   - Go to `/opt/homebrew/opt/tomcat@9/9.0.89/libexec/webapps` and copy the `helloproject.war`
   - Open browser and go to link --> `http://localhost:8080/helloproject`

## Reference
https://mkyong.com/ant/ant-spring-mvc-and-war-file-example/