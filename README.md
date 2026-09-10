# REDSIM CONTROL

## Case técnico — Plataforma SaaS para gestión operacional

> De una necesidad real a una solución real.

**REDSIM CONTROL** es una plataforma SaaS desarrollada por **Kairós Tech** a partir de una necesidad real de operación en terreno: transformar información dispersa en una solución centralizada, estructurada y trazable.

---

## 🎯 El desafío

En operaciones en terreno, la información puede terminar distribuida entre:

- WhatsApp
- Fotografías
- Planillas
- Registros manuales
- Comunicación dispersa

El desafío no era solamente reemplazar una planilla.

Era construir una solución que pudiera adaptarse a las personas que trabajan en terreno y, al mismo tiempo, entregar información organizada para la gestión.

---

## 👥 Las personas primero

Uno de los principales criterios del proyecto fue considerar que no todos los trabajadores tienen el mismo nivel de familiaridad con la tecnología.

Por eso, REDSIM CONTROL fue diseñado buscando una experiencia:

**Simple. Clara. Directa.**

La tecnología debía adaptarse a las personas y a la realidad de la operación.

---

## 💡 La solución

REDSIM CONTROL centraliza la gestión operacional en una única plataforma.

### Principales áreas

- 👥 Gestión de funcionarios
- 🏢 Empresas y plantas
- 📋 Gestión y seguimiento del trabajo
- 📝 Novedades
- 📅 Ausencias
- 📊 Informes
- ⚙️ Configuración
- 🔐 Control de acceso

La información pasa de estar dispersa a estar estructurada y disponible para la gestión.

---

## 🔐 Seguridad

La seguridad fue considerada desde la arquitectura de la solución.

### Implementaciones principales

- Autenticación
- Control de acceso por perfiles
- Aislamiento de información por empresa
- Row Level Security (RLS)
- PostgreSQL
- Supabase Auth
- Protección de operaciones según empresa y permisos

El objetivo es garantizar que cada usuario pueda acceder únicamente a la información correspondiente a su contexto y permisos.

---

## 🛠️ Stack tecnológico

| Tecnología | Uso |
|---|---|
| React | Interfaz de usuario |
| TypeScript | Desarrollo tipado |
| Vite | Build y desarrollo |
| Supabase | Backend y servicios |
| PostgreSQL | Base de datos |
| Supabase Auth | Autenticación |
| RLS | Seguridad y aislamiento de datos |
| PWA | Experiencia adaptada a dispositivos móviles |

---

## 📱 Experiencia móvil

REDSIM CONTROL también fue pensado para dispositivos móviles, permitiendo una experiencia adaptada a trabajadores que realizan parte de su actividad en terreno.

---

## 🔄 De la operación a la gestión

```text
CAMPO
   ↓
REGISTRO
   ↓
INFORMACIÓN
   ↓
GESTIÓN
   ↓
DECISIÓN
