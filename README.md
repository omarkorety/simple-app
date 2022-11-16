# ITI-FinalProject files and Jenkins files
Building and deploying an application using Jenkins CI/CD
## Docoratize the application 
#### build the app then push it to Docker hub
```bash
docker build -t omarkorey/myapp:V1 .
docker push omarkorey/myapp:V1  
```

# content of Jenkins file
## jenkins file has 2 stages :
### Build stage :
#### build the app then push it to Docker hub
### Deploy stage :
#### authorize  my service account to  jenkins deployment 
#### create deployment from our Docoratize application 
  
 
