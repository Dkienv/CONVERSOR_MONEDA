# Conversor de Monedas

Este es un programa de consola desarrollado en Java que permite convertir montos de una moneda a otra utilizando los tipos de cambio actuales obtenidos de la API de ExchangeRate-API.

## 🛠️ Características

- Conversión rápida y precisa entre múltiples monedas.
- Obtención de tipos de cambio en tiempo real.
- Interfaz simple y fácil de usar.

## 📋 Requisitos previos

- **Java**: Asegúrate de tener instalada la versión 8 o superior de Java. Verifica tu versión de Java ejecutando:
    ```bash
    java -version
    ```
- **Conexión a Internet**: Es necesaria para acceder a los datos en tiempo real desde la API de ExchangeRate-API.

## 🚀 Instalación y Ejecución

Sigue los pasos a continuación para configurar y ejecutar el programa en tu máquina local:

1. **Clona este repositorio** en tu máquina local usando el siguiente comando:
    ```bash
    git clone https://github.com/usuario/repositorio.git
    ```
    Cambia `usuario/repositorio` por la URL del repositorio correspondiente.

2. **Navega al directorio del proyecto**:
    ```bash
    cd repositorio
    ```

3. **Compila el programa**:
    ```bash
    javac Main.java
    ```

4. **Ejecuta el programa**:
    ```bash
    java Main
    ```

5. **Realiza una conversión de moneda**:
    - Selecciona la moneda base y la moneda de destino de entre las opciones disponibles.
    - Introduce el monto que deseas convertir.
    - Visualiza el resultado de la conversión directamente en la consola.

## 📖 Cómo funciona

1. **Selección de monedas**:
   - El usuario introduce el código de la moneda base (por ejemplo, `USD` para dólares).
   - El usuario introduce el código de la moneda de destino (por ejemplo, `EUR` para euros).

2. **Obtención de tipos de cambio**:
   - El programa se conecta a la API de ExchangeRate-API para obtener el tipo de cambio actual.

3. **Cálculo de la conversión**:
   - El programa multiplica el monto introducido por el tipo de cambio y muestra el resultado.

4. **Resultados**:
   - Muestra el equivalente del monto en la moneda de destino.

## 🧪 Ejemplo de Uso

1. Ejecuta el programa.
2. Cuando se te solicite, ingresa el código de la moneda base (`USD`).
3. Ingresa el código de la moneda de destino (`EUR`).
4. Ingresa el monto a convertir (por ejemplo, `100`).
5. El programa mostrará un mensaje similar a:
    ```
    100 USD equivale a 92.50 EUR
    ```

## 👨‍💻 Contribuir

¡Contribuciones son bienvenidas! Sigue estos pasos para colaborar:

1. Realiza un fork del repositorio.
2. Crea una nueva rama para tu funcionalidad o corrección de errores:
    ```bash
    git checkout -b feature/nueva-caracteristica
    ```
3. Realiza los cambios necesarios y confirma los cambios:
    ```bash
    git commit -am "Agrega nueva característica"
    ```
4. Sube tus cambios a tu repositorio remoto:
    ```bash
    git push origin feature/nueva-caracteristica
    ```
5. Abre un Pull Request detallando tus cambios.

## 🔗 Recursos Adicionales

- [Documentación oficial de Java](https://docs.oracle.com/javase/8/docs/)
- [ExchangeRate-API](https://www.exchangerate-api.com/)

## 📜 Licencia

Este proyecto está licenciado bajo la licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.
