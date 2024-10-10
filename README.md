# Banking Microservices Application

## What is this project about?
This is a simple banking app split into 3 different parts (microservices): **Accounts**, **Loans**, and **Cards**. Each part does its own thing, but they work together to give users a full banking experience. For example, one microservice handles user accounts, another manages loans, and the last one deals with cards.

## What makes it cool?
- **Microservices Architecture**: Instead of building one big app, each service (Accounts, Loans, Cards) runs separately. This makes it easier to manage, scale, and update.
- **Docker**: The services are containerized, which means they can run anywhere. You don't have to worry about where they live!
- **Kubernetes**: Used to deploy and manage our services. It helps in automatically handling scaling, failures, and restarting.
- **Security**: The services are secured using **OAuth2** (don’t worry if you’re not familiar, it’s just for safety).
- **Kafka**: Some parts of the app need to talk to each other without waiting, and Kafka helps with that.
- **Monitoring**: The app comes with cool tools like **Prometheus** and **Grafana** to monitor how it’s doing. If something breaks, **Zipkin** and **Loki** help you figure out what went wrong.

## What can you learn?
By working with this project, you’ll learn:
- How to break up a big app into smaller, manageable parts (microservices).
- How to use **Spring Boot** and **Spring Cloud** to build and connect these services.
- How to use **Docker** and **Kubernetes** to run and manage apps easily.
- How to secure your services with **OAuth2**.
- How to monitor and trace errors using **Prometheus**, **Grafana**, and **Zipkin**.
