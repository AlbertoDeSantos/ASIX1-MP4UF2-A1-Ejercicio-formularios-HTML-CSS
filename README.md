#### En un nuevo repositorio llamado `ASIX1-M4UF2-A1-forms` se han de generar (replicar) los siguientes formularios:

![Texto alternativo](https://github.com/AlbertoDeSantos/ASIX1-MP4UF2-A0.1-Ejercicio-formularios-HTML-CSS/blob/main/forms.png)

**Requerimientos:**

- Formulario para registrar mascotas:

  - el tercer campo `<select>` ha de contener las como mínimo 10 provincias `<option>`

- Formulario para registrar alumnos:

  - el campo *Estudios de procedencia* `<select>` ha de contener las opciones `<option>`: ESO, Bachillerato, CFGM, CFGS, Universidad, Master, Doctorado.

Utilizar los siguientes estilos (agregarlos a una hoja de estilos css):

```CSS
  input, select {
    width: 100%;
    padding: 12px 20px;
    margin: 8px 0;
    display: inline-block;
    border: 1px solid #ccc;
    border-radius: 4px;
    box-sizing: border-box;
  }

  input[type=submit] {
    width: 100%;
    background-color: #4CAF50;
    color: white;
    padding: 14px 20px;
    margin: 8px 0;
    border: none;
    border-radius: 4px;
    cursor: pointer;
  }

  input[type=submit]:hover {
    background-color: #45a049;
  }

  form {
    border-radius: 5px;
    background-color: #f2f2f2;
    padding: 20px;
  }
```

¿Qué hace la pseudo-clase `:hover`?

Finalmente, utiliza GitHub Pages para publicar el repositorio. Investiga como se puede utilizar la plataforma https://www.netlify.com/ para mostrar en la web el desarrollo. Una vez investigado, utiliza **netlify** para desplegar el desarrollo.

#### En un nuevo repositorio llamado `ASIX1-M4UF2-A1-login` se ha de generar (replicar) el siguiente formulario:

![Texto alternativo](https://github.com/AlbertoDeSantos/ASIX1-MP4UF2-A0.1-Ejercicio-formularios-HTML-CSS/blob/main/ex-login.png)

Los estilos del formulario son los mismos utilizados en el ejercicio anterior. Se ha de centrar el formulario, para ello se ha de utilizar la clase `flex` vista en clase: 
Mini-video [absolute/Flex/Grid]: https://drive.google.com/file/d/1WjFTJUQxLE4UZjj3nP__izwTN8Y2gAaR/view

Utiliza **netlify** para desplegar el desarrollo.
