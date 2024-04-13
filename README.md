# Proxecto fin de ciclo

- [Proxecto fin de ciclo](#proxecto-fin-de-ciclo)
  - [Taboleiro do proyecto](#taboleiro-do-proyecto)
  - [Descrición](#descrición)
  - [Instalación / Posta en marcha](#instalación--posta-en-marcha)
  - [Uso](#uso)
  - [Sobre o autor](#sobre-o-autor)
  - [Licenza](#licenza)
  - [Índice](#índice)
  - [Guía de contribución](#guía-de-contribución)
  - [Links](#links)

> *EXPLICACIÓN*: Este documento será a "*páxina de aterrizaxe*" do teu proxecto. Será ou primeiro que vexan vos que se interesen por el. Cúida a sua redacción con todo ou mimo. Elimina posteriormente todas as lineas "EXPLICACIÓN*" cando creas finalizada a súa redacción.
> Podes acompañar á redacción deste ficheiro con imaxes ou gifs, pero non abuses deles.

## Taboleiro do proyecto

> *EXPLICACIÓN:* neste punto indica se o proyecto está en fase de desenrolo ou finalizado.
| Estado do Proyecto | Descrición |
| --- | --- |
| En desarrollo | O proyecto está actualmente en fase de desarrollo. |

## Descrición

> *EXPLICACIÓN*: Realiza unha breve descrición do proxecto. Non menos de 100 palabras e non máis de 300. Resalta o fundamental *coas túas propias palabras**. Utiliza unha linguaxe correcta, *pero natural**, que o entenda todo o mundo, mesmo e en especial, as persoas que non teñan un coñecemento técnico avanzado. Pode ser un estracto ou resumo de apartados que xa contemples noutros ficheiros.
> Descrición básica das ferramentas/tecnoloxías/linguaxes de programación,... empregados.

Este proxecto é unha páxina web de minixogos, un lugar onde os xogadores poden disfrutar de varios xogos e competir por as máximas puntuacións. Os usuarios poden rexistrarse para gardar as suas puntuacións e seguir o seu progreso. A idea é crear unha comunidade de xogadores que disfruten dos xogos e queiran mellorar as suas habilidades. A páxina web será deseñada para ser intuitiva e fácil de usar, para que calquera persoa, independentemente do seu coñecemento técnico, poida xogar e divertirse. As tecnoloxías utilizadas para o desenvolvemento deste proxecto incluirán HTML, CSS, JavaScript e un servidor backend para xestionar os datos dos usuarios e as puntuacións.

## Instalación / Posta en marcha

> *EXPLICACIÓN*: Neste apartado describe con toda precisión e a poder ser coa maior simplicidade/facilidade posible, como poñer en marcha a túa aplicación para probala (nun ambiente local). Valorarase moi positivamente que este proceso sexa o máis fácil posible, cunha simple instrución (p. e. un script de instalación, descarga e posta en marcha dun contedor,...).

Para poñer en marcha a aplicación, necesitarás ter instalado Docker e Docker Compose no teu sistema. Unha vez instalados, segue os seguintes pasos:

1. Clona o repositorio do proxecto no teu sistema local usando Git.
2. Navega ata o directorio do proxecto.
3. Executa o comando `docker-compose up` no terminal. Este comando construirá e iniciará os contenedores necesarios para a aplicación.

Os contenedores que se crearán son os seguintes:

- Un contenedor para a base de datos, que utilizará unha imaxe de MySQL.
- Un contenedor para o servidor web, que utilizará unha imaxe de Apache.
- Un contenedor para PHP, que utilizará unha imaxe de PHP.

Estes contenedores comunicaranse entre si para proporcionar un entorno de desenvolvemento completo para a aplicación.

Unha vez que os contenedores estean en marcha, podes acceder á aplicación web navegando ata `http://localhost` no teu navegador.
## Uso

> *EXPLICACIÓN*: É este apartado describe brevemente como se usará a aplicación Web do proxecto. Describe o uso da interface web *só o uso** (a modo de sumario) *dos aspectos máis relevantes do seu funcionamento** (máxima brevidade, coma se fose un anuncio reclamo ou comercial).

Para usar a aplicación, os usuarios deben navegar ata a páxina principal onde verán unha lista de xogos dispoñibles. Poden elixir un xogo para xogar e, unha vez que o xogo se carga, recibirán instrucións sobre como xogar. Se o usuario está rexistrado e iniciou sesión, as súas puntuacións serán gardadas e poderán ver as súas puntuacións máximas en cada xogo. Tamén poderán ver unha táboa de clasificación global para cada xogo, onde poderán competir coas puntuacións máximas doutros usuarios. Se o usuario non está rexistrado ou non iniciou sesión, aínda poderán xogar aos xogos, pero as súas puntuacións non serán gardadas.

## Sobre o autor

> *EXPLICACIÓN*: Realiza unha breve descrición de quen es (perfil profesional), os teus puntos fortes, ou tecnoloxías que máis dominas... a motivación do proxecto, tendo sobre todo en conta un nicho de mercado sen explotar.. *Non máis de 200 palabras**. Indica a forma fiable de contactar contigo durante o proceso de creación do proxecto.

Sobre min, son un desenvolvedor web apaixonado con fortes habilidades en JavaScript e PHP. Teño unha gran experiencia en desenvolvemento frontend e backend, creando solucións eficientes e escalables. A miña motivación para este proxecto vén da miña paixón polos xogos e a programación. Quero crear un espazo onde os xogadores poden competir e divertirse, ao mesmo tempo que melloran as súas habilidades. Creo que este proxecto pode encher un nicho de mercado para xogos web competitivos e accesibles. Durante o proceso de creación deste proxecto, podes contactar comigo a través do meu correo electrónico (eloypro12@gmail.com) ou a través do sistema de mensaxes de GitHub.
## Licenza

> *EXPLICACIÓN*: É requisito INDISPENSABLE o licenciar explicitamente o proxecto software. Recoméndase licenciar con GNU Free Documentation License Version 1.3*. Crear un ficheiro `LICENSE` na raiz do repo, co teu ficheiro de licenza. Lembra que se empregas unha licenza de software libre estás a autorizar a derivación da túa obra baixo a mesma licenza que elixas, podendo dar continuidade, p. e. outro alumno, para continuar o teu proxecto noutro curso.

Este proxecto está licenciado baixo a licenza Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0). Isto significa que podes compartir e adaptar o material para calquera propósito, sempre e cando:

- Des sexo crédito, proporcionando unha ligazón á licenza, e indicando se fixeches cambios. Podes facelo de calquera maneira razonable, pero non dunha maneira que sugira que o licenciante te respalda a ti ou ao teu uso.
- Non o utilices con fins comerciais.
- Se remezclas, transformas ou constrúes a partir do material, debes distribuír as túas contribucións baixo a mesma licenza que o orixinal.

Para máis información, consulta a [páxina da licenza CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.gl).

## Índice

> *EXPLICACIÓN*: Simplemente indexa ordenadamente todo o teu proxecto.

1. [Anteproyecto](doc/templates/1_Anteproxecto.md)
2. [Análise](doc/templates/2_Analise.md)
3. [Deseño](doc/templates/3_Deseño.md)
4. [Codificación e probas](doc/templates/4_Codificacion_e_probas.md)
5. [Implantación](doc/templates/5_Implantación.md)
6. [Referencias](doc/templates/6_Referencias.md)
7. [Incidencias](doc/templates/7_Incidencias.md)

## Guía de contribución

> EXPLICACIÓN*: Tratándose dun proxecto de software libre, é moi importante que expoñas como se pode contribuír co teu proxecto. Algúns exemplos disto son realizar novas funcionalidades, corrección e/o optimización do código, realización de tests automatizados, novas interfaces de integración, desenvolvemento de plugins etc. Se o máis conciso que poidas.

## Links

> EXPLICACIÓN*: Ligazóns externas e descipciones destas ligazóns que creas conveniente indicar aquí. Xeralmente xa van estar integrados coa túa documentación, pero se requires realizar unha listaxe deles, leste é o lugar.