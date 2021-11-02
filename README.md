# LPP kiosk slideshow machines setup

basic usage:
- ensure inventory.yaml is upto date 
- ensure variables are ok inside setup.yaml
- install roles `ansible-galaxy install -f -r roles/requirements.yml`
- install collections `ansible-galaxy collection install -f -r collections/requirements.yml`
- run `ansible-playbook -i inventory.yaml setup.yaml`