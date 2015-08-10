##Django-Ansible
Resources to deploy and provision an AWS EC2 instance and deploy a django application with ansible. The tools used for this include: - 
- Ansible
- Nginx
- Supervisor
- Celery
- Uwsgi

File permissions may be set as preffered in any of the role tasks created.
```
ansible-playbook deploy.yml -i hosts
```
Include project vars in the global vars folder as well as in the various vars files. 
```
<vars>/vars.yml
```

```
<role>/vars/*yml
```


