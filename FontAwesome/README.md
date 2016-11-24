## FontAwesome

1 Copiar [fontawesome-webfont.ttf](http://fontawesome.io/) en el assests.<br>
2 Copiar font.xml en values
3 Añadir el icono que queramos al objeto.
```java
 <Button 
     android:text="@string/icon_heart" />
 ```
 
4 Importar la fuente a la app.

```java
Typeface font = Typeface.createFromAsset( getAssets(), "fontawesome-webfont.ttf" );
```

5 Aplicar la fuente al elemento.

````java 
  *.setTypeface(font);
```

