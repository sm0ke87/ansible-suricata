# ansible-suricata
<img alt="suricata" src="https://img.shields.io/badge/suricata-6.0.4-red"> <img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/sm0ke87/ansible-suricata/master">

## Basic setup IDS ##

Playbook was created for get knowledge in ansible

### What we are have? ###

* suricata.yml is playbook for install and configure suricata for IDS mode ([check it out ](https://suricata.readthedocs.io/en/suricata-6.0.4/quickstart.html#basic-setup "suricata docs"))

* suricata_stop.yml will stop service if it needs

### Launch ###

``` ansible-playbook suricata.yml -u root -i hosts --private-key {{ private key }} ```

and

``` ansible-playbook suricata_stop.yml -u root -i hosts --private-key {{ private key }} ```