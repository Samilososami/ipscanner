Un escaneador de ips en la misma red wifi basado en arp-scan para verificar si una Ip en concreto esta conectada. Lo he creado para uso propio y para aumentar mi velocidad de trabajo.

Instalacion y exportación al path:
```
git clone https://github.com/Samilososami/ipscanner.git
cd ipscanner
chmod +x scan
pip3 install colorama
python3 scan
```
para añadirlo al path:
```
mv scan /usr/bin
```
Configuración de la IP a encontrar:
```
# te diriges al directorio ipscanner
nano scan
# cambias la variable IP a la deseada, importante, entre dos comillas
IP = "10.10.10.100"
