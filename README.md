# Política de Privacidad — AhorraPe

**Última actualización:** 13 de mayo de 2026  
**Desarrollador:** ManuPrimeStudio  
**Nombre de la aplicación:** AhorraPe  
**Paquete:** com.manuprimestudio.ahorrape

---

## 1. Introducción

AhorraPe ("la Aplicación") es una herramienta de finanzas personales diseñada para ayudar a los usuarios a registrar sus ingresos, gastos y metas de ahorro de forma privada. En ManuPrimeStudio respetamos tu privacidad y nos comprometemos a proteger tus datos personales.

Esta Política de Privacidad explica qué información recopilamos, cómo la usamos y cuáles son tus derechos.

---

## 2. Información que Recopilamos

### 2.1. Datos Financieros Ingresados por el Usuario
La Aplicación permite al usuario registrar voluntariamente:
- Ingresos (monto, fuente, frecuencia)
- Gastos (monto, categoría, nota, fecha)
- Metas de ahorro (nombre, monto objetivo, fecha límite)
- Presupuestos mensuales por categoría

### 2.2. Datos de Perfil y Preferencias
- Preferencias de tema (claro/oscuro/sistema)
- Configuración de notificaciones (hora del recordatorio)
- Modo simplificado y tamaño de texto
- Progreso de gamificación (monedas virtuales, rachas, mascotas desbloqueadas)

### 2.3. Imágenes (Opcional)
El usuario puede opcionalmente tomar o seleccionar fotos desde su galería para personalizar sus metas de ahorro. Estas imágenes se almacenan **únicamente en el dispositivo** del usuario.

### 2.4. Datos Biométricos
Si el usuario habilita el bloqueo biométrico, la Aplicación utiliza el sistema de autenticación del dispositivo (huella dactilar, reconocimiento facial). **No almacenamos ni transmitimos datos biométricos.** La verificación es procesada íntegramente por el sistema operativo del dispositivo.

### 2.5. Datos de Publicidad (Google AdMob)
La Aplicación puede incluir anuncios proporcionados por Google AdMob. Google puede recopilar cierta información del dispositivo con fines publicitarios, incluyendo:
- Identificadores de publicidad del dispositivo
- Información técnica del dispositivo (modelo, sistema operativo)
- Datos de interacción con los anuncios

Para más información, consulta la [Política de Privacidad de Google](https://policies.google.com/privacy).

---

## 3. Cómo Almacenamos los Datos

### 3.1. Almacenamiento Local y Encriptado
**Todos los datos financieros y de perfil se almacenan exclusivamente en el dispositivo del usuario**, utilizando almacenamiento encriptado (Hive con cifrado AES-256 mediante Flutter Secure Storage). 

**No enviamos, transferimos ni almacenamos tus datos financieros en ningún servidor externo.**

### 3.2. No Hay Cuentas de Usuario
La Aplicación **no requiere registro, inicio de sesión, correo electrónico, número de teléfono ni ningún dato de identificación personal** para funcionar.

### 3.3. No Hay Sincronización en la Nube
Los datos no se sincronizan con servicios en la nube. Si el usuario desinstala la Aplicación o cambia de dispositivo, los datos se perderán a menos que el usuario los exporte manualmente.

---

## 4. Cómo Usamos los Datos

Usamos la información almacenada en el dispositivo exclusivamente para:
- Mostrar resúmenes financieros, gráficos y estadísticas al usuario
- Calcular presupuestos y progreso de metas de ahorro
- Gestionar la mecánica de gamificación (mascotas, monedas, rachas)
- Enviar notificaciones locales de recordatorio (configuradas por el usuario)
- Generar reportes exportables (a solicitud del usuario)

**No vendemos, compartimos ni transferimos datos del usuario a terceros**, excepto por la información técnica que Google AdMob pueda recopilar según su propia política de privacidad.

---

## 5. Permisos de la Aplicación

| Permiso | Propósito |
|---|---|
| **Biometría** (`USE_BIOMETRIC`, `USE_FINGERPRINT`) | Autenticación opcional para proteger el acceso a la app |
| **Notificaciones** (`POST_NOTIFICATIONS`) | Enviar recordatorios diarios configurados por el usuario |
| **Internet** | Mostrar anuncios de Google AdMob |
| **Cámara/Galería** (mediante `image_picker`) | Permitir al usuario adjuntar fotos a sus metas de ahorro |

---

## 6. Compartir Información

La Aplicación incluye funciones de exportación y compartir que **el usuario activa voluntariamente**:
- **Reportes financieros** (archivo .txt) que el usuario puede compartir via WhatsApp, Gmail, etc.
- **Datos en formato CSV** (archivo .csv) que el usuario puede abrir en Excel o Google Sheets.
- **Resumen semanal** (imagen .png) que el usuario puede compartir en redes sociales.

Estos archivos se generan localmente y se comparten **solo cuando el usuario lo decide**. No se envían automáticamente a ningún servidor.

---

## 7. Seguridad

Implementamos las siguientes medidas de seguridad:
- **Encriptación AES-256** para todos los datos almacenados localmente
- **Bloqueo biométrico opcional** para proteger el acceso a la aplicación
- **Desactivación de backups automáticos** (`android:allowBackup="false"`) para prevenir que los datos sean extraídos por herramientas de respaldo
- **Tráfico HTTPS obligatorio** (`android:usesCleartextTraffic="false"`)
- **Sanitización de datos** en todos los modelos para prevenir inyección de datos maliciosos

---

## 8. Menores de Edad

La Aplicación no está dirigida a menores de 18 años. No recopilamos intencionalmente información de niños menores de 13 años. Si eres padre o tutor y crees que tu hijo nos ha proporcionado información, contáctanos para que podamos tomar las medidas necesarias.

---

## 9. Cambios en esta Política

Podemos actualizar esta Política de Privacidad periódicamente. Notificaremos a los usuarios sobre cambios significativos a través de una actualización en la Aplicación. Te recomendamos revisar esta política regularmente.

---

## 10. Tus Derechos

Como usuario, tienes derecho a:
- **Acceder** a todos tus datos (están almacenados en tu propio dispositivo)
- **Exportar** tus datos en cualquier momento mediante las funciones de reporte
- **Eliminar** todos tus datos desinstalando la Aplicación
- **Desactivar** la publicidad personalizada desde la configuración de tu dispositivo Android (Configuración → Google → Anuncios)

---

## 11. Contacto

Si tienes preguntas o inquietudes sobre esta Política de Privacidad, puedes contactarnos en:

**ManuPrimeStudio**  
📧 Email: soporte.ahorrape@gmail.com


---

*Esta política es efectiva a partir de la fecha de última actualización indicada arriba.*
