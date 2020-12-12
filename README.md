## A simple Python IoT code with BME280 sensor

This is a simple project that prints the data from the BME280 sensor connected to a Raspberry Pi running [balena](https://balena.io).

The sensor BME280 is a low-cost environmental sensor that senses temperature, humidity and pressure and can be easily connected to a Raspberry Pi or other devices.

### Getting started

* Raspberry Pi 3, 4 or balenaFin.
* BME280 sensor

* A balenaCloud account ([sign up here](https://dashboard.balena-cloud.com/))
* [balenaEtcher](https://balena.io/etcher)

Once all of this is ready, you are able to deploy this repository following instructions below.

### Connect the hardware

To connect the BME280 with the Raspberry Pi follow this diagram connections below:

![alt text](https://github.com/balena-io-playground/python-bme280/blob/main/bme280-raspberrypi4.png)

### Deploy the code

#### Deploy with balena

Running this project is as simple as deploying it to a balenaCloud application. You can do it in just one click by using the button below:

[![](https://www.balena.io/deploy.png)](https://dashboard.balena-cloud.com/deploy?repoUrl=https://github.com/balena-io-playground/python-bme280)

Follow instructions, click Add a Device and flash an SD card with that OS image dowloaded from balenaCloud. Enjoy the magic 🌟Over-The-Air🌟!

#### balena CLI

If you are a balena CLI expert, feel free to use balena CLI.

- Sign up on [balena.io](https://dashboard.balena.io/signup)
- Create a new application on balenaCloud.
- Clone this repository to your local workspace.
- Using [Balena CLI](https://www.balena.io/docs/reference/cli/), push the code with `balena push <application-name>`
- See the magic happening, your device is getting updated 🌟Over-The-Air🌟!

### Attribution

- This is a code made by David Tischler from balena during the IoT Happy Hour.
- This code has been presented at the PyDay Barcelona 2020.

