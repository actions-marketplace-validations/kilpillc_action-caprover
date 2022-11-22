# CapRover App Deploy

Action to deploy application to CapRover server


## Inputs

### `host`: required

CapRover machine url i.e., https://captain.your-domain.com

### `password`: required

CapRover app token password. Use secret for more security

### `app`: required

App name on CapRover server

### `branch`

Branch which will be deployed


> *NOTE:* if image is used `branch` will be ignored


## Usage

```
uses: kilpillc/action-caprover@v1
with:
  host: 'https://captain.your-domain.com'
  password: '${{ secrets.CAPROVER_PASSWORD }}'
  app: 'my-app'
  branch: 'master'

```
