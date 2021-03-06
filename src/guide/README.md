# Titulo

VuePress is composed of two parts: a [minimalistic static site generator](https://github.com/vuejs/vuepress/tree/master/packages/%40vuepress/core) with a Vue-powered [theming system](https://v1.vuepress.vuejs.org/theme/) and [Plugin API](https://v1.vuepress.vuejs.org/plugin/), and a [default theme](https://v1.vuepress.vuejs.org/theme/default-theme-config.html) optimized for writing technical documentation. It was created to support the documentation needs of Vue's own sub projects.

Each page generated by VuePress has its own pre-rendered static HTML, providing great loading performance and is SEO-friendly. Once the page is loaded, however, Vue takes over the static content and turns it into a full Single-Page Application (SPA). Additional pages are fetched on demand as the user navigates around the site.

## Subtitulo
### Subtitulo 6

* Item 1
* Item 2
* Item 3

1. Item 1
2. Item 2
3. Item 3


## Imagenes

![mi imagen desde lorem](https://picsum.photos/300)

<img :src="$withBase('/img/1.jpg')">


## Códigos

```html
    <html>
	<head>
		<title>Mi página de ejemplo</title>
	</head>
	<body>
	Aquí va el contenido
	</body>
    </html>
```