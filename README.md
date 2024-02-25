<a name="_1ux3hpcrv11w"></a>Демо завдання Хмарного вітрильника

This is a simple list of task that gives you opportunity to start studying DevOps field. To study further we offer a 3 month course for you

**Note:** if you have no clue what is AWS, Terraform or other stuff - you may free to research it by yourself. This lab doesn’t check you knowledge. It’s a great opportunity to start

Всім привіт! Тут для тебе ми виклали перелік простих завдань для того, щоб закласти фундамент у твоєму розвитку в девопсі. Якщо тобі ще невідомі технології, які використовуються у цих завдання - не біда, саме для цього ми і вчимося)

## <a name="_45k0k46w3epy"></a>AWS
- [ ] Create new account on AWS 
- [ ] Create EC2 instance (Login as admin user) with the following specifications: 
  - OS: Ubuntu  
  - Resources: 1 CPU / 1 gb RAM
  - Open 22 port
  - Give name for your instance
- [ ] SSH onto this server from local machine
- [ ] Install docker, docker-compose on EC2, put here commands that you used
- [ ] Put here proofs that docker and docker-compose installed successfully 

## <a name="_mxqcu0c8cibh"></a>Terraform 
- [ ] Install terraform on your local machine
- [ ] Create AWS EC2 instance
  - It should has public ip
  - Add your ssh key, install docker + docker-compose 
  - Create security group and attach it to the EC2: 
    - in - 22 (home ip), 443, 80; 
    - out - all traffic
  - Attach 10 gb disk
- [ ] Output instance IP
- [ ] Destroy this instance
## <a name="_bv8m933g1ecj"></a>Containers
- [ ] Install docker desktop on your local machine
- [ ] Run container with name “webapp” and image nginx, which will be accessible via 8080 port (do it on your local machine)
- [ ] Put here command how to list docker images and container via cmd 

## <a name="_j7rj8qfn1ycp"></a>Bash
- [ ] Write bash script on your local machine which will create on your recently created ec2 instance docker container 
  - **Note 1:** you need to execute code from **your local machine** **via SSH**
  - **Note 2:** you should have access to nginx homepage via <http://ec2_instance_ip_example:8080>, so modify Security Group in advance
- [ ] Put screen of your <http://ec2_instance_ip_example:8080> site


