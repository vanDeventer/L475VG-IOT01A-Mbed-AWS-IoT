# AWS IoT with the L475VG-IOT01A on Mbed OS
An application for the STMicroelectronics STM32L4 Discovery Kit IoT Node using ARM Mbed OS to connect to AWS IoT cloud. In parts it is inspired by the example [AWS IoT from Mbed OS device](https://os.mbed.com/users/coisme/notebook/aws-iot-from-mbed-os-device/) using the Wifi and sensor example from [Team ST](https://os.mbed.com/teams/ST/). Although specifically built for the IOT01A-model, it should be compatible with the Non-US IOT01B-model.

## Intended use of this program code
I built the program as I was unable to connect the STM32L4 to the AWS IoT cloud with any existing examples or libraries. I provide it on an AS IS basis for anyone that wants to get ahead faster with the STM32, ARM Mbed and AWS IoT. Therefore the intended user of this program should bring some basic C/C++ knowledge.

## How to install the program on a STM32 L475VG-IOT01A
In order to run the program on your STM32L475, you need to configure and compile it. I will explain the process using the Mbed online compiler for which you need to create a free account on [os.mbed.com](https://os.mbed.com). Further you need to have an AWS account to create AWS IoT things.

### Import the program into the Mbed compiler
Make sure you are logged in to your mbed.com account. You can easily import the program into the mbed online compiler using the following link: [Import the program into the compiler](https://os.mbed.com/compiler/#import:https://github.com/jankammerath/L475VG-IOT01A-Mbed-AWS-IoT/). You will afterwards see the program and it's code components, just as on GitHub. 

### Configure your AWS certificate and key
