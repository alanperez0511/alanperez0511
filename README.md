# ¡Hola, soy Alan Pérez! 👋

Desarrollador Full-Stack y soporte de infraestructura TI en **ISTHO S.A.S.** (Girardota, Colombia). Hago parte del equipo que desarrolla **CenthriX**, una suite de software multiempresa para logística, almacenamiento y gestión de activos, en producción.

## 🚀 Sobre mí

- 🏗️ Desarrollo y mantengo tres productos en producción bajo la marca CenthriX: **OMS** (operaciones logísticas y transporte), **WMS** (gestión de bodegas) y **EAM** (gestión de activos y mesa de ayuda).
- 🏢 Trabajo con arquitectura **multiempresa (multi-tenant)**: aislamiento de datos por empresa, productos y suscripciones, y permisos por rol y módulo.
- 🔌 Integro sistemas entre sí y con terceros: sincronización entre el WMS y el OMS, conectores de datos para **Power BI**, correo transaccional y un **asistente de IA** que consulta información operativa.
- 📊 Construyo reportería de negocio de punta a punta: exportación a Excel/PDF, KPIs, reportes programados y vistas consolidadas sobre grandes volúmenes de datos.
- ⚡ Me enfoco en rendimiento: paginación server-side, optimización de consultas SQL y reducción de payloads (por ejemplo, una vista que pesaba 5+ MB por carga bajó a ~100 KB).
- 🔐 Aplico buenas prácticas de seguridad: autenticación JWT con **MFA**, permisos por rol, auditoría de acciones, API keys con alcances, rate limiting, sanitización y políticas CSP.
- ⚙️ Uso **Claude Code** como herramienta diaria de desarrollo, con pruebas de integración automatizadas, migraciones versionadas y flujo de ramas con PRs hacia pruebas y producción.
- 🖥️ Además del desarrollo, apoyo la infraestructura tecnológica de la empresa: Microsoft 365, equipos de cómputo y red.

## 🧩 Ecosistema CenthriX

| Producto | Qué hace | Stack |
| --- | --- | --- |
| **CenthriX OMS** | Operaciones logísticas: entradas, salidas y kardex, inventario en tiempo real, viajes y transporte, portal de clientes, reportes y tableros. | Node.js · Express · Sequelize · PostgreSQL · React · Vite · Tailwind · Socket.IO · AWS S3 |
| **CenthriX WMS** | Gestión de bodegas: recepciones, ubicaciones, picking, kardex y trazabilidad, terminal móvil para operarios con lectura de códigos, rótulos y reportes. | NestJS · Prisma · PostgreSQL · Next.js · React · TypeScript · Socket.IO |
| **CenthriX EAM** | Gestión de activos empresariales y mesa de ayuda con SLA: hoja de vida de equipos, actas con firma digital, formularios dinámicos e importación masiva. | Node.js · Express · Sequelize · PostgreSQL · React · Vite · Tailwind |

## 🏆 Lo que he construido (selección)

- **Arquitectura multiempresa** en los tres productos, con aislamiento automático de datos, catálogos y configuración por empresa, y una capa de plataforma para productos y suscripciones.
- **Integración WMS ↔ OMS** con sincronización híbrida (eventos + consultas), tolerante a fallos y con trazabilidad de cada envío.
- **Flujos operativos completos** de bodega: recepción, ubicación, picking, correcciones sobre órdenes en curso y actualización en vivo en pantalla.
- **Reportería y documentos**: reportes nativos con filtros y exportación, PDFs de operación optimizados para impresión, cargas y ajustes masivos por Excel.
- **Gestión de activos y soporte**: ciclo de vida de equipos, actas con firma digital, mesa de ayuda con SLA y calendario laboral.
- **Calidad y seguridad**: baterías de pruebas de integración contra base de datos real, CI, MFA, auditoría y cierre de vulnerabilidades de acceso entre empresas.

## 🛠️ Stack técnico

**Frontend**
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white)
![MUI](https://img.shields.io/badge/MUI-007FFF?style=flat&logo=mui&logoColor=white)

**Backend**
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat&logo=nestjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Sequelize](https://img.shields.io/badge/Sequelize-52B0E7?style=flat&logo=sequelize&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=flat&logo=socket.io&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-C21325?style=flat&logo=jest&logoColor=white)

**Infraestructura, Cloud e IA**
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=flat&logo=railway&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Anthropic](https://img.shields.io/badge/Claude_API-191919?style=flat&logo=anthropic&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Microsoft](https://img.shields.io/badge/Microsoft_365-5E5E5E?style=flat&logo=microsoft&logoColor=white)
![Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)

## 🖥️ Infraestructura & Soporte TI

- Administración de **Microsoft 365**: cuentas de correo corporativo, licencias y métodos de autenticación.
- Despliegues en **AWS**, **Railway** y **Vercel**, con entornos de producción y pruebas separados.
- Mantenimiento preventivo y correctivo de equipos de cómputo; soporte en infraestructura de red (Access Points, racks, CCTV).

## 💼 Experiencia

**ISTHO S.A.S.**
- **Auxiliar Desarrollo de Software** · oct. 2025 – Presente
- **Practicante de Desarrollo de Software** · abr. 2025 – oct. 2025 (6 meses)

**Desarrollo de software:**
- Desarrollo y mantenimiento de la suite CenthriX (OMS, WMS y EAM), en producción y en uso diario.
- Arquitectura multiempresa y plataforma de productos y suscripciones.
- Integración de sistemas: WMS ↔ OMS, Power BI, correo e IA.
- Reportería configurable (Excel/PDF, programada) y mejoras de rendimiento medibles.
- Seguridad: MFA, permisos por rol, auditoría, API keys, rate limiting y CSP.

**Infraestructura y soporte TI:**
- Administración de cuentas, licencias y autenticación en Microsoft 365.
- Mantenimiento de equipos y soporte en infraestructura de red (Access Points, racks, CCTV).

## 📫 Contacto

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alan-pérez/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:alanperez0511@gmail.com)
