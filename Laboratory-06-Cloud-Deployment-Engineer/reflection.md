# Mission Reflection – Laboratory 6

## Reflection

In this activity, I learned how using a `docker-compose.yml` file can make a cloud engineer's job easier compared to manually typing Docker commands. Instead of running separate commands for each container, Docker Compose allows multiple services to be defined in one YAML file and deployed together using a single command.

I also learned that YAML is sensitive to indentation, so using a Tab instead of the required spaces can cause an error and prevent the configuration from working properly. This taught me that careful formatting is important when writing Infrastructure as Code.

I learned that environment variables such as `MYSQL_PASSWORD`, `MYSQL_DATABASE`, and `MYSQL_USER` are used to provide configuration information to the containers and allow the Nextcloud application to connect correctly to the MariaDB database. Using these variables also keeps the configuration organized instead of putting all settings directly into application commands.

It was also a good experience to deploy a functional enterprise cloud storage system like Nextcloud in just a few minutes. Seeing the Nextcloud installation page through the browser showed me how a web application and database can work together as a multi-tier system.

Compared to my first Cloud Computing activities, my understanding has developed from learning basic cloud concepts to actually deploying and managing containers and services. I now have a better understanding of Docker, Docker Compose, multi-tier architecture, YAML configuration, and Infrastructure as Code. This mission also helped me become more comfortable using the Linux command line and troubleshooting deployment steps.

Overall, the activity showed me that cloud engineers can use code and automation to make infrastructure deployment more organized, repeatable, and efficient.