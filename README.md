# Instalador del controlador UNIFI
By Glenn Rietveld

Ejemplo script instalación 9.3.54:
```bash
bash <(curl -fsSL https://get.glennr.nl/unifi/install/unifi-9.3.45.sh)
```
Lista de versiones:
> https://glennr.nl/s/unifi-network-controller

# Instalador por Git

1. Instala git si aún no está instalado
```bash 
apt update && apt install -y git
```
2. Clona el repo
```bash 
git clone https://github.com/villagoservices/install-unifi-controller-linux.git
```
3. Entra a la carpeta
```bash 
cd install-unifi-controller-linux
```
5. Da permisos de ejecución al script
```bash
chmod +x unifi-9.3.45.sh
```
6. Ejecuta el script
```bash
./unifi-9.3.45.sh
```

## 🙌 ¿Te fue útil este proyecto? ¡Apóyalo con una donación!
Recuerda dejar un mensaje especificando UNIFI GR para dar la mayoría de aportes a  Glenn Rietveld

Si este script te ahorró tiempo, dolores de cabeza o simplemente te pareció genial, considera apoyar su desarrollo:

☕ **Invítame un café:**

[![Buy Me a Coffee](https://img.shields.io/badge/-Invítame_un_café-ff813f?style=for-the-badge&logo=buy-me-a-coffee&logoColor=white)](https://coff.ee/villago)

💸 **O haz una donación directa por PayPal:**

[![Donate](https://img.shields.io/badge/Donar-PayPal-0070ba?style=for-the-badge&logo=paypal&logoColor=white)](https://www.paypal.com/ncp/payment/K3748XUX2BM5Y)

---
> Tu aporte ayuda a mantener y mejorar este y muchos otros proyectos, ¡gracias por tu apoyo!
