![verdaccio logo](images/verdaccio.png)

---

[Verdaccio](https://verdaccio.org/) es un registro npm privado local simple que no requiere configuración . ¡No es necesario tener una base de datos completa solo para comenzar! Verdaccio viene listo para usar con su propia base de datos diminuta y la capacidad de usar proxy para otros registros (p. ej., npmjs.org), almacenando en caché los módulos descargados en el camino. Para aquellos que buscan ampliar sus capacidades de almacenamiento, Verdaccio admite varios complementos creados por la comunidad para conectarse a servicios como s3 de Amazon, Google Cloud Storage o crear su propio complemento.

[![verdaccio (latest)](https://img.shields.io/npm/v/verdaccio/latest.svg)](https://www.npmjs.com/package/verdaccio)
[![verdaccio (downloads)](https://img.shields.io/npm/dy/verdaccio.svg)](https://www.npmjs.com/package/verdaccio)
[![docker pulls](https://img.shields.io/docker/pulls/verdaccio/verdaccio.svg?maxAge=43200)](https://verdaccio.org/docs/en/docker.html)
[![backers](https://opencollective.com/verdaccio/tiers/backer/badge.svg?label=Backer&color=brightgreen)](https://opencollective.com/verdaccio)
[![stackshare](https://img.shields.io/badge/Follow%20on-StackShare-blue.svg?logo=stackshare&style=flat)](https://stackshare.io/verdaccio)

[![discord](https://img.shields.io/discord/388674437219745793.svg)](http://chat.verdaccio.org/)
[![MIT](https://img.shields.io/github/license/mashape/apistatus.svg)](https://github.com/verdaccio/verdaccio/blob/master/LICENSE)
[![Crowdin](https://d322cqt584bo4o.cloudfront.net/verdaccio/localized.svg)](https://crowdin.com/project/verdaccio)

[![Twitter followers](https://img.shields.io/twitter/follow/verdaccio_npm.svg?style=social&label=Follow)](https://twitter.com/verdaccio_npm)
[![Github](https://img.shields.io/github/stars/verdaccio/verdaccio.svg?style=social&label=Stars)](https://github.com/verdaccio/verdaccio/stargazers)
[![StandWithUkraine](https://raw.githubusercontent.com/vshymanskyy/StandWithUkraine/main/badges/StandWithUkraine.svg)](https://github.com/vshymanskyy/StandWithUkraine/blob/main/docs/README.md)

---

<br/><br/>

## ¿Qué hace Verdaccio por mí?

### Usar paquetes privados

Si desea utilizar todos los beneficios del sistema de paquetes npm en su empresa sin enviar todo el código al público, y utilice sus paquetes privados con la misma facilidad que los públicos.

### Registro de caché npmjs.org

Si tiene más de un servidor en el que desea instalar paquetes, es posible que desee usarlo para disminuir la latencia (presumiblemente, npmjs.org "lento" se conectará solo una vez por paquete/versión) y proporcionar una conmutación por error limitada (si npmjs. org está inactivo, aún podemos encontrar algo útil en el caché) o evitar problemas como Cómo un desarrollador rompió Node, Babel y miles de proyectos en 11 líneas de JavaScript , Muchos paquetes desaparecieron repentinamente o el Registro devuelve 404 para un paquete que he instalado antes \_

### Vincular varios registros

Si utiliza varios registros en su organización y necesita obtener paquetes de varias fuentes en un solo proyecto, puede aprovechar la función de enlaces ascendentes con Verdaccio, encadenando varios registros y obteniendo desde un único punto final.

### Anular paquetes públicos

Si desea utilizar una versión modificada de algún paquete de terceros (por ejemplo, encontró un error, pero el mantenedor aún no aceptó la solicitud de extracción), puede publicar su versión localmente con el mismo nombre. Ver en detalle [aquí](https://verdaccio.org/docs/en/best#override-public-packages).

### Pruebas E2E

Verdaccio ha demostrado ser un registro liviano que se puede iniciar en un par de segundos, lo suficientemente rápido para cualquier CI. Muchos proyectos de código abierto usan verdaccio para pruebas de extremo a extremo, por mencionar algunos ejemplos, create-react-app , mozilla neutrino , pnpm , storybook , babel.js , angular-cli o docusaurus . Puedes leer más [aquí](https://verdaccio.org/docs/e2e).

Además, aquí algunos ejemplos de cómo empezar:

- [e2e-ci-example-gh-actions](https://github.com/juanpicado/e2e-ci-example-gh-actions)
- [verdaccio-end-to-end-tests](https://github.com/juanpicado/verdaccio-end-to-end-tests)
- [verdaccio-fork](https://github.com/juanpicado/verdaccio-fork)

---

<br/><br/>

## Maintainers

| [Juan Picado](https://github.com/juanpicado)                                   | [Ayush Sharma](https://github.com/ayusharma)                             | [Sergio Hg](https://github.com/sergiohgz)                                 |
| ------------------------------------------------------------------------------ | ------------------------------------------------------------------------ | ------------------------------------------------------------------------- |
| ![jotadeveloper](https://avatars3.githubusercontent.com/u/558752?s=120&v=4)    | ![ayusharma](https://avatars2.githubusercontent.com/u/6918450?s=120&v=4) | ![sergiohgz](https://avatars2.githubusercontent.com/u/14012309?s=120&v=4) |
| [@jotadeveloper](https://twitter.com/jotadeveloper)                            | [@ayusharma\_](https://twitter.com/ayusharma_)                           | [@sergiohgz](https://twitter.com/sergiohgz)                               |
| [Priscila Oliveria](https://github.com/priscilawebdev)                         | [Daniel Ruf](https://github.com/DanielRuf)                               |
| ![priscilawebdev](https://avatars2.githubusercontent.com/u/29228205?s=120&v=4) | ![DanielRuf](https://avatars3.githubusercontent.com/u/827205?s=120&v=4)  |
| [@priscilawebdev](https://twitter.com/priscilawebdev)                          | [@DanielRufde](https://twitter.com/DanielRufde)                          |

Puede encontrarlos y chatear con ellos a través de Discord, haga click [aquí](http://chat.verdaccio.org) o sígalos en Twitter _Twitter_.

---

<br/><br/>

### License

Verdaccio tiene [MIT licensed](https://github.com/verdaccio/verdaccio/blob/master/LICENSE)

La documentación y los logotipos de Verdaccio (excluyendo /thanks, p. ej., .md, .png, .sketch) archivos dentro de la carpeta /assets) tienen
[Creative Commons licensed](https://creativecommons.org/licenses/by/4.0/).
