# Application with auto-deployment capabilities - UDAPEOPLE
In this project, I setup a CI/CD pipeline to auto-deploy a React/Nestjs application to AWS using CircleCi and Ansible. I configure alerts to a slack channel to notify the team on successful or failed builds.
I also configure Prometheus as a tool for logging and monitoring, with alert-manager on the side to send critical alert errors to my email.

### Relevant links (temporary):

- Production Frontend URL: [http://d1ay69k43k8yae.cloudfront.net](http://d1ay69k43k8yae.cloudfront.net)
- Backend URL: [http://ec2-52-90-173-48.compute-1.amazonaws.com:3030](http://ec2-52-90-173-48.compute-1.amazonaws.com:3030)
- Prometheus Dashboard: [http://ec2-18-234-128-93.compute-1.amazonaws.com:9090](http://ec2-18-234-128-93.compute-1.amazonaws.com:9090/)

### Built With

- [Circle CI](www.circleci.com) - Cloud-based CI/CD service
- [Amazon AWS](https://aws.amazon.com/) - Cloud services
- [AWS CLI](https://aws.amazon.com/cli/) - Command-line tool for AWS
- [CloudFormation](https://aws.amazon.com/cloudformation/) - Infrastrcuture as code
- [Ansible](https://www.ansible.com/) - Configuration management tool
- [Prometheus](https://prometheus.io/) - Monitoring tool
