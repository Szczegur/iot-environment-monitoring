# IoT Environment Monitoring System  
# System monitoringu środowiska IoT

---

## 🇵🇱 Opis projektu

Projekt przedstawia demonstracyjny system monitoringu środowiska wewnętrznego
z wykorzystaniem węzłów pomiarowych opartych na mikrokontrolerze ESP32
oraz komunikacji MQTT.

Węzły pomiarowe realizują cykliczny odczyt parametrów środowiskowych,
takich jak:
- temperatura,
- wilgotność,
- ciśnienie atmosferyczne,
- eCO₂ (ekwiwalent CO₂),
- TVOC,
- natężenie oświetlenia (opcjonalnie).

Dane pomiarowe są publikowane do brokera MQTT w formacie JSON
z zachowaniem hierarchicznej struktury topiców.

Warstwa prezentacji została zrealizowana jako aplikacja webowa
(HTML, CSS, JavaScript) z wykorzystaniem biblioteki Chart.js.
Dashboard ma charakter demonstracyjny i wykorzystuje dane symulowane
do wizualizacji działania systemu.

Projekt **nie zawiera dedykowanego backendu aplikacyjnego ani REST API**
i został przygotowany w celach edukacyjnych.

---

## EN Project description

This project presents a demonstration IoT system for indoor environment
monitoring using ESP32-based measurement nodes and MQTT communication.

The measurement nodes perform cyclic readings of environmental parameters,
including:
- temperature,
- humidity,
- atmospheric pressure,
- eCO₂ (CO₂ equivalent),
- TVOC,
- light intensity (optional).

Measurement data are published to an MQTT broker in JSON format
using a hierarchical topic structure.

The presentation layer is implemented as a web-based dashboard
(HTML, CSS, JavaScript) using the Chart.js library.
The dashboard is demonstrational and uses simulated data
to visualize system functionality.

The project **does not include a dedicated application backend or REST API**
and was developed for educational purposes.

---

## 🛠 Technologies / Technologie

- ESP32 (Arduino framework)
- MQTT (Eclipse Mosquitto)
- HTML5 / CSS3 / JavaScript
- Chart.js
- ArduinoJson

---

## 📁 Project structure / Struktura projektu


