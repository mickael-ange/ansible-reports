# ansible-reports
Repo for Ansible reports

# Playbooks

* [test-handlers-01](playbooks/test-handlers-01.yml): Play twice `test-handler-01` role with different variable value in order to test how an handler deals with redefined variable.
* [test-vars-01](playbooks/test-vars-01.yml): Issue with role dependency variable substitution and include task in Ansible 2.1.0, was working in ansible 2.0.2.0.
Ansible bug report: [https://github.com/ansible/ansible/issues/16080](https://github.com/ansible/ansible/issues/16080)


# Roles:

* [test-handler-01](roles/test-handler-01.yml): Define an handler using variable in its task. Flush handler at the end of the role.
* [test-vars-01](roles/test-vars-01.yml): Top level role for playbooks/test-vars-01.yml 
* [test-vars-01](roles/test-vars-01.yml): Top second level role for playbooks/test-vars-01.yml
