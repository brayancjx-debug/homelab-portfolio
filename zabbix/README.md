# 📊 Zabbix — Monitoreo del Homelab

> **Objetivo:** Monitorear en tiempo real el estado de mis servidores, servicios de red y disponibilidad, con alertas automáticas ante fallos.

---

## 1. Resumen del proyecto

| Dato | Detalle |
|------|---------|
| Servicio | Zabbix (Server + Frontend) |
| Versión | *(ej. Zabbix 7.0 LTS)* |
| Sistema operativo | *(ej. Ubuntu Server 22.04)* |
| Base de datos | *(ej. MySQL / PostgreSQL)* |
| Equipos monitoreados | *(ej. 3 servidores Linux, 1 Windows, pfSense)* |

---

## 2. ¿Qué es y para qué lo uso?

Explica en 2–3 líneas, con tus palabras, qué problema resuelve Zabbix en tu homelab.

> Ejemplo: *"Instalé Zabbix para tener visibilidad centralizada del uso de CPU, RAM, disco y disponibilidad de mis máquinas, y recibir alertas por correo cuando algo falla."*

---

## 3. Arquitectura / Cómo está montado

Describe brevemente dónde corre el servidor y qué monitorea.

![Arquitectura de monitoreo](./img/01-arquitectura.png)

---

## 4. Instalación (paso a paso)

Documenta los pasos principales que seguiste. Puedes pegar los comandos reales:

```bash
# Ejemplo — reemplaza por tus comandos reales
sudo apt update
# ... instalación del repositorio de Zabbix
# ... instalación de zabbix-server, frontend y agente
```

![Instalación completada](./img/02-instalacion.png)

---

## 5. Configuración clave

Explica las configuraciones importantes que hiciste. Algunas ideas:

- **Alta de hosts:** cómo agregaste los equipos a monitorear.
- **Agente Zabbix:** instalación y configuración en los clientes.
- **Templates aplicados:** ej. *Linux by Zabbix agent*, *Windows*, etc.
- **Triggers / umbrales:** qué condiciones generan alerta.
- **Notificaciones:** correo, Telegram, etc.

![Dashboard principal](./img/03-dashboard.png)

![Configuración de host](./img/04-host.png)

---

## 6. Alertas y notificaciones

Muestra cómo configuraste las alertas y una captura de una alerta real (si la tienes).

![Ejemplo de alerta](./img/05-alerta.png)

---

## 7. Resultado final

Resume qué lograste y qué aprendiste.

> Ejemplo: *"Ahora tengo un panel centralizado con el estado de todo mi homelab y recibo alertas en menos de 1 minuto ante caídas de servicio."*

---

## 8. Problemas encontrados y soluciones (opcional pero recomendado)

Este apartado suma mucho valor ante reclutadores: demuestra resolución de problemas.

| Problema | Cómo lo resolví |
|----------|-----------------|
| *(ej. El agente no conectaba)* | *(ej. Abrí el puerto 10050 en el firewall)* |

---

[⬅️ Volver al portafolio principal](../README.md)
