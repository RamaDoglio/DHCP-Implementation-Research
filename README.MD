# 🔧 DHCP Implementation Research

Este repositorio documenta mi investigación sobre diferentes formas de implementar el servicio DHCP (Dynamic Host Configuration Protocol) en una red con múltiples VLANs y sedes interconectadas mediante Frame Relay.


---

## 📌 Contenido del repositorio

| Parte | Tema |
| :--- | :--- |
| **Parte 1** | DHCP con servidor dedicado por red/VLAN (Server-PT) |
| **Parte 2** | DHCP directamente en routers de capa 3 |

---

## 🛠️ Tecnologías utilizadas

- Cisco Packet Tracer (versión 8.x)
- DHCP (Dynamic Host Configuration Protocol)
- VLANs (802.1Q)
- Frame Relay
- Protocolo RIP

---

## 🧠 Aprendizajes clave por parte

| Parte | Aprendizaje |
| :--- | :--- |
| **Parte 1** | El Server-PT tiene una particularidad: el pool por defecto (`serverPool`) funciona mejor que los pools creados manualmente para transmitir el Gateway. |
| **Parte 2** | Los nombres de los pools DHCP en el router deben ser únicos. Si se repiten, el router sobreescribe la configuración anterior sin avisar. |

---

## 📫 Contacto

- **Autor:** Doglio Ramiro Matías
- **Email:** matiasdoglio@gmail.com
- **LinkedIn:** https://www.linkedin.com/in/ramiro-mat%C3%ADas-doglio-325476305/

---

⭐ Si te resultó útil este repositorio, ¡no olvides darle una estrella!