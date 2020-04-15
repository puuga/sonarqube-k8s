# sonarqube-k8s

Create /data/sonarqube-database for storing the database

    mkdir -p /data/sonarqube-database
    
Create the sonar-db deployment
    
      kubectl apply -f https://raw.githubusercontent.com/jaganthoutam/sonarqube-k8s/master/sonar-db-deployment.yaml
      
 
Create the sonar deployment

      kubectl apply -f https://raw.githubusercontent.com/jaganthoutam/sonarqube-k8s/master/sonar-deployment.yaml
      
      
You can access the sonar:

      http://IPADDOFNODE:30010/sonar/
      user: admin
      pass: admin
      
