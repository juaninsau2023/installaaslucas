<h1 align="center">AutoAtende SaaS</h1>

## ¿Vamos a instalar?

DESCARGANDO EL INSTALADOR E INICIANDO LA PRIMERA INSTALACIÓN (USAR SOLO PARA LA PRIMERA INSTALACIÓN):
```bash
sudo apt install -y git && git clone git@github.com:lucassaud/installaas.git install && sudo chmod -R 777 ./install && cd ./install && sudo ./install_primaria
```

ACCEDIENDO AL DIRECTORIO DEL INSTALADOR E INICIANDO INSTALACIONES ADICIONALES (USAR ESTE COMANDO PARA LA SEGUNDA O MÁS INSTALACIÓN):
```bash
cd && cd ./install && sudo ./install_instancia
```

## Para la instalación necesitará:
```bash
Una VPS con Ubuntu 20.04 (Configuración recomendada: 3 VCPU + 4 GB de RAM)
Subdominio para el Frontend
Subdominio para la API - backoffice
Correo electrónico válido para la certificación SSL
```
