# front-3
jzin
/* http://meyerweb.com/eric/tools/css/reset/ 
   v2.0 | 20110126
   License: none (public domain)
*/

html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, embed, 
figure, figcaption, footer, header, hgroup, 
menu, nav, output, ruby, section, summary,
time, mark, audio, video {
	margin: 0;
	padding: 0;
	border: 0;
	font-size: 100%;
	font: inherit;
	vertical-align: baseline;
}
/* HTML5 display-role reset for older browsers */
article, aside, details, figcaption, figure, 
footer, header, hgroup, menu, nav, section {
	display: block;
}
body {
	line-height: 1;
}
ol, ul {
	list-style: none; 
}
blockquote, q {
	quotes: none;
}
blockquote:before, blockquote:after,
q:before, q:after {
	content: '';
	content: none;
}
table {
	border-collapse: collapse;
	border-spacing: 1;
}.flex {
    display: flex;
}

.full {
    height: 100vh;
    background: #ffffff;
}

.logo-wrapper {
    display: none;
}

.from-wrapper {
    display: flex;
    flex-direction: column;

    width: 100%;

}          

<!DOCTYPE html>
<html lang="pt-BR">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>login-adobe</title>
    <link rel="stylesheet" href="css/reset.css" />
    <link rel="stylesheet" href="css/style.css" />
  </head>
  <body>
    <div class="flex full bg-img">
      <div class="logo-wrapper">
      </div>
      <div class="form-wrapper">
        <div class="flex">
          <div class="mb-1">
            <img src="img/adobe_logo.svg" class="form-logo" alt="logo Adobe" />
          </div>
        </div>
      </div>
    </div>
  </body>
</html>

.flex {
    display: flex;
}

.full {
    height: 100vh;
    background: #ffffff;
}

.logo-wrapper {
    display: none;
}

.form-wrapper {
    display: flex;
    flex-direction: column;

    width: 100%;

}          

.mb-1 {
    margin: 0.5rem;
}
.form-logo {
    filter: brightness(0);
}
