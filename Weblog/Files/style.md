---
Type: file
Content-Type: text/css
Title: Stylesheet
Location: /style.css
---

<style>
.table-wrapper{
    display: block;
    overflow-x: auto;
}

table {
    border-collapse: collapse;
    border-spacing: 0;
    width: 100%;
}

table td:first-child {
    background: var(--background);
    background-image: url(https://www.transparenttextures.com/patterns/diagmonds.png);
}

table td, table th {
    border: 5px solid var(--articleBorder);
    text-align: center;
}

table th:first-of-type {
    width: 20%;
}
table th:nth-of-type(2) {
    width: 40%;
}
table th:nth-of-type(3) {
    width: 20%;
}
table th:nth-of-type(4) {
    width: 20%;
}

* {
    box-sizing: border-box;
}

body {
    font-family: 'Open Sans', sans-serif;
    font-size: 120%;
    color: var(--foreground);
    background: var(--background);
}

img {
    width: 100%;
    border-radius: 30px;
}

img.setup-image {
max-width: 100%;
    height: 100%;
    object-fit: contain;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}

.img-container-wide {
    background: var(--background);
    background-image: url(https://www.transparenttextures.com/patterns/inspiration-geometry.png);
    position: relative;
    width: 100%;
    height:0;
    padding-bottom: 50%;
    border-radius: 30px;
}

.img-container-square {
    position: relative;
    width: 100%;
    height:0;
    padding-bottom: 100%;
}

h1, h2, h3, h4, h5, h6 {
    font-family: 'VC Honey Deck', serif;
    margin: 1rem 0;
}

p, li {
    line-height: inherit;
}

nav {
    font-family: 'VC Honey Deck';
    line-height: 150%;
    overflow: hidden;
    width: 100%;
}

nav li {
    list-style-type: none;
}

nav ul {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-evenly;
    padding: 0;
    margin: 5px 0px 5px 0px;
    align-content: center;
}

.box ul {
    padding-inline-start: 20px;
}

header, main, footer {
    max-width: 60em;
    margin: 1em auto;
    padding: 0 1em;
}

main {
    display: flex;
    flex-wrap: wrap;
    width: 100%;
    margin: 1em auto;
    padding: 0;
}

footer p {
    font-size: 90%;
    text-align: center;
}

a:link { color: var(--link); text-decoration: none; border-bottom: 1px dotted var(--link); }
a:visited { color: var(--link); text-decoration: none; border-bottom: 1px dotted var(--link) }
a:hover { color: var(--link); text-decoration: none; border-bottom: 1px solid var(--link) }
a:active { color: var(--link); text-decoration: none; border-bottom: 1px solid var(--link) }

.post-info, .post-tags {
    font-size: 85%;
    color: var(--unimportant);
    text-align: center;
}

.post-info i:nth-child(2) {
    margin-left: .75em;
}

.tag {
    font-family: 'VC Honey Deck';
    color: var(--foreground) !important;
    padding: 0em .4em;
    border-radius: 25px;
    display: inline-block;
}

.tag:before {
    font-family: "Font Awesome 6 Free";
    font-weight: bold;
    content: '\f02b';
    padding-right: 0.25em;
}
hr {
    border: 0;
    height: 1px;
    background: var(--articleBorder);
    margin: 1em 0;
}

.video-container {
    position: relative;
    width: 100%;
    padding-bottom: 56.25%;
}

.video-container-square {
    position: relative;
    width: 100%;
    padding-bottom: 100%;
}

.video {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    border-radius: 30px;
    
}

.caption {
    font-size: 90%;
    font-style: italic;
    text-align: center;
    margin-top: -18px;
}

.box {
    border-radius: 30px;
    background: var(--articleBG);
    border: 5px solid var(--articleBorder);
    padding: 5px 25px 5px 25px;
}

.nav-box {
    border-radius: 30px;
    background: var(--articleBG);
    border: 5px solid var(--articleBorder);
}

.box:not(:first-of-type) {
margin-top: 20px;
}

.flex-column{
    display: block;
    flex-grow: 1;
    flex-shrink: 1;
    flex-basis: auto;
    align-self: auto;
    order: 0;
    height: fit-content;
    margin: 10px;

}

.flex-column:nth-child(1) {
  width: 100%;
    padding: 0;
}

.flex-column:nth-child(2) {
  width: 60%;
}

.flex-column:nth-child(3) {
  width: 35%;
  font-size: 90%;
  line-height: 150%;
}

aside {
    border-radius: 100px;
    background: var(--articleBorder);
    padding: 10px;
    margin-bottom: 10px;
}

blockquote {
    background: var(--articleBorder);
    border-radius: 20px;
    padding: inherit;
    font-style: italic;
    margin: 20px 0 20px 0;
}

code {
    background: var(--foreground);
    color: var(--articleBG);
    padding: 5px;
}

form {
  background-color: var(--articleBorder);
  height: 50px;
  border-radius: 20px;
  display: flex;
  flex-direction: row;
  align-items: center;
margin-bottom: 10px;
}

input {
  all: unset;
  font: 16px 'Open Sans', sans-serif;
  color: #fff;
  height: 100%;
  width: 100%;
  padding: 6px 10px;
}

::placeholder {
  color: #fff;
  opacity: 0.7; 
}

button {
  all: unset;
  cursor: pointer;
  width: 50px;
  height: 50px;
}

svg {
  color: #fff;
  fill: currentColor;
  width: 50px;
  height: 50px;
  padding: 10px;
}

del {
    text-decoration-line: line-through;
    opacity: 50%;
    /* text-decoration-style: wavy;
    text-decoration-color: #ff0000CC; */
}
</style>