# Google Professional Cloud Developer: Deploying Google Applications to GKE

1. Question: Assuming that you have a group of YAML manifests in a subdirectory named deploy directly under your current app directory, which kubectl command will successfully deploy the application to GKE?
- [ ] kubectl apply -r ./deploy/
- [x] kubectl apply -f ./deploy/
- [ ] kubectl config -f ./deploy/
- [ ] kubectl config -r ./deploy/

2. Question: Which type of object configuration does not require that an explicit definition of the operations to be executed be specified?
- [ ] Universal object configuration
- [ ] Localized object configuration
- [x] Declarative object configuration
- [ ] Imperative object configuration


3. Question: Which two modes of operation are available in Google Kubernetes Engine?
- [ ] Basic
- [x] Standard
- [x] Autopilot
- [ ] Expert

4. Question: At a minimum, which IAM permissions are required in order to list clusters in GKE?
- [ ] container.clusters.bind
- [ ] container.clusters.list
- [x] container.clusters.get
- [ ] container.clusters.read

5. Question: Which statements accurately describe namespaces in Kubernetes., names must be unique within a namespace, but not across namespaces so it’s possible to have two identically named objects residing in different namespaces?
- [ ] Administrative
- [x] Resource names must be unique within a namespace
- [ ] Resource names must be unique across namespaces
- [ ] Identical names can occur in namespaces in Kubernetes Engine
- [x] Resource names do not need to be unique across namespaces

6. Question: Topology spread constraints depend on which attributes for identifying topology domains that nodes reside in?
- [ ] Node type
- [ ] Node policy
- [x] Node labels
- [ ] Name prefix

7. Complete the YAML manifest for a Role that will provide those bound to the role with read permissions to all pods in the sales namespace?
```yaml
apiVersion: rbac.authorization.k8s.io/v1
kind: Role
metadata:
  namespace: sales
  name: sales-pod-reader
rules:
- apiGroups: [""]
  resources: ["pods"]
  verbs: ["get", "watch", "list"]
```
- [ ] "get", "delete", "list"
- [x] "get", "watch", "list"
- [ ] "get", "update", "list"
- [ ] "get", "read", "list"

8. Which are valid categories under which new features in Google Kubernetes Engine may be classified?
- [x] Beta
- [ ] Available
- [ ] Gamma
- [x] Alpha
- [x] Stable


9. Why would it be wise to omit development (dev) dependencies when building a container using Cloud Build?
- [ ] Dev dependencies are disallowed in GKE
- [x] Effectively reduces attack surface
- [x] May reduce the time taken to build a container
- [ ] It is how it has always been done

10. VPC Service Controls makes it possible to use a context-aware access approach in control of cloud resources. Which attributes may organizations base their granular access policies on when using VPC Service Controls?
- [x] Identity type
- [x] Identity
- [ ] Resource type
- [x] IP address
- [ ] Group Permissions

11. Complete the policy.yaml manifest so that it will allow request traffic to flow to the pods in a nginx service?

```
apiVersion: networking.k8s.io/v1
kind: NetworkPolicy
metadata:
  name: allow-nginx
spec:
  podSelector:
    matchLabels:
      app: nginx
  <missing code>
  - from:
    - podSelector:
        matchLabels:
          allow: "true"
```
- [x] ingress:
- [ ] egress:
- [ ] allow:
- [ ] access: