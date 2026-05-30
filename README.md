# Operación Escudo Pet Spa

Evaluación de vulnerabilidades, simulación de explotación, análisis de riesgos y propuesta de mitigaciones para el sistema **Pet Spa**.

## Alcance

El análisis se realizó exclusivamente sobre un **repositorio clonado en entorno local **.  
No se contó con acceso a un proyecto desplegado en producción, servidores reales, arquitectura distribuida, APIs funcionales ni bases de datos operativas.  
La revisión se limitó a la **superficie de ataque observable**: dominios, puertos, subdominios, formularios y componentes visibles en el código clonado.  

## Contenido

- Pruebas de lógica de negocio  
- Manipulación de sesiones  
- Integridad de datos  
- Inyección SQL (SQLi)  
- Cross‑Site Scripting (XSS)  
- Seguridad en carga de archivos  
- Auditoría y trazabilidad  
- Privacidad de datos sensibles  
- Validación de cifrado  
- Clasificación de vulnerabilidades  
- Mitigaciones y remediación  

## Áreas evaluadas

- Login y autenticación  
- Registro de usuarios  
- Recuperación de contraseñas  
- Panel administrativo  
- Gestión de empleados  
- Gestión de clientes  
- Roles y permisos  
- Logs de auditoría  
- Base de datos  

##  Metodologías utilizadas

- OWASP Top 10  
- OWASP Testing Guide  
- Análisis teórico de vulnerabilidades  
- Simulación ofensiva en entorno controlado  
- Evaluación de lógica de negocio  
- Revisión de controles de acceso  
- Análisis de superficie de ataque (dominios, puertos, subdominios)  

## Resultados

Se documentaron vulnerabilidades clasificadas en:  
- **Alto**  
- **Medio**  
- **Bajo**  

Incluyendo escenarios de:  
- Fuerza bruta  
- Credential Stuffing  
- Session Hijacking  
- SQL Injection  
- XSS  
- File Upload Attack  
- Escalación de privilegios  
- Manipulación de inventario  
- Alteración de registros de auditoría  

---

> ⚠️ **Nota:** Las pruebas se desarrollaron únicamente en entorno local mediante clonación de repositorio, sin acceso a APIs, servidores ni código en producción. Las conclusiones corresponden a simulaciones ofensivas técnicamente plausibles basadas en la superficie de ataque observable.
