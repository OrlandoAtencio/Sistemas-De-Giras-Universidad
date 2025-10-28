# 📚 Sistema de Registro de Giras Técnicas - Universidad de Panamá

Este proyecto permite a estudiantes, organizadores y administradores gestionar giras técnicas universitarias. Incluye autenticación, inscripción, comentarios, bitácora de accesos y reportes.

---

## 🏗️ Estructura del Proyecto

Sistemas-De-Giras-Universidad/ ├── database/ │   ├── schema.sql │   ├── insert.sql │   ├── select.sql │   ├── update.sql │   ├── delete.sql ├── docs/ │   └── erd-diagram.png ├── .env.example ├── README.md ├── LICENSE ├── .gitignore

---

## 🧠 Esquema de Base de Datos

El sistema incluye las siguientes tablas:

- `Usuarios`: login, roles y registro
- `Facultades`: facultades académicas
- `Organizadores`: responsables de giras
- `Giras`: eventos técnicos disponibles
- `Inscripciones`: registro de estudiantes
- `Comentarios`: opiniones sobre giras
- `BitacoraAccesos`: historial de accesos

Consulta el diagrama ERD en [`/docs/erd-diagram.png`](docs/erd-diagram.png)

---

## 👥 Roles del Equipo

| Nombre             | Rol en el Proyecto     | Archivo asignado   |
|--------------------|------------------------|--------------------|
| Mario Barsallo     | Arquitecto técnico     | `schema.sql`, `.env.example` |
| Abdiel             | Consultas y reportes   | `select.sql`       |
| Allen              | Modificaciones         | `update.sql`       |
| Cristopher Hull    | Eliminaciones seguras  | `delete.sql`       |
| Orlando            | Revisión y aprobación  | Pull Requests      |

---

## ⚙️ Instalación del Backend

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/Sistemas-De-Giras-Universidad.git
   cd Sistemas-De-Giras-Universidad
   bash npm install
   Scripts de Base de Datos
Ejecuta los scripts en este orden para poblar la base de datos:
1. 	 → crea las tablas
2. 	 → inserta datos iniciales
3. 	 → consultas para reportes
4. 	 → pruebas de modificación
5. 	 → pruebas de eliminación
