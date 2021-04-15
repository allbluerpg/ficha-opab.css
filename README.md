:root {
--cor-ficha: #D07D5A;
--pirata: #b92222;
--agente: #9C9C9C;
--marinheiro: #6BB8DB;
--cacador: #bfc342;
--revolucionario: #B34B54;
--civil: #c1ac75;
}

#ficha-opab {
  width: 650px;
  background: #1C1C1C;
  border: 20px solid #1C1C1C;
  margin: auto;
  border-radius: 10px;
  align-items: center;
  justify-content: center;
  color: #fff;
  display: flex;
  flex-wrap: wrap;
}

#ficha-opab strong {
  color: var(--cor-ficha);
}

#ficha-opab a {
  color: #fff!important;
  text-decoration: underline;
}

#ficha-opab .imagem {
  width: 650px;
  height: 250px;
  border-radius: 5px 5px 0px 0px;
}

.caixanome {
  width: 610px;
  height: 60px;
  padding: 20px;
  background: var(--cor-ficha);
  font-family: poppins;
  font-size: 30px;
  font-weight: bold;
  text-transform: uppercase;
  text-align: left;
  line-height: 60px;
  letter-spacing: -1px;
  margin-top: -20px;
}

#ficha-opab .f-icone {
  width: 170px;
  height: 170px;
  background: var(--cor-ficha);
  clip-path: circle(50% 0%, 100% 50%, 50% 100%, 0% 50%);
  position: absolute;
  margin-top: -164px;
  margin-left: 420px;
}

#ficha-opab .icone {
  width: 150px;
  height: 150px;
  clip-path: circle(50% 0%, 100% 50%, 50% 100%, 0% 50%);
  margin-top: 10px;
  margin-left: 10px;
}

#ficha-opab input[type="radio"] {
    display: none;
}

#ficha-opab label {
display: flex;
flex-grow: 1;
width: 205px;
height: 30px;
background: #424242;
margin-top: 10px;
margin-right: 10px;
}

#ficha-opab label:nth-of-type(3n) {
  margin-right: 0px;
}

#ficha-opab label i {
  height: 30px;
  width: 30px;
  background: #2f2f2f;
  line-height: 30px;
  text-align: center;
  font-size: 20px;
  float: left;
}

#ficha-opab label titulo {
  float: right;
  width: 180px;
  height: 30px;
  line-height: 30px;
  text-align: center;
  font-family: poppins;
  text-transform: uppercase;
  font-size: 13px;
  font-weight: bold;
}

#ficha-opab input[type='radio']:checked + label {
background: var(--cor-ficha);
}

#ficha-opab input[type='radio']:checked + label i {
background: #fff;
color: var(--cor-ficha);
}

#ficha-opab #zona1, #ficha-opab #zona2, #ficha-opab #zona3, #ficha-opab #zona4, #ficha-opab #zona5, #ficha-opab #zona6 {
  display: none;
  width: 570px;
  padding: 20px 40px;
  background: #1b1919;
  margin-top: 10px;
  border-radius: 0px 0px 5px 5px;
  font-family: roboto;
  font-size: 13px;
text-align: justify;
}

#ficha-opab #geral:checked ~ #zona1, #ficha-opab #particularidades:checked ~ #zona2, #ficha-opab #combate:checked ~ #zona3, #ficha-opab #haki:checked ~ #zona4, #ficha-opab #pertences:checked ~ #zona5, #ficha-opab #popularidade:checked ~ #zona6 {
  display: block;
}

#ficha-opab h1 {
  font-size: 18px;
  text-transform: uppercase;
  font-family: poppins;
  background: var(--cor-ficha);
  height: 10px;
  line-height: 10px;
  padding: 20px;
  letter-spacing: -1px;
  margin-top: 20px;
font-weight: bold;
}

#ficha-opab h1:nth-of-type(1) {
  margin-top: 0px;
}

#ficha-opab #zona2 mascote {
  text-transform:uppercase;
  font-size: 16px;
  font-weight: bold;
  color: var(--cor-ficha);
}






#ficha-opab br {display: none;} #ficha-opab #zona1 br, #ficha-opab #zona2 br, #ficha-opab #zona3 br, #ficha-opab #zona4 br, #ficha-opab #zona5 br, #ficha-opab #zona6 br {display: block;}

/* latin-ext */
@font-face {
  font-family: 'Poppins';
  font-style: italic;
  font-weight: 400;
  src: url(https://fonts.gstatic.com/s/poppins/v15/pxiGyp8kv8JHgFVrJJLufntAKPY.woff2) format('woff2');
  unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
}
/* latin */
@font-face {
  font-family: 'Poppins';
  font-style: italic;
  font-weight: 400;
  src: url(https://fonts.gstatic.com/s/poppins/v15/pxiGyp8kv8JHgFVrJJLucHtA.woff2) format('woff2');
  unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
}

/* latin-ext */
@font-face {
  font-family: 'Poppins';
  font-style: italic;
  font-weight: 500;
  src: url(https://fonts.gstatic.com/s/poppins/v15/pxiDyp8kv8JHgFVrJJLmg1hVGdeOcEg.woff2) format('woff2');
  unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
}
/* latin */
@font-face {
  font-family: 'Poppins';
  font-style: italic;
  font-weight: 500;
  src: url(https://fonts.gstatic.com/s/poppins/v15/pxiDyp8kv8JHgFVrJJLmg1hVF9eO.woff2) format('woff2');
  unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
}

/* latin-ext */
@font-face {
  font-family: 'Poppins';
  font-style: italic;
  font-weight: 600;
  src: url(https://fonts.gstatic.com/s/poppins/v15/pxiDyp8kv8JHgFVrJJLmr19VGdeOcEg.woff2) format('woff2');
  unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
}
/* latin */
@font-face {
  font-family: 'Poppins';
  font-style: italic;
  font-weight: 600;
  src: url(https://fonts.gstatic.com/s/poppins/v15/pxiDyp8kv8JHgFVrJJLmr19VF9eO.woff2) format('woff2');
  unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
}

/* latin-ext */
@font-face {
  font-family: 'Poppins';
  font-style: italic;
  font-weight: 700;
  src: url(https://fonts.gstatic.com/s/poppins/v15/pxiDyp8kv8JHgFVrJJLmy15VGdeOcEg.woff2) format('woff2');
  unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
}
/* latin */
@font-face {
  font-family: 'Poppins';
  font-style: italic;
  font-weight: 700;
  src: url(https://fonts.gstatic.com/s/poppins/v15/pxiDyp8kv8JHgFVrJJLmy15VF9eO.woff2) format('woff2');
  unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
}

/* latin-ext */
@font-face {
  font-family: 'Poppins';
  font-style: italic;
  font-weight: 800;
  src: url(https://fonts.gstatic.com/s/poppins/v15/pxiDyp8kv8JHgFVrJJLm111VGdeOcEg.woff2) format('woff2');
  unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
}
/* latin */
@font-face {
  font-family: 'Poppins';
  font-style: italic;
  font-weight: 800;
  src: url(https://fonts.gstatic.com/s/poppins/v15/pxiDyp8kv8JHgFVrJJLm111VF9eO.woff2) format('woff2');
  unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
}

/* latin-ext */
@font-face {
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 400;
  src: url(https://fonts.gstatic.com/s/poppins/v15/pxiEyp8kv8JHgFVrJJnecmNE.woff2) format('woff2');
  unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
}
/* latin */
@font-face {
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 400;
  src: url(https://fonts.gstatic.com/s/poppins/v15/pxiEyp8kv8JHgFVrJJfecg.woff2) format('woff2');
  unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
}

/* latin-ext */
@font-face {
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 500;
  src: url(https://fonts.gstatic.com/s/poppins/v15/pxiByp8kv8JHgFVrLGT9Z1JlFc-K.woff2) format('woff2');
  unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
}
/* latin */
@font-face {
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 500;
  src: url(https://fonts.gstatic.com/s/poppins/v15/pxiByp8kv8JHgFVrLGT9Z1xlFQ.woff2) format('woff2');
  unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
}

/* latin-ext */
@font-face {
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 600;
  src: url(https://fonts.gstatic.com/s/poppins/v15/pxiByp8kv8JHgFVrLEj6Z1JlFc-K.woff2) format('woff2');
  unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
}
/* latin */
@font-face {
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 600;
  src: url(https://fonts.gstatic.com/s/poppins/v15/pxiByp8kv8JHgFVrLEj6Z1xlFQ.woff2) format('woff2');
  unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
}

/* latin-ext */
@font-face {
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 700;
  src: url(https://fonts.gstatic.com/s/poppins/v15/pxiByp8kv8JHgFVrLCz7Z1JlFc-K.woff2) format('woff2');
  unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
}
/* latin */
@font-face {
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 700;
  src: url(https://fonts.gstatic.com/s/poppins/v15/pxiByp8kv8JHgFVrLCz7Z1xlFQ.woff2) format('woff2');
  unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
}

/* latin-ext */
@font-face {
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 800;
  src: url(https://fonts.gstatic.com/s/poppins/v15/pxiByp8kv8JHgFVrLDD4Z1JlFc-K.woff2) format('woff2');
  unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
}
/* latin */
@font-face {
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 800;
  src: url(https://fonts.gstatic.com/s/poppins/v15/pxiByp8kv8JHgFVrLDD4Z1xlFQ.woff2) format('woff2');
  unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
}

/* latin-ext */
@font-face {
  font-family: 'Roboto';
  font-style: normal;
  font-weight: 400;
  src: url(https://fonts.gstatic.com/s/roboto/v27/KFOmCnqEu92Fr1Mu7GxKOzY.woff2) format('woff2');
  unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
}
/* latin */
@font-face {
  font-family: 'Roboto';
  font-style: normal;
  font-weight: 400;
  src: url(https://fonts.gstatic.com/s/roboto/v27/KFOmCnqEu92Fr1Mu4mxK.woff2) format('woff2');
  unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
}

/* latin-ext */
@font-face {
  font-family: 'Roboto';
  font-style: normal;
  font-weight: 500;
  src: url(https://fonts.gstatic.com/s/roboto/v27/KFOlCnqEu92Fr1MmEU9fChc4EsA.woff2) format('woff2');
  unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
}
/* latin */
@font-face {
  font-family: 'Roboto';
  font-style: normal;
  font-weight: 500;
  src: url(https://fonts.gstatic.com/s/roboto/v27/KFOlCnqEu92Fr1MmEU9fBBc4.woff2) format('woff2');
  unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
}
