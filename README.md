<h1><img width="40" height="40" src="https://img.icons8.com/external-those-icons-flat-those-icons/24/external-Docker-Logo-social-media-those-icons-flat-those-icons.png" alt="external-Docker-Logo-social-media-those-icons-flat-those-icons"/> <b>container-implement-course</b></h1>

## Welcome to Container Implementation (Docker) Course

**this is Google Drive Folder:** *[link to slide](https://www.google.com)*

## Contents on this course including on this:
### Material content on training update with these section
- **What's Docker?**
  - Container Platform Interfaces
    1. [Docker](https://www.docker.com/)
    2. [Podman](https://podman.io/)
    3. [Portainer](https://www.portainer.io/)
  - How to install Docker on your PC with Hyper-V [<img width="20" height="20" src="https://img.icons8.com/matisse/100/youtube.png" alt="youtube"/>](https://www.youtube.com/watch?v=EdnDKJc8qBw) 
  - How to install Docker on your PC with WSL[<img width="20" height="20" src="https://img.icons8.com/matisse/100/youtube.png" alt="youtube"/>](https://www.youtube.com/watch?v=1G4xuqoLepI&t=271s)
  
    <label style="color: cornflowerblue"><u>**REMARK:** </u></label> on your PC has been enabled *<u style="color: salmon">Virtualization</u>* feature in BIOS both Hyper-V and WSL
  - More Information
    - รู้จัก Docker ใน 3 นาที [<img width="20" height="20" src="https://img.icons8.com/matisse/100/youtube.png" alt="youtube"/>](https://www.youtube.com/watch?v=nDIWwvy07uQ&t=14s)
    - docker จำเป็นจริงๆมั้ย [<img width="20" height="20" src="https://img.icons8.com/matisse/100/youtube.png" alt="youtube"/>](https://www.youtube.com/watch?v=rtqYzg6oJPw&t=380s)
- **Docker Components**
  
- **Basic Docker Commands**
  - Practices Docker commands by yourself with playground: *[Docker Playground](https://labs.play-with-docker.com)*
  - <u>Exercise Info</u><br/>For more information about container image<br/>
    1. [Hello-World](https://hub.docker.com/_/hello-world)
    2. [Geeting-Started](https://hub.docker.com/r/docker/getting-started)
    3. [Nginx:20-Alpine](https://hub.docker.com/_/nginx/tags?page=1&name=alpine)
  
- **Dockerfile**
  
- **Docker Registry**
  - Website Store Container Image for pulling & pushing with container repository: *[Docker Hub](https://hub.docker.com/)*
  
- **Docker Volume**
  
- **Docker Network**
  
- **Docker Compose**
  Follow Step in documetation link: *[Try Compose](https://docs.docker.com/compose/gettingstarted/)*
  - *<p style="color: wheat">Command for **start** compose creating containers with detach mode</p>*
    ```
    docker compose up -d
    ```
  - *<p style="color: wheat">Command for **stop** compose containers</p>*
    ```
    docker compose down
    ```
  - *<p style="color: wheat">Command for **editing** compose some containers with detach mode by re-create only the container has edited</p>*
    ```
    docker compose up -d --build
    ```
- **Portainer.io**

  - *<p style="color: wheat">Script for build & run portainer on your services</p>*
  ```
  docker run -d -p 9000:9000 --name=portainer --restart=unless-stopped -v /var/run/docker.sock:/var/run/docker.sock -v $HOME/portainer:/data portainer/portainer:latest
  ```
