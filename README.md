common_bitbucket-create-repo
=========

This role will create a repo on bitbucket.
This will also need a set-vars-all of the project you will work on.

Requirements
------------

All dependencies will appear on requirements.yml file

Role Variables
--------------

bitbucket_create_repo:
  1:
    repo_name: repo4
    workspace: arsolute
    project: MONO
    is_private: true
    scm: git


Dependencies
------------

All dependencies will appear on requirements.yml file

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: xussof.common_create-user }

License
-------

BSD

Author Information
------------------
Made by @xussof
