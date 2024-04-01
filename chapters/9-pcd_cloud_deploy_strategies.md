# Google Professional Cloud Developer: Google Cloud Deployment Strategies

1. Question: In order to make sure that the PATH actually contains the spinnakers command line tools like spin and hal; which command should be ran?
- [x] Source $HOME/.bashrc
- [ ] Source Reload $PATH
- [ ] Source ./bash
- [ ] Source $HOME/.path
- [ ] Source $PATH/.bashrc

2. Question: Which testing strategy is used when you want to deploy your application to a subset of users for feedback, before releasing it to all users?
- [ ] Blue/green deployment
- [ ] Shadow pattern
- [x] Canary pattern
- [ ] Rolling deployment
- [ ] A/B pattern

3. Question: Traffic splitting allows you to perform which type of testing scenario?  
- [ ] Canary testing
- [ ] Rolling deployments
- [x] A/B testing
- [ ] Shadow testing
- [ ] Blue/green deployments

4. Question: Which template type is a template that is configured to work together and create resources interchangeably?
- [ ] nested template
- [ ] joined template
- [ ] team template
- [ ] custom template
- [x] composite template

5. Question: Which Anthos concept refers to the simplification in managing multi-cluster deployments and allows users to logically group and normalize Kubernetes clusters?
- [x] Fleets
- [ ] Cluster groups
- [ ] Taskforces
- [ ] Instance groups
- [ ] Teams

6. Question: What are the advantages to performing a rolling deployment?
- [ ] Backward capability
- [ ] Quick upgrade time
- [ ] Complexity of setup
- [x] Quick rollback
- [x] Lower cost compared to blue/green

7. Question: What is a drawback when running a blue/green deployment?
- [ ] Rollback capabilities
- [ ] Speed of deployment
- [ ] Complexity of setup
- [ ] Backup options
- [x] Cost

8. Question: What are some downsides of canary deployments?
- [ ] No test feedback available
- [ ] Frustration of group using buggy canary release
- [ ] Very high cost
- [x] Hard to rollback
- [x] Time to set up canary pipeline

9. Question: Which file is used by the Cloud Build service to determine which steps must be followed to successfully build your application?
- [ ] dockerbuild.yaml
- [ ] Dockerfile
- [ ] build.spec
- [x] cloudbuild.yaml
- [ ] app.yaml

10. Question: Which Tekton component is responsible for defining a series of steps that specify order of execution as part of your CI/CD workflow?
- [ ] builder
- [ ] taskrun
- [ ] pipeline
- [ ] trigger
- [x] task
