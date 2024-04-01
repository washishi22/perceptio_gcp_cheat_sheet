# Google Professional Cloud Architect: Using Google Container Orchestration

1. Question: Which Service type should be used to publish a GKE service to public users over the internet?
- [ ] NodeIP
- [x] LoadBalancer
- [ ] ClusterIP
- [ ] Ingress

2. Question: Which are best practices for building container apps?
- [ ] Avoid handling Linux signals
- [x] Create images with common layers
- [x] Build smallest possible images
- [ ] Create images with only unique layers
- [x] Package one app per container

3. Question: Which filenames are supported when using a Cloud Build config?
- [ ] cloudbuild.js
- [x] cloudbuild.json
- [ ] cloudbuild.cfg
- [x] cloudbuild.yaml

4. Question: Which are common use cases that effectively leverage Cloud Run?
- [x] Websites and web applications
- [ ] Lift and shift migrations
- [x] API-based web services
- [ ] Continuous delivery pipeline

5. Question: Which statements accurately describe containers?
- [x] Virtualize at the OS layer
- [x] Use a shared OS kernel
- [ ] Use a private OS kernel
- [ ] Virtualize at the hardware layer

6. Question: You are using Cloud Build to build a container. Which gcloud CLI command can be used to build a container image using a config file named cloudbuild.yaml?
- [ ] gcloud submit --build true --region=us-central1 --config cloudbuild.yaml
- [ ] gcloud docker build --region=us-central1 --config cloudbuild.yaml
- [x] gcloud builds submit --region=us-central1 --config cloudbuild.yaml
- [ ] gcloud docker submit --region=us-central1 --config cloudbuild.yaml

7. Question: Which are required APIs for deploying containers using Cloud Run?
- [x] Cloud Build API
- [ ] Cloud Compute API
- [x] Artifact Registry API
- [x] Cloud Run Admin API
- [ ] Cloud Storage Admin API

8. Question: Which statements accurately describe Cloud Run?
- [ ] Cloud Run provides full control of VM
- [ ] Cloud Run gives customers control over clusters
- [x] Cloud Run is a fully managed service
- [x] Cloud Run is considered a serverless service

9. Question: What are some advantages offered by using Kubernetes Engine?
- [ ] Very simple cluster configuration
- [x] Clusters function as a single system
- [ ] Less expensive than other GCP services
- [x] Deployments are scaled automatically

10. Question: Which are use cases that effectively leverage GKE?
- [x] Migrate workloads to containers
- [ ] Lift and shift cloud migrations
- [ ] Running dynamic HTML websites
- [x] Continuous delivery pipeline

11. Question: While evaluating the Mountkirk Games case study you learn that they wish to roll out new continuous deployment capabilities while updating their software at a fast pace. Which complementary Google services could they utilize for the build step in their continuous delivery pipelines?
- [ ] Build Automate
- [ ] Cloud Compute
- [x] Artifact Registry
- [x] Cloud Build

12. Question: Compute Engine allows an organization to create scalable services by leveraging which resource?
- [x] Managed instance groups
- [ ] Managed virtual machines
- [ ] Managed Fleet machines
- [ ] Virtual machine groups

13. Question
 
Complete the code snippet that creates a firewall rule to publish a port from a container deployed using GCE.

```
gcloud compute firewall-rules <missing code> allow-http `
   --allow tcp:3000 `
   --target-tags http-express
```

- [ ] --name
- [ ] name
- [ ] --create
- [x] create
