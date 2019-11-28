# nautilus_cluster_guide
You should get the storage first if you want to donwload your dataset.
##How to get the permanent storage:
‘’‘
kubectl apply -f storage.yaml
'''
## How to get an interactive shell:
use the "Pod". But a pod can only exist for 6 hours. For long time use, you should create a job.
Create "Pod"
'''
kubectl create -n ecepxie -f login.yaml
'''
