# Segundo Parcial - Servicios Telemáticos

Implementación del segundo parcial de Servicios Telemáticos.

## Topología

- Cliente: `cli-2225727` - 192.168.56.20
- Servidor 1: `srv1-2225727` - 192.168.56.10
- Servidor 2: `srv2-2225727` - 192.168.50.2

## Servicios implementados

- FTPS con vsftpd
- Firewall UFW y DNAT
- DNS sobre TLS (DoT)
- SFTP con OpenSSH
- Chroot para usuario SFTP

## Archivos de configuración

- `configuraciones/before.rules`
- `configuraciones/vsftpd.conf`
- `configuraciones/resolved.conf`
- `configuraciones/sshd_config`