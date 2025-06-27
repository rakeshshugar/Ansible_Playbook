# Ansible Playbooks – Java, Git, Maven, and Spring Boot Setup

This repository contains Ansible playbooks to automate the setup of Java, Git, Maven, and a Spring Boot project on a target server.

---

## 📁 Contents

- **install_java_git.yml**  
  Installs Java 17 and Git on the target machine.

- **spring_setup.yml**  
  Performs complete setup:  
  - Installs Java 17, Git, and Maven  
  - Clones a Spring Boot project from GitHub  
  - Builds the project using Maven

---

## 🛠️ Requirements

- Ansible installed on the control node
- Target machine accessible via SSH
- User with sudo privileges on the target machine

---

## 👨‍💻 Author

**Rakesh S hugar**  

