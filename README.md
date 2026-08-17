# Nikita Lystsev

## Junior DevOps Engineer

Portfolio focus: containerized services, reverse-proxy configuration, and CI test automation. The projects below link directly to public implementation artifacts; they are educational or test-task work, not production experience.

## Selected projects

### [BookSmart](https://github.com/nikitalystsev/BookSmart)

An educational library-booking service with an existing multi-container infrastructure layer.

Project infrastructure includes Docker and Docker Compose, Nginx routing and load balancing, PostgreSQL primary/replica services, Redis, and GitLab CI test/report jobs.

Evidence:

- [Docker Compose](https://github.com/nikitalystsev/BookSmart/blob/main/docker-compose.yml)
- [Application Dockerfile](https://github.com/nikitalystsev/BookSmart/blob/main/Dockerfile)
- [Nginx configuration](https://github.com/nikitalystsev/BookSmart/blob/main/nginx/nginx.conf)
- [GitLab CI configuration](https://github.com/nikitalystsev/BookSmart/blob/main/.gitlab-ci.yml)
- [Run notes and infrastructure overview](https://github.com/nikitalystsev/BookSmart#readme)

### [Stackbridge DevOps test task](https://github.com/nikitalystsev/stackbridge_devops_test_task)

A small test-task application where Docker Compose connects a containerized Python backend to an Nginx reverse proxy on a dedicated bridge network.

Evidence:

- [Docker Compose](https://github.com/nikitalystsev/stackbridge_devops_test_task/blob/main/docker-compose.yml)
- [Backend Dockerfile](https://github.com/nikitalystsev/stackbridge_devops_test_task/blob/main/backend/Dockerfile)
- [Nginx reverse-proxy configuration](https://github.com/nikitalystsev/stackbridge_devops_test_task/blob/main/nginx/nginx.conf)
- [Run and verification instructions](https://github.com/nikitalystsev/stackbridge_devops_test_task#запуск-проекта)
