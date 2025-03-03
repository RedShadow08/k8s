**KUBERNETES MANIFEST FILES**

The files contain the example of manifest files for different objects.

Kubernetes Objects 
  1. Pod
  2. ReplicaController
  3. ReplicaSet
  4. Deployment
  5. Services
       - clusterIP
       - NodePort
       - LoadBalancer

Volumes:
  1. EmptyDir
  2. hostpath
  3. Persistent Volume (persistent volume claim)


Secrets & ConfigMap
 >> kubectl create cm <name> --from-file=<filename>
 >> kubectl create secrets <name> --from-file=<file1> --from<file2>
