Android Fecha
=====

## Desarrollo

```
// Obtenemos la fecha
DateFormat df = new SimpleDateFormat("dd-MM-yyyy,HH:mm");
String date = df.format(Calendar.getInstance().getTime());
```

#### Nota:

<p align="justify">
    En Android Studio hay que importar las librerias de Java directamente y no las que dicen Android. En mi caso así funcionó.
</p>

## Fuente

* <a href="https://stackoverflow.com/questions/26880063/how-to-get-current-date-and-time-in-android">How to get current date and time in Android?</a>