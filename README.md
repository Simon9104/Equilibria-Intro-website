# Equilibria – Tlačiarenské služby Košice

Webstránka pre tlačiarenskú firmu Equilibria so sídlom v Košiciach.

## O projekte

Jednoduchá statická HTML stránka bez závislostí na frameworkoch. Obsahuje všetky sekcie potrebné pre prezentáciu tlačiarenskej firmy.

## Sekcie

- **Hero** – hlavný banner s CTA tlačidlami a hodnotením
- **Trust bar** – rýchle dôveryhodnostné signály
- **Služby** – 6 kariet tlačiarenských služdieb
- **Štatistiky** – kľúčové čísla firmy
- **O nás** – predstavenie firmy
- **Kontakt** – adresa, telefón, otváracie hodiny
- **Formulár** – cenová ponuka cez EmailJS
- **Mapa** – Google Maps embed
- **Footer** – navigácia a kontaktné info

## Technológie

- Plain HTML / CSS / JavaScript
- [Inter](https://fonts.google.com/specimen/Inter) + [Playfair Display](https://fonts.google.com/specimen/Playfair+Display) (Google Fonts)
- [Motion](https://motion.dev) – spring animácie (vanilla JS)
- [EmailJS](https://www.emailjs.com) – odosielanie formulára bez backendu

## Spustenie

Stačí otvoriť `index.html` v prehliadači. Žiadna inštalácia nie je potrebná.

## EmailJS konfigúrácia

Formulár používa EmailJS. Credentials sú nastavené priamo v `index.html`:

| Parameter | Hodnota |
|---|---|
| Public Key | `kXLXwsJknN8aGv-97` |
| Service ID | `service_43xvxme` |
| Template ID | `template_my1gg5n` |

Premenné šablóny: `{{meno}}`, `{{firma}}`, `{{email}}`, `{{tel}}`, `{{sluzba}}`, `{{sprava}}`

## Kontakt

**Equilibria**  
Textilná 4, 040 12 Košice  
Tel: 0909 186 702  
Web: [equilibria.sk](https://equilibria.sk)  
Otvorené: Po–Pia 8:00–17:00
