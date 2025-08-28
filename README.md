# 📦 Deployments para K3s

Este repositorio contiene una colección de **Deployments** listos para usar en un clúster **K3s**.  
Cada manifiesto `.yaml` despliega una aplicación o servicio útil en entornos de laboratorio o productividad personal.

---

## 📂 Deployments incluidos

- **brave.yaml** → Navegador Brave en contenedor (uso remoto / testing).
- **cloudflare.yaml** → Conector para Cloudflare Tunnel (exponer servicios de forma segura).
- **ittools.yaml** → Suite de herramientas de IT accesibles vía web.
- **kuma_uptime.yaml** → Uptime Kuma, monitorización de servicios y disponibilidad.
- **mysql.yaml** → Base de datos MySQL lista para usar.
- **n8n.yaml** → Plataforma de automatización de flujos de trabajo.
- **obsidian.yaml** → Obsidian en contenedor para gestión de notas Markdown.
- **pihole.yaml** → Pi-hole, bloqueador de publicidad y rastreadores DNS.
- **stirling_pdf.yaml** → Stirling PDF, utilidades para manipulación de archivos PDF.
- **vs_code.yaml** → Visual Studio Code en versión web (VS Code Server).

---

## 🚀 Uso

Clona el repositorio y aplica el deployment que necesites:

```bash
kubectl apply -f deployments/<archivo>.yaml
