This Project is about implementing a CI/CD pipeline with the following DevOps tools
(1)Git: For Version control and tracking changes in the code files (2) Jenkins : For continuous integration (3) Ansible : For continous deployment (4) Docker: For deploying containerized applications (5) Dockerhub : For storing Docker images

As soon as the Developer pushes the code to GitHub,Jenkins will take that code and build the .WAR file and then copied to Ansible.The Docker image is then created on Ansible server through Jenkins and Pushed to Dockerhub.Post this, the Docker node pulls the image from DockerHub and build the Docker container.






![Addressbook Screenshot](addressbook_screenshot.png "Addressbook Screenshot")

