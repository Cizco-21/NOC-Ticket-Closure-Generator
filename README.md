# 🛠 NOC Ticket Closure Generator

Generador web para **cierre de tickets NOC**, diseñado para agilizar la documentación de incidentes y solicitudes.

Permite generar textos estandarizados, gestionar historial por usuario y trabajar completamente desde el navegador sin dependencias externas.

---

## 🚀 Características principales

- 🔐 **1. Login de usuarios** (sesión por navegador)
  - 👤 Campo *Quién cierra* autocompletado según el usuario logueado (editable)

- ✍️ **2. Generación automática de cierre de tickets**
  - 📋 Copiar texto generado con un clic
  - 🧾 Listas dinámicas según tipo de reporte (**FALLA / SOLICITUD**)

- 💾 **3. Gestión de soluciones predefinidas**

- 🧠 **4. Historial por usuario** (localStorage)
  - 🔍 Búsqueda en historial
  - 📤 Exportación de historial a **Excel (CSV)**

- 🌙 **5. Modo oscuro / modo claro**

---

### ✅🔐 1. Al iniciar sesión:
- Se cargan tus **presets personales**
- Se muestra tu **historial individual**
- El campo **QUIÉN CIERRA** se completa automáticamente (editable)

---
### ✍️ 2. Generar el cierre del ticket

Completa los campos según el ticket que estás cerrando:

**CAUSA DE FALLA**
   - La lista cambia automáticamente según el tipo de **REPORTE**
     - FALLA → causas técnicas
     - SOLICITUD → requerimientos administrativos o de configuración

- Presiona **✍️ Escribir**
- El texto completo se genera automáticamente en el área inferior
- El resultado se guarda automáticamente en el **historial**

- Presiona **📋 Copiar**
- El texto queda listo para pegar.

---

### 💾 3. Gestión de soluciones predefinidas

#### Guardar una solución
1. Escribe el texto en **SOLUCIÓN**
2. Presiona **💾 Guardar**
3. La solución quedará disponible solo para tu usuario

#### Editar una solución
1. Selecciona una solución guardada
2. Modifica el texto
3. Presiona **✏️ Editar**

#### Eliminar una solución
1. Selecciona una solución guardada
2. Presiona **🗑 Eliminar**

⚠️ Las soluciones base no pueden eliminarse.

---

### 📜 4. Historial

- Cada cierre generado se guarda automáticamente
- El historial es **individual por usuario**
- Incluye:
  - Fecha y hora
  - Todos los campos del cierre

#### Buscar en el historial
- Usa el campo **🔍 Buscar historial**
- Filtra por:
  - Cliente
  - Causa
  - Producto
  - Fecha
  - Texto libre

---

### 📤 Exportar historial a Excel

- Presiona **📤 Exportar Excel**
- Se descarga un archivo `.csv`
- Puede abrirse directamente en Excel

---

### ⚠️ Consideraciones importantes

- Toda la información se guarda en el navegador usando **localStorage**
- Los datos:
  - No se comparten entre equipos
  - No se suben a internet
- Si se limpia el navegador, el historial se pierde

