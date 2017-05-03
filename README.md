Ansible Generic Topic Handler Listener Rumbling
==============================================

Giving a try to the listen property of Ansible handler, which is new in version
2.2.



Requirements
------------

- ansible >= 2.2
- molecule
- docker / vagrant libs for python
- tox

install requirements with pip in a virtualenv like:

```
$ virtualenv .venv
$ source .venv/bin/activate
(.venv) $ pip install -r requirements.txt -r test-requirements.txt
(.venv) $ molecule converge # molecule test would destroy the env
# OR
(.venv) $ tox
```

Example Playbook
----------------

Check out playbook.yml

License
-------

M.I.T.

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
