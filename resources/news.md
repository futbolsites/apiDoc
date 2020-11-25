

### GET /news/latest

| Parameter | Explanation       |
|-----------|-------------------|
| size      | Amount of results |
| page      | Page to show      |

`HTTP/1.1 200 OK`

```json
{
  "data": {
    "items": [
      {
        "title": "Los cinco equipos candidatos para firmar al ‘robo’ de la agencia libre",
        "images": {
          "wide": {
            "big": "https://bolavip.com/__export/1606256055613/sites/bolavip/img/2020/11/24/blake_snell_pitcher_de_los_rays.jpg_1546398727.jpg",
            "medium": "https://bolavip.com/__export/1606256055613/sites/bolavip/img/2020/11/24/blake_snell_pitcher_de_los_rays.jpg_1624932088.jpg",
            "small": "https://bolavip.com/__export/1606256055613/sites/bolavip/img/2020/11/24/blake_snell_pitcher_de_los_rays.jpg_1762501607.jpg"
          },
          "classic": {
            "big": "https://bolavip.com/__export/1606256055613/sites/bolavip/img/2020/11/24/blake_snell_pitcher_de_los_rays.jpg_412320734.jpg",
            "medium": "https://bolavip.com/__export/1606256055613/sites/bolavip/img/2020/11/24/blake_snell_pitcher_de_los_rays.jpg_1055622710.jpg",
            "small": "https://bolavip.com/__export/1606256055613/sites/bolavip/img/2020/11/24/blake_snell_pitcher_de_los_rays.jpg_1592070664.jpg"
          },
          "square": {
            "big": "https://bolavip.com/__export/1606256055613/sites/bolavip/img/2020/11/24/blake_snell_pitcher_de_los_rays.jpg_1159711837.jpg",
            "medium": "https://bolavip.com/__export/1606256055613/sites/bolavip/img/2020/11/24/blake_snell_pitcher_de_los_rays.jpg_1216690859.jpg",
            "small": "https://bolavip.com/__export/1606256055613/sites/bolavip/img/2020/11/24/blake_snell_pitcher_de_los_rays.jpg_1890075089.jpg"
          },
          "full": "https://bolavip.com/__export/1606256055613/sites/bolavip/img/2020/11/24/blake_snell_pitcher_de_los_rays.jpg_1902800913.jpg"
        },
        "epigraph": "Blake Snell, pitcher de los Rays",
        "url": "https://bolavip.com/america/MLB-Blake-Snell-los-equipos-quieren-firmar-al-lanzador-de-Tampa-Bay-Rays-20201124-0148.html",
        "label": "MLB",
        "excerpt": "<p><strong>Toda una sorpresa fue el anuncio de los Tampa Bay Rays cuando informaron que est&aacute;n dispuestos a intercambiar al pitcher estelar Blake Snell.</strong></p>",
        "section": "América",
        "link": "/america/MLB-Blake-Snell-los-equipos-quieren-firmar-al-lanzador-de-Tampa-Bay-Rays-20201124-0148.html",
        "local_path": "/contenidos/2020/11/24/noticia_0148.html",
        "published_at": "2020-11-24T19:23:25-0300",
        "modified_at": "2020-11-24T19:23:32-0300"
      }
    ]
  }
}
```

### GET /news/tag/{tag}

| Parameter | Explanation       |
|-----------|-------------------|
| size      | Amount of results |
| page      | Page to show      |

`HTTP/1.1 200 OK`

```json
{
  "data": {
    "items": [
      {
        "title": "Los cinco equipos candidatos para firmar al ‘robo’ de la agencia libre",
        "images": {
          "wide": {
            "big": "https://bolavip.com/__export/1606256055613/sites/bolavip/img/2020/11/24/blake_snell_pitcher_de_los_rays.jpg_1546398727.jpg",
            "medium": "https://bolavip.com/__export/1606256055613/sites/bolavip/img/2020/11/24/blake_snell_pitcher_de_los_rays.jpg_1624932088.jpg",
            "small": "https://bolavip.com/__export/1606256055613/sites/bolavip/img/2020/11/24/blake_snell_pitcher_de_los_rays.jpg_1762501607.jpg"
          },
          "classic": {
            "big": "https://bolavip.com/__export/1606256055613/sites/bolavip/img/2020/11/24/blake_snell_pitcher_de_los_rays.jpg_412320734.jpg",
            "medium": "https://bolavip.com/__export/1606256055613/sites/bolavip/img/2020/11/24/blake_snell_pitcher_de_los_rays.jpg_1055622710.jpg",
            "small": "https://bolavip.com/__export/1606256055613/sites/bolavip/img/2020/11/24/blake_snell_pitcher_de_los_rays.jpg_1592070664.jpg"
          },
          "square": {
            "big": "https://bolavip.com/__export/1606256055613/sites/bolavip/img/2020/11/24/blake_snell_pitcher_de_los_rays.jpg_1159711837.jpg",
            "medium": "https://bolavip.com/__export/1606256055613/sites/bolavip/img/2020/11/24/blake_snell_pitcher_de_los_rays.jpg_1216690859.jpg",
            "small": "https://bolavip.com/__export/1606256055613/sites/bolavip/img/2020/11/24/blake_snell_pitcher_de_los_rays.jpg_1890075089.jpg"
          },
          "full": "https://bolavip.com/__export/1606256055613/sites/bolavip/img/2020/11/24/blake_snell_pitcher_de_los_rays.jpg_1902800913.jpg"
        },
        "epigraph": "Blake Snell, pitcher de los Rays",
        "url": "https://bolavip.com/america/MLB-Blake-Snell-los-equipos-quieren-firmar-al-lanzador-de-Tampa-Bay-Rays-20201124-0148.html",
        "label": "MLB",
        "excerpt": "<p><strong>Toda una sorpresa fue el anuncio de los Tampa Bay Rays cuando informaron que est&aacute;n dispuestos a intercambiar al pitcher estelar Blake Snell.</strong></p>",
        "section": "América",
        "link": "/america/MLB-Blake-Snell-los-equipos-quieren-firmar-al-lanzador-de-Tampa-Bay-Rays-20201124-0148.html",
        "local_path": "/contenidos/2020/11/24/noticia_0148.html",
        "published_at": "2020-11-24T19:23:25-0300",
        "modified_at": "2020-11-24T19:23:32-0300"
      }
    ]
  }
}
```

### GET /news/detail/{link}

`HTTP/1.1 200 OK`

```json
{
  "data": {
    "title": "La cabeza de Galactus comienza a emerger del agua en Fortnite",
    "images": {
      "wide": {
        "big": "https://bolavip.com/__export/1606312122873/sites/bolavip/img/2020/11/25/galactus-cabeza-fortnite_crop1606312122414.jpg_1546398727.jpg",
        "medium": "https://bolavip.com/__export/1606312122873/sites/bolavip/img/2020/11/25/galactus-cabeza-fortnite_crop1606312122414.jpg_1624932088.jpg",
        "small": "https://bolavip.com/__export/1606312122873/sites/bolavip/img/2020/11/25/galactus-cabeza-fortnite_crop1606312122414.jpg_1762501607.jpg"
      },
      "classic": {
        "big": "https://bolavip.com/__export/1606312122873/sites/bolavip/img/2020/11/25/galactus-cabeza-fortnite_crop1606312122414.jpg_412320734.jpg",
        "medium": "https://bolavip.com/__export/1606312122873/sites/bolavip/img/2020/11/25/galactus-cabeza-fortnite_crop1606312122414.jpg_1055622710.jpg",
        "small": "https://bolavip.com/__export/1606312122873/sites/bolavip/img/2020/11/25/galactus-cabeza-fortnite_crop1606312122414.jpg_1592070664.jpg"
      },
      "square": {
        "big": "https://bolavip.com/__export/1606312122873/sites/bolavip/img/2020/11/25/galactus-cabeza-fortnite_crop1606312122414.jpg_1159711837.jpg",
        "medium": "https://bolavip.com/__export/1606312122873/sites/bolavip/img/2020/11/25/galactus-cabeza-fortnite_crop1606312122414.jpg_1216690859.jpg",
        "small": "https://bolavip.com/__export/1606312122873/sites/bolavip/img/2020/11/25/galactus-cabeza-fortnite_crop1606312122414.jpg_1890075089.jpg"
      }
    },
    "epigraph": "",
    "url": "https://bolavip.com/gamer/Fortnite-Isla-Galactus-aparece-cabeza-20201125-0030.html",
    "label": "Fortnite",
    "excerpt": "<p><strong>El Devorador de Mundos est&aacute; cada vez m&aacute;s cerca de hacer su ataque en la Isla.</strong></p>",
    "section": "Gamer",
    "link": "/gamer/Fortnite-Isla-Galactus-aparece-cabeza-20201125-0030.html",
    "local_path": "/contenidos/2020/11/25/noticia_0030.html",
    "published_at": "2020-11-25T10:58:25-0300",
    "modified_at": "2020-11-25T10:58:30-0300",
    "body": "<p>Como ya sabemos, el próximo 1 de diciembre es el día indicado para <strong><a href=\"https://bolavip.com/gamer/Fecha-y-Hora-evento-Fortnite-Guerra-en-Nexus-20201121-0047.html\" target=\"_blank\">el ataque de Galactus</a></strong> a la Isla de <a href=\"https://bolavip.com/fortnite-t18184\" target=\"_blank\"><strong>Fortnite</strong></a>, y el Devorador de Mundos poco a poco va mostrándose en los alrededores. Lo que comenzó con <a href=\"https://bolavip.com/gamer/Fortnite-aparecen-los-cuernos-de-Galactus-en-la-Isla-20201123-0051.html\" target=\"_blank\">sus cuernos emergiendo del agua</a>, ahora ha escalado hasta mostrar parte de su cabeza.</p> \n<p>Los jugadores que ingresen a Fortnite podrán ver <strong>los cuernos y la parte superior del casco de Galactus a la lejanía en el océano alrededor de la Isla,</strong> sobre el sector de Industrias Stark. Así es como se ve actualmente en el juego:</p> \n<div style=\"text-align:center\"> \n <figure class=\"image\" style=\"display:inline-block\"> \n  <img alt=\"\" data-height=\"340\" data-size=\"w:2199,h:1248\" data-width=\"600\" hspace=\"5\" src=\"/export/sites/bolavip/img/2020/11/25/fortnite-galactus-parte.jpg_1004321246.jpg\" title=\"\" vspace=\"5\"> \n  <figcaption></figcaption> \n </figure> \n</div> \n<p>Los Superhéroes serán quienes enfrentarán a Galactus e intentarán defender la Isla ya están planeando sus estrategias. Ayer en las redes sociales de Fortnite nos mostraron que, entre otras cosas, tienen Células Gamma preparadas en caso de emergencia.<span></span></p> \n<div style=\"text-align:center\"> \n <div class=\"ck-twitter\" id=\"twitter-95\" style=\"display: inline-block;\"> \n  <blockquote class=\"twitter-tweet\"> \n   <p dir=\"ltr\" lang=\"es\">¿Crees que tenemos suficientes células gamma?<br> <br> Galactus llega el 12.1.20 18 hs AR 15 hs MX <a href=\"https://t.co/rrn59TkZWB\">pic.twitter.com/rrn59TkZWB</a></p> — Fortnite Latam (@FortniteGameLAT) \n   <a href=\"https://twitter.com/FortniteGameLAT/status/1331314471340564490?ref_src=twsrc%5Etfw\">November 24, 2020</a> \n  </blockquote> \n  <script async src=\"//platform.twitter.com/widgets.js\" charset=\"utf-8\"></script> \n  <span class=\"item first\"></span> \n  <span class=\"item second\"></span> \n  <span class=\"item third\"></span> \n </div> \n</div> \n<p>Veremos cómo continúa progresando esta historia que tendrá su momento cúlmine el próximo 1 de diciembre, pero antes de ello seguramente Galactus ya sea mucho más visible y los Superhéroes tengan muchas armas listas para la gran batalla.</p>",
    "created_by": "gcelsan",
    "has": {
      "HAS_EMBEDDED_IMAGE": true,
      "HAS_EMBEDDED_VIDEO_YOUTUBE": false,
      "HAS_EMBEDDED_IMAGE_GALLERY": false,
      "HAS_EMBEDDED_PINTEREST": false,
      "HAS_EMBEDDED_VINE": false,
      "HAS_EMBEDDED_INSTAGRAM": false,
      "HAS_EMBEDDED_TWITTER": true,
      "HAS_EMBEDDED_FACEBOOK": false,
      "HAS_EMBEDDED_EMBEDDED": false,
      "HAS_EMBEDDED_POLL": false,
      "HAS_EMBEDDED_STORIFY": false,
      "HAS_EMBEDDED_FLICKR": false,
      "HAS_EMBEDDED_YOUTUBE": false,
      "HAS_EMBEDDED_IFRAME": false,
      "HAS_EMBEDDED_RELATED_NEWS": false,
      "HAS_EMBEDDED_JWPLAYER": false,
      "HAS_EMBEDDED_BRID": false
    },
    "hidden": {
      "HIDDEN_COMMENTS": false,
      "HIDDEN_TIME": false,
      "HIDDEN_AUTHOR": false,
      "HIDDEN_EXCERPT": false,
      "HIDDEN_LABEL": false,
      "HIDDEN_ADS": false
    },
    "author": [
      {
        "name": "Germán Celsan",
        "username": "gcelsan",
        "picture": "https://bolavip.com/export/system/cmsMedios/users/f20190301_141352121.jpg_782479081.jpg"
      }
    ],
    "tags": [
      {
        "text": "fortnite",
        "url": "/fortnite-t18184"
      },
      {
        "text": "epic-games",
        "url": "/epic-games-t20605"
      },
      {
        "text": "marvel",
        "url": "/marvel-t28288"
      },
      {
        "text": "gamer",
        "url": "/gamer-t20247"
      }
    ]
  }
}
```