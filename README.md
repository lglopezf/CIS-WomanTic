# CIS-WomanTic

## Tecnologías emergentes que abren camino

<p align="justify">
Impulsando la participación de adolescentes mujeres de los colegios de la ciudad de Loja en trayectorias formativas TIC.
</p>

<p align="justify">
Es un proyecto de vinculación con la sociedad de la carrera de Computación de la Universidad Nacional de Loja, que propone actividades para que las estudiantes exploren las tecnologias emergentes (inteligencia artificial, realidad aumentada y creación de prototipos guiados por IA) en escenarios prácticos.
</p>

## Instalar Quarto y TinyTeX

Descarga e instala Quarto para tu sistema operativo. [Descargar Quarto](https://quarto.org/docs/download/)

Abre una terminal y comprueba la instalación.

```bash
quarto --version
```

Instala TinyTeX para generar los PDF. [Documentación de Quarto para PDF](https://quarto.org/docs/output-formats/pdf-basics.html#prerequisites)

```bash
quarto install tinytex
```

## Clonar y abrir el proyecto

Clona el repositorio desde una terminal.

```bash
git clone https://github.com/lglopezf/CIS-WomanTic.git
```

En Visual Studio Code, selecciona **Archivo > Abrir carpeta** y abre la carpeta `CIS-WomanTic` que acabas de clonar.

## Generar la vista previa

En Visual Studio Code, selecciona **Terminal > Nueva terminal**. Desde la raíz del proyecto, donde está `_quarto.yml`, ejecuta este comando.

```bash
quarto preview --render all
```

Quarto muestra el sitio en HTML en el navegador. Los archivos generados se guardan en `doc/`. Cada guía configurada para PDF lo genera junto a su archivo HTML.
