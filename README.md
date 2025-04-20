<h1 align="center">Hi 👋, I'm Dani</h1>
<h3 align="center">I am a Mechatronics Engineer from Peru with knowledge in PCB design, programming and basic modelling skills. I am motivated in learning more about AI and robotics simulation</h3>

## 🌐 Socials:

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/http://www.linkedin.com/in/daniela-carcausto-osco) [![email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:danicarcausto@hotmail.com)

## 💻 Programming Languages:

![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white) ![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=csharp&logoColor=white) ![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)

<h1>💻 PCB Experience </h1>

In this section I will present projects Ive been part of mostly in electronics and PCB design which have been implemented and tested during my experience in university and work usind differente softwares like Eagle, Easy EDA, and KiCAD.

### Projects:

- [Tank Barrel Inspection System](#proy1)
- [Unnamanned Superficial Vehicle](#proy2)
- [Swarm robotics](#proy3)

## Tank Barrel Inspection System

## Unnamanned Superficial Vehicle

Design and development of four PCBs for an autonomous surface vehicle (USV) project. This project integrated multiple communication protocols including **Ethernet, RS232, RS485**, and **TTL**, allowing the system to interface with a variety of sensors. The four custom-designed PCBs were:

- **Main PCB**
- **Communication PCB**
- **Tumivision PCB**
- **Electric Winch PCB**

---

### 🔌 Main PCB

**Authors:** Jefferson Camargo, Daniela Carcausto  
The main PCB managed power distribution to all sensors, the onboard computer, the Tumivision module, and the electric winch. It also featured voltage selection capabilities to power different sensors according to their requirements. Moreover, with the GPIOs of the main computer and the communicaction PCB, different protocols depending on the sensor could be selected.  
**Features:**

- Power management for various modules
- Voltage selection for sensors
- Integrated **Ethernet switch** for communication with Tumivision, **PTZ camera**

<p align="center">
  <img src="./usv/principal/principal_top.png" alt="PCB top" width="300"/>
  <img src="./usv/principal/principal_bottom.png" alt="PCB bottom" width="300"/>
  <img src="./usv/principal/principal_2D.png" alt="PCB 2d" width="300"/>
</p>
<p align="center">
  <img src="./usv/principal/principal_3D.png" alt="PCB top" width="400"/>
  <img src="./usv/principal/principal_3D2.png" alt="PCB bottom" width="400"/>
</p>
<p align="center">
  <img src="./usv/principal/principal_realtop.png" alt="PCB top" width="300"/>
  <img src="./usv/principal/principal_realbottom.png" alt="PCB bottom" width="300"/>
</p>

### 📡 Communication PCB

**Authors:** Jefferson Camargo, Daniela Carcausto  
This compact board enabled switching between communication protocols such as **RS232, RS485**, and **TTL**. It connected to the main PCB and allowed the onboard computer to dynamically choose the desired protocol.

**Features:**

- Multi-protocol support
- Control interface with main computer
- Compact design for easy integration

<p align="center">
  <img src="./usv/comunicacion/comunicacion_top.png" alt="PCB top" width="250"/>
  <img src="./usv/comunicacion/comunicacion_bottom.png" alt="PCB bottom" width="250"/>
  <img src="./usv/comunicacion/comunicacion_2D.png" alt="PCB 2d" width="250"/>
</p>
<p align="center">
  <img src="./usv/comunicacion/comunicacion3D_1.png" alt="PCB top" width="400"/>
  <img src="./usv/comunicacion/comuniccion3D_2.png" alt="PCB bottom" width="400"/>
</p>
<p align="center">
  <img src="./usv/comunicacion/comunicacion_real.png" alt="PCB top" width="300"/>
</p>

### 🎥 Tumivision PCB

**Author:** Daniela Carcausto  
This small board powered and connected the Tumivision module, which consisted of a **Jetson AGX Xavier**, a **Mid360 camera**, and a **stereoscopic camera**.

**Features:**

- Power supply for vision components, Ethernet switch, and indicator LED

<p align="center">
  <img src="./usv/tumivision/tumivision_top.png" alt="PCB top" width="250"/>
  <img src="./usv/tumivision/tumivision_bottom.png" alt="PCB bottom" width="250"/>
  <img src="./usv/tumivision/tumivision_2D.png" alt="PCB 2d" width="250"/>
</p>
<p align="center">
  <img src="./usv/tumivision/tumivision_3D1.png" alt="PCB top" width="300"/>
  <img src="./usv/tumivision/tumivision_3D2.png" alt="PCB bottom" width="300"/>
</p>
<p align="center">
  <img src="./usv/tumivision/tumivision_real.png" alt="PCB top" width="300"/>
</p>

### ⚙️ Electric Winch PCB

**Author:** Daniela Carcausto  
Designed to control an electric winch module. It communicated via **RS485** with the main PCB to receive distance commands. An **encoder** is used for position feedback and included a **limit switch** to stop the winch when it returned to the initial position.

**Features:**

- RS485 communication
- Encoder integration for distance tracking
- Limit switch for safety stop

<p align="center">
  <img src="./usv/winche/winche_top.png" alt="PCB top" width="300"/>
  <img src="./usv/winche/winche_bottom.png" alt="PCB bottom" width="300"/>
  <img src="./usv/winche/winche_2D.png" alt="PCB 2d" width="300"/>
</p>
<p align="center">
  <img src="./usv/winche/winche_3D.png" alt="PCB top" width="400"/>
  <img src="./usv/winche/winche_3D2.png" alt="PCB top" width="400"/>
  <img src="./usv/winche/winche_real.png" alt="PCB bottom" width="300"/>
</p>

## Swarm robotics
