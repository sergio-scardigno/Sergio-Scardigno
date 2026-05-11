# Sergio Scardigno

### Backend & DevOps — Arquitectura, CI/CD, Infraestructura

[![LinkedIn](https://img.shields.io/badge/LinkedIn-sergio--scardigno-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/sergio-scardigno/)
[![CV](https://img.shields.io/badge/CV-Online-0f3460?style=flat)](https://cv-sergio-scardigno.vercel.app)
[![Email](https://img.shields.io/badge/Email-sergioscardigno82%40gmail.com-EA4335?style=flat&logo=gmail)](mailto:sergioscardigno82@gmail.com)

---

## Stack

**Backend:** PHP 8.x · Laravel 10/11 · Node.js · Express · Python · C#

**Frontend:** Angular 16+ · React · Next.js · TypeScript · Tailwind CSS

**Infra & DevOps:** Docker · Kubernetes · AWS (EKS, EC2, LB) · Jenkins · Terraform · Ansible · GitOps (ArgoCD) · Prometheus · Grafana

**Databases:** PostgreSQL · MySQL · SQL Server · MongoDB

**OS & Tools:** Linux (Ubuntu/Debian) · Nginx · Bash · Git · Vagrant

---

## Lo que suelo resolver

- **APIs backend** que escalan sin sorpresas: diseño REST, rate limiting, caché, testing
- **Pipelines CI/CD** que automatizan build → test → deploy → rollback. Menos clicks, menos errores
- **Refactors de sistemas legacy**: PHP 5 a 8.2, migración de ORMs, reemplazo de librerías deprecadas sin romper prod
- **Observabilidad**: métricas con Prometheus + Grafana, alertas, dashboards que dicen algo útil
- **Infraestructura como código**: entornos reproducibles con Docker Compose para desarrollo, Kubernetes o VMs para producción

---

## Proyectos y cosas que armé

### CI/CD para Angular con Jenkins
Pipeline declarativo (Jenkinsfile) que toma PRs de GitHub, corre tests, build de producción y deploy automático a Nginx. Reducción del ~60% en tiempo de entrega comparado con deploys manuales.
`Jenkins` `Angular` `Docker` `Nginx`

### Monitoreo de apps Laravel con Prometheus + Grafana
Docker Compose con exporters personalizados. Dashboard con throughput, latencia p95, tasa de errores 5xx y saturación de conexiones PostgreSQL. Publicado en [LinkedIn](https://bit.ly/3HmZR4X).
`Docker Compose` `Prometheus` `Grafana` `Laravel`

### Migración de VMs Proxmox → VMware ESXi
Conversión automatizada con StarWind V2V Converter. Zero-downtime para 5 VMs de producción. Artículo técnico en [LinkedIn](https://bit.ly/4jUYz34).
`Proxmox` `VMware ESXi` `StarWind V2V`

### Verificación de firmas digitales en PDF
Script en Python que detecta si una firma en un PDF es una imagen plana (inválida legalmente) o una firma digital criptográfica. [LinkedIn](https://bit.ly/3DbV5ZD)
`Python` `PyPDF2` `OpenCV`

### Reemplazo de `ultraware/roles` en Laravel 10
Librería deprecada → sistema de RBAC propio con gates y policies nativas de Laravel. Sin dependencias externas, 100% testeado. [LinkedIn](https://www.linkedin.com/pulse/reemplazando-la-librer%C3%ADa-deprecada-ultrawareroles-en-php-scardigno-zeeaf/)
`Laravel 10` `PHP 8.2` `RBAC`

### Conectando Ubuntu 22.04 a SQL Server 2000
¿Legacy extremo? Sí. ¿Imposible? No. Artículo con la solución paso a paso. [LinkedIn](https://www.linkedin.com/pulse/conectando-ubuntu-2204-sql-server-2000-superando-sergio-scardigno%3FtrackingId=eKnJ9deG2EZPGrAcajPAVg%253D%253D/?trackingId=eKnJ9deG2EZPGrAcajPAVg%3D%3D)
`Ubuntu` `SQL Server 2000` `ODBC`

---

## Principios que sigo

- **Testing no es opcional.** Si no tiene tests, no está terminado.
- **Infraestructura en código.** Todo entorno se reconstruye con un comando.
- **Simplicidad primero.** Complejidad solo cuando se justifica con datos.
- **Code review sin ego.** Discutir arquitectura y decisiones técnicas es parte del laburo.
- **Documentación viva.** Un `README.md` desactualizado es deuda técnica.

---

## Dónde estoy ahora

- **Dirección Gral. de Cultura y Educación (PBA)** — Full-Stack & DevOps. Mantengo y evoluciono plataformas de gestión educativa con Angular + Laravel + PostgreSQL. CI/CD con Jenkins, monitoreo con Prometheus/Grafana.
- **Freelance** — Arquitectura, refactors y automatización para clientes. Abierto a proyectos donde el backend, la infra o la seguridad sean el core.

---

## Contacto técnico

Si tenés un proyecto donde pueda aportar desde arquitectura, backend o DevOps, o si querés discutir alguna de las publicaciones técnicas:

- **GitHub Issues/Discussions** en este repo
- **LinkedIn:** [sergio-scardigno](https://www.linkedin.com/in/sergio-scardigno/)
- **Email:** sergioscardigno82@gmail.com
