# 🍽️ Sistema de Reservas para Restaurante Gourmet

Este proyecto es una aplicación web moderna para gestionar reservas de un restaurante gourmet. Permite a los usuarios registrar su reservación, ver el estado, realizar pagos en línea mediante PayPal, y gestionar cancelaciones. El sistema utiliza tecnologías modernas como Firebase, GitHub Pages y Bootstrap para ofrecer una experiencia elegante, rápida y funcional.

---

## 🚀 Tecnologías Utilizadas

- **HTML5 & CSS3**: Lenguajes base para estructura y estilo.
- **Bootstrap 5**: Framework para diseño responsive y componentes modernos.
- **JavaScript (ES6 Modules)**: Lógica de interacción del sitio.
- **Firebase (Firestore)**: Almacenamiento de reservas en tiempo real.
- **Firebase Hosting (parcial)**: Uso de servicios de Google para gestionar datos.
- **PayPal SDK**: Procesamiento de pagos seguros.
- **Git & GitHub**: Control de versiones y despliegue.
- **GitHub Pages**: Hosting gratuito y público para el sitio web.

---

## 📋 Funcionalidades principales

- ✅ **Formulario de reserva** con validación de campos y selección de cantidad de personas.
- 🕒 **Validación de fechas y horarios**: No permite reservar en fechas pasadas ni duplicar horarios.
- 💳 **Integración con PayPal**: Los usuarios pueden pagar desde la misma página.
- 📦 **Base de datos en la nube (Firebase Firestore)**: Registra, actualiza y elimina reservas en tiempo real.
- 🔄 **Estado de las reservas**:
  - `Pendiente`: Requiere pago.
  - `Pagada`: Confirmada.
  - `Cancelada`: Eliminada o anulada.
- 🔧 **Gestión de reservas**: Los usuarios pueden cancelar una reserva y verla reflejada inmediatamente.
- 🌐 **Despliegue en GitHub Pages**: El sistema está disponible en línea 24/7.

---

## 📁 Estructura del proyecto

```bash
.
├── index.html              # Página principal
├── /images                 # Carpeta para imágenes del sitio (opcional)
├── /css                    # Estilos personalizados si aplica
├── /js                     # Scripts JavaScript si están separados

🙋‍♂️ Autor
Desarrollado por Giovanny Rivera
Estudiante de Ingeniería en Tecnologías de la Información
GitHub: @giooriveraa

📄 Licencia
Este proyecto es de uso libre para fines educativos. Créditos al autor original. Puedes adaptarlo o mejorarlo dando reconocimiento adecuado.
