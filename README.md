# kubernetes-project
kubernetes-project
Tasks:
A) Run uname command in a single busybox container.The command should run every minute and must complete within 10 seconds or be terminated by Kubernetes. The CronJob name and container name should both be hello.
cronjob.yaml creates a "Cronjob" that runs every minute.

B) You have a broken Pod, what steps will you follow to troubleshoot?
Troubleshoot Applications

C) Create a pod named myapp with 4 containers, using nginx, redis, memchached, consul images
Create myapp.yaml file ,and made a coniguration inside . I put for the name pod myapp,that includes 4 containers.

D) Find a pod which is  using the most CPU resources and pipe the name to report.txt file * Create the report.txt file.

E) Create a new pod , from  redis image ,running in web namespaces and listening at port 9090

F) Create a pod in test  namespace and set  resource limit to 1Gi of memory and 200m CPU * Create the namespace if it doesn’t exist
