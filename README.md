*This project has been created as part of the **42 curriculum** by  **mleschev**.* <center>

## Description :

The **NetPractice** project at 42 is designed to help students understand **how computer networks work**.  
It allows students to **discover** and **practice** several fundamental networking concepts and protocols:

- TCP/IP
- IP addressing
- How routers and switches work

And more.

NetPractice presents itself as a **network simulator composed of 10 levels**.  
The difficulty increases progressively:
<center>- Level 1 focuses on connecting two simple networks.</center>
<center>- Level 10 involves a large network with multiple routers, switches, and gateways.</center>

In each exercise, some values such as **IP addresses**, **subnet masks**, or **gateways** are missing.  
The simulator also imposes specific constraints that must be respected.

<image src="https://preview.redd.it/42-netpractice-is-broken-v0-fzjgmumbawbg1.png?width=720&format=png&auto=webp&s=ffcd3ab10d0ee0bb4be9dd4a3bc93d078350a441" alt="NetPractice simulator example" width=300>

For each interface, we must configure at least an **IP address** and its **subnet mask**, either manually or by respecting fixed values, for example:

| IP | **42.42.42.1** |
|:-:|:-:|
| **Netmask** | **/30** or **255.255.255.252** |

For some levels or interfaces, one or more **gateways** must also be configured, such as:

| 128.42.42.202/30 | **==>** | 128.250.62.1 |
|:-:|:-:|:-:|
| **42.42.42.0/24** | **==>** | **128.250.63.1** |

By respecting the constraints of each exercise, we must assign the correct **IP addresses**, **subnet masks**, and **gateways** to reach the objective, such as:
<center>- Connecting host A to host B</center>
<center>- Connecting a network to the internet</center>


## Instructions :

For NetPractice, a `.tgz` file is provided (also included at the root of this repository).  
This archive contains all the exercises and the evaluation part of the project.

To run the training interface:

    1. Extract the `.tgz` file
    2. Open `index.html`

Unfortunately, not all web browsers support this interface correctly.  
To ensure proper execution, it is recommended to use **Google Chrome**.

As mentioned before, the project is divided into two parts:

**Exercises**  
Levels 1 to 10, each one increasing in difficulty.

**Evaluation**  
A rush composed of **3 random exercises**, chosen between levels 6 and 10,  
to be completed in **under 15 minutes**.

<br>

<b>Exporting configurations</b>

Once a level is successfully completed, the configuration must be **exported** using the NetPractice interface.  
Each level generates a configuration file corresponding to its network setup.

<br>

<b>Submission requirements</b>

For submission:
- **10 exported configuration files** are required  
- **One configuration file per level (levels 1 to 10)**  
- All exported files must be placed **at the root of the Git repository**


## Resources :

<center><b>Networking concepts studied</b></center>

<center>- TCP/IP addressing</center>
<center>- IPv4 structure</center>
<center>- Subnet masks and CIDR notation</center>
<center>- Default gateway</center>
<center>- Routers and switches</center>
<center>- OSI layers</center>

<br>

<center><b>Documentation and references</b></center>
<br>

[Routing](https://fr.wikipedia.org/wiki/Routage)

[Subnetting](https://fr.wikipedia.org/wiki/Sous-r%C3%A9seau)

[OSI model](https://fr.wikipedia.org/wiki/Mod%C3%A8le_OSI)

[TCP/IP](https://fr.wikipedia.org/wiki/Suite_des_protocoles_Internet)

<br>

<center><b>Use of Artificial Intelligence</b></center>

AI was used as a learning assistant to:
<center>- Clarify networking concepts during late-night study sessions (subnetting, routing, gateways)</center>
<center>- Help rewrite and improve documentation in clear English</center>

AI was not used to automatically solve the exercises.  
All configurations were manually validated using **NetPractice only**.

---
