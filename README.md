#nodejs application deploymant on k8s using helm
step1:setting up the k8s cluster
   - Inintialze the mininkube in the local environment($minikube start)
   - verified the kubectl is intracted with the cluster($kubectl get node/pod ,kubectl config set-context mininkube)
step 2: preparing the Nodejs applicatiom
  - create simple nodejs applivcction with expressjs (npm init -y,npm install express)
  - containeraized the appl
