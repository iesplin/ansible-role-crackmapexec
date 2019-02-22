ansible-role-crackmapexec
=========

Ansible role to install the 'Bleeging-Edge' version of CrackMapExec from the official GitHub repo

Example Playbook
----------------

    - hosts: servers
      roles:
        - role: ansible-role-crackmapexec
          jtr_local_src_dir: /usr/local/src
          jtr_openmpi_support_enabled: true
          jtr_rexgen_support_enabled: false

License
-------

MIT
