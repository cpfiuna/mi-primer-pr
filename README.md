# Primeras Contribuciones

<img align="right" width="300" src="https://cpfiuna.github.io/recursos/Imagenes/Logos/cpf-logo.png" alt="cloná este repositorio" />

Antes de empezar a colaborar con nosotros es importante estar todos en la misma página, por eso este proyecto tiene como objetivo simplificar y guiar la forma en que los miembros hacen su primera contribución. Si estás buscando hacer tu primera contribución, seguí los pasos de abajo.

#### *Si no te sentís cómodo usando command line, [acá hay tutoriales usando herramientas GUI](#Tutoriales-con-otras-herramientas)*

Si no tenés git en tu computadora, [instalalo](https://docs.github.com/en/get-started/quickstart/set-up-git).

## Forkeá este repositorio

<img align="right" width="300" src="https://cpfiuna.github.io/recursos/mi-primer-pr/images/fork.png" alt="fork de este repositorio" />

Hacé fork de este repositorio haciendo click en el botón fork en la parte superior de esta página. Esto crea una copia de este repositorio en tu cuenta.

## Cloná el repositorio

<img align="right" width="300" src="https://cpfiuna.github.io/recursos/mi-primer-pr/images/clone.png" alt="cloná este repositorio" />

Ahora cloná el repositorio forkeado a tu máquina. Andá a tu cuenta de GitHub, abrí el repositorio forkeado, hacé click en el botón code, después en la pestaña SSH y luego hacé click en el ícono de *copiar url al portapapeles*.

Abrí una terminal y ejecutá el siguiente comando git:

```
git clone "url que acabás de copiar"
```
donde "url que acabás de copiar" (sin las comillas) es la url de este repositorio (tu fork de este proyecto). Mirá los pasos anteriores para obtener la url.

<img align="right" width="300" src="https://cpfiuna.github.io/recursos/mi-primer-pr/images/copy-to-clipboard.png" alt="copiar URL al portapapeles" />

Por ejemplo:

```
git clone git@github.com:este-sos-vos/mi-primer-pull-request.git
```
donde este-sos-vos es tu nombre de usuario de GitHub. Acá estás copiando el contenido del repositorio mi-primer-pull-request de GitHub a tu computadora.

## Creá una rama

Cambiá al directorio del repositorio en tu computadora (si ya no estás ahí):

```
cd mi-primer-pull-request
```
Ahora creá una rama usando el comando git switch:
```
git switch -c tu-nombre-de-nueva-rama
```

Por ejemplo:
```
git switch -c add-juan-perez
```

## Hacé los cambios necesarios y commiteá esos cambios

Ahora abrí el archivo `Contributors.md` en un editor de texto (el que quieras, podés usar VS Code también), agregá tu nombre. No lo agregues al principio o al final del archivo. Ponelo en cualquier lugar en el medio (Después del título y ántes del final). Ahora, guardá el archivo.

<img align="right" width="450" src="https://cpfiuna.github.io/recursos/mi-primer-pr/images/git-status.png" alt="git status" />

Si vas al directorio del proyecto y ejecutás el comando `git status`, vas a ver que hay cambios.

Agregá esos cambios a la rama que acabás de crear usando el comando `git add`:

```
git add Contributors.md
```

Ahora commiteá esos cambios usando el comando `git commit`:
```
git commit -m "Añadir a tu-nombre a la lista de contribuidores"
```
reemplazando tu-nombre con tu nombre.

Por ejemplo:
```
git commit -m "Añadir a Juan Pérez a la lista de contribuidores"
```

## Pusheá los cambios a GitHub

Pusheá tus cambios usando el comando `git push`:
```
git push -u origin nombre-de-tu-branch
```
Reemplazando tu-nombre-de-branch con el nombre de la branch que creaste anteriormente.

Por ejemplo:
```
git push -u origin add-juan-perez
```

## Enviá tus cambios para revisión

Si vas a tu repositorio en GitHub, vas a ver un botón `Compare & pull request`. Hacé click en ese botón.

<img style="float: right;" src="https://cpfiuna.github.io/recursos/mi-primer-pr/images/compare-and-pull.png" alt="crear un pull request" />

Ahora enviá el pull request.

<img style="float: right;" src="https://cpfiuna.github.io/recursos/mi-primer-pr/images/submit-pull-request.png" alt="enviar pull request" />

Pronto el bot de acciones estará mergeando todos tus cambios en la rama principal de este proyecto. Vas a recibir un email de notificación una vez que los cambios hayan sido mergeados.

## ¿Ahora qué?

<img align="right" width="200" src="https://cpfiuna.github.io/recursos/mi-primer-pr/cat_code.gif" alt="coding cat" />

¡Felicitaciones! Acabás de hacer tu primer pull request.

Completaste el flujo de trabajo estándar fork -> clone -> edit -> pull request que vas a encontrar seguido como contribuidor!

Si querés más práctica, chequeá las [contribuciones de código](https://github.com/cpfiuna/contribuciones-de-codigo).

## ¿Listo para contribuir?

Ahora sí, si querés empezar a contribuir con nuestros proyectos. Entrá a ver en qué estámos trabajando en [nuestros repos](https://github.com/orgs/cpfiuna/repositories).

### [Material adicional](../additional-material/git_workflow_scenarios/additional-material.md)

## Tutoriales con otras herramientas

| <a href="../gui-tool-tutorials/github-desktop-tutorial.md"><img alt="GitHub Desktop" src="https://desktop.github.com/images/desktop-icon.svg" width="100"></a> | <a href="../gui-tool-tutorials/github-windows-vs2017-tutorial.md"><img alt="Visual Studio 2017" src="https://upload.wikimedia.org/wikipedia/commons/c/cd/Visual_Studio_2017_Logo.svg" width="100"></a> | <a href="../gui-tool-tutorials/gitkraken-tutorial.md"><img alt="GitKraken" src="https://firstcontributions.github.io/assets/gui-tool-tutorials/gitkraken-tutorial/gk-icon.png" width="100"></a> | <a href="../gui-tool-tutorials/github-windows-vs-code-tutorial.md"><img alt="VS Code" src="https://upload.wikimedia.org/wikipedia/commons/1/1c/Visual_Studio_Code_1.35_icon.png" width=100></a> | <a href="../gui-tool-tutorials/sourcetree-macos-tutorial.md"><img alt="Sourcetree App" src="https://wac-cdn.atlassian.com/dam/jcr:81b15cde-be2e-4f4a-8af7-9436f4a1b431/Sourcetree-icon-blue.svg" width=100></a> | <a href="../gui-tool-tutorials/github-windows-intellij-tutorial.md"><img alt="IntelliJ IDEA" src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9c/IntelliJ_IDEA_Icon.svg/512px-IntelliJ_IDEA_Icon.svg.png" width=100></a> |
| --- | --- | --- | --- | --- | --- |
| [GitHub Desktop](../gui-tool-tutorials/github-desktop-tutorial.md) | [Visual Studio 2017](../gui-tool-tutorials/github-windows-vs2017-tutorial.md) | [GitKraken](../gui-tool-tutorials/gitkraken-tutorial.md) | [Visual Studio Code](../gui-tool-tutorials/github-windows-vs-code-tutorial.md) | [Atlassian Sourcetree](../gui-tool-tutorials/sourcetree-macos-tutorial.md) | [IntelliJ IDEA](../gui-tool-tutorials/github-windows-intellij-tutorial.md) |
