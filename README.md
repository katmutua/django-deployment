# Django Deployment
Resources to deploy and provision an AWS EC2 instance and deploy a django applciation with ansible. 

##Deployment stack
- Ansible
- Nginx
- Supervisor
- Celery
- Uwsgi

##Launch
```
ansible-playbook deploy.yml -i hosts
```



