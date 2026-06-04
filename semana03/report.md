# Reporte de Analisis de Logs

**Archivo analizado:** sample.log
**Fecha del analisis:** 2026-06-04 02:47:36
**Total de entradas:** 500

---

## 1. Top 10 Direcciones IP

| Solicitudes | Direccion IP |
|-------------|--------------|
| 184 | 192.168.1.10 |
| 120 | 10.0.0.5 |
| 58 | 10.0.0.99 |
| 51 | 192.168.1.25 |
| 46 | 203.0.113.42 |
| 41 | 172.16.0.3 |

## 2. Distribucion por Severidad

| Nivel | Cantidad |
|-------|----------|
| FATAL | 81 |
| ERROR | 88 |
| WARNING | 68 |
| INFO | 263 |

## 3. Eventos por Hora

| Hora | Eventos |
|------|---------|
| 00:00 | 20 |
| 01:00 | 26 |
| 02:00 | 19 |
| 03:00 | 15 |
| 04:00 | 22 |
| 05:00 | 17 |
| 06:00 | 13 |
| 07:00 | 25 |
| 08:00 | 19 |
| 09:00 | 20 |
| 10:00 | 29 |
| 11:00 | 25 |
| 12:00 | 23 |
| 13:00 | 17 |
| 14:00 | 25 |
| 15:00 | 24 |
| 16:00 | 22 |
| 17:00 | 10 |
| 18:00 | 21 |
| 19:00 | 19 |
| 20:00 | 20 |
| 21:00 | 28 |
| 22:00 | 24 |
| 23:00 | 17 |

## 4. Top 5 Mensajes de Error

| Frecuencia | Mensaje |
|------------|---------|
| 68 | Connectiontimeoutafter30s |
| 37 | Authenticationfailedforuseradmin |
| 23 | OutofmemoryerrorinmoduleX |
| 21 | Failedtowritetodisk |
| 20 | Databaseconnectionrefused |

## 5. Resumen

- Sistema analizado con 500 eventos registrados
- 169 eventos requieren atencion (ERROR y FATAL)
- Analisis completado con herramientas UNIX estandar
