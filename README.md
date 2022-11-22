# devops_chal

## The task

1.	Create a GitLab Repository for the Challenge
2.	Create .devcontainer utilizing Ansible or Rocky Linux that contains everything to run ansible. Should be able to start the container from scratch, so make sure that the .devcontainer is setup for build. 
3.	Utilize the docker_container module https://docs.ansible.com/ansible/latest/collections/community/docker/docker_container_module.html#examples
    - Task - Build a Server Based HTTPD Server Container
    - Task - Start the Container (At this point should be able to go to http://localhost and see the site)
4.	Create a Template for the index.html
5.	Create a Task for copy over the index.html j2 template into the correct directory for httpd container. 
6.	Produce a Read Me file with instructions on how to run the playbook and validate. 

### Run the playbook

ansible-playbook ansible/site.yml