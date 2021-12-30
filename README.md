# Marp Themes - `marpstyle`

Repository for Marp Themes created with beauty and simplicity as first concerns.

![](https://camo.githubusercontent.com/83d3746e5881c1867665223424263d8e604df233d0a11aae0813e0414d433943/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6c6963656e73652d4d49542d626c75652e737667)


![](img/plow_man.gif) | This set of styles were designed bearing simplicity and beauty in mind as first class requirements. As the first style (plato.css) got ready I decided to share.  Hope sincerely you enjoy it and that it comes to be useful to as many users as possible. <br> <br>More styles are due to come. Stay tuned!  
---------|----------


# Available Themes

## Socrates Theme: [pdf](examples/example-socrates.pdf)
![Style: Plato](img/socrates01.png)<br>

## Plato Theme: [pdf](examples/example-plato.pdf)
![Style: Plato](img/plato01.png)<br>

## Leibniz Theme: [pdf](examples/example-leibniz.pdf)
![Style: Leibniz](img/leibniz01.png)<br>

## Hegel Theme: [pdf](examples/example-hegel.pdf)
![Style: Hegel](img/hegel01.png)<br>

# Install
Remember to include the path to the style files (CSS files) in your `workspace.code-workspace` in order to make them available to your slide deck.

It might look similar to:

```bash
{
	"folders": [
		{
			"path": "."
		}
	],
	"settings": {
		"markdown.marp.themes": [
			"./style/socrates.css"
			"./style/plato.css"
			"./style/leibniz.css"
			"./style/kant.css"
			"./style/hegel.css"
			"./style/schema.css"
			"./style/structure.css"
		]
	}
}
```

# Typefaces
Some of the fonts necessary to the available styles are listed below with its respective link for download:

- ## Socrates Theme:
  - Noto Sans: https://fonts.google.com/noto/specimen/Noto+Sans

- ## Plato Theme:  
  - Fira: https://github.com/bBoxType/FiraSans

- ## Leibniz Theme:  
  - Georgia or Serif: 

- ## General 
  - Metropolis: https://github.com/njugunagathere/Metropolis


# Credits

- **Plato** theme was inspired by [Metropolis Beamer Theme](https://github.com/matze/mtheme) for LaTeX by [Mathias Vogelgesang](https://github.com/matze/mtheme). Vielen Dank!!
- Used some parts of [Juan Vera del Campo](https://github.com/Juanvvc) CSS styles. Gracias!