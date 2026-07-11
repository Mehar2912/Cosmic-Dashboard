# Cosmic-Dashboard 

Cosmic Dashboard is a visually immersive web application that brings live space data to your fingertips. From asteroid tracking to real-time ISS mapping, the project combines interactive visuals with space exploration data in a cosmic-themed experience.

##  Key Features

* **Asteroid Tracking**
  Integrated with NASA’s NeoWs API to fetch and display data on near-Earth objects.

* **ISS Location Tracking**
  Powered by the N2YO API, allowing users to monitor the International Space Station’s real-time position.

* **Satellite Telemetry**
  Embedded live satellite maps with an external link option for extended telemetry visualization.

* **Planetary Clock**
  A custom JavaScript + Canvas simulation demonstrating orbital mechanics, featuring planetary orbits, Saturn’s rings, Earth’s moon, and an asteroid belt.

##  Tech Stack & Tools

### Languages

* HTML
* CSS
* JavaScript

### Animations & Visuals

* Canvas API → starfields, orbital mechanics, drifting stars
* CSS Animations → glowing effects, transitions, planetary visuals

### APIs & Data Sources

* NASA NeoWs API → asteroid data
* N2YO API → ISS tracking
* Satellitemap.space → satellite telemetry

##  Project Structure

```bash
Cosmic-Dashboard/
│── index.html                  # Main landing page
│── asteroid.html               # Asteroid tracking page
│── iss.html                    # ISS real-time location tracker
│── planetaryclock.html         # Planetary clock simulation
│── satellite_telemetry.html    # Satellite telemetry visualization
│
│── asteroid_bg.mp4             # Background video for asteroid page
│── blackhole_bg.mp4            # Black hole themed background
│── sat_bg.mp4                  # Satellite telemetry background
│── stars_bg.mp4                # Starfield background
│
│── README.md                   # Project documentation
```

##  System Architecture

```text
                ┌────────────────────┐
                │   User Interface   │
                │  (HTML/CSS/JS)     │
                └─────────┬──────────┘
                          │
        ┌─────────────────┼─────────────────┐
        │                 │                 │
        ▼                 ▼                 ▼
 ┌─────────────┐   ┌─────────────┐   ┌─────────────┐
 │ NASA NeoWs │   │  N2YO API  │   │ Satellitemap│
 │ Asteroid   │   │ ISS Data   │   │ Telemetry   │
 └─────────────┘   └─────────────┘   └─────────────┘
                          │
                          ▼
              ┌──────────────────┐
              │ Canvas Animations│
              │ & Visual Effects │
              └──────────────────┘
```

