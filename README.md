# 🐧 RHEL 10 Labs - NFS, Samba y Controlador de Dominio con Samba4

Repositorio con las prácticas realizadas en **Red Hat Enterprise Linux 10 (RHEL 10)** para la asignatura de Sistemas Operativos III.

## 📚 Contenido

### ✅ Práctica 1 - Servidor NFS

Implementación de un servidor **NFS (Network File System)** para compartir archivos entre dos máquinas Linux.

**Objetivos**

* Instalar y configurar NFS Server.
* Crear el directorio compartido **OS3**.
* Generar 100 archivos (`Adrian1.txt` hasta `Adrian100.txt`).
* Configurar permisos y propietarios.
* Configurar `/etc/exports`.
* Montar el recurso desde un cliente Linux.
* Configurar montaje automático mediante `/etc/fstab`.
* Verificar el montaje después de reiniciar el sistema.

---

### ✅ Práctica 2 - File Server con Samba

Implementación de un servidor de archivos compatible con Windows utilizando **Samba**.

**Objetivos**

* Instalar y configurar Samba.
* Crear usuarios y grupos.
* Configurar una carpeta compartida.
* Generar 100 archivos (`adrian1.txt` hasta `adrian100.txt`).
* Mapear la carpeta compartida como una unidad de red en Windows.
* Modificar el archivo `Adrian99.txt` desde Windows.
* Verificar desde Linux que los cambios fueron aplicados correctamente.

---

### ✅ Práctica 3 - Controlador de Dominio Samba4

Implementación de un **Controlador de Dominio** utilizando Samba4.

**Objetivos**

* Crear el usuario `lanegracubana`.
* Agregar el usuario a Samba.
* Crear el dominio:

```text
SO3.inet
```

* Configurar Samba4 como Domain Controller.
* Unir un cliente Windows al dominio.
* Iniciar sesión utilizando el usuario del dominio.
* Verificar la autenticación correctamente.

---

# 🖥️ Tecnologías utilizadas

* Red Hat Enterprise Linux 10
* Samba
* Samba4 Active Directory
* NFS
* Windows 10/11
* systemd
* Firewalld
* SELinux

---

---

# 🎯 Competencias desarrolladas

* Administración de servidores Linux.
* Compartición de archivos mediante NFS.
* Administración de recursos compartidos con Samba.
* Integración Linux–Windows.
* Administración de usuarios y permisos.
* Implementación de un Controlador de Dominio.
* Gestión de Active Directory con Samba4.
* Configuración de clientes Windows en un dominio.

---

# 📸 Evidencias

Cada práctica incluye capturas de pantalla mostrando:

* Configuración realizada.
* Ejecución de comandos.
* Verificación del funcionamiento.
* Resultados obtenidos.

---

# 👨‍💻 Autor

**Víctor De Peña**
Tecnólogo en Seguridad Informática


⭐ Si este repositorio te resulta útil, no olvides darle una estrella.
