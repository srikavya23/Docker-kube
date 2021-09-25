# Docker-kube
# Google Kubernetes Engine

In the cloud shell environment type the following command to set the zone:

        gcloud config set compute/zone us-central1-b

After seting the zone, start up a cluster for use

        gcloud container clusters create io

Clone the GitHub repository from the Cloud Shell command line:

        gsutil cp -r gs://spls/gsp021/* .
        
Change into the directory needed for this lab:

        cd orchestrate-with-kubernetes/kubernetes
