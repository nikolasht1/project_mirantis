# project_mirantis
- Requirements:
- Vagrant
- Docker
- Helm
- Jenkins
- Run command:
            vagrant up  in folder vagrant
- Connect via ssh: 
            ssh vagrant@10.0.0.10
            password: vagrant
- Run command: 
           cd jenkinslts
         kubectl apply -f namespace.yaml
         kubectl apply -f serviceAccount.yaml
         kubectl apply -f service.yaml volume.yaml
         kubectl apply -f deployment.yaml
- Open any brovser url:
         10.0.0.11:32200
