# firefox_in_container
Ansible Playbook and Dockerfile to launch firefox in contianer
Following steps are required :-
1) Download the centos:latest image or copy its tar in the current folder.
2) Change ip and hostname accordingly in your DNS file and /etc/ansible/hosts file. See the hosts file for futher reference.
3) Mention the folder where the Dockerfile is to be kept in the container.lw.com in the var.yml file. If configuration is for localhost, then mention the current folder.
4) Run the playbook and enjoy using firefox.
5) By default firefox will always open google maps as soon we start the container.


