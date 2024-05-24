# ¡Gracias por visitar el repositorio de Yugi Bot!

Aquí están los comandos que debes poner en Termux. Si te aparece algo, dale Y y presiona Enter comando por comando.

## Enlaces útiles:
- [YouTube](https://youtube.com/@eliasar_yt?si=rX57tbCTd1VDxdp-)
- [Grupo de WhatsApp](https://chat.whatsapp.com/C4LPn0cWKrx8Y7UgGZkneI)

Para cualquier duda o pregunta, no dudes en unirte al grupo de WhatsApp o visitar nuestro canal de YouTube.

## Instrucciones detalladas:

1. Configura el almacenamiento en Termux:
    ```sh
    termux-setup-storage
    ```

2. Actualiza e instala los paquetes necesarios:
    ```sh
    apt update && apt upgrade && pkg update && pkg upgrade && pkg install bash && pkg install libwebp && pkg install git -y && pkg install nodejs -y && pkg install ffmpeg -y && pkg install wget && pkg install imagemagick -y && pkg install yarn
    ```

3. Clona el repositorio del bot:
    ```sh
    git clone https://github.com/Eliasar54/-YUGI-BOT-MD-.git
    ```

4. Navega al directorio del bot:
    ```sh
    cd /data/data/com.termux/files/home/-YUGI-BOT-MD-
    ```

5. Descomprime los archivos zip si existen:
    ```sh
    for zip in *.zip; do unzip "$zip"; done
    ```

6. Instala las dependencias del proyecto:
    ```sh
    npm install
    ```

7. Inicia el bot:
    ```sh
    npm start
    ```
