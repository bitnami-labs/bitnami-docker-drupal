# Test results

## Smoke testing

Smoke tests are a subset of tests covering important functionality of an application, used to aid assessment if its main functions appear to work correctly. They are not a replacement of a properly tested application, which should be done by the upstreaam project.

Bitnami maintained dockerfile images are smoke tested in a docker compose deployment to ensure they work properly.

## Results

Application: **Drupal 8.5.6**

Dockerfile: [`8-rhel-7`, `8.5.6-rhel-7-r0` (8/rhel-7/Dockerfile)](https://github.com/bitnami-labs/bitnami-docker-drupal/blob/8.5.6-rhel-7-r0/8/rhel-7/Dockerfile) 

Date: **2018-09-02 11:34:23**

Test | Compose
--- | :---:
Login - Logout  | Ok
Check up-to-date  | Ok
Add article | Ok
Check article  | Ok
Add image | Ok
Check image | Ok
Add page | Ok
Check page | Ok
Change fav icon | Ok
Check fav icon | Ok
Change logo | Ok
Check logo | Ok
Check htAceess | Ok
Add user | Ok
Login new user | Ok
