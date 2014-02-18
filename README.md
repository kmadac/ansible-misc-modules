ansible-misc-modules
====================

Some small modules for ansible (http://ansible.cc)

For now, only the patch module is available

patch
======

Example: 

```

name: Patch some paramiko code
patch: patchfile=/tmp/critical.patch filetopatch=/usr/share/pyshared/paramiko/critical"

```

Prerequisites:

GNU patch installed
