## Oracle APEX:

Oracle APEX is a low-code web application development platform that runs inside the Oracle Database. It lets you build secure, scalable web apps quickly using mostly SQL and minimal coding.

### APEX is used for:
- Dashboards & reports (BI-style apps)
- Data entry / CRUD applications
- Enterprise internal systems (HR, ERP modules, etc.)
- Public-facing web apps
- REST API integration



---
---



## Oracle REST Data Services (ORDS):

Oracle REST Data Services (ORDS) is a free Java-based middleware that bridges HTTPS clients (browsers, mobile apps) and Oracle Database, acting as a REST API gateway.

It connects browsers (or apps) to the database and enables APEX, REST APIs, and SQL access over HTTP/HTTPS.


### What ORDS Does:

```
Client (Browser / App)
   ↓
ORDS (HTTP/HTTPS)
   ↓
Oracle Database (APEX / SQL / REST)
```


### Important ORDS Users:

| User                    | Purpose       |
| ----------------------- | ------------- |
| `APEX_PUBLIC_USER`      | APEX runtime  |
| `APEX_LISTENER`         | ORDS listener |
| `APEX_REST_PUBLIC_USER` | REST APIs     |


