# AnsiblePlayground
## init swarm on local machine
`docker swarm init`
## init my-net
`docker network create --attachable --driver overlay --subnet=10.0.9.0/24 my-net`
## start playbook
`ansible-playbook site.yml`
