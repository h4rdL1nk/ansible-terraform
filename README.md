```
ansible-playbook -e workdir=$(pwd) -e user='' -e pass='' --tags=templating play.yml
ansible-playbook -e workdir=$(pwd) -e user='' -e pass='' -e tf_action=present --tags=creating play.yml
```