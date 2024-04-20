# Requerimientos do sistema

- [Requerimientos do sistema](#requerimientos-do-sistema)
  - [1- Descrición Xeral](#1--descrición-xeral)
  - [2- Funcionalidades](#2--funcionalidades)
  - [3- Tipos de usuarios](#3--tipos-de-usuarios)
  - [4- Contorno operacional](#4--contorno-operacional)
  - [5- Normativa](#5--normativa)
  - [6- Melloras futuras](#6--melloras-futuras)

> *EXPLICACION*: Este documento describe os requirimentos para "nome do proxecto" especificando que funcionalidade ofrecerá e de que xeito.

## 1- Descrición Xeral

>*EXPLICACION*: Descrición Xeral do proxecto

O noso proxecto consiste na creación dunha plataforma web de minixogos (os minixogos serán propios da paxina). O propósito principal é proporcionar un espazo onde calquera persoa poida xogar a estes minixogos. Ademais, se os usuarios deciden rexistrarse, poderán competir polas puntuacións máis altas.

A aplicación está destinada a todo tipo de persoas que disfruten dos xogos en liña, independentemente da súa idade ou coñecementos técnicos. Pretendemos cubrir a necesidade de entretemento e competición en liña.

Actualmente existen varias plataformas que ofrecen xogos en liña, pero a nosa proposta é diferenciarse ofrecendo unha experiencia de usuario máis competitiva e social.

Vemos unha oportunidade de negocio no desenvolvemento desta aplicación, xa que poderíamos monetizala a través de publicidade ou mediante a venda de melloras ou vantaxes para os usuarios rexistrados.

En canto ás tecnoloxías, decidimos usar PHP para o backend e JavaScript para o frontend, xa que son linguaxes amplamente utilizadas e soportadas, e proporcionan todas as funcionalidades que necesitamos para o noso proxecto.

## 2- Funcionalidades

>*EXPLICACION* Describir que servizos ou operacións se van poder realizar por medio do noso proxecto, indicando que actores interveñen en cada caso.
>
> Enumeradas, de maneira que na fase de deseño poidamos definir o diagrama ou configuración correspondente a cada funcionalidade.
> Cada función ten uns datos de entrada e uns datos de saída. Entre os datos de entrada e de saída, realízase un proceso, que debe ser explicado.

| Acción   |  Descrición        |
|----------|--------------------|
| Presentación dos productos  | Mostra dos produtos (xogos) por medio da páxina web |
| Rexistro de usuarios | Permitir que os usuarios se rexistren na plataforma |
| Inicio de sesión | Permitir que os usuarios inicien sesión na plataforma |
| Xogar minixogos | Permitir que os usuarios xoguen os minixogos dispoñibles |
| Rexistro de puntuacións | Rexistrar as puntuacións dos usuarios nos minixogos |
| Clasificación de puntuacións | Mostrar unha clasificación das puntuacións máis altas |
| Compartir puntuacións en redes sociais | Permitir que os usuarios compartan as súas puntuacións en redes sociais |
| Xestión de perfil de usuario | Permitir que os usuarios modifiquen a súa información de perfil |
| Recuperación de contrasina | Permitir que os usuarios recuperen a súa contrasinal en caso de esquecemento |



## 3- Tipos de usuarios

> *EXPLICACION* Describir os tipos de usuario que poderán acceder ao noso sistema. Habitualmente os tipos de usuario veñen definidos polas funcionalidades ás cales teñen acceso. En termos xerais existen moitos grupos de usuarios: anónimos, novos, rexistrados, bloqueados, confirmados, verificados, administradores, etc.
>
> Exemplo:
>
> - Usuario xenérico, que terá acceso a ...
> - Usuario técnico, que poderá...

- Usuario anónimo: Tendrá acceso a presentación dos produtos e a xogar os minixogos, pero non poderá rexistrar puntuacións nin acceder a funcionalidades exclusivas para usuarios rexistrados.
- Usuario rexistrado: Poderá acceder a todas as funcionalidades do sistema, incluindo o registro das suas máximas puntuacións, a clasificación de puntuacións, compartir puntuacións en redes sociais e xestionar seu perfil de usuario.


## 4- Contorno operacional

> *EXPLICACION* Neste apartado deben describirse os recursos necesarios, dende o punto de vista do usuario, para poder operar coa aplicación web. Habitualmente consiste nun navegador web actualizado e unha conexión a internet.
Se é necesario algún hardware ou software adicional, deberá indicarse.

Para operar coa nosa aplicación web, os usuarios necesitarán:

- Un navegador web actualizado, como Google Chrome, Mozilla Firefox ou Microsoft Edge.
- Unha conexión a internet estable.

Non se require ningún hardware ou software adicional para utilizar a nosa aplicación.

## 5- Normativa

> *EXPLICACION* Investigarase que normativa vixente afecta ao desenvolvemento do proxecto e de que maneira. O proxecto debe adaptarse ás esixencias legais dos territorios onde vai operar.
> 
> Pola natureza dos sistema de información, unha lei que se vai a ter que mencionar de forma obrigatoria é la [Ley Orgánica 3/2018, de 5 de diciembre, de Protección de Datos Personales y garantía de los derechos digitales (LOPDPGDD)](https://www.boe.es/buscar/act.php?id=BOE-A-2018-16673). O ámbito da LOPDPGDD é nacional. Se a aplicación está pensada para operar a nivel europeo, tamén se debe facer referencia á [General Data Protection Regulation (GDPR)](https://eur-lex.europa.eu/eli/reg/2016/679/oj). Na documentación debe afirmarse que o proxecto cumpre coa normativa vixente.
>
> Para cumplir a LOPDPGDD e/ou GDPR debe ter un apartado na web onde se indique quen é a persoa responsable do tratamento dos datos e para que fins se van utilizar. Habitualmente esta información estructúrase nos seguintes apartados:
>
> - Aviso legal.
> - Política de privacidade.
> - Política de cookies.
>
> É acosenllable ver [exemplos de webs](https://www.spotify.com/es/legal/privacy-policy/) que conteñan textos legais referenciando a LOPDPGDD ou GDPR.

Para cumprir coa normativa vixente, o noso proxecto debe adaptarse á [Ley Orgánica 3/2018, de 5 de diciembre, de Protección de Datos Personales y garantía de los derechos digitales (LOPDPGDD)](https://www.boe.es/buscar/act.php?id=BOE-A-2018-16673) e, se aplicable, á [General Data Protection Regulation (GDPR)](https://eur-lex.europa.eu/eli/reg/2016/679/oj). Na nosa aplicación web, debemos incluír os seguintes apartados:

- Aviso legal: Debe incluír información sobre a identidade do responsable do tratamento dos datos e os fins para os que se van utilizar os datos persoais.
- Política de privacidade: Debe explicar como se recollen, almacenan e utilizan os datos persoais dos usuarios, así como os seus dereitos en relación coa protección de datos.
- Política de cookies: Debe informar sobre o uso de cookies na nosa aplicación e obter o consentimento dos usuarios para o seu uso.

## 6- Melloras futuras

> *EXPLICACION* É posible que o noso proxecto se centre en resolver un problema concreto que se poderá ampliar no futuro con novas funcionalidades, novas interfaces, etc.

- Ampliación de xogos: Engadir novos minixogos á plataforma para ofrecer máis variedade e entretemento aos usuarios.
- Integración de redes sociais: Permitir que os usuarios compartan as súas puntuacións directamente nas súas contas de redes sociais, como Facebook ou Twitter.
- Modo multixogador: Implementar a posibilidade de xogar en liña con outros usuarios en tempo real.
- Sistema de logros: Engadir un sistema de logros ou desafíos para motivar aos usuarios a xogar máis e alcanzar obxectivos específicos.
- Personalización de perfil: Permitir que os usuarios personalicen a aparencia do seu perfil, como a foto de perfil ou o tema de cores.
- Soporte para dispositivos móbiles: Adaptar a aplicación para que sexa compatible e teña unha boa experiencia de usuario en dispositivos móbiles, como smartphones e tablets.
- Integración de pagamentos: Permitir que os usuarios realicen pagamentos dentro da aplicación para adquirir melloras ou vantaxes.
- Localización: Traducir a aplicación a diferentes idiomas para alcanzar un público máis amplo.