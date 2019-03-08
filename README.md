# firefox_in_container
Ansible Playbook and Dockerfile to launch firefox in contianer
Following steps are required :-
1) Docker engine must be previously installed on the container system. Here the system on which the docker is running has its hostname "container.lw.com". 
2) Change ip and hostname accordingly in your DNS file and /etc/ansible/hosts file. See the hosts file for futher reference.
3) Mention the folder where the Dockerfile is to kept in the container.lw.com in the var.yml file.
4) Run the playbook and enjoy using firefox.
5) By default firefox will always open google maps as soon we start the container.


