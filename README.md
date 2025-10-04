# MetSisII
Repositorio de la materia Metodologías en Sistemas II, destinado a la presentación del proyecto de la materia.

🐾 Plataforma Veterinaria Online – Veterinarias del sur

🚀 Objetivo:

El objetivo principal de esta WebApp es ofrecer una solución moderna y accesible para veterinarias y profesionales independientes, que necesiten una herramienta sencilla para gestionar sus pacientes (mascotas), dueños y turnos médicos.

La plataforma busca ser amigable, adaptable y escalable, de forma que pueda personalizarse fácilmente según la estética o las necesidades de cada clínica o profesional.

🔑 Funcionalidades:

🧑‍⚕️ Para veterinarios/as:

Registrar, editar o eliminar mascotas y dueños.

Gestionar fichas médicas (vacunas, diagnósticos, tratamientos).

Controlar el stock de medicamentos.

Visualizar un dashboard con estadísticas (cantidad de pacientes, visitas, vacunas pendientes, etc.).

Exportar fichas médicas a PDF o JSON.

👤 Para dueños de mascotas:

Registrarse y acceder a su perfil.

Consultar información de su mascota y su historial médico.

Solicitar, confirmar o cancelar turnos online.

Recibir recordatorios automáticos sobre vacunas o citas próximas.

⚙ Tecnologías a utilizar
Frontend:

TypeScript + React + Vite → interfaz moderna y rápida.

TailwindCSS o Bootstrap → estilos simples y responsive.

Axios → comunicación con el backend.

Backend:

Node.js con Express → API REST para manejo de datos.

JWT → autenticación segura.

Multer → manejo de archivos (fotos de mascotas, documentos).

Base de datos:

PostgreSQL (principal)

Prisma ORM o Sequelize para el manejo de datos.

Hosting:

Frontend: Vercel o Netlify.

Backend: Render, Railway o Fly.io.

Base de datos: NeonDB o Supabase.

☢ Patrones de diseño a utilizar

Singleton:
Controlará la conexión a la base de datos para garantizar una única instancia activa del cliente de conexión.

Factory Method:
Se aplicará para crear diferentes tipos de usuarios (veterinario, cliente, administrador) o distintos modelos de notificación.
