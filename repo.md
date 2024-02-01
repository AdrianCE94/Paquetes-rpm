
# Ubicación de Repositorios en Rocky Linux

Los repositorios, esenciales para la gestión de software, son almacenados en ficheros con extensión `.repo`. Estos ficheros pueden ser habilitados o deshabilitados para instalar, actualizar o eliminar paquetes rpm. En Rocky Linux, estos archivos repositorios se encuentran en el directorio `/etc/yum.repos.d/`.

Cada fichero en este directorio puede contener uno o más repositorios, identificados por un nombre entre corchetes. A continuación, se muestra un ejemplo con el contenido del fichero `rocky.repo`, que alberga los repositorios oficiales de Rocky Linux:


```ini
[baseos]
name=Rocky Linux $releasever - BaseOS
baseurl=http://dl.rockylinux.org/pub/rocky/$releasever/BaseOS/$basearch/os/
gpgcheck=1
enabled=1
gpgkey=file:///etc/pki/rpm-gpg/RPM-GPG-KEY-rockyofficial

[appstream]
name=Rocky Linux $releasever - AppStream
baseurl=http://dl.rockylinux.org/pub/rocky/$releasever/AppStream/$basearch/os/
gpgcheck=1
enabled=1
gpgkey=file:///etc/pki/rpm-gpg/RPM-GPG-KEY-rockyofficial



[![Volver al README](img/seccion.png)](README.md)
