# spring-gumball ci/cd example

### This example demonstrates the following two GitHub Workflows.

* https://help.github.com/actions/language-and-framework-guides/building-and-testing-java-with-gradle

* https://github.com/google-github-actions/setup-gcloud/tree/master/example-workflows/gke

### Build Dependencies

* Gradle 5.6
* JDK 11


### CMPE 172 - Lab #10 Notes by Sarthak Madrecha

# CI Workflow (Part 1)

screenshots for create grade.yml, create google.yml, update docker-compose.yaml, update deployment.yaml from action tab in GitHub and their builds 
<img width="1440" alt="CI - Workflow - 1" src="https://user-images.githubusercontent.com/59553910/168736285-7b3ec215-1b72-46a2-9026-5dc1e9ec104c.png">
<img width="1440" alt="CI - Workflow - 2" src="https://user-images.githubusercontent.com/59553910/168736301-5d3ad508-a2cb-4462-aa3b-217a862bf822.png">
<img width="1440" alt="CI - Workflow - 3" src="https://user-images.githubusercontent.com/59553910/168736304-0171a4a7-a304-468e-92fb-c331fa75faca.png">
<img width="1440" alt="CI - Workflow - 4" src="https://user-images.githubusercontent.com/59553910/168736307-f8408cac-08a9-4dad-95ce-cc5466740228.png">
<img width="1440" alt="CI - Workflow - 5" src="https://user-images.githubusercontent.com/59553910/168736314-cd7f063a-8717-43e3-9926-0b3d736bdb93.png">
<img width="1440" alt="CI - Workflow - 6" src="https://user-images.githubusercontent.com/59553910/168736317-86dec9d4-c12f-4109-bf94-98bba6d99f4b.png">
<img width="1440" alt="CI - Workflow - 7" src="https://user-images.githubusercontent.com/59553910/168736320-fc90799f-f656-44fa-9d56-fc50a7a91305.png">
<img width="1440" alt="CI - Workflow - 8" src="https://user-images.githubusercontent.com/59553910/168736321-fc1d743e-11aa-4abf-a621-0b358f56f12c.png">

# CD Workflow (Part 2)

service account
<img width="1440" alt="service - account" src="https://user-images.githubusercontent.com/59553910/168737179-254a6021-6250-4570-9a81-148add2fdadd.png">

service account with key
<img width="1440" alt="service - account - key" src="https://user-images.githubusercontent.com/59553910/168737241-7bb6584e-a84d-493b-87e4-d0023d30e28a.png">

secret keys
<img width="1440" alt="github - action - secrets" src="https://user-images.githubusercontent.com/59553910/168737323-3fdd82f8-1b57-4070-9df7-7298a942a4f4.png">

cluster created
<img width="1440" alt="create - cluster" src="https://user-images.githubusercontent.com/59553910/168737424-8ab406eb-1724-4047-b34a-c62da872326b.png">

pipeline test
<img width="1440" alt="initialize - release" src="https://user-images.githubusercontent.com/59553910/168737569-f167a1d9-17bd-4719-8be0-c224ab43efed.png">

<img width="1440" alt="release - created" src="https://user-images.githubusercontent.com/59553910/168737589-1d1e9619-5ab8-4b53-be59-d15e64234147.png">

<img width="1440" alt="release - trigger" src="https://user-images.githubusercontent.com/59553910/168737638-98031113-060d-4985-84e6-523afcfb522f.png">

<img width="1440" alt="release - trigger - overview" src="https://user-images.githubusercontent.com/59553910/168737670-7be1a165-a9cd-4323-9976-432003a0e4f9.png">

<img width="1440" alt="release - trigger - end" src="https://user-images.githubusercontent.com/59553910/168737737-9d1a8076-2487-4ef3-a585-2b0a37c6fbd2.png">

<img width="1440" alt="release- success" src="https://user-images.githubusercontent.com/59553910/168737905-d5b59a6c-611e-4bd2-b2af-c79d9af933b6.png">

workload
<img width="1440" alt="workloads" src="https://user-images.githubusercontent.com/59553910/168737958-1c8622a7-b7c7-4a97-bf36-64ed9e490041.png">

<img width="1440" alt="workloads - details" src="https://user-images.githubusercontent.com/59553910/168738173-5467a7ee-c41e-4628-ba14-d05761f42d46.png">

service 
<img width="1440" alt="services" src="https://user-images.githubusercontent.com/59553910/168738353-aba4242a-ef9a-4d06-a26d-9646af79f851.png">

ingress
<img width="1440" alt="create - ingress" src="https://user-images.githubusercontent.com/59553910/168738376-53d685d1-d2b0-4eea-ac23-f121013204e8.png">

<img width="1440" alt="ingress - created" src="https://user-images.githubusercontent.com/59553910/168738407-009053f3-e9cc-4d13-b640-5e07f3c67d92.png">

successfully deployed
<img width="1440" alt="proof - of - success" src="https://user-images.githubusercontent.com/59553910/168738572-f85c1292-9103-40b3-983b-e7bb35bdca3d.png">
