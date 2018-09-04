# Test results

## Smoke testing

Smoke tests are a subset of tests covering important functionality of an application, used to aid assessment if its main functions appear to work correctly. They are not a replacement of a fully tested application, which should be done by the upstream project.

Bitnami maintained dockerfile images are smoke tested in a docker compose deployment to ensure important functions work properly.

## Test summary

Application: **Drupal 8.5.6**

Dockerfile: [`8-rhel-7`, `8.5.6-rhel-7-r0`](./Dockerfile) 

Date: **2018-09-01 11:34:23**

Test | Compose
--- | :---:
[Log in and out](#log-in-and-out) | Ok
[Check up to date](#check-up-to-date) | Ok
[Add article](#add-article) | Ok
[Check existing article](#check-existing-article)  | Ok
[Add image](#a) | Ok
[Check image](#a) | Ok
[Add page](#a) | Ok
[Check page](#a) | Ok
[Change fav icon](#a) | Ok
[Check fav icon](#a) | Ok
[Change logo](#a) | Ok
[Check logo](#a) | Ok
[Check htaccess](#a) | Ok
[Add user](#a) | Ok
[Login new user](#a) | Ok

## Test details

### Log in and out

- **Description**: It should be possible to log in and out  
- **Test results**:
  - GKE (Google): **Pass** (in 4.3 seconds on 2018/09/01 at 23:49:13)
  - AKS (Azure): **Pass** (in 3.1 seconds on 2018/09/01 at 12:31:01)
  - OKE (Oracle): **Pass** (in 1.9 seconds on 2018/09/01 at 10:00:58)

### Check up to date

- **Description**: The application should be up to date  
- **Test results**:
  - GKE (Google): **Pass** (in 4.3 seconds on 2018/09/01 at 23:49:13)
  - AKS (Azure): **Pass** (in 3.1 seconds on 2018/09/01 at 12:31:01)
  - OKE (Oracle): **Pass** (in 1.9 seconds on 2018/09/01 at 10:00:58)

### Add article

- **Description**: It should be possible to add an article  
- **Test results**:
  - GKE (Google): **Pass** (in 4.3 seconds on 2018/09/01 at 23:49:13)
  - AKS (Azure): **Pass** (in 3.1 seconds on 2018/09/01 at 12:31:01)
  - OKE (Oracle): **Pass** (in 1.9 seconds on 2018/09/01 at 10:00:58)

### Check existing article

- **Description**: An article created in a previous test should exist  
- **Test results**:
  - GKE (Google): **Pass** (in 4.3 seconds on 2018/09/01 at 23:49:13)
  - AKS (Azure): **Pass** (in 3.1 seconds on 2018/09/01 at 12:31:01)
  - OKE (Oracle): **Pass** (in 1.9 seconds on 2018/09/01 at 10:00:58)

### ...
