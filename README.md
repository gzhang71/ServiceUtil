# ServiceUtil

This is a collection of config files I used in my private repo including: 
- Airflow. This is a task scheduler job consists three parts: one webserver, one scheduler and N workers. The current setting. All tasks are decoupled loosely using RabbitMQ. 

- JupyterHub. This is a centrally managed Jupyter Notebook service used for multi-user. This allows users to login to the same Jupyter from different machines, and protected by different permissions. 

- Postgres. The Postgres database connection config. The server is hosted locally using static IP. 
