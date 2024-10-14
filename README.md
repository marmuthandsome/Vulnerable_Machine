# Setup Guide

This guide will walk you through the process of setting up Redis, MySQL, and DVWA on your local environment. We will cover the installation, startup instructions, and provide default credentials for each service.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Redis Setup](#redis-setup)
  - [Starting Redis](#starting-redis)
  - [Redis Credentials](#redis-credentials)
- [MySQL Setup](#mysql-setup)
  - [Starting MySQL](#starting-mysql)
  - [MySQL Credentials](#mysql-credentials)
- [DVWA Setup](#dvwa-setup)
  - [Starting DVWA](#starting-dvwa)
  - [DVWA Credentials](#dvwa-credentials)

## Prerequisites

Ensure that you have the following installed on your system:

- Docker
- Docker Compose

Alternatively, you can install Redis, MySQL, and DVWA manually if not using Docker.

## Redis Setup

### Starting Redis

If you are using Docker, you can start Redis with the following command:

```bash
docker run --name redis-server -d -p 6379:6379 redis
