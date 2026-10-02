<p align="center">
  <img src="images/header.png?raw=true" alt="Logotipo de securus" weigh="420" height="420"/>
</p>

![internaluse-green](images/internal_use_-stable-green.svg)

---

## Motivación / [Rationale](README.md)
Planificar una [cuenta de respaldo](https://gitlab.com/users/IMHICIHU/projects) para los repositorios alojados en GitHub parece ser una tarea rutinaria.
Pero a veces esto no es lo habitual. Siguiendo ciertas reglas, un "plan B" resiliente en una época de [destrucción de datos](https://openai.com/index/hugging-face-model-evaluation-security-incident/) puede resultar eficaz.
En la medida de lo posible, se han guardado todos los metadatos junto con toda la documentación relacionada. Algunos repositorios [no son visibles](https://github.com/imhicihu/ArchWeb/blob/main/images/Screenshot_2026-07-17_at_2.20.37.png) por motivos de seguridad. 
Una declaración final: redundancia es una condición _sine qua non_

![Repositorios de GitLab](images/Screenshot_2026-08-14_at_12.47.34_PM.png)

> <https://gitlab.com/users/IMHICIHU/projects>

## [Cron](https://es.wikipedia.org/wiki/Cron_(Unix)) job

```
0 17 15 7 * /usr/bin/python3 /home/usuario/tarea.py
```
> “A las 17:00 horas el día 15 de julio, cada año”

### Plan

| Sitio | Repositorio GitHub | Copia de seguridad |
|:--|:--|:--|
| [Enlaces](https://enlacesimhicihu.vercel.app/) | &#10004; | &#10004; |
| [website](https://imhicihu.conicet.gov.ar/)| &#10004; | &#10004; |
| [Calendar](https://zoom-calendar.vercel.app/)| &#10004; | &#10004; |
| [biblio-searcher](https://biblio-searcher-v2.vercel.app/)| &#10004; | &#10004; |
| [TranscriptIO](https://hablante.surge.sh/)| &#10004; | &#10004; |
| [Temas Medievales](https://temasmedievales.imhicihu-conicet.gov.ar/index.php/TemasMedievales) | No | No |
| [Status page](https://imhicihu.statuspage.io/)| &#10004; | &#10004; |
| [DILA](https://imhicihu.gitbook.io/dila)| &#10004; | &#10004; |
| [Rescate digital](https://rescatedigital.vercel.app/)| &#10004; | &#10004; |
| [RegRex](https://reg-rex.vercel.app/)| &#10004; | &#10004; |
| [EditorCo-digo](https://editorco-digo.vercel.app/)| &#10004; | &#10004; |
| [Biblioteca](https://catalogo.imhicihu-conicet.gov.ar/) | No | No |

### Código de conducta

* Por favor, consulta nuestro [Código de conducta](código_de_conducta.md)

### Aspectos legales ###

* Todas las marcas registradas son propiedad de sus respectivos titulares

### Licencia ###

* El contenido de este proyecto no está sujeto a ninguna [licencia](https://github.com/imhicihu/securus/blob/main/LICENSE)
