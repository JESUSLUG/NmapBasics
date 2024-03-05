
```markdown
# Comandos Básicos de Nmap

## 1. Escaneo de Puertos TCP (-sS)
   Comando: `nmap -sS <objetivo>`
   Propósito: Escaneo rápido y menos intrusivo utilizando un escaneo de tipo SYN para determinar qué puertos están abiertos.

## 2. Escaneo de Puertos UDP (-sU)
   Comando: `nmap -sU <objetivo>`
   Propósito: Descubre servicios que utilizan el protocolo UDP, útil para servicios como DNS y DHCP.

## 3. Escaneo de Enumeración de Versiones (-sV)
   Comando: `nmap -sV <objetivo>`
   Propósito: Determina versiones y detalles de servicios en puertos abiertos, proporciona información sobre posibles vulnerabilidades.

## 4. Escaneo de Sistema Operativo (-O)
   Comando: `nmap -O <objetivo>`
   Propósito: Intenta identificar el sistema operativo del objetivo basándose en patrones de respuesta.

## 5. Escaneo Agresivo (-A)
   Comando: `nmap -A <objetivo>`
   Propósito: Combina diversas técnicas, incluyendo detección de sistema operativo, detección de versiones, detección de scripts, proporcionando una visión integral.

## 6. Escaneo de Red Completa (-sn)
   Comando: `nmap -sn <objetivo/rango-de-red>`
   Propósito: Explora hosts activos en una red sin realizar un escaneo de puertos.

## 7. Escaneo de Puertos Específicos (-p)
   Comando: `nmap -p puerto,<objetivo>`
   Propósito: Escanea únicamente los puertos específicos 80 y 443 en el host con la dirección IP especificada.

## 8. Escaneo de Intensidad Moderada (-T3)
   Comando: `nmap -T3 <objetivo>`
   Propósito: Realiza un escaneo de intensidad moderada, ajustando la velocidad de escaneo para equilibrar velocidad e intrusión.

## 9. Escaneo de Intensidad Agresiva (-T4)
   Comando: `nmap -T4 <objetivo>`
   Propósito: Realiza un escaneo de intensidad agresiva, aumentando la velocidad de escaneo.

## 10. Escaneo de Intensidad Insana (-T5)
   Comando: `nmap -T5 <objetivo>`
   Propósito: Realiza un escaneo de intensidad máxima (insana), aumentando la velocidad al máximo, pero potencialmente más intrusivo.
```
