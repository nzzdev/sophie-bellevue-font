# Sophie Font Styles for bellevue.nzz.ch

## Requirements

Infos from Bellevue regarding fonts:

* Titel: Beausite Slick Medium (color #060821)
* Subtitel: Damien Text Regular (color #060821)
* Legende-Element: Beausite Fit Regular (color #060821)
* Karten-Annotation: Beausite Fit Regular  (color #060821)
* Quelle: Beausite Fit Regular (for that one we use grey -> #060821 60%)

Available Fonts on the Site:

```css
 @font-face {
	font-display: swap;
	font-family: BeausiteGrand-Bold;
	font-weight: 700;
	src: url(//assets.static-nzz.ch/bellevue/assets/fonts/Beausite/BeausiteGrand-Bold.eot) format("embedded-opentype"), url(//assets.static-nzz.ch/bellevue/assets/fonts/Beausite/BeausiteGrand-Bold.woff) format("woff")
}

@font-face {
	font-display: swap;
	font-family: BeausiteSlick-Regular;
	font-weight: 400;
	src: url(//assets.static-nzz.ch/bellevue/assets/fonts/Beausite/BeausiteSlickWeb-Regular.woff2) format("woff2"), url(//assets.static-nzz.ch/bellevue/assets/fonts/Beausite/BeausiteSlickWeb-Regular.woff) format("woff")
}

@font-face {
	font-display: swap;
	font-family: BeausiteSlick-Medium;
	font-weight: 500;
	src: url(//assets.static-nzz.ch/bellevue/assets/fonts/Beausite/BeausiteSlickWeb-Medium.woff2) format("woff2"), url(//assets.static-nzz.ch/bellevue/assets/fonts/Beausite/BeausiteSlickWeb-Medium.woff) format("woff")
}

@font-face {
	font-display: swap;
	font-family: BeausiteSlick-Bold;
	font-weight: 700;
	src: url(//assets.static-nzz.ch/bellevue/assets/fonts/Beausite/BeausiteSlickWeb-Bold.woff2) format("woff2"), url(//assets.static-nzz.ch/bellevue/assets/fonts/Beausite/BeausiteSlickWeb-Bold.woff) format("woff")
}

@font-face {
	font-display: swap;
	font-family: BeausiteFit-Regular;
	font-weight: 300;
	src: url(//assets.static-nzz.ch/bellevue/assets/fonts/Beausite/BeausiteFit-Regular.eot) format("embedded-opentype"), url(//assets.static-nzz.ch/bellevue/assets/fonts/Beausite/BeausiteFit-Regular.woff) format("woff")
}

@font-face {
	font-display: swap;
	font-family: BeausiteFit-Medium;
	font-weight: 500;
	src: url(//assets.static-nzz.ch/bellevue/assets/fonts/Beausite/BeausiteFit-Medium.eot) format("embedded-opentype"), url(//assets.static-nzz.ch/bellevue/assets/fonts/Beausite/BeausiteFit-Medium.woff) format("woff")
}

@font-face {
	font-display: swap;
	font-family: BeausiteFit-Bold;
	font-weight: 700;
	src: url(//assets.static-nzz.ch/bellevue/assets/fonts/Beausite/BeausiteFit-Bold.eot) format("embedded-opentype"), url(//assets.static-nzz.ch/bellevue/assets/fonts/Beausite/BeausiteFit-Bold.woff) format("woff")
}

@font-face {
	font-display: swap;
	font-family: DamienText-Regular;
	font-weight: 300;
	src: url(//assets.static-nzz.ch/bellevue/assets/fonts/Damien/Damien_Text_Regular.eot) format("embedded-opentype"), url(//assets.static-nzz.ch/bellevue/assets/fonts/Damien/Damien_Text_Regular.woff2) format("woff2"), url(//assets.static-nzz.ch/bellevue/assets/fonts/Damien/Damien_Text_Regular.woff) format("woff")
}

@font-face {
	font-display: swap;
	font-family: DamienText-Medium;
	font-weight: 500;
	src: url(//assets.static-nzz.ch/bellevue/assets/fonts/Damien/Damien_Text_Medium.eot) format("embedded-opentype"), url(//assets.static-nzz.ch/bellevue/assets/fonts/Damien/Damien_Text_Medium.woff2) format("woff2"), url(//assets.static-nzz.ch/bellevue/assets/fonts/Damien/Damien_Text_Medium.woff) format("woff")
}

@font-face {
	font-display: swap;
	font-family: DamienText-Semibold;
	font-weight: 600;
	src: url(//assets.static-nzz.ch/bellevue/assets/fonts/Damien/Damien_Text_Semibold.eot) format("embedded-opentype"), url(//assets.static-nzz.ch/bellevue/assets/fonts/Damien/Damien_Text_Semibold.woff2) format("woff2"), url(//assets.static-nzz.ch/bellevue/assets/fonts/Damien/Damien_Text_Semibold.woff) format("woff")
}

@font-face {
	font-display: swap;
	font-family: DamienText-Bold;
	font-weight: 700;
	src: url(//assets.static-nzz.ch/bellevue/assets/fonts/Damien/Damien_Text_Bold.eot) format("embedded-opentype"), url(//assets.static-nzz.ch/bellevue/assets/fonts/Damien/Damien_Text_Bold.woff2) format("woff2"), url(//assets.static-nzz.ch/bellevue/assets/fonts/Damien/Damien_Text_Bold.woff) format("woff")
}

@font-face {
	font-display: swap;
	font-family: DamienText-Italic;
	font-style: italic;
	font-weight: 300;
	src: url(//assets.static-nzz.ch/bellevue/assets/fonts/Damien/Damien_Text_Italic.eot) format("embedded-opentype"), url(//assets.static-nzz.ch/bellevue/assets/fonts/Damien/Damien_Text_Italic.woff2) format("woff2"), url(//assets.static-nzz.ch/bellevue/assets/fonts/Damien/Damien_Text_Italic.woff) format("woff")
}

@font-face {
	font-display: swap;
	font-family: DamienDisplay-Regular;
	font-weight: 400;
	src: url(//assets.static-nzz.ch/bellevue/assets/fonts/Damien/DamienDisplay_Regular.eot) format("embedded-opentype"), url(//assets.static-nzz.ch/bellevue/assets/fonts/Damien/DamienDisplay_Regular.woff2) format("woff2"), url(//assets.static-nzz.ch/bellevue/assets/fonts/Damien/DamienDisplay_Regular.woff) format("woff")
}

@font-face {
	font-display: swap;
	font-family: DamienDisplay-Medium;
	font-weight: 500;
	src: url(//assets.static-nzz.ch/bellevue/assets/fonts/Damien/DamienDisplay_Medium.eot) format("embedded-opentype"), url(//assets.static-nzz.ch/bellevue/assets/fonts/Damien/DamienDisplay_Medium.woff2) format("woff2"), url(//assets.static-nzz.ch/bellevue/assets/fonts/Damien/DamienDisplay_Medium.woff) format("woff")
}

@font-face {
	font-display: swap;
	font-family: DamienDisplay-Semibold;
	font-weight: 600;
	src: url(//assets.static-nzz.ch/bellevue/assets/fonts/Damien/DamienDisplay_Semibold.eot) format("embedded-opentype"), url(//assets.static-nzz.ch/bellevue/assets/fonts/Damien/DamienDisplay_Semibold.woff2) format("woff2"), url(//assets.static-nzz.ch/bellevue/assets/fonts/Damien/DamienDisplay_Semibold.woff) format("woff")
}
```