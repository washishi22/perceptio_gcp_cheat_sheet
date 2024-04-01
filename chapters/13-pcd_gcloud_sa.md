# Google Professional Cloud Developer: Google Cloud Service Accounts

1. Question: Which field of Google Cloud’s projects.serviceAccounts.signJwt API endpoint defines the claims of a JWT?
- [ ] delegates
- [ ] claims
- [x] payload
- [ ] name
- [ ] jwt

2. Question: Which roles allow service account impersonation in Google Cloud?
- [ ] Manage Service Account
- [x] Service Account Token Creator
- [ ] View Service Account
- [ ] Edit Service Account
- [x] Service Account User

3. Question: What is the characteristic of Google-managed key pairs?
- [x] They support JSON Web Key (JWK) public key format
- [ ] The cloud user needs to handle rotation of the keys
- [ ] They are always valid for two weeks
- [ ] You can have a maximum of ten key pairs

4. Question: Which fields does Google Cloud’s projects.serviceAccounts.generateAccessToken API endpoint return?
- [ ] scope
- [x] accessToken
- [ ] id
- [x] expireTime

5. Question: What are the characteristics of a Google Cloud service account?
- [ ] Included in Google Workspace domain
- [x] Uses public/private RSA key pairs for security
- [x] Does not contain a password
- [ ] Does not support impersonation

6. Question: Which name field value is valid for the projects.serviceAccounts.delete Google Cloud API call? Assume a project exists with ID ‘MyProject’ and that project contains a service account with email ‘MyServiceAccount@google.com’.
- [x] projects/MyProject/serviceAccounts/MyServiceAccount@google.com
- [ ] serviceAccounts/MyServiceAccount@google.com
- [ ] serviceAccounts/MyServiceAccount@google.com/projects/MyProject
- [ ] projects/MyProject/MyServiceAccount@google.com

7. Question: What are the characteristics of the principle of least privilege?
- [x] Users are given the privileges they need
- [ ] Only administrators are given access to the system
- [x] Privileges are revoked when they are not required
- [ ] Admin rights are given frequently

8. Question: Which IAM role will allow you to call the Google Cloud’s projects.serviceAccounts.getIamPolicy API endpoint?
- [ ] Service Account Token Creator
- [ ] Delete Service Accounts
- [ ] Service Account Key Admin
- [x] View Service Accounts

9. Question: Which formats does Google Cloud support for private service account key downloads?
- [x] JSON
- [ ] XML
- [x] P12
- [ ] Text
- [ ] HTML

10. Question: Which Google Cloud monitoring component offers the most flexibility in specifying which data to display?
- [ ] Authentication Traffic chart
- [ ] Authentication Traffic per key chart
- [ ] Dashboard
- [x] Metrics Explorer
