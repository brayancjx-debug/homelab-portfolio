# 🛡️ Wazuh — SIEM y Detección de Amenazas

> **Objetivo:** Centralizar logs, detectar intrusiones y amenazas en mis equipos, y tener visibilidad de eventos de seguridad de mi homelab.

---

## 1. Resumen del proyecto

| Dato | Detalle |
|------|---------|
| Servicio | Wazuh (Manager + Indexer + Dashboard) |
| Versión | *(ej. Wazuh 4.9)* |
| Sistema operativo | *(ej. Ubuntu Server 22.04)* |
| Agentes desplegados | *(ej. 2 Linux, 1 Windows)* |
| Tipo de despliegue | *(ej. All-in-one / distribuido)* |

---

## 2. ¿Qué es y para qué lo uso?

Explica con tus palabras qué aporta Wazuh a tu homelab.

> Ejemplo: *"Desplegué Wazuh como SIEM para recolectar y analizar logs de mis equipos, detectar accesos sospechosos, cambios en archivos críticos y evaluar el cumplimiento de seguridad."*

---

## 3. Arquitectura / Cómo está montado

![Arquitectura Wazuh](./img/01-arquitectura.png)

---

## 4. Instalación (paso a paso)

```bash
# Ejemplo — reemplaza por tus comandos reales
curl -sO https://packages.wazuh.com/4.x/wazuh-install.sh
# sudo bash ./wazuh-install.sh -a
```

![Instalación completada](./img/02-instalacion.png)

---

## 5. Configuración clave

Ideas de lo que puedes documentar:

- **Despliegue de agentes:** cómo instalaste y registraste los agentes en Linux/Windows.
- **File Integrity Monitoring (FIM):** monitoreo de cambios en archivos críticos.
- **Detección de vulnerabilidades:** activación del módulo.
- **Reglas y decoders personalizados:** si creaste alguno.
- **Integraciones:** VirusTotal, correo, etc.

![Panel de agentes](./img/03-agentes.png)

![Dashboard de seguridad](./img/04-dashboard.png)

---

## 6. Alertas de seguridad

Muestra ejemplos de alertas detectadas (ej. intentos de login fallidos, cambios en archivos).

![Ejemplo de alerta](./img/05-alerta.png)

---

## 7. Resultado final

> Ejemplo: *"Tengo un SIEM funcional que me alerta de eventos de seguridad y me permite investigar incidentes desde un único panel."*

---

## 8. Problemas encontrados y soluciones (opcional)

| Problema | Cómo lo resolví |
|----------|-----------------|
| *(ej. El agente aparecía como desconectado)* | *(ej. Ajusté la IP del manager en ossec.conf)* |

---

[⬅️ Volver al portafolio principal](../README.md)
