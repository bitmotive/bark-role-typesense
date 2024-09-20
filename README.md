BARK: Typesense
Configure typesense service with sane defaults.
v26.0 of Typesense Server requires Ubuntu 20 or later.
The config file is at /etc/typesense/typesense-server.ini
Logs are under /var/log/typesense/
Data dir is under /var/lib/typesense/

Requirements
All roles in the Bitmotive Ansible Role Kit are configuration driven.

Customize this role by providing environment variables in your shell or at the CLI when prompted during runtime.

Role Variables
TYPESENSE_SERVICE_PORT:

Port where typesense service should be listening to incoming requests

Dependencies
Currently assumes that python3 is installed on the target machine

License
MIT

Author Information
A Bitmotive Project: Build. Incubate. Train. https://bitmotive.com