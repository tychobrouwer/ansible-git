Git install and configure
=========

This role installs and configures Git for my servers.

Role Variables
--------------

The git name and email should be set using the ```git_name``` and ```git_email``` variables.

The default branch and editor of git can be set using the ```git_branch``` and ```git_editor``` variables.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
- hosts: all
  vars:
    git_name: Jan Janssen
    git_email: janjanssen@gmail.com

  roles:
    - role: tychobrouwer.git
    
    - role: tychobrouwer.git
      git_branch: main
      git_editor: nano
```

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
