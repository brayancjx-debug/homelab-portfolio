# 🔥 pfSense — Firewall y Segmentación de Red

> **Objetivo:** Controlar el tráfico de mi red, segmentar servicios con VLANs y proteger el homelab con reglas de firewall.

---

## 1. Resumen del proyecto

| Dato | Detalle |
|------|---------|
| Servicio | pfSense |
| Versión | *(ej. pfSense CE 2.7)* |
| Hardware / VM | *(ej. VM en Proxmox / mini PC)* |
| Interfaces | *(ej. WAN, LAN, VLAN de servidores)* |

---

## 2. ¿Qué es y para qué lo uso?

> Ejemplo: *"Uso pfSense como firewall y router principal de mi homelab para separar mi red de laboratorio de la red doméstica y controlar qué tráfico entra y sale."*

---

## 3. Topología de red

![Topología](./img/01-topologia.png)

---

## 4. Instalación y configuración inicial

Documenta la instalación y la asignación de interfaces (WAN/LAN).

![Asignación de interfaces](./img/02-interfaces.png)

---

## 5. Configuración clave

Ideas de lo que puedes documentar:

- **Reglas de firewall:** qué permites y bloqueas en cada interfaz.
- **VLANs / segmentación:** separación de redes.
- **NAT / Port forwarding:** si expones algún servicio.
- **DHCP y DNS:** configuración de rangos y resolución.
- **VPN:** OpenVPN / WireGuard si lo tienes.
- **Paquetes instalados:** ej. pfBlockerNG, Suricata.

![Reglas de firewall](./img/03-reglas.png)

![Dashboard de pfSense](./img/04-dashboard.png)

---

## 6. Resultado final

> Ejemplo: *"Mi homelab está aislado de la red doméstica y solo permito el tráfico estrictamente necesario, mejorando la seguridad."*

---

## 7. Problemas encontrados y soluciones (opcional)

| Problema | Cómo lo resolví |
|----------|-----------------|
| *(ej. No tenía salida a internet en la LAN)* | *(ej. Creé la regla de NAT de salida correcta)* |

---

[⬅️ Volver al portafolio principal](../README.md)
