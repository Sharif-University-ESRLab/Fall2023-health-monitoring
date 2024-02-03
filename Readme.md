![download](https://github.com/Sharif-University-ESRLab/Fall2023-health-monitoring/assets/79312684/97b4b68f-0b38-42f5-a88e-9bb99df35cc2)

# Patient Monitoring Device

The Internet of Medical Things (IoMT) refers to a collection of medical devices and equipment that are connected to the healthcare system network via the Internet. Medical devices equipped with wireless systems (Wi-Fi) enable M2M (machine-to-machine) communication, which is the foundation of IoMT. Today, IoMT has increased the well-being of patients and hospital staff in hospitals.

This project investigates the application of IoT in medicine and implements a patient monitoring device.

## Tools
- NodeMCU board
- GPS sensor
- Biometric sensors (pulse oximeter, heart rate, blood pressure)
- Battery or power bank
- Server

## Implementation Details

This project aims to design a prototype of a patient monitoring device for an elderly patient with Alzheimer's. To this end, at least pulse oximeter, heart rate, and blood pressure sensors should be used to monitor the patient's vital signs. Since the patient may forget the location of their home, a GPS sensor is also needed to show the location of the person. Considering that the device should be portable, using a battery or powerbank is essential. Also, one of the design challenges of this device is to consider the principles to be able to operate in a low-power manner. You should research the methods of power reduction in this device.

The information from these sensors is received by the Raspberry Pi board or NodeMCU Wi-Fi module and sent to an internet server. The communication of these modules with the server must be through common IoT protocols such as MQTT or CoApp. Any language can be used on the server side.

An application is also needed to display sensor data in real time. To this end, you can design an Android mobile application or a web application. Since the customer in this scenario is considered an ordinary customer with no computer knowledge, the user-friendliness of the product's user interface is important. Also, considering the availability of 3D printing facilities in the lab, building a box for this product has a bonus point.

Note:

Considering that the above prototype is a device with minimal features, adding new features to the device has a bonus point.
It is better to do a short research on the available sensors in this field and how to use them at the beginning of the project.
Also, considering that the required biometric sensors are not available in the lab, they should be prepared by the group itself.
Project Stages:

Connecting the sensors to the board and testing the offline system
Designing the backend and connecting the board to the server
Designing the frontend and connecting to the board through the server
Designing a box with a 3D printer (bonus section)

## How to Run

In this part, you should provide instructions on how to run your project. Also if your project requires any prerequisites, mention them. 

#### Examples:
#### Build Project
Your text comes here
```bash
  build --platform=OvmfPkg/OvmfPkgX64.dsc --arch=X64 --buildtarget=RELEASE --tagname=GCC5
```

#### Run server
Your text comes here
```bash
  pyhton server.py -p 8080
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `-p` | `int` | **Required**. Server port |



## Results
In this section, you should present your results and provide an explanation for them.

Using image is required.

## Related Links
Some links related to your project come here.
 - [ESP32 Pinout](https://randomnerdtutorials.com/esp32-pinout-reference-gpios/)
 - [Django Doc](https://docs.djangoproject.com/en/5.0/)


## Authors
Authors and their github link comes here.
- [@Author1](https://github.com/Sharif-University-ESRLab)

