# Automatización de Emisión de Facturas ante la AFIP con Selenium

Este proyecto consiste en un script en Python diseñado para automatizar el proceso de emisión de facturas ante la Administración Federal de Ingresos Públicos (AFIP) de Argentina. La automatización se logra mediante la interacción programática con el sitio web de la AFIP utilizando la biblioteca Selenium, lo que permite agilizar y simplificar el proceso de emisión de facturas, ahorrando tiempo y reduciendo posibles errores manuales.

## Funcionalidades

- **Emisión de Facturas**: El script permite generar y enviar facturas directamente desde el sistema, utilizando los servicios provistos por la AFIP.
  
- **Datos de Facturación**: Los datos necesarios para la factura, se pueden escribir directamente en el archvio facturacion.xlsx el cual proporciona una plantilla predefinida para ingresar los datos que luego seran emitidos automaticamente.

## Requisitos

- **Python**: El script está escrito en Python y requiere tener instalado Python en el sistema.
  
- **Selenium WebDriver**: Se utiliza Selenium WebDriver para la automatización del navegador. Asegúrate de tener el WebDriver correspondiente a tu navegador instalado y configurado correctamente.

- **Credenciales de AFIP**: Se necesitan las credenciales de acceso al sitio web de la AFIP para poder iniciar sesión y utilizar los servicios de emisión de facturas.

## Uso

1. Clona este repositorio en tu máquina local:

    ```bash
    git clone https://github.com/francolautaro2/facturaElectronica.git
    ```

2. Instala las dependencias necesarias:

    ```bash
    pip install -r requirements.txt
    ```

3. Asegúrate de que las facturas estén en el formato del archivo XLSX para que el programa pueda leerlas automáticamente. 

4. Configura el script con tus credenciales de AFIP y otros datos necesarios.

5. Ejecuta el script:

    ```bash
    python main.py
    ```

6. Sigue las instrucciones que aparecerán en la consola para completar el proceso de emisión de la factura.

## Contribuciones

Las contribuciones son bienvenidas. Si encuentras algún problema o tienes alguna sugerencia de mejora, por favor, abre un issue en este repositorio o envía un pull request con tus cambios propuestos.

## Aclaraciones

No me hago responsable de su uso, esto fue creado con el objetivo de agilizar el proceso de emision de facturas ante el AFIP para ayudar a los contribuyentes.
