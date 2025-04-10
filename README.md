# Giraffe Subscription Template Marzban

*A stylish and clean subscription dashboard template for Marzban, built with HTML, CSS, and JavaScript*

---

## Overview

"Giraffe Subscription Template Marzban" is a fresh, modern, and fully responsive subscription dashboard made specifically for the Marzban VPN Panel. With a smooth glassmorphism design, RTL support, theme switching, and dynamic QR code generation, this template offers a perfect blend of aesthetics and functionality to provide end-users with a seamless subscription experience.

### Features
- **Responsive Design: Perfectly adapts to mobile and desktop screens (optimized for small screens up to 480px).
- **Glassmorphism UI: Clean transparent cards with subtle blur and gradient accents.
- **Light/Dark Mode: Toggle between light and dark themes with a soft animated transition.
- **RTL Support: Fully supports Persian and other RTL languages.
- **Accordion for Configs: Click to expand and view V2Ray configuration links, with copy and QR code options.
- **Multi-Platform Icons: Font Awesome icons for all major platforms – Android, iOS, Windows, macOS, and Linux.
- **On-Demand QR Codes: Instantly generate QR codes for configuration links.
- **Smooth Animations: Polished user interface with fade-in and slide animations for a premium feel.

---

## Demo
![1en](https://github.com/user-attachments/assets/db14fe19-42bb-4fd3-832f-2269c5881d17)
![2endark](https://github.com/user-attachments/assets/ae865498-2801-42eb-83ad-7977b9970254)
![1persian](https://github.com/user-attachments/assets/9c3edac6-b421-4757-b523-c93491ba7317)
![2persiandark](https://github.com/user-attachments/assets/49988a71-7f86-46fc-9d3f-cfec46f7db5f)



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
