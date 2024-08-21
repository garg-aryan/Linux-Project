# Linux-Project
This project sets up various virtual machines, using both manual and automated provisioning, to host a website that utilizes RabbitMQ, Apache Tomcat servers, and MySQL databases.

In the manual provisioning process, the Vagrantfile is used only to create the virtual machines, while the user manually configures each machine using the necessary commands.

In the automated provisioning process, the entire workflow—including creating, configuring, and initializing the virtual machines—is handled by the script. The user only needs to run vagrant up to initiate the setup.
