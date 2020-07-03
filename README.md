# enos-simple-device-invoke-service
This is the sample codes to invoke a service created in an EnOS model. To be used with enos-simple-device-mqtt.

## Techology stack
- Python
- EnOS Platform
- https://pypi.org/project/aphrodite/

## Prerequitsites

### Get organization unit, save the OU id to .env file
Follow the instructions below to get the organization unit id:
- https://www.envisioniot.com/docs/enos/en/latest/iam/howto/managing_org_info_account.html?highlight=organization%20unit#editing-the-organization-profile

### Get the APIM url and port, save to .env file
Follow the instructions below to get the APIM url and port:
- https://www.envisioniot.com/docs/enos/en/latest/getting_started_with_enos/planning.html?highlight=environment%20information#getting-environment-information

### Create an EnOS model and service, save the service id to .env file
Follow the instructions below to create an EnOS model and service:
- https://www.envisioniot.com/docs/device-connection/en/latest/howto/model/creating_model#adding-service

### Create an EnOS device, save the asset id to .env file
Follow the instructions below to create an EnOS device:
- https://www.envisioniot.com/docs/device-connection/en/latest/howto/device/manage/creating_device.html

### Register an EnOS application, save app access key and secret to .env file
Follow the instructions below to register an EnOS application:
- https://www.envisioniot.com/docs/app-development/en/latest/app_management/managing_apps.html#registering-an-application

### Run the init shell script to build the python dependencies
```bash
./init.sh
```

## How to run
To run the demo, run the following command in a new terminal.
```bash
python index.py
```
