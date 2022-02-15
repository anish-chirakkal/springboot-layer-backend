# springboot-layer-backend
Token Creation Using Java Spring Boot

## Steps to run application

1. Open the downloaded project/folder into your editor.

2. There are three application.properties file inside main/resources folder. 


   1. application-sandbox.properties - The Token creation URL and authorization of sandbox can be given here
   2. application-live.properties - The Token creation URL and authorization of live can be given here
   3. application.properties - Just add spring.profiles.active=sandbox or live here to pick the profile accordingly.
   
3. If you do not want to maintain different files for sandbox and live, just add the below properties in application.properties file and delete the    spring.profiles.active property.

   1. open.api.url= {Create Token API URL for sandbox or live}
   2. open.api.token=Bearer {accesskey}:{secretkey}
   
4. After saving the above changes, run the LayerIntegrationApplication.java file.

Note: Make sure to configure the java build path(in the editor) and corresponding java jdk version in pom.xml if you are not using Java version of the original application.

   
   
   
