# Welcome to My wiki Pages

## Abstract
With the development of Internet of Things products, it has improved people's quality of life and also brought security challenges. The public key infrastructure system is one of the most widely used security verification technologies, but its usage in IoT products is very low. In this summary paper, we do research on several structures of public key infrastructure for the Internet of Things. According to the research on several public key infrastructures, it is found that there are insufficient resources in IoT devices. Based on the research, I discussed a solution to decentralized KPI, using gateways and other IoT devices with sufficient resources and insufficient resources. Connected devices. This solution can reduce the online certificate status protocol (OCSP) verification time. At the same time, the distributed node certificate verification method is used to improve scalability, and multiple Internet of Things devices can be accessed and controlled at the same time.



## INTRODUCTION
There are more and more signs that the Internet of Things (IoT) is changing people's lifestyles. IoT products include smartphones, wearable devices, sensors, smart homes, and automated cars. These networkable devices and sensors are providing people with a more comfortable and convenient life. At the same time, there are hidden security risks in networked devices. From system operation to data packet transmission, it is possible to be hijacked or leaked, such as personal health information, house surveillance video or even smart door locks.

![IOT Netrwork](https://github.com/QiushiYe/Research-on-Security-of-Public-Key-Infrastructure-in-Internet-of-Things-Terminal-Equipment/blob/master/20190326-iot-in-five-years2-1.jpg?raw=true)

The public key infrastructure system is one of the most widely used security verification and encryption systems. In the development of the Internet of Things technology, it can be found that the public key infrastructure system is not used on a large scale in the Internet of Things devices and sensors. By studying three feasible KPI prototypes IoT-PKI, PKIoT, and PKI4IoT, it is proved that the traditional certificate authority (CA) public key infrastructure is not suitable for IoT devices.

![KPI Trust Model](https://media.springernature.com/lw785/springer-static/image/prt%3A978-1-4419-5906-5%2F16/MediaObjects/978-1-4419-5906-5_16_Part_Fig1-97_HTML.gif)

The traditional CA-PKI verification method requires the key to be generated and installed on the IoT device. When a CA key is leaked, it is necessary to interrupt all device connections until the certificate list is updated from a trusted certificate authority. Second, the traditional CA public key infrastructure system needs to update the list regularly, which will greatly increase the response time of the online certificate status protocol. 
Current systems usually use pre-shared keys for verification, but this certificate framework does not consider the security of data packet transmission in an open situation. An attacker only needs to decrypt a key to invade the entire terminal device.

## RELATED WORK
Through previous research, I found that IoT devices have limitations in device hardware functions. Many IoT devices themselves have fewer resources and even lower hardware requirements than standard KPIs, which have tens of KB of memory. I reckon that it is necessary to deploy an expandable service platform for these micro IoT devices. It can be a gateway product or any IoT device with more resources. And optimize the low-power IoT device signcryption method, which can effectively improve security.
Based on the above findings, I conducted in-depth research, according to KPI's M2M authentication function (MAF) -based framework and IoT-PKI framework, which uses third-party hosting for authentication and KPI decentralization, using distributed nodes. In my opinion, designing a gateway as a platform service and using a new heterogeneous online/offline signcryption scheme proposed by Pei-Yih Ting can reduce the calculation cost and the signcryption time of devices with low computing capacity. This platform can be installed with a visual operating system to facilitate users' online/offline management and control of IoT devices connected to the platform system.

## CONCLUSION
Using this decentralized method, you can increase the security of the terminal IoT device. The terminal device only needs to pass the KPI verification and connect to the gateway or a device with high computing capacity. In this model, the public and private keys need not be from the CA Obtain and generate, generate the corresponding key between the device as the node and the IoT terminal device, so as to maximize the protection of the data between the terminal data and the node. Even if the key of one node is cracked, it will not threaten the devices of other nodes. This method also supports the control and management of IoT terminal devices through local connections while the nodes are offline.

![My hypothetical model](https://github.com/QiushiYe/Research-on-Security-of-Public-Key-Infrastructure-in-Internet-of-Things-Terminal-Equipment/blob/master/IoT%20KPI%20model.png?raw=true)

## REFERENCES
	S. Blionas, G. Doukas, K. Doukas, and N. D. Tselikas, “A Flexible/Scalable IoT Server Node testbed, from Gateway to Edge Computing. A Smart Home Use Case,” in 2019 Panhellenic Conference on Electronics & Telecommunications (PACET), 2019, pp. 1–6, doi: 10.1109/PACET48583.2019.8956284.
	J. Höglund, S. Lindemer, M. Furuhed, and S. Raza, “PKI4IoT: Towards public key infrastructure for the Internet of Things,” Comput. Secur., vol. 89, p. 101658, 2020, doi: https://doi.org/10.1016/j.cose.2019.101658.
	F. Marino, C. Moiso, and M. Petracca, “PKIoT: A public key infrastructure for the Internet of Things,” Trans. Emerg. Telecommun. Technol., vol. 30, no. 10, p. e3681, Oct. 2019, doi: 10.1002/ett.3681.
	D. Trinchero, R. Stefanelli, D. Brunazzi, A. Casalegno, M. Durando, and A. Galardini, “Integration of smart house sensors into a fully networked (web) environment,” in SENSORS, 2011 IEEE, 2011, pp. 1624–1627, doi: 10.1109/ICSENS.2011.6127374.
	P. Ting, J. Tsai, and T. Wu, “Signcryption Method Suitable for Low-Power IoT Devices in a Wireless Sensor Network,” IEEE Syst. J., vol. 12, no. 3, pp. 2385–2394, 2018, doi: 10.1109/JSYST.2017.2730580.
	S. Raza, T. Helgason, P. Papadimitratos, and T. Voigt, “SecureSense: End-to-end secure communication architecture for the cloud-connected Internet of Things,” Futur. Gener. Comput. Syst., vol. 77, pp. 40–51, 2017, doi: https://doi.org/10.1016/j.future.2017.06.008.
	J. Won, A. Singla, E. Bertino, and G. Bollella, “Decentralized Public Key Infrastructure for Internet-of-Things,” in MILCOM 2018 - 2018 IEEE Military Communications Conference (MILCOM), 2018, pp. 907–913, doi: 10.1109/MILCOM.2018.8599710.
