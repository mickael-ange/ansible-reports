Role Description
================

Test handler behavior: When reusing a role, the handler is not using expecting role's variable value when using variable in handler task.

Dependencies
------------

None

Requirements
------------

None

Playbook Example
----------------


Define a playbook that calls twice 

```yaml
---
- hosts: 
    - localhost
  roles:
    - { role: test-handler-01, test_name: test1 }
    - { role: test-handler-01, test_name: test2 }

```


Role Variables
--------------


```
test_name: any string
```


License
-------

None


Author Information
------------------

Mickael Ange (akiran28@hotmail.com)


Contributors Information
------------------------


