# ansible-reports
Repo for Ansible reports

# Playbooks

* [test-handlers-01](playbooks/test-handlers-01.yml): Play twice `test-handler-01` role with different variable value in order to test how an handler deals with redefined variable.

# Roles:

* [test-handler-01](roles/test-handler-01.yml): Define an handler using variable in its task. Flush handler at the end of the role.
