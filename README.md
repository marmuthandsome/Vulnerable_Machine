# Setup Guide

This guide will walk you through the process of setting up Redis, MySQL, and Apache on your local environment. We will cover the installation, startup instructions, and provide default credentials for each service.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Redis Setup](#redis-setup)
  - [Starting Redis](#starting-redis)
- [MySQL Setup](#mysql-setup)
  - [Starting MySQL](#starting-mysql)
  - [MySQL Credentials](#mysql-credentials)
- [Apache Setup](#apache-setup)
  - [Starting Apache](#starting-apache)
  - [Apache Credentials](#apache-credentials)

## Prerequisites

Ensure that you have the following installed on your system:

- Virtual Box

## Redis Setup

### Starting Redis

You can start Redis with the following command:

- Go to directory `C:/Program Files/Redis`.
- Open file redis-cli.exe.
- Run commands `shutdown`.
- Open powershell and Go to folder `C:/Program Files/Redis`.
- And run command `redis-server --protected-mode no`.
- And the redis running on port 6379.

## Mysql Setup

### Starting Mysql

You can start Mysql with the following command:

- Using XAMPP Application.
- And start the Mysql.

### Mysql Credentials

```
username: root
password: <blank>
```

## Apache Setup

### Starting Apache

You can start Apache with the following command:

- Using XAMPP Application.
- And start the Apache.

### Apache Credentials

- Visit `https://localhost/DVWA/login.php`.
```
username: admin
password: password
```

---
