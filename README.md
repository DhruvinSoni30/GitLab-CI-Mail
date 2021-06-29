# What is GitLab CI/CD?

**GitLab CI/CD** is a tool built into GitLab for software development through the continuous methodologies: 

* `Continuous Integration (CI)`

* `Continuous Delivery (CD)`

* `Continuous Deployment (CD)`

**CI/CD** is a method to frequently deliver apps to customers by introducing automation into the stages of app development. Specifically, CI/CD introduces ongoing automation and continuous monitoring throughout the lifecycle of apps, from integration and testing phases to delivery and deployment.

Learn more about GitLab CI/CD by visiting below page.

https://docs.gitlab.com/ee/ci/README.html

In this tutorial you can learn how send email to Gmail accout using GitLab CI/CD

**Step 1:-** Create account on [mailgun](https://www.mailgun.com/)

**Step 2:-** Get the value of Domain & API key from mailgun

API Key: ![apikey](https://github.com/DhruvinSoni30/GitLab-CI-Mail/blob/main/key.png?raw=true)

Domain Name: ![domainname](https://github.com/DhruvinSoni30/GitLab-CI-Mail/blob/main/domain.png?raw=true)

**Step 3:-** Create repo on GitLab and add below environment variables in it. 

![mail](https://github.com/DhruvinSoni30/GitLab-CI-Mail/blob/main/mail.png?raw=true?)

**Step 4:-** Create .gitlab-ci.yml file and add code provided above

**Step 5:-** As soon as you commit the code you will receive the mail like below

![sample](https://github.com/DhruvinSoni30/GitLab-CI-Mail/blob/main/maill.png?raw=true)
