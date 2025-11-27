<div align="center">

---

<!-- Tabla con Fotos con el texto de las diferentes partes fisicas del M5Stick -->

<table>
  
<!-- Cabezera de la tabla -->
<tr>
  <td colspan="2" style="text-align: center; padding: 0; margin: 0;">
    <h1 style="margin: 5px 0 0 0;"> ⚙️ M5StickC-Plus2 ⚙️</h1>
    <h2> Este dispositivo compacto integra un ESP32-PICO-V3-02 con módulos básicos de WIFI, Bluetooth, IR, RF, RFID, NRF24, FM y Scripts Ejecutables</h2>
    <div style="display: inline-block; margin: 0; padding: 0;">
      <img 
        src="https://github.com/user-attachments/assets/0ed07dd0-3e60-4009-a55c-9aa83ca68854"
        width="500"
        style="border-radius: 10px; margin: 0; padding: 0; display: block;"
      />
      <div style="margin: 0; padding: 0; line-height: 1;">
         <h2 style="margin: 5px 0 0 0;">  🡻🢃Hardware del M5StickC Plus2🢃🡻</h2>
      </div>
    </div>

  </td>
</tr>
  

  <!-- FILA 1 -->
  <tr>
    <td>
      <img 
        src="https://github.com/user-attachments/assets/97862fe6-a9d0-4725-b9fe-d3d0144f1149"
        width="440"
        style="border-radius: 20px;"
      />
    </td>
    <td style="padding-left: 20px;">
      <h3>🖲️Frontal del M5Stick🖲️</h3>
      En su frontal, cuenta con la pantalla LCD de 1.14 pulgadas donde correrá el entorno visual del firmware que instalemos, debajo,  el botón M5 (BtnA), botón para simplemente moverte por el sistema, su función es (Aceptar, Siguiente).
    </td>
  </tr>

  <!-- FILA 2 -->
  <tr>
    <td>
      <img 
        src="https://github.com/user-attachments/assets/e9c1bbb9-3954-4955-ba58-45c39d393342"
        width="440"
        style="border-radius: 20px;"
      />
    </td>
    <td style="padding-left: 20px;">
      <h3>🎫Dorsal del M5Stick🎫</h3>
      En la parte trasera, cuenta con la etiqueta que nos indica varios de los módulos que integra, aparte de un imán debajo de la pegatina, para fijar el M5Stick a cualquier superficie metalica, a parte, orificios del zumbador (altavoz de pitidos) , y el sensor IMU (Giroscopio).
    </td>
  </tr>
  
  <!-- FILA 3 -->
  <tr>
    <td>
      <img 
        src="https://github.com/user-attachments/assets/e4f70780-ebd5-462d-8b16-6c1d73df8bdb"
        width="440"
        style="border-radius: 20px;"
      />
    </td>
    <td style="padding-left: 20px;">
      <h3>⬇️Parte inferior del M5StickC⬇️</h3>
      Incluye un puerto de carga y transferencia de datos USB Tipo C, y cuatro pines para conectar los modulos éxtras ( GND, 5V OUT, G32 y G33 ).
    </td>
  </tr>

  <!-- FILA 4 -->
  <tr>
    <td>
      <img 
        src="https://github.com/user-attachments/assets/7ea70924-9b95-4222-8fd5-c99684f58df0"
        width="440"
        style="border-radius: 20px;"
      />
    </td>
    <td style="padding-left: 20px;">
      <h3>⬇️Parte superior del M5StickC⬇️</h3>
      Incluye entrada de 8 pines para conectar los modulos éxtras ( GND, 5V OUT, G26, G36/G25, G0, BAT, 3V3 ,5V IN ) y orificios para los sensores internos.
    </td>
  </tr>

    <!-- FILA 5 -->
  <tr>
    <td>
      <img 
        src="https://github.com/user-attachments/assets/cd70c47d-e1fd-456e-b789-02244e1de3d5"
        width="440"
        style="border-radius: 20px;"
      />
    </td>
    <td style="padding-left: 20px;">
      <h3>👉Lateral (R) del M5StickC👉</h3>
      Incluye el botón (BtnB) el cual es utilizado para movernos por el sistema.
    </td>
  </tr>

</table>




<!-- SOFTWARE BASE DE M5STICK -->

## 🔌 FIRMWARE QUE VIENE DE SERIE EN EL M5STICKC PLUS2 🔌
Nuestra pequeña herramienta viene ya con un firmware pre-instalado de fábrica, el cual es un firmware demo (no pensado como firmware final) se instala para la demostración y para que el aparato tenga algo instalado, que luego le cambiaremos (más adelante en este mismo repositorio lo mencionaré).
Éste firmware tiene opciones básicas, como:
- 🧭 **Giroscopio** (Comprueba la calibración del M5.)
  
- 🌈 **Color** (Demostración y calibración de la paleta de colores que utiliza el sistema.)
   
- 🌐 **Wifi Scan** (Un simple sniffer de wifi que escanea los APs e información al rededor.)
  
- 🕓 **Clock** (Simple reloj digital.)
  
- 🎮 **IR Send** (Modulo Infrarojos que manda pulsos en el canal que elijas.)

- 🗣 **Detector de sonido** (Modulo detector de sonido por el microfono incorporado.)

- ᛒ **Modulo Bluetooth** (Modulo bluetooth el cual muestra si tenemos el Bluetooth activo o no, e información de nuestro dispositivo.)
  


<!-- SOFTWARE M5BURNER PARA FLASHEAR M5 -->

## 👨‍💻 SOFTWARE M5BURNER PARA FLASHEAR LOS DISPOSITIVOS M5STICKC 👨‍💻

Para instalarle otros Firmwares de la comunidad a nuestro dispositivo M5StickC Plus 2 necesitamos el programa M5Burner, que la misma empresa M5 nos lo facilita en su pagina web:

<!-- BOTÓN DE DESCARGA QUE LLEVA A LA URL DEL M5BURNER -->
<a href="https://docs.m5stack.com/en/uiflow/m5burner/intro"> <img src="https://img.shields.io/badge/Download-Now-green?style=for-the-badge"> </a>

<p align="center">
  <a href="https://docs.m5stack.com/en/uiflow/m5burner/intro" target="_blank">
    <img
      src="https://img.shields.io/badge/View-Documentation-blue?style=for-the-badge"
      height="60"
    >
  </a>
</p>

<p align="center">
  <a href="https://docs.m5stack.com/en/uiflow/m5burner/intro" target="_blank">
    <img
      src="https://img.shields.io/badge/🔗%20Go%20to-Documentation-0A7AFF?style=for-the-badge"
      height="60"
    >
  </a>
</p>

<p align="center">
  <a href="https://docs.m5stack.com/en/uiflow/m5burner/intro" target="_blank">
    <img
      src="https://img.shields.io/badge/Documentation-Open-informational?style=for-the-badge"
      height="55"
    >
  </a>
</p>

<p align="center">
  <a href="https://docs.m5stack.com/en/uiflow/m5burner/intro" target="_blank">
    <img
      src="https://img.shields.io/badge/M5Stack-Docs-black?style=for-the-badge&logo=github"
      height="60"
    >
  </a>
</p>



- 📡 **NRF24** (comunicación inalámbrica)  


<!-- MODULOS EXTRAS ¿¿DEJAR PARA OTRO REPOSITORIO?? -->

## 🔌 Módulos que elevan su potencial

Si además le añades módulos externos como:

- 📡 **NRF24** (comunicación inalámbrica)  
- 📶 **IR** (control y lectura infrarroja)  
- 🟦 **RFID** (lectura de tarjetas)  

…el dispositivo se vuelve aún más versátil.  
Pronto comentaré cada uno de ellos en detalle.

<!-- SOFTWARE BRUCE ¿¿DEJAR PARA OTRO REPOSITORIO?? -->

##✨ **Software Bruce para M5StickC Plus2** ✨

> 🔸Después de estar probando el software de **Bruce** en sus últimas versiones para el **M5StickC Plus2**, puedo decir que es un **divertido e interactivo software bien refinado y bastante completo**.
(IMAGEN DE INICIO DE BRUCE)


Aún mas si le añades los respectivos módulos como la antena **NRF24, IR, RFID**, los cuales iré comentando a continuación.

</div>















---
