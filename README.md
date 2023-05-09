# ansible_shareplex
Ansible Automation for Installing SharePlex on Source and Target for Postgres to Postgres replication. 

## Main.yml: 
Main yml file for execution

## shareplex_vars.yml: 
Define variables for source and target servers

## shareplex_install.yml: 
copy software and install SharePlex on defined servers

## shareplex_setup.yml: 
setup odbc environment, setup shareplex thru pg_setup, and run pg_security for basic network security setup.

## shareplex_setup.yml: 
start shareplex processes (sp_cop) and return status 
