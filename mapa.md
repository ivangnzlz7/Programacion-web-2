```mermaid
   
graph TD
    A[Ecosistema Web] --> B[Usuarios]
    A --> C[Frontend]
    A --> D[Backend]
    A --> E[Infraestructura]
    A --> F[Seguridad]
    A --> G[DevOps]

    B --Navegador--> B1[chrome, Brave, Firefox]
    B --Dispositivos--> B2[Tablet, Celular, Computadora]
    B2 --> B1

    C --> C1[HTML/CSS/JS]
    C --Frameworks--> C2[React, Vue, Angular]

    D --Lenguajes--> D1[Python, Java, PHP, Node.js]
    D --Base de datos--> D2[MySql, MongoDB, Apache, Redis, Oracle, Firebase]
    D --APIs--> D3[REST, GraphQL]
    D --Frameworks--> D4[express, flask, django, laravel, spring boot]

    E --Servidores--> E1[Proxy, correo, DHCP, DNS, Aplicaciones, Comunicación, archivos, impresión o de base de datos]
    E --Nube--> E2[AWS, Azure, GCP]

    F --> F1[HTTPS/SSL]
    F --Autenticación--> F2[JSON Web Tokens, OAuth 2.0]
    F --> F3[OWASP]

    G --> G1[Git, Jenkis, Ansible, Docker, Chef, Kubernetes] 
    
```
