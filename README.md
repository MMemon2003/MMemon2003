<h1 align="center">Hi, I'm Muhammad 👋</h1>
<p align="center">
  Computer engineer from Dublin who likes building things that actually run.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/muhammad-memon-67819a246/"><img src="https://img.shields.io/badge/LinkedIn-Muhammad%20Memon-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:muhammadmemon210@gmail.com"><img src="https://img.shields.io/badge/Email-muhammadmemon210%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="YOUR-PORTFOLIO-LINK"><img src="https://img.shields.io/badge/Engineering-Portfolio-1F3864?style=flat" alt="Engineering Portfolio"></a>
</p>

---

```cpp
// muhammad.cpp
struct Me {
    const char* from        = "Dublin, Ireland";
    const char* studied     = "Computer Engineering, TU Dublin";
    const char* love[3]     = {"Football", "Badminton", "Programming"};
    const char* learning[2] = {"C++", "Machine learning"};
    const char* best_when   = "Working with a new team";
};
```

## A bit about me

I'm happiest when a sensor reading on a tiny chip ends up as a live graph on a screen, and I'd rather work out why something is broken than leave it alone. I'm into football and badminton, and I like joining a new team and finding my place in it.

Right now I'm teaching myself C++ and machine learning, and I'm looking for my first graduate engineering role in Dublin.

## What I'm proudest of

### 🚗 AI ADAS Detection System

My final year project: a low-cost driver assistance system that spots objects in real time and runs **on the device itself**, not in the cloud. The hard part was making it fast enough to matter, so I spent a lot of time testing its response time.

## Other things I've built

- **Networked IoT system.** A small ESP8266 board sends sensor readings over MQTT to Azure, and I watch them live on Grafana. Most of the fun was tracking down why messages sometimes went missing.
- **GP monitoring system.** A virtual GP check-up tool that tracks things like temperature, blood pressure and heart rate, and keeps the medical reports safe and easy to open.
- **Greenhouse monitor.** A little device that watches temperature, humidity and light so plants grow well. I calibrated the sensors and redesigned the circuit board layout to cut down noise.

<details>
<summary><b>How the IoT system fits together</b></summary>

```mermaid
flowchart LR
    A[Sensors] --> B[ESP8266]
    B -->|MQTT| C[Azure]
    C --> D[InfluxDB]
    D --> E[Grafana dashboard]
```

</details>

## My toolbox

![C](https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat&logo=postgresql&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white)
![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat&logo=css3&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=flat&logo=arduino&logoColor=white)
![Assembly](https://img.shields.io/badge/Assembly-6E4C13?style=flat)
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A22846?style=flat&logo=raspberrypi&logoColor=white)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=flat&logo=mqtt&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Node-RED](https://img.shields.io/badge/Node--RED-8F0000?style=flat&logo=nodered&logoColor=white)
![InfluxDB](https://img.shields.io/badge/InfluxDB-22ADF6?style=flat&logo=influxdb&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)

## Away from the keyboard

At university I started the Irish Sign Language Society, which grew to more than 50 members, and I was a student ambassador and class representative. I like bringing people together, and I'd like to do the same with a team of engineers.

## Say hello

If you're hiring graduates in embedded, software, IoT or networking, or you just want to talk about projects, message me on [LinkedIn](https://www.linkedin.com/in/muhammad-memon-67819a246/) or email me.

