

[jenkins]

lz_master:~/environment $ helm install cicd stable/jenkins -f values.yaml                                                                          
WARNING: This chart is deprecated
NAME: cicd
LAST DEPLOYED: Tue Sep 29 02:03:45 2020
NAMESPACE: default
STATUS: deployed
REVISION: 1
NOTES:
*******************
****DEPRECATED*****
*******************
* The Jenkins chart is deprecated. Future development has been moved to https://github.com/jenkinsci/helm-charts

1. Get your 'admin' user password by running:
  printf $(kubectl get secret --namespace default cicd-jenkins -o jsonpath="{.data.jenkins-admin-password}" | base64 --decode);echo
2. Get the Jenkins URL to visit by running these commands in the same shell:
  NOTE: It may take a few minutes for the LoadBalancer IP to be available.
        You can watch the status of by running 'kubectl get svc --namespace default -w cicd-jenkins'
  export SERVICE_IP=$(kubectl get svc --namespace default cicd-jenkins --template "{{ range (index .status.loadBalancer.ingress 0) }}{{ . }}{{ end }}")
  echo http://$SERVICE_IP:80/login

3. Login with the password from step 1 and the username: admin

4. Use Jenkins Configuration as Code by specifying configScripts in your values.yaml file, see documentation: http:///configuration-as-code and examples: https://github.com/jenkinsci/configuration-as-code-plugin/tree/master/demos

For more information on running Jenkins on Kubernetes, visit:
https://cloud.google.com/solutions/jenkins-on-container-engine
For more information about Jenkins Configuration as Code, visit:
https://jenkins.io/projects/jcasc/
lz_master:~/environment $   printf $(kubectl get secret --namespace default cicd-jenkins -o jsonpath="{.data.jenkins-admin-password}" | base64 --decode);echo
p1TPI4jZRZ



http://ab2b3eb498ffc48b09cdd9cc882610b3-618372656.ap-southeast-1.elb.amazonaws.com/login

lz_master:~/environment $ echo $GIT_USERNAME
git-user-at-534993021321
lz_master:~/environment $ echo $GIT_PASSWORD
5SE+TTcnliwwxVkFM5u722oo4wj7pzA+s150SNFXGbE=


[2048]
http://3e100955-2048game-2048ingr-6fa0-1626240617.ap-southeast-1.elb.amazonaws.com/

[wordpress]
http://ae62ca4c19279413888fa4e3c3d422f6-1404490460.ap-southeast-1.elb.amazonaws.com/wp-admin/edit.php

[sample app[
http://a664e65b2f37a4345802dda760c2cc2e-212722739.ap-southeast-1.elb.amazonaws.com/

[kibana]
https://search-eksworkshop-logging-6u466w5mompxx4duxjeo2xk4qi.ap-southeast-1.es.amazonaws.com/_plugin/kibana/app/kibana#/home/tutorial/cloudwatchLogs?_g=()

[github]
aws-jeongjihwan
aws-jeongjihwan
qwer1234@12!


access tokens
231c3207c6bef00d4c3c85cd74a5e51dc7488d16


https://github.com/aws-samples/eks-workshop/blob/main/content/intermediate/245_x-ray/sample-back.files/main.go#L26


https://medium.com/@buw/aws-client-vpn%EC%9D%84-%EC%82%AC%EC%9A%A9%ED%95%98%EC%97%AC-%EA%B0%80%EC%A0%95%EC%97%90%EC%84%9C-%EC%97%85%EB%AC%B4-%ED%99%95%EC%9E%A5-b5416749081c


추가된 메세지
