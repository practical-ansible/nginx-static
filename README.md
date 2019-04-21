# Practical Ansible Nginx static site

[![CircleCI](https://img.shields.io/circleci/project/github/practical-ansible/nginx-static.svg)](https://circleci.com/gh/practical-ansible/nginx-static)
[![Quality](https://img.shields.io/ansible/quality/21429.svg)](https://galaxy.ansible.com/practical-ansible/nginx-static)
[![Downloads](https://img.shields.io/ansible/role/d/21429.svg)](https://galaxy.ansible.com/practical-ansible/nginx-static)

Deploy static HTML site to your Nginx and give it Lets Encrypt support.

## Variables

* `nginx_static_directory` - Path to directory that will be synced to the remote machine.
* `nginx_static_enabled` - Enable (default True)
* `nginx_static_project_environment` - Environment used to deploy data (default 'staging')
* `nginx_static_project_name` - Name that is used to identify your redirect
* `nginx_static_projects_directory` - Location used to store all the projects (default '/var/www')
* `nginx_static_server_name` - Space separated list of domain names that are to be redirected
* `nginx_static_version` - Project version used to identify the release (default 'develop')
