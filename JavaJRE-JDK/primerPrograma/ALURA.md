## JAVA - ALURA

### Conceptos

JVM - Java Virtual Machine
- Generar codigo en el lenguaje Java
- Generar un ejecutable, Bytecode (archivo.class de java)
- Compilar para que el pc lo entienda (JVM)
- Y enviar las instrucciones al sistema operativo

JVM Se encarga de:
- Administrar la memoria (Garbage collector)
- Hacerlo mulriplataforma (Diferentes S.O.)
- Seguridad
- Optimización constante del uso del procesador
- Librerias utilitarias que tiene

¿JDK?

*  JDK - Java Development Kit
    *  JRE - Java Runtime Enviroment
        *  JVM
        *  Librerias
    *  Tools

JRE Es el ambiente de ejecución.

JRE + Tools (herramientas del desarrollo) son el JDK

JRE = JVM + Librerías

No se puede descargar la JVM individualmente, siempre tendremos que descargar el JRE que tiene la JVM y el conjunto de librerías.

## ¿Cómo se ejecuta?

Primero se compila con:

```
javac NameClass.java
```

Luego se ejecuta con:

```
javac NameClass.class
```


