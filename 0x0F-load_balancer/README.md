0x0F. Load balancer

Background Context
This task is targetted at improving our web stack so that there is redundancy for our web servers. This will allow us to be able to accept more traffic by doubling the number of web servers, and to make our infrastructure more reliable. If one web server fails, we will still have a second one to handle requests.

For this project, I will need to write Bash scripts to automate my work. All scripts must be designed to configure a brand new Ubuntu server to match the task requirements.

Resource
Load balancer
Web stack debugging
Introduction to load-balancing and HAproxy
HTTP Header
Debian/Ubuntu HAProxy packages

Tasks
0. Double the number of webservers
1. Install your load balancer
2. Add a custom HTTP header with Puppet
