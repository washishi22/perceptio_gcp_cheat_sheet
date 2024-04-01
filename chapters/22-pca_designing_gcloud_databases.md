# Google Professional Cloud Architect: Designing Google Cloud Databases

1. Question: Which is the correct format for the running Cloud SQL Auth proxy assuming you’ve downloaded it, renamed it cloud_sql_proxy.exe, and copied to the current directory?
- [ ] ./cloud_sql_proxy -database=INSTANCE_CONNECTION_NAME=tcp:1433
- [x] ./cloud_sql_proxy -instances=INSTANCE_CONNECTION_NAME=tcp:1433
- [ ] ./cloud_sql_proxy -database=INSTANCE_CONNECTION_NAME=tcp:80
- [ ] ./cloud_sql_proxy -instances=INSTANCE_CONNECTION_NAME=tcp:8080

2. Question: You have just installed gcloud CLI. Which command should you now use to configure gcloud?
- [ ] gcloud --init
- [ ] gcloud --config
- [x] gcloud init
- [ ] gcloud config

3. Question: Which gcloud command may be used to list the clusters for an instance assuming the instance is named my-bigtable-instance?
- [x] gcloud bigtable clusters list --instances=my-bigtable-instance
- [ ] gcloud bigtable --clusters --list --instances=my-bigtable-instance
- [ ] gcloud bigtable clusters --list-instances=my-bigtable-instance
- [ ] gcloud bigtable list --instances=my-bigtable-instance

4. Question: You’ve opened a public data set in Google cloud console using BigQuery. When you select QUERY in the public data set toolbar, which options appear?
- [ ] In new terminal
- [x] In new tab
- [x] In split tab
- [ ] In new window

5. Question: While evaluating the Mountkirk Games case study you learn that they want to provide a leader board in a global setting. Which relational database is ideally suited for such a feature?
- [x] Cloud Spanner
- [ ] Cloud SQL
- [ ] Firestore
- [ ] Cloud Storage

6. Question: Which are typical relational database features?
- [ ] Data is written to any location across a deployment
- [x] Writes are generally performed to one location
- [ ] Scaling is performed by adding commodity-type servers
- [x] Scaling is performed by scaling servers up

7. Question: Which statements accurately describe typical NoSQL databases?
- [x] Support cost-effective scaling
- [ ] Typically scale for reads but not writes
- [ ] Support fixed schema
- [x] They scale horizontally
- [x] Support dynamic schema

8. Question: Which are characteristics of Cloud Bigtable?
- [x] Delivers sub-10ms latency
- [ ] Delivers up to 4-9’s of availability
- [x] Ideally suited for IoT use cases
- [ ] 1 hour downtime for reconfiguration

9. Question: Which command is used to install the Firebase CLI?
- [ ] npm -g firebase-cli
- [ ] npm -g firebase-tools
- [x] npm -g i firebase-tools
- [ ] npm -g i firebase-cli

10. Question: You are creating a MySQL database instance in Google cloud console. On the create a MySQL instance page which versions are available under Database version?
- [x] MySQL 8.0
- [ ] MySQL 6.0
- [x] MySQL 5.7
- [ ] MySQL 7.2
