# satellite-reconfigure-ar

Role to re-configure deployed satellite for new domain name, password, certificates, etc.
This is copy of andible_bu_satellite role in AgnosticD
https://github.com/redhat-cop/agnosticd/tree/development/ansible/roles/ansible_bu_satellite

## Variables

pert_satellite_external_fqdn: "{{ groups['satellites'][0].split('.')[0] }}.{{ subdomain_base }}"
pert_satellite_user_name: admin
pert_satellite_user_password: "{{ common_password }}"

