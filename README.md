# Hola, soy Dalton Gómez 👋

Desarrollador web enfocado en **Angular** y **TypeScript**. Estudiante de noveno semestre de Tecnologías de la Información en la UAT, en Nuevo Laredo, Tamaulipas. Me interesa construir aplicaciones que funcionen bien en condiciones reales: sin conexión, con datos confiables y probadas a fondo.

**Busco mi primer puesto como desarrollador frontend o full stack.**

## Tecnologías

Angular · TypeScript · Tailwind CSS · Node.js · Electron · Supabase · PostgreSQL · SQLite · GitHub Actions

## Proyectos destacados

### [Kiosco de asistencia](https://github.com/DaltonAkenaton/Kiosco) · Instalado y entregado

Sistema de control de asistencia para el personal de limpieza y los veladores de la FCACS (UAT, Nuevo Laredo). Un kiosco en Windows registra entradas y salidas con número de empleado, PIN y foto, aunque no haya internet; un panel web le muestra al jefe retardos, faltas y pendientes por atender.

- Electron + Angular 21 con SQLite local; sincroniza con Supabase sin duplicar registros
- Fotos cifradas con AES-256-GCM que nunca salen del kiosco: a la nube sólo viaja su hash
- PostgreSQL con RLS en todas las tablas, Edge Functions y pruebas automáticas en GitHub Actions
- Turno nocturno que cruza la medianoche y cambio de horario de verano resueltos en el servidor

Lo diseñé y desarrollé de principio a fin para un cliente real: requisitos, seguridad, instalación, manuales y capacitación del responsable del sistema.

### [Stenbrary](https://github.com/DaltonAkenaton/Stenbrary) · [Demo en vivo](https://stenbrary.pages.dev)

Sistema de control de acceso y registro de visitas para bibliotecas universitarias. Es una PWA que funciona sin internet: el personal lee la credencial del alumno con un lector USB o la cámara, y el sistema genera estadísticas, reportes en PDF y Excel, y constancias.

- Angular 21 (standalone, signals), IndexedDB y Service Worker
- 491 pruebas unitarias y 85 E2E con Playwright, con CI en GitHub Actions
- Desplegado en Cloudflare Pages

En la demo, "Explorar con datos de ejemplo" carga datos ficticios para ver las estadísticas sin configurar nada.
