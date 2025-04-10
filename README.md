# Giraffe Subscription Template Marzban

*A stylish and clean subscription dashboard template for Marzban, built with HTML, CSS, and JavaScript*

---

## Overview

"Giraffe Subscription Template Marzban" is a fresh, modern, and fully responsive subscription dashboard made specifically for the Marzban VPN Panel. With a smooth glassmorphism design, RTL support, theme switching, and dynamic QR code generation, this template offers a perfect blend of aesthetics and functionality to provide end-users with a seamless subscription experience.

### Features
- Responsive Design: Perfectly adapts to mobile and desktop screens (optimized for small screens up to 480px).
- Glassmorphism UI: Clean transparent cards with subtle blur and gradient accents.
- Light/Dark Mode: Toggle between light and dark themes with a soft animated transition.
- RTL Support: Fully supports Persian and other RTL languages.
- Accordion for Configs: Click to expand and view V2Ray configuration links, with copy and QR code options.
- Multi-Platform Icons: Font Awesome icons for all major platforms – Android, iOS, Windows, macOS, and Linux.
- On-Demand QR Codes: Instantly generate QR codes for configuration links.
- Smooth Animations: Polished user interface with fade-in and slide animations for a premium feel.

---

## Demo
![light](https://github.com/user-attachments/assets/4358e4bb-f330-4295-9a7c-ad9218e75abf)
------------------------------------------------------------------------
![dark](https://github.com/user-attachments/assets/935bc901-a216-4fd0-ab5d-8b1366eca3ae)
---

## Installation

To use this template in your project, follow these steps:

1. **Clone the Repository**:
   ```bash
   sudo wget -N -P /var/lib/marzban/templates/subscription/ https://raw.githubusercontent.com/pourjavadi/GiraffeSubscription/refs/heads/main/index.html
2. **Run the following commands in your server terminal** :
   ```bash
   echo 'CUSTOM_TEMPLATES_DIRECTORY="/var/lib/marzban/templates/"' | sudo tee -a /opt/marzban/.env
   echo 'SUBSCRIPTION_PAGE_TEMPLATE="subscription/index.html"' | sudo tee -a /opt/marzban/.env
3. **Restart marzban** :
   ```bash
   sudo marzban restart
Done , Good Luck :)
