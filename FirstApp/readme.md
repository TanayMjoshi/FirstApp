1. Add `<packaging>war</packaging>`
2. Add `build` section.
3. Create maven folder `src/main/java` , `src/main/resources` , `src/main/webapp`
4. Copy contents of WEB-INF under webapp
5. Run mvn clean install this will create the war file in /target folder
6. Copy file under `/webapps` folder
7. Start Tomcat
8. App is deployed successfully.
9. Now access your servlet from browser - `http://localhost:8080/firstAppWar_war/test`
10. Notice the servlet lifeccle and service logs are being printed on console

