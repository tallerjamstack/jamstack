# Taller Introducción a JAMstack
Este codigo es para el taller de la conferencia de CEUTEC. En este taller aprenderemos que es JAMstack y como podemos usarlo. 

# Parte 1: Crea un sitio utilizando la arquitectura JAMstack
- crea un archivo index.html 
- Usa npx serve para cargar el sitio durante el desarollo 
- crea un archivo estilos.css con reglas de estilo basicas
- crea un archivo mail.js que cargara repositorios de GitHub
- conecta todo en el archivo index.html

# Parte 2: Publica un sitio utilizando la arquitecture JAMstack
- Configura Netlify CLI `npm install netlify-cli -g`
- Crea un Repositorio en GitHub sin usar github CLI sigue las instrucciones https://docs.github.com/en/github/importing-your-projects-to-github/importing-source-code-to-github/adding-an-existing-project-to-github-using-the-command-line#adding-a-project-to-github-without-github-cli
- Crea un sitio en netlify conectado a tu github repositorio `netlify init`
- Haz un push a tu codigo `git add -A`, `git commit -m 'message'`, `git push --set-upstream origin master`
- Mira tu deploy en netlify 
- Ejecuta una modificación a tu codigo como un PR. 
  - checkout out a una nueva rama (branch) (`git checkout -b hola-mundo`)
  - haz la modificación (cambia el color de fondo)
  - agrega un commit a la modificación (`git commit -am 'feat: update background color'`)
  - haz push a tu modificación (`git push origin hola-mundo`)
  - abre el PR en github
- Mira la vista previa 
- Ejecuta el Merge del PR 
- Mira el sitio publicado
