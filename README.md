🛒 E-Commerce Website (Ansible Automated Deployment)

A fully automated E-commerce web application deployed and configured using Ansible. This project demonstrates a production-style architecture using modern configuration-management practices to manage the frontend, backend, and database layers across multiple servers or environments.

📌 About

This project is a complete Ansible-powered e-commerce platform designed to showcase a production-ready automation and deployment workflow using modern configuration-management techniques. The goal is to provide a scalable and modular setup where each component—frontend, backend, and database—is provisioned, configured, and managed through Ansible playbooks, ensuring consistency, repeatability, and efficient deployment across environments.

While Ansible is powerful and widely adopted, it's important to understand one of its limitations: Ansible is not stateful like Terraform. It does not maintain a persistent state file that tracks the infrastructure’s exact configuration. Because of this, Ansible cannot automatically detect infrastructure drift and relies heavily on the idempotency of modules. This makes it less ideal for managing large-scale, long-lived cloud resources.

However, Ansible excels at what it is designed for:
configuration management, server provisioning, application deployment, and orchestration.
Its simplicity, agentless nature, and flexibility make it perfect for consistently configuring systems, deploying code, installing services, and automating operational tasks across multiple hosts.

In short:
Terraform = best for provisioning infrastructure
Ansible = best for configuring and managing infrastructure