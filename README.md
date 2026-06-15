
<div align="center">

# 🚀 Nagios Web-Based Host Management System

### Automated Host Monitoring & Management Panel for Nagios Core

<img src="https://img.shields.io/badge/Nagios-Core-red?style=for-the-badge">
<img src="https://img.shields.io/badge/PHP-8.x-blue?style=for-the-badge">
<img src="https://img.shields.io/badge/Apache2-Web%20Server-orange?style=for-the-badge">
<img src="https://img.shields.io/badge/Linux-Ubuntu-green?style=for-the-badge">

</div>

---

# 📌 Project Overview

This project extends the default Nagios Core installation by providing a fully web-based Host Management Panel.

Instead of manually creating `.cfg` files and reloading Nagios every time, administrators can:

✅ Add Hosts

✅ Edit Hosts

✅ Delete Hosts

✅ Enable / Disable Hosts

✅ Create Host Groups

✅ Remove Host Groups

✅ Auto Validate Configurations

✅ Auto Reload Nagios

Everything is managed from a secured web interface.

---

# 🏗 Architecture

```text
Ubuntu Server
│
├── Apache2
│
├── Nagios Core
│
├── Nagios Plugins
│
├── PHP Admin Panel
│
├── Host Manager Script
│
└── Web Browser
