# Connect the MXchip to Azure IoT Central (Preview tempaltes)

In this short workshop (max 1 hour) you will learn howto connect a MXchip (AZ3166) to Azure IoT Central preview templates.

In this quickstart, you create the MXchip device template and add a real device to the system. An MXchip sensor device:

Sends telemetry such as temperature.
Responds to commands such as led on and led off.
Reports generic device properties such as firmware version and serial number

## Create an Azure IoT Central preview environment

If in the workshop no enviornment is given, you have to create first an Azure IoT Central environment to connect the MXchip on. If you have already an environment, please go to the next section.

Navigate to the [Azure IoT Central Build site](https://aka.ms/iotcentral/). Then sign in with a Microsoft personal, work, or school account.

You create a new application either from the list of industry-relevant IoT Central templates to help you get started quickly, or start from scratch using the Custom app template. For this workshop you have to create a custom app and not an industry template. 

## Device templates

A device template defines the capabilities of a device that connects to your IoT Central application. Capabilities include telemetry the device sends, device properties, and the commands a device responds to. From a device template, a builder or operator can add both real and simulated devices to an application. Simulated devices are useful for testing the behavior of your IoT Central application before you connect real devices.