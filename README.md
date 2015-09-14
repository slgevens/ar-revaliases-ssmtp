ansible-revaliases-ssmtp
========================

Ansible role for configuring the revaliases file of sSMTP

We use [ansible-ssmtp](https://github.com/brisho/ansible-ssmtp)
installable via
[ansible-galaxy](https://galaxy.ansible.com/list#/roles/158)

This one can be used as secondary stage configuration for ssmtp

Role Variables
--------------

See templates/revaliases.j2 file

Reuse ansible-ssmtp variables

  **ssmtp_mailhub** - Hostname or IP address of server that will receive emails

  **ssmtp_rewrite_domain** - Mail will seem to come from this domain

Add a list of alias

  **ssmtp_revaliases** - list of reveresed aliases
