# Practica3: WIFI y bluetooth en ESP32
## Objetivo
El objetivo de la practica es comprender como funcionan tanto el WIFI como el bluetooth en la ESP32, a partir de dos ejercicios:
1. Creación de un servidor web en ESP32
2. Comunicación Bluetooth con un móvil a través de puerto serie
## Apartado 1: Servidor web con ESP32 (Modo STA)
En este apartado queremos que la placa funcione como un servidor conectandose a WIFI y SSID. 
Los materiales usados han sido:
1. Placa ESP32
### Funcionamiento del código:
1. El ESP32 se conecta a una red WiFi utilizando un SSID y una contraseña.
2. Una vez conectado, obtiene una dirección IP dentro de la red.
3. Se inicia un servidor web en el puerto 80.
4. Al acceder a la dirección IP desde un navegador, el ESP32 responde con una página HTML sencilla.
5. La página se genera directamente en el código, pero se debe modificar para incluir un archivo HTML e

### Salidas:
En el puerto serie se muestra este mensaje:
Try Connecting to [SSID] ...... WiFi connected successfully Got IP: 192.168.X.X HTTP server started. Una vez nos conectamos al mismo WIFI y al IP nos carga la página Web:
![image](https://github.com/user-attachments/assets/aec9d82d-f639-41cc-8e39-892030f13606)
·Aqui modificada para que sea dinámica y con colores:
![image](https://github.com/user-attachments/assets/8bdea965-7aad-4f6d-9b3c-215ffd511013)


## Apartado 2: 


