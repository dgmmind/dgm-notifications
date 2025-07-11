# 🔔 Simple Notification System

**Sistema de notificaciones en JavaScript orientado a objetos (POO)**  
Permite mostrar notificaciones simples o con confirmación, con personalización de tema, posición e iconos.

---

## ✨ Características

- 🌙 **Cambiar Tema**: `light`, `dark` o `auto`
- 📍 **Cambiar Posición**: personalizable por clase o estilo
- 🗑️ **Limpiar Todo**: eliminar todas las notificaciones activas
- 🎯 **Notificaciones Básicas**: mensajes informativos
- ✅ **Success**
- ❌ **Danger**
- ℹ️ **Info**
- 📝 **Confirmaciones**: notificaciones con botones de acción
  - 🗑️ Confirmar Eliminación
  - 💾 Confirmar Guardado
  - 🚪 Confirmar Logout

---

## 📚 Uso de la API

### 🔹 Notificación básica

```js
showNotify({
  type: 'success',           // success, danger, info
  titulo: 'Operación exitosa',
  descripcion: 'Todo salió bien',
  tiempo: 5000,              // milisegundos
  icono: '✅',              // emoji o texto
  theme: 'light'             // light, dark, auto
});
