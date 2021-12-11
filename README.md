# ansible-suricata
<img alt="AUR license" src="https://img.shields.io/aur/license/Apache%202"> <img alt="suricata" src="https://img.shields.io/amo/v/6.0.4?label=suricata">

## Basic setup IDS ##

Playbook was created for get knowledge in ansible

### What we are have? ###

suricata.yml is playbook for install and configure suricata for IDS mode (check it out https://suricata.readthedocs.io/en/suricata-6.0.4/quickstart.html#basic-setup)

suricata_stop.yml will stop service if it needs

### Launch ###

``` ansible-playbook suricata.yml -u root -i hosts --private-key {{ private key }} ```

and

``` ansible-playbook suricata_stop.yml -u root -i hosts --private-key {{ private key }} ```