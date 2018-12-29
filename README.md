# AnsiblePlayground
## create secret api-key
`printf "<api-runner-token>" | docker secret create gitlab-runner-token -`
## init swarm on local machine
`docker swarm init`
## init network for swarm services
`docker network create --attachable --driver overlay --subnet=10.0.9.0/24 my-net`
## start playbook
`ansible-playbook site.yml`
