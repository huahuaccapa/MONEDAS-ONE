📊 Conversor de Monedas con API en Tiempo Real
Java
API
Licencia

Un conversor de monedas completo que obtiene tasas de cambio en tiempo real usando la API de ExchangeRate-API, implementado en Java con IntelliJ IDEA.

🌟 Características Principales
Conversiones en tiempo real para las principales monedas latinoamericanas

Interfaz intuitiva con menú de opciones

Caché inteligente de tasas de cambio (actualización cada hora)

Manejo robusto de errores y validaciones

Información completa sobre las tasas y su actualización

🛠 Tecnologías Utilizadas
Java 17+

Gson para el manejo de JSON

HTTP Client de Java para conexiones API

ExchangeRate-API como proveedor de datos

📋 Monedas Disponibles
Opción	Conversión	Códigos
1	Dólar → Peso argentino	USD→ARS
2	Peso argentino → Dólar	ARS→USD
3	Dólar → Real brasileño	USD→BRL
4	Real brasileño → Dólar	BRL→USD
5	Dólar → Peso colombiano	USD→COP
6	Peso colombiano → Dólar	COP→USD
🚀 Cómo Ejecutar el Proyecto
Clona el repositorio:
git clone https://github.com/tu-usuario/conversor-monedas.git
Abre el proyecto en IntelliJ IDEA

Configura la API Key:

Obtén tu API Key gratuita en ExchangeRate-API

Reemplaza 8260b64c969d1e1a7613b9b3 en la variable API_KEY

Ejecuta el programa:

Busca la clase ConversorMoneda

Haz clic derecho → "Run 'ConversorMoneda.main()'"
🎨 Vista Previa del Programa
********************************************
Sea bienvenido/a al Conversor de Moneda =]
********************************************

1) Dólar => Peso argentino
2) Peso argentino => Dólar
3) Dólar => Real brasileño
4) Real brasileño => Dólar
5) Dólar => Peso colombiano
6) Peso colombiano => Dólar
7) Actualizar tasas de cambio
8) Salir

Elija una opción válida:
********************************************
📌 Ejemplo de Uso
Selecciona una opción (1-6)

Ingresa la cantidad a convertir

Obtén el resultado inmediato:
100.00 USD = 82350.00 ARS
Tasas actualizadas: Fri, 27 Mar 2020 00:00:00 +0000
Próxima actualización: Sat, 28 Mar 2020 00:00:00 +0000
🛡 Manejo de Errores
El programa detecta y maneja:

Entradas inválidas

Problemas de conexión

Límites de la API alcanzados

API Keys incorrectas

Tasas de cambio no disponibles

📊 Estructura del Código
src/
└── main/
    └── java/
        └── ConversorMoneda.java  # Lógica principal
🤝 Contribuciones
¡Las contribuciones son bienvenidas! Por favor abre un issue o pull request para:

Añadir nuevas monedas

Mejorar la interfaz

Optimizar el código
