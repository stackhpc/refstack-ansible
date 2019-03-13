------
Usage
------

ansible-galaxy install -p roles -r requirements.yml

deploy
--------

ansible-playbook setup.yml -i inventory/ -e @site.yml -e refstack_action=deploy --vault-password-file vault-pass

destroy
--------
ansible-playbook setup.yml -i inventory/ -e @site.yml -e refstack_action=destroy --vault-password-file vault-pass
