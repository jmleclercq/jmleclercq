<h1 align="center">Hey, I'm jmleclercq 👋</h1>

<p align="center">
  <img src="https://img.shields.io/badge/HTB-Master-9FEF00?style=for-the-badge&logo=hackthebox&logoColor=black" />
  <img src="https://img.shields.io/badge/ESPHome-Builder-000000?style=for-the-badge&logo=esphome" />
  <img src="https://img.shields.io/badge/Home%20Assistant-Enthusiast-41BDF5?style=for-the-badge&logo=homeassistant&logoColor=white" />
  <img src="https://img.shields.io/badge/Based%20in-France-002395?style=for-the-badge&logo=googlemaps&logoColor=white" />
</p>

<p align="center">
  Cybersecurity & pentesting on one side, ESP32/IoT tinkering on the other.<br/>
  I like understanding <em>why</em> something works, not just making it work.
</p>

---

## ⌨️ hastty

<p align="left">
  <a href="https://github.com/jmleclercq/hastty"><img src="https://img.shields.io/github/stars/jmleclercq/hastty?style=for-the-badge&color=41BDF5&label=stars" /></a>
  <a href="https://pypi.org/project/hastty/"><img src="https://img.shields.io/pypi/v/hastty?style=for-the-badge&label=pypi&cacheSeconds=3600&v=0.1.4" /></a>
</p>

A terminal (TUI) dashboard for Home Assistant, built with [Textual](https://textual.textualize.io/). It mirrors your existing Lovelace views and lets you toggle a light, run a scene, or trigger an automation straight from the keyboard — no browser required, live state updates included.

```bash
pip install hastty
```

**[github.com/jmleclercq/hastty](https://github.com/jmleclercq/hastty)**

---

## 🎯 Security & CTF

I work through Hack The Box retired machines and write up the methodology — not just the commands, but the reasoning behind each step (enumeration → foothold → privesc → lessons learned).

<table>
<tr>
<td width="60%">

**[htb-writeups](https://github.com/jmleclercq/htb-writeups)**
Personal collection of HTB retired machine & challenge walkthroughs. Documents information gathering, enumeration, initial access, privilege escalation and post-exploitation for each box.

</td>
<td>

![Keeper](https://img.shields.io/badge/Keeper-Easy-success)
![Zero](https://img.shields.io/badge/Zero-Insane-success)
![Knife](https://img.shields.io/badge/Knife-Easy-success)
![Nibbles](https://img.shields.io/badge/Nibbles-Easy-success)
![Editor](https://img.shields.io/badge/Editor-Easy-success)
![NanoCorp](https://img.shields.io/badge/NanoCorp-Hard-success)

</td>
</tr>
</table>

---

## 🏠 IoT & Home Assistant

Most of these start from the same itch: something in my home isn't controllable *locally* the way I want, so I build the missing piece with an ESP32 and ESPHome.

| Project | What it does |
|---|---|
| 📷 **[xiao-esp32s3-sense-ha-cam](https://github.com/jmleclercq/xiao-esp32s3-sense-ha-cam)** | Camera on a Seeed XIAO ESP32S3 Sense, streamed & snapshotted into Home Assistant via ESPHome. First milestone of a bigger HA control-screen project. |
| 🎵 **[sonos-esp32-panel](https://github.com/jmleclercq/sonos-esp32-panel)** | A working touchscreen Sonos remote — play/pause, skip, volume — built on a Sunton ESP32 2.8" display, wired straight into Home Assistant. |
| 🎵 **[esp32-sonos-touch-controller](https://github.com/jmleclercq/esp32-sonos-touch-controller)** | The bigger-screen take on the same idea: a 3.5" ST7796 display driving a standalone Sonos control panel. Display + Wi‑Fi + HA API are working; touch input is still being wired up. |
| 🌡️ **[esp32c6-zigbee-sht3x-sensor](https://github.com/jmleclercq/esp32c6-zigbee-sht3x-sensor)** | DIY Zigbee temperature & humidity sensor (ESP32-C6 + SHT3X), talks natively to Home Assistant ZHA — no cloud, no extra gateway. |
| 🌡️ **[esphome-esp32-dht22-ha-sensor](https://github.com/jmleclercq/esphome-esp32-dht22-ha-sensor)** | The Wi‑Fi/ESPHome equivalent: an ESP32 + DHT22 sensor, fully local, OTA-ready, wiring documented. |
| 📶 **[esp32-wifi-repeater](https://github.com/jmleclercq/esp32-wifi-repeater)** | A Wi‑Fi NAT repeater for the ESP32-C6, written from scratch with ESP-IDF — station + access point routed with lwIP NAPT, Wi‑Fi 6 on 20 MHz, auto-reconnect. Around 10 Mbit/s through a single 2.4 GHz radio; web config page and OTA are next. |
| 🎙️ **[self-hosted-audio-guestbook](https://github.com/jmleclercq/self-hosted-audio-guestbook)** | Not IoT, but the same self-hosting mindset: guests scan a QR code and record a voice message straight from their browser. Lightweight PHP + vanilla JS, deploys on any shared hosting via FTP. |

---

## 🛠️ Tools & stack

<p>
  <img src="https://img.shields.io/badge/ESPHome-000000?style=flat-square&logo=esphome" />
  <img src="https://img.shields.io/badge/Home%20Assistant-41BDF5?style=flat-square&logo=homeassistant&logoColor=white" />
  <img src="https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white" />
  <img src="https://img.shields.io/badge/Zigbee-FF6600?style=flat-square" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
</p>

---

<!--
  Optional: live GitHub stats card (third-party service, can be flaky/rate-limited —
  remove this block entirely if the images don't load reliably for you).
  <p align="center">
    <img src="https://github-readme-stats.vercel.app/api?username=jmleclercq&show_icons=true&theme=default&hide_title=true&hide_border=true" width="48%" />
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=jmleclercq&layout=compact&hide_border=true" width="38%" />
  </p>
-->

<p align="center"><sub>Writeups cover retired HTB machines only, in line with platform rules — published for educational purposes.</sub></p>
