# UD1 A1. Lenguajes de marcas

## 1. ¿Qué es un lenguaje de marcas?
Un **lenguaje de marcas** es básicamente un conjunto de reglas que usamos para organizar y describir información. Se basa en usar etiquetas o "tags" para indicar cómo debe verse o funcionar algo, ya sea en un navegador, una app o cualquier programa.

## 2. Características generales de los lenguajes de marcas
- **Uso de etiquetas**: Se usan etiquetas para decir dónde empieza y termina algo, como un párrafo o un título.
- **Estructura en árbol**: El contenido se organiza de manera jerárquica, como un árbol con ramas que contienen más cosas dentro.
- **Fácil de leer**: Aunque es para máquinas, los humanos también podemos entenderlo fácilmente con un poco de práctica.
- **Súper popular**: Estos lenguajes están por todos lados: en páginas web, calendarios, archivos de contactos, etc.
- **Funciona en cualquier lugar**: No importa si usas Windows, Mac o Linux, los lenguajes de marcas funcionan igual en todos.

## 3. Clasificación de los lenguajes de marcas

### Lenguajes de marcas más conocidos
1. **HTML (HyperText Markup Language)**: Lo que usamos para hacer páginas web.
2. **XML (Extensible Markup Language)**: Sirve para organizar y transportar datos.
3. **Markdown**: Un lenguaje súper simple para dar formato a texto, muy usado en GitHub y documentación.
4. **KML (Keyhole Markup Language)**: Para representar datos geográficos, como mapas.
5. **iCalendar**: Un formato que intercambia información de calendarios y eventos.
6. **vCard**: Para guardar y compartir datos de contacto.
7. **RSS (Really Simple Syndication)**: Sirve para suscribirse y recibir actualizaciones de blogs y noticias.

## 4. ¿Para qué se usan los lenguajes de marcas?

- **Web**: HTML es el estándar para crear páginas en internet.
- **Intercambio de datos**: XML se usa mucho para enviar y recibir datos entre programas.
- **Documentación**: Markdown se usa para escribir documentación técnica y hacerla fácil de leer.
- **Mapas**: KML se usa para mostrar mapas y datos geográficos.
- **Calendarios**: iCalendar sirve para compartir eventos entre diferentes apps de calendario.
- **Contactos**: vCard te deja guardar y compartir información de contacto.
- **Noticias**: RSS se usa para suscribirse a blogs o canales de noticias y recibir actualizaciones.

## 5. Ejemplos de código en diferentes lenguajes de marcas

### HTML

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi página web</title>
</head>
<body>
    <h1>¡Hola mundo!</h1>
    <p>Esto es un ejemplo básico de HTML.</p>
</body>
</html>
```
**Explicación**: HTML es el lenguaje que usamos para crear páginas web. Navegadores como Chrome, Firefox o Safari lo leen para mostrar el contenido.

### iCalendar

```
BEGIN:VCALENDAR
VERSION:2.0
BEGIN:VEVENT
SUMMARY:Ir al grado superior
DTSTART:20241002T090000Z
DTEND:20241002T100000Z
LOCATION:Fátima
DESCRIPTION:Atender a las clases
END:VEVENT
END:VCALENDAR
```
**Explicación**: iCalendar se usa para crear y compartir eventos de calendario. Apps como Google Calendar o Outlook pueden leer estos archivos y añadir los eventos.

### vCard
```
BEGIN:VCARD
VERSION:3.0
FN:Daniel Contreras
ORG:Mi Empresa
TEL;WORK;VOICE:(142) 4562-78950
EMAIL:daniel.contreras@example.com
END:VCARD
```
**Explicación**: vCard es un formato usado para compartir contactos. Se puede abrir en apps de contactos como las que tienes en tu teléfono o en Gmail.

### KML
```
<?xml version="1.0" encoding="UTF-8"?>
<kml xmlns="http://www.opengis.net/kml/2.2">
  <Placemark>
    <name>Mi lugar favorito</name>
    <description>Descripción del lugar</description>
    <Point>
      <coordinates>-122.0822035425683,37.42228990140251,0</coordinates>
    </Point>
  </Placemark>
</kml>
```
**Explicación**: KML es un formato que se usa para mostrar lugares en mapas, como en Google Earth o Google Maps.

### RSS
```
<?xml version="1.0" encoding="UTF-8" ?>
<rss version="2.0">
  <channel>
    <title>Mi Blog</title>
    <link>http://www.miblog.com</link>
    <description>Últimas noticias de mi blog</description>
    <item>
      <title>Nuevo artículo</title>
      <link>http://www.miblog.com/articulo1</link>
      <description>Este es un resumen del nuevo artículo.</description>
      <pubDate>Tue, 02 Oct 2024 14:00:00 +0000</pubDate>
    </item>
  </channel>
</rss>
```
**Explicación**: RSS es un formato para que te puedas suscribir a blogs o noticias. Lectores de RSS o apps como Feedly leen estos archivos y te muestran las actualizaciones.

