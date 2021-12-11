# ansible-suricata

/suricata/v/:6.0.4

## Basic setup IDS ##

Playbook was created for get knowledge in ansible

### What we are have ###

suricata.yml is playbook will install and configure suricata for IDS mode (check it out https://suricata.readthedocs.io/en/suricata-6.0.4/quickstart.html#basic-setup)

suricata_stop.yml will stop service if it needs

### Launch ###

< ansible-playbook suricata.yml -u root -i hosts --private-key {{ private key }} >
< ansible-playbook suricata_stop.yml -u root -i hosts --private-key {{ private key }} >