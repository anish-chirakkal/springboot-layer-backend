# springboot-layer-backend
Backend for Token Creation Using Java Spring Boot

## Steps to run application

1. There are three application.properties file inside main/resources folder. 
   application-sandbox.properties - The Token creation URL and authorization of sandbox can be given here
   application-live.properties - The Token creation URL and authorization of live can be given here
   application.properties - Just add spring.profiles.active=sandbox or live here to pick the profile accordingly.
   
2. If you do not want to maintain different files for sandbox and live, just add directly the below properties in application.properties file.
   open.api.url= <Create Token API URL for sandbox or live>
   open.api.token=Bearer <accesskey>:<secretkey>
   
3. After saving the above changes, run the LayerIntegrationApplication.java file.

Note: Make sure to configure the java build path(in the editor) and corresponding java version in pom.xml if you are not using Java version of the original application.

   
   
   
