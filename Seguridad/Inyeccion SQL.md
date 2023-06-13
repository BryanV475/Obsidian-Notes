Ataque que sucede cuando se nevían datos no fiables a un intérprete como parte de un comando o consulta, con la finalidad de tratar de ejecutar comandos no deseados y acceder a datos sin la autorización adecuada

## Comandos que pueden ser insertados

|                  |                  |
|---------------|---------------|
| Consultas | SQL |
| Comandos S.O | LDAP |
| Redirecciones HTTP | Redirecciones XML |

## Prevención

- Utilizar Prepared Statements
- Parametrización de consultas
- Sanitización de los parámetros a usarse en las consultas
- Utilizar configuración segura en el servidor, cuentas con los mínimos privilegios posibles