---
title: Password Gen Live, una herramienta para generar contraseñas y frases seguras 
excerpt: >-
  
date: '2022-07-21'
seo:
  title: Password Gen Live, una herramienta para generar contraseñas y frases seguras
  description: >-
    Password Gen Live, una herramienta para generar contraseñas y frases seguras
  extra:
    - name: 'og:type'
      value: article
      keyName: property
    - name: 'og:title'
      value: Password Gen Live, una herramienta para generar contraseñas y frases seguras
      keyName: property
    - name: 'og:description'
      value: >-
        Password Gen Live, una herramienta para generar contraseñas y frases seguras
layout: post
---

Es una aplicación web que realice con JavaScript (react), no utilize bases de datos, la web esta hosteada en Netlify y las contraseñas se generan en el navegador mediante una API OpenSource de Mozilla [Crypto.getRandomValues](https://developer.mozilla.org/en-US/docs/Web/API/Crypto/getRandomValues), además las contraseñas generadas no se trasmiten del navegador bajo ningún concepto. 

Ofrece una serie de criterios que el usuario puede tomar como base para crear una contraseña segura, entre estos símbolos, letras mayúsculas y minúsculas, números y la longitud máxima deseada, de acuerdo al gusto del usuario, lo recomendado es generar una contraseña de más de 12 caracteres, y no reutilizar las mismas para cada servicio. 

Adicionalmente, recomiendo guardar las contraseñas en un gestor como [Bitwarden](https://bitwarden.com).

La web es [passwordgen.live](https://passwordgen.live), el código es Open Source y se puede obtener desde el siguiente [repositorio](https://github.com/chelol/passwordgen).







