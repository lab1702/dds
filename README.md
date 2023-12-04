# Dockerized Data Science

***The default settings here leave everything configured without passwords and are intended for a personal workstation
where you can access them only via localhost.***

Clone:

    git clone https://github.com/lab1702/dds.git
    cd dds

To update images:

    docker-compose pull

To start:

    docker-compose up -d

Then access JupyterLab at: [http://localhost:8888/](http://localhost:8888/)
and RStudio at: [http://localhost:8787/](http://localhost:8787/).

To watch logs:

    docker-compose logs -f

To stop:

    docker-compose down

To clean up unused images:

    docker system prune -f
