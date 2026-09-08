<div align="center">

# 👨‍💻 ssskiarrr

### Trainee Support Engineer

<img
  src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&pause=1100&center=true&vCenter=true&width=720&lines=Linux+%E2%80%A2+SQL+%E2%80%A2+HTTP+%E2%80%A2+REST+API;Logs+%E2%80%A2+Monitoring+%E2%80%A2+Troubleshooting;Learning+Support+Engineering"
/>

<br><br>

![Status](https://img.shields.io/badge/STATUS-OPEN_TO_INTERNSHIP-238636?style=for-the-badge)
![Role](https://img.shields.io/badge/ROLE-SUPPORT_ENGINEER-111111?style=for-the-badge)
![Focus](https://img.shields.io/badge/FOCUS-WEB_SERVICES-111111?style=for-the-badge)

</div>

---

## `$ whoami`

Начинающий **Support Engineer**, развиваюсь в направлении поддержки и диагностики веб-сервисов.

Практикую работу с:

**Linux • SQL • Logs • HTTP • REST API • Networking • Monitoring**

При решении проблемы стараюсь идти по цепочке:

`симптом → проверка → логи → данные → метрики → локализация → решение / эскалация`

> 🎯 Сейчас ищу стажировку / Trainee-позицию в Support Engineering.

---

## ⚙️ Core Stack

<div align="center">

![Linux](https://img.shields.io/badge/Linux-CLI-111111?style=for-the-badge&logo=linux&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-SQLite-111111?style=for-the-badge&logo=sqlite&logoColor=white)
![Git](https://img.shields.io/badge/Git-111111?style=for-the-badge&logo=git&logoColor=white)

![HTTP](https://img.shields.io/badge/HTTP-REST_API-111111?style=for-the-badge)
![Logs](https://img.shields.io/badge/Logs-Analysis-111111?style=for-the-badge)
![Networking](https://img.shields.io/badge/TCP%2FIP-Networking-111111?style=for-the-badge)

![Prometheus](https://img.shields.io/badge/Prometheus-Monitoring-111111?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-Dashboards-111111?style=for-the-badge&logo=grafana&logoColor=white)
![Troubleshooting](https://img.shields.io/badge/Troubleshooting-Incidents-111111?style=for-the-badge)

</div>

---

## 🧩 Support Engineering

<table>
<tr>

<td width="33%" valign="top">

### 🔍 Troubleshooting

- Problem isolation
- Log analysis
- HTTP errors
- API diagnostics
- Network checks
- Root Cause Analysis
- Technical escalation

</td>

<td width="33%" valign="top">

### 🐧 Linux

- Linux CLI
- Processes
- Files & directories
- `grep`
- `curl`
- `journalctl`
- `ps`
- `top`
- `ss`
- `ip`

</td>

<td width="33%" valign="top">

### 🌐 Networking

- TCP/IP
- DNS
- DHCP
- NAT
- ARP
- IPv4 / IPv6
- Ports
- Client-server architecture

</td>

</tr>
</table>

---

## 🌐 HTTP & REST API

Понимаю базовую логику взаимодействия клиента и сервера и использую HTTP-коды при диагностике проблем.

| Code | Meaning |
|---|---|
| `200` | запрос выполнен успешно |
| `400` | некорректный запрос |
| `401` | проблема с аутентификацией |
| `403` | недостаточно прав |
| `404` | ресурс не найден |
| `429` | слишком много запросов |
| `500` | внутренняя ошибка сервера |
| `502` | ошибка upstream / gateway |
| `503` | сервис недоступен |
| `504` | timeout upstream |

---

## 🗄️ SQL & Data

Работаю с **SQLite** и использую SQL для анализа и проверки данных.

```sql
select
    customer_id,
    count(*) as operations_count
from operations
group by customer_id
having count(*) > 5;
