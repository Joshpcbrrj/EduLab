<html><head><meta http-equiv="Content-Type" content="text/html; charset=utf-8"/><title>Hackaton StartSe</title><style>
/* cspell:disable-file */
/* webkit printing magic: print all background colors */
html {
	-webkit-print-color-adjust: exact;
}
* {
	box-sizing: border-box;
	-webkit-print-color-adjust: exact;
}

html,
body {
	margin: 0;
	padding: 0;
}
@media only screen {
	body {
		margin: 2em auto;
		max-width: 900px;
		color: rgb(55, 53, 47);
	}
}

body {
	line-height: 1.5;
	white-space: pre-wrap;
}

a,
a.visited {
	color: inherit;
	text-decoration: underline;
}

.pdf-relative-link-path {
	font-size: 80%;
	color: #444;
}

h1,
h2,
h3 {
	letter-spacing: -0.01em;
	line-height: 1.2;
	font-weight: 600;
	margin-bottom: 0;
}

.page-title {
	font-size: 2.5rem;
	font-weight: 700;
	margin-top: 0;
	margin-bottom: 0.75em;
}

h1 {
	font-size: 1.875rem;
	margin-top: 1.875rem;
}

h2 {
	font-size: 1.5rem;
	margin-top: 1.5rem;
}

h3 {
	font-size: 1.25rem;
	margin-top: 1.25rem;
}

.source {
	border: 1px solid #ddd;
	border-radius: 3px;
	padding: 1.5em;
	word-break: break-all;
}

.callout {
	border-radius: 3px;
	padding: 1rem;
}

figure {
	margin: 1.25em 0;
	page-break-inside: avoid;
}

figcaption {
	opacity: 0.5;
	font-size: 85%;
	margin-top: 0.5em;
}

mark {
	background-color: transparent;
}

.indented {
	padding-left: 1.5em;
}

hr {
	background: transparent;
	display: block;
	width: 100%;
	height: 1px;
	visibility: visible;
	border: none;
	border-bottom: 1px solid rgba(55, 53, 47, 0.09);
}

img {
	max-width: 100%;
}

@media only print {
	img {
		max-height: 100vh;
		object-fit: contain;
	}
}

@page {
	margin: 1in;
}

.collection-content {
	font-size: 0.875rem;
}

.column-list {
	display: flex;
	justify-content: space-between;
}

.column {
	padding: 0 1em;
}

.column:first-child {
	padding-left: 0;
}

.column:last-child {
	padding-right: 0;
}

.table_of_contents-item {
	display: block;
	font-size: 0.875rem;
	line-height: 1.3;
	padding: 0.125rem;
}

.table_of_contents-indent-1 {
	margin-left: 1.5rem;
}

.table_of_contents-indent-2 {
	margin-left: 3rem;
}

.table_of_contents-indent-3 {
	margin-left: 4.5rem;
}

.table_of_contents-link {
	text-decoration: none;
	opacity: 0.7;
	border-bottom: 1px solid rgba(55, 53, 47, 0.18);
}

table,
th,
td {
	border: 1px solid rgba(55, 53, 47, 0.09);
	border-collapse: collapse;
}

table {
	border-left: none;
	border-right: none;
}

th,
td {
	font-weight: normal;
	padding: 0.25em 0.5em;
	line-height: 1.5;
	min-height: 1.5em;
	text-align: left;
}

th {
	color: rgba(55, 53, 47, 0.6);
}

ol,
ul {
	margin: 0;
	margin-block-start: 0.6em;
	margin-block-end: 0.6em;
}

li > ol:first-child,
li > ul:first-child {
	margin-block-start: 0.6em;
}

ul > li {
	list-style: disc;
}

ul.to-do-list {
	text-indent: -1.7em;
}

ul.to-do-list > li {
	list-style: none;
}

.to-do-children-checked {
	text-decoration: line-through;
	opacity: 0.375;
}

ul.toggle > li {
	list-style: none;
}

ul {
	padding-inline-start: 1.7em;
}

ul > li {
	padding-left: 0.1em;
}

ol {
	padding-inline-start: 1.6em;
}

ol > li {
	padding-left: 0.2em;
}

.mono ol {
	padding-inline-start: 2em;
}

.mono ol > li {
	text-indent: -0.4em;
}

.toggle {
	padding-inline-start: 0em;
	list-style-type: none;
}

/* Indent toggle children */
.toggle > li > details {
	padding-left: 1.7em;
}

.toggle > li > details > summary {
	margin-left: -1.1em;
}

.selected-value {
	display: inline-block;
	padding: 0 0.5em;
	background: rgba(206, 205, 202, 0.5);
	border-radius: 3px;
	margin-right: 0.5em;
	margin-top: 0.3em;
	margin-bottom: 0.3em;
	white-space: nowrap;
}

.collection-title {
	display: inline-block;
	margin-right: 1em;
}

.simple-table {
	margin-top: 1em;
	font-size: 0.875rem;
	empty-cells: show;
}
.simple-table td {
	height: 29px;
	min-width: 120px;
}

.simple-table th {
	height: 29px;
	min-width: 120px;
}

.simple-table-header-color {
	background: rgb(247, 246, 243);
	color: black;
}
.simple-table-header {
	font-weight: 500;
}

time {
	opacity: 0.5;
}

.icon {
	display: inline-block;
	max-width: 1.2em;
	max-height: 1.2em;
	text-decoration: none;
	vertical-align: text-bottom;
	margin-right: 0.5em;
}

img.icon {
	border-radius: 3px;
}

.user-icon {
	width: 1.5em;
	height: 1.5em;
	border-radius: 100%;
	margin-right: 0.5rem;
}

.user-icon-inner {
	font-size: 0.8em;
}

.text-icon {
	border: 1px solid #000;
	text-align: center;
}

.page-cover-image {
	display: block;
	object-fit: cover;
	width: 100%;
	max-height: 30vh;
}

.page-header-icon {
	font-size: 3rem;
	margin-bottom: 1rem;
}

.page-header-icon-with-cover {
	margin-top: -0.72em;
	margin-left: 0.07em;
}

.page-header-icon img {
	border-radius: 3px;
}

.link-to-page {
	margin: 1em 0;
	padding: 0;
	border: none;
	font-weight: 500;
}

p > .user {
	opacity: 0.5;
}

td > .user,
td > time {
	white-space: nowrap;
}

input[type="checkbox"] {
	transform: scale(1.5);
	margin-right: 0.6em;
	vertical-align: middle;
}

p {
	margin-top: 0.5em;
	margin-bottom: 0.5em;
}

.image {
	border: none;
	margin: 1.5em 0;
	padding: 0;
	border-radius: 0;
	text-align: center;
}

.code,
code {
	background: rgba(135, 131, 120, 0.15);
	border-radius: 3px;
	padding: 0.2em 0.4em;
	border-radius: 3px;
	font-size: 85%;
	tab-size: 2;
}

code {
	color: #eb5757;
}

.code {
	padding: 1.5em 1em;
}

.code-wrap {
	white-space: pre-wrap;
	word-break: break-all;
}

.code > code {
	background: none;
	padding: 0;
	font-size: 100%;
	color: inherit;
}

blockquote {
	font-size: 1.25em;
	margin: 1em 0;
	padding-left: 1em;
	border-left: 3px solid rgb(55, 53, 47);
}

.bookmark {
	text-decoration: none;
	max-height: 8em;
	padding: 0;
	display: flex;
	width: 100%;
	align-items: stretch;
}

.bookmark-title {
	font-size: 0.85em;
	overflow: hidden;
	text-overflow: ellipsis;
	height: 1.75em;
	white-space: nowrap;
}

.bookmark-text {
	display: flex;
	flex-direction: column;
}

.bookmark-info {
	flex: 4 1 180px;
	padding: 12px 14px 14px;
	display: flex;
	flex-direction: column;
	justify-content: space-between;
}

.bookmark-image {
	width: 33%;
	flex: 1 1 180px;
	display: block;
	position: relative;
	object-fit: cover;
	border-radius: 1px;
}

.bookmark-description {
	color: rgba(55, 53, 47, 0.6);
	font-size: 0.75em;
	overflow: hidden;
	max-height: 4.5em;
	word-break: break-word;
}

.bookmark-href {
	font-size: 0.75em;
	margin-top: 0.25em;
}

.sans { font-family: ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol"; }
.code { font-family: "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace; }
.serif { font-family: Lyon-Text, Georgia, ui-serif, serif; }
.mono { font-family: iawriter-mono, Nitti, Menlo, Courier, monospace; }
.pdf .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK JP'; }
.pdf:lang(zh-CN) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK SC'; }
.pdf:lang(zh-TW) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK TC'; }
.pdf:lang(ko-KR) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK KR'; }
.pdf .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.pdf .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK JP'; }
.pdf:lang(zh-CN) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK SC'; }
.pdf:lang(zh-TW) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK TC'; }
.pdf:lang(ko-KR) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK KR'; }
.pdf .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.highlight-default {
	color: rgba(55, 53, 47, 1);
}
.highlight-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.highlight-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.highlight-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.highlight-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.highlight-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.highlight-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.highlight-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.highlight-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.highlight-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.highlight-gray_background {
	background: rgba(241, 241, 239, 1);
}
.highlight-brown_background {
	background: rgba(244, 238, 238, 1);
}
.highlight-orange_background {
	background: rgba(251, 236, 221, 1);
}
.highlight-yellow_background {
	background: rgba(251, 243, 219, 1);
}
.highlight-teal_background {
	background: rgba(237, 243, 236, 1);
}
.highlight-blue_background {
	background: rgba(231, 243, 248, 1);
}
.highlight-purple_background {
	background: rgba(244, 240, 247, 0.8);
}
.highlight-pink_background {
	background: rgba(249, 238, 243, 0.8);
}
.highlight-red_background {
	background: rgba(253, 235, 236, 1);
}
.block-color-default {
	color: inherit;
	fill: inherit;
}
.block-color-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.block-color-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.block-color-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.block-color-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.block-color-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.block-color-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.block-color-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.block-color-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.block-color-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.block-color-gray_background {
	background: rgba(241, 241, 239, 1);
}
.block-color-brown_background {
	background: rgba(244, 238, 238, 1);
}
.block-color-orange_background {
	background: rgba(251, 236, 221, 1);
}
.block-color-yellow_background {
	background: rgba(251, 243, 219, 1);
}
.block-color-teal_background {
	background: rgba(237, 243, 236, 1);
}
.block-color-blue_background {
	background: rgba(231, 243, 248, 1);
}
.block-color-purple_background {
	background: rgba(244, 240, 247, 0.8);
}
.block-color-pink_background {
	background: rgba(249, 238, 243, 0.8);
}
.block-color-red_background {
	background: rgba(253, 235, 236, 1);
}
.select-value-color-pink { background-color: rgba(245, 224, 233, 1); }
.select-value-color-purple { background-color: rgba(232, 222, 238, 1); }
.select-value-color-green { background-color: rgba(219, 237, 219, 1); }
.select-value-color-gray { background-color: rgba(227, 226, 224, 1); }
.select-value-color-opaquegray { background-color: rgba(255, 255, 255, 0.0375); }
.select-value-color-orange { background-color: rgba(250, 222, 201, 1); }
.select-value-color-brown { background-color: rgba(238, 224, 218, 1); }
.select-value-color-red { background-color: rgba(255, 226, 221, 1); }
.select-value-color-yellow { background-color: rgba(253, 236, 200, 1); }
.select-value-color-blue { background-color: rgba(211, 229, 239, 1); }

.checkbox {
	display: inline-flex;
	vertical-align: text-bottom;
	width: 16;
	height: 16;
	background-size: 16px;
	margin-left: 2px;
	margin-right: 5px;
}

.checkbox-on {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20width%3D%2216%22%20height%3D%2216%22%20fill%3D%22%2358A9D7%22%2F%3E%0A%3Cpath%20d%3D%22M6.71429%2012.2852L14%204.9995L12.7143%203.71436L6.71429%209.71378L3.28571%206.2831L2%207.57092L6.71429%2012.2852Z%22%20fill%3D%22white%22%2F%3E%0A%3C%2Fsvg%3E");
}

.checkbox-off {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20x%3D%220.75%22%20y%3D%220.75%22%20width%3D%2214.5%22%20height%3D%2214.5%22%20fill%3D%22white%22%20stroke%3D%22%2336352F%22%20stroke-width%3D%221.5%22%2F%3E%0A%3C%2Fsvg%3E");
}
	
</style></head><body><article id="ff0374d3-787c-4d1d-b49e-819c5fa12b32" class="page sans"><header><img class="page-cover-image" src="Hackaton%20StartSe%20ff0374d3787c4d1db49e819c5fa12b32/hackathon.jpg" style="object-position:center 60.160000000000004%"/><div class="page-header-icon page-header-icon-with-cover"><span class="icon">🌐</span></div><h1 class="page-title">Hackaton StartSe</h1></header><div class="page-body"><ul id="65939a2c-a84c-42ed-a5e2-1e677c20e2b1" class="toggle"><li><details close=""><summary><mark class="highlight-gray_background"> Resumo do conteúdo do curso </mark></summary><p id="a500bf7b-26a2-45be-a0b6-0a664078c29a" class=""><a href="https://www.notion.so/StartSe-781a14cf4bdc4db79d2f20e621d921cb">https://www.notion.so/StartSe-781a14cf4bdc4db79d2f20e621d921cb</a></p></details></li></ul><figure id="d55b36b4-41ae-43a3-b6c9-b724abfc1d23" class="link-to-page"><a href="Hackaton%20StartSe%20ff0374d3787c4d1db49e819c5fa12b32/Data%20d55b36b441ae43a3b6c9b724abfc1d23.html">Data</a></figure><h1 id="27b77642-01cd-415f-a815-862c2b9e4a2a" class="">Nome do projeto: <span style="border-bottom:0.05em solid"><strong>EduLab</strong></span></h1><div id="0f0d184b-68ca-4b1b-81ad-9da3e47cb507" class="column-list"><div id="c2ef0ca5-7941-4a5c-97dd-41241553fea7" style="width:31.25%" class="column"><h3 id="bcf6a6c8-5a0c-4e1f-8360-733db641d136" class=""><mark class="highlight-orange_background">   O que será avaliado ??   </mark></h3><ol type="1" id="ebee9255-8a67-43af-83d6-36fa1ebde901" class="numbered-list" start="1"><li>Força da solução (Potencialidade)</li></ol><ol type="1" id="14f73407-4bce-48f1-bb1d-34ea0a1dc334" class="numbered-list" start="2"><li>Criatividade </li></ol><ol type="1" id="8564d9e4-278f-49e4-b876-9e0687b6cf45" class="numbered-list" start="3"><li>Qualidade do código </li></ol></div><div id="b763587e-08af-44af-9e2d-da7e9895cdde" style="width:68.7499999999999%" class="column"><h3 id="201a6e7d-27d7-427b-8330-a1b658b83dc4" class=""><mark class="highlight-blue">N</mark>ome da squad :  Edugrup   </h3><p id="3695b64f-bc24-4e2d-8ab5-9946b5e3e882" class=""><mark class="highlight-blue">Trilha </mark>: Educação</p><p id="14707870-e181-4422-81aa-eb98ede5d0eb" class=""><mark class="highlight-blue">Problema </mark>: Evasão escolar</p></div></div><h2 id="dd9cc6bb-e7cf-4db4-96af-2eb313816f94" class=""><mark class="highlight-brown">M</mark>em<mark class="highlight-brown_background">b</mark>ros: </h2><ul id="5434b102-27e7-4cd2-9836-ee2269b9d84f" class="bulleted-list"><li style="list-style-type:disc">Erick - <mark class="highlight-teal">Tech lead</mark></li></ul><ul id="28ae5111-6c2a-4328-a78f-b872745a4484" class="bulleted-list"><li style="list-style-type:disc">Bruno</li></ul><ul id="0df33b81-4c69-4920-a15b-66f41612207b" class="bulleted-list"><li style="list-style-type:disc">Josue B. Almeida - <mark class="highlight-blue">Manager</mark></li></ul><ul id="22335a8b-1eb0-46d0-aa9d-ba092bdbdaea" class="bulleted-list"><li style="list-style-type:disc">Aline Cesar - <mark class="highlight-blue">Manager 2</mark></li></ul><ul id="504df5af-2668-4ee8-ac59-32544c79c250" class="bulleted-list"><li style="list-style-type:disc">Daniel dias</li></ul><p id="73ed77f9-e0f0-41ff-8a34-64e585222303" class="">
</p><h2 id="8437b224-750a-4566-b9b5-29f14af0b0bf" class=""><details close=""><summary><mark class="highlight-pink">M</mark>aterial base para entender o problema</summary></details></h2><div class="indented"><h3 id="a34188df-9d29-40d3-8136-1d38c29a53c5" class="">Conteúdo auxiliar (Resumos)</h3><figure id="40a5881d-d8c2-4de9-91a1-624e6f9ef047" class="link-to-page"><a href="Hackaton%20StartSe%20ff0374d3787c4d1db49e819c5fa12b32/(2016)%20-%20AUSENTES%20evasa%CC%83o%20escolar%20no%20ensino%20me%CC%81dio%2040a5881dd8c24de991a1624e6f9ef047.html">(2016) - AUSENTES: evasão escolar no ensino médio - DOCUMENTÁRIO </a></figure><figure id="3b6225aa-c3fe-4bb1-b675-4fe906b05365" class="link-to-page"><a href="Hackaton%20StartSe%20ff0374d3787c4d1db49e819c5fa12b32/(2017)%20-%20Pec%CC%A7a%20Vagas%20de%20luz%20(Desenvolvido%20por%20educ%203b6225aac3fe4bb1b6754fe906b05365.html">(2017) - Peça: Vagas de luz (Desenvolvido por educandos do 8° termo do EJA)</a></figure><figure id="3d745a3c-721c-4204-825d-0c000b9e2389" class="link-to-page"><a href="Hackaton%20StartSe%20ff0374d3787c4d1db49e819c5fa12b32/(2018)%20-%20MEC%20quer%20aproximar%20estudantes%20da%20escola%20p%203d745a3c721c4204825d0c000b9e2389.html">(2018) - MEC quer aproximar estudantes da escola para evitar a evasão </a></figure><figure id="da6d8a6e-d3b7-4c7e-8663-9ec69c81c512" class="link-to-page"><a href="Hackaton%20StartSe%20ff0374d3787c4d1db49e819c5fa12b32/(2018)%20-%20Evasa%CC%83o%20escolar%20no%20Brasil%20(dados%20do%20MEC)%20da6d8a6ed3b74c7e86639ec69c81c512.html">(2018) - Evasão escolar no Brasil (dados do MEC)</a></figure><figure id="29e953d2-4a80-4cb4-8ec6-eea616e78009" class="link-to-page"><a href="Hackaton%20StartSe%20ff0374d3787c4d1db49e819c5fa12b32/(2018)%20-%20Como%20na%CC%83o%20esquecer%20o%20conteu%CC%81do%20que%20estudo%2029e953d24a804cb48ec6eea616e78009.html">(2018) - Como não esquecer o conteúdo que estudou - Entenda a Curva do Esquecimento de Ebbinghaus</a></figure><figure id="b5966d3c-3288-40bb-a147-8248dfde602e" class="link-to-page"><a href="Hackaton%20StartSe%20ff0374d3787c4d1db49e819c5fa12b32/(2019)%20-%20Causas%20da%20evasa%CC%83o%20e%20defasagem%20escolar%20Ent%20b5966d3c328840bba1478248dfde602e.html">(2019) - Causas da evasão e defasagem escolar | Entrevista Evasão Escola no Brasil </a></figure><figure id="dedfecd0-a5de-4474-aa62-856f56972c51" class="link-to-page"><a href="Hackaton%20StartSe%20ff0374d3787c4d1db49e819c5fa12b32/(2019)%20-%209%20MAIORES%20ERROS%20Que%20Todo%20ESTUDANTE%20Comete%20dedfecd0a5de4474aa62856f56972c51.html">(2019) - 9 MAIORES ERROS Que Todo ESTUDANTE Comete ( COMPROVADO CIENTIFICAMENTE) - Isso mudou minha vida</a></figure><figure id="36f839a9-ebfc-4970-802f-97bfabb87d88" class="link-to-page"><a href="Hackaton%20StartSe%20ff0374d3787c4d1db49e819c5fa12b32/(2020)%20-%20Educac%CC%A7a%CC%83o%20na%20pandemia%20-%20Mario%20Sergio%20Cor%2036f839a9ebfc4970802f97bfabb87d88.html">(2020) - Educação na pandemia - Mario Sergio Cortella </a></figure><figure id="5e57b86b-de14-461e-ad80-83978c7cc22d" class="link-to-page"><a href="Hackaton%20StartSe%20ff0374d3787c4d1db49e819c5fa12b32/(2020)%20-%20COMO%20EVITAR%20O%20AUMENTO%20DA%20EVASA%CC%83O%20ESCOLAR%20%205e57b86bde14461ead8083978c7cc22d.html">(2020) - COMO EVITAR O AUMENTO DA EVASÃO ESCOLAR PÓS-PANDEMIA | CNN Tonight </a></figure><figure id="b5e65b3b-7f0f-4fbc-9936-14f3650db2ce" class="link-to-page"><a href="Hackaton%20StartSe%20ff0374d3787c4d1db49e819c5fa12b32/(2020)%20-%20O%20que%20e%CC%81%20possi%CC%81vel%20fazer%20para%20combater%20o%20%20b5e65b3b7f0f4fbc993614f3650db2ce.html">(2020) - O que é possível fazer para combater o abandono escolar ? </a></figure><figure id="bc1fe784-2334-45e1-a290-f1151b53fb2c" class="link-to-page"><a href="Hackaton%20StartSe%20ff0374d3787c4d1db49e819c5fa12b32/(2020)%20-%20O%20SISTEMA%20DE%20EDUCAC%CC%A7A%CC%83O%20NA%CC%83O%20TE%20INCENTIVA%20bc1fe784233445e1a290f1151b53fb2c.html">(2020) - O SISTEMA DE EDUCAÇÃO NÃO TE INCENTIVA A ESTUDAR | Cortes do Flow </a></figure><figure id="b9281558-19f0-4644-8f67-c9cbfd4cfd2b" class="link-to-page"><a href="Hackaton%20StartSe%20ff0374d3787c4d1db49e819c5fa12b32/(2022)%20-%20Dados%20do%20MEC%20apontam%20que%20abandono%20escolar%20b928155819f046448f67c9cbfd4cfd2b.html">(2022) - Dados do MEC apontam que abandono escolar mais que dobrou em 2021</a></figure><figure id="320450c1-3723-428c-8a48-52217aa343ef" class="link-to-page"><a href="Hackaton%20StartSe%20ff0374d3787c4d1db49e819c5fa12b32/(2022)%20-%20Artigo%205%C2%BA%20(Dados%20mostram%20que%20abandono%20esc%20320450c13723428c8a4852217aa343ef.html">(2022) - Artigo 5º (Dados mostram que abandono escolar na pandemia é preocupante)</a></figure><figure id="472b55ac-329e-4d8c-961b-e3df2fdcb868" class="link-to-page"><a href="Hackaton%20StartSe%20ff0374d3787c4d1db49e819c5fa12b32/(2022)%20-%20Evasa%CC%83o%20escolar%20e%20o%20abandono%20um%20guia%20para%20472b55ac329e4d8c961be3df2fdcb868.html">(2022) - Evasão escolar e o abandono: um guia para entender esses conceitos</a></figure><h3 id="a8704204-14c2-42e6-b029-67281975adf3" class="">Conteúdo para ajudar na implementação (Resumos)</h3><figure id="045928d0-bb93-44fe-9a36-bd4cb2f99a80" class="link-to-page"><a href="Hackaton%20StartSe%20ff0374d3787c4d1db49e819c5fa12b32/(2021)%20-%20Gamificac%CC%A7a%CC%83o%20na%20educac%CC%A7a%CC%83o%20o%20que%20e%CC%81%20e%20co%20045928d0bb9344fe9a36bd4cb2f99a80.html">(2021) - Gamificação na educação: o que é e como pode ser aplicada</a></figure></div><h2 id="fea361b7-a96f-4154-8dd6-69963ab87bce" class=""><details close=""><summary><mark class="highlight-red">P</mark>ossíveis ideias </summary></details></h2><div class="indented"><figure id="45ae2bdd-f60b-4d8f-9227-04cc60e03203" class="link-to-page"><a href="Hackaton%20StartSe%20ff0374d3787c4d1db49e819c5fa12b32/PROJETO%20HACKATHON%20-%20Aline%2045ae2bddf60b4d8f922704cc60e03203.html">PROJETO HACKATHON - Aline</a></figure><figure id="586422b4-0b69-4afc-a177-518b22210eb8" class="link-to-page"><a href="Hackaton%20StartSe%20ff0374d3787c4d1db49e819c5fa12b32/Possi%CC%81veis%20features%20-%20Josue%CC%81%20586422b40b694afca177518b22210eb8.html">Possíveis features - Josué</a></figure></div><h1 id="e25ffe7c-a3c9-44dd-bf4c-f1f4548fd702" class=""><details close=""><summary><mark class="highlight-teal">S</mark>olução escolhida: </summary></details></h1><div class="indented"><figure id="fff66a5e-175a-4c53-be00-f91092e3d8f3" class="link-to-page"><a href="Hackaton%20StartSe%20ff0374d3787c4d1db49e819c5fa12b32/Tudo%20do%20projeto%20fff66a5e175a4c53be00f91092e3d8f3.html"><span class="icon">🛠️</span>Tudo do projeto</a></figure><ul id="c4ba2ad1-fe32-49bd-b319-f097212bb723" class="toggle"><li><details close=""><summary>Apresentação do pitch (Miro)</summary></details></li></ul></div><h1 id="ea35dd6f-bd4c-43dc-b5bb-01193320986a" class=""><details close=""><summary><mark class="highlight-yellow">Q</mark>uadro de tarefas</summary></details></h1><div class="indented"><div id="79111324-47ee-42e8-910c-f800917ce92b" class="collection-content"><h4 class="collection-title">Quadro de tarefas</h4><table class="collection-content"><thead><tr><th><span class="icon property-icon"><svg viewBox="0 0 14 14" style="width:14px;height:14px;display:block;fill:rgba(55, 53, 47, 0.45);flex-shrink:0;-webkit-backface-visibility:hidden" class="typesTitle"><path d="M7.73943662,8.6971831 C7.77640845,8.7834507 7.81338028,8.8943662 7.81338028,9.00528169 C7.81338028,9.49823944 7.40669014,9.89260563 6.91373239,9.89260563 C6.53169014,9.89260563 6.19894366,9.64612676 6.08802817,9.30105634 L5.75528169,8.33978873 L2.05809859,8.33978873 L1.72535211,9.30105634 C1.61443662,9.64612676 1.2693662,9.89260563 0.887323944,9.89260563 C0.394366197,9.89260563 0,9.49823944 0,9.00528169 C0,8.8943662 0.0246478873,8.7834507 0.0616197183,8.6971831 L2.46478873,2.48591549 C2.68661972,1.90669014 3.24119718,1.5 3.90669014,1.5 C4.55985915,1.5 5.12676056,1.90669014 5.34859155,2.48591549 L7.73943662,8.6971831 Z M2.60035211,6.82394366 L5.21302817,6.82394366 L3.90669014,3.10211268 L2.60035211,6.82394366 Z M11.3996479,3.70598592 C12.7552817,3.70598592 14,4.24823944 14,5.96126761 L14,9.07922535 C14,9.52288732 13.6549296,9.89260563 13.2112676,9.89260563 C12.8169014,9.89260563 12.471831,9.59683099 12.4225352,9.19014085 C12.028169,9.6584507 11.3257042,9.95422535 10.5492958,9.95422535 C9.60035211,9.95422535 8.47887324,9.31338028 8.47887324,7.98239437 C8.47887324,6.58978873 9.60035211,6.08450704 10.5492958,6.08450704 C11.3380282,6.08450704 12.040493,6.33098592 12.4348592,6.81161972 L12.4348592,5.98591549 C12.4348592,5.38204225 11.9172535,4.98767606 11.1285211,4.98767606 C10.6602113,4.98767606 10.2411972,5.11091549 9.80985915,5.38204225 C9.72359155,5.43133803 9.61267606,5.46830986 9.50176056,5.46830986 C9.18133803,5.46830986 8.91021127,5.1971831 8.91021127,4.86443662 C8.91021127,4.64260563 9.0334507,4.44542254 9.19366197,4.34683099 C9.87147887,3.90316901 10.6232394,3.70598592 11.3996479,3.70598592 Z M11.1778169,8.8943662 C11.6830986,8.8943662 12.1760563,8.72183099 12.4348592,8.37676056 L12.4348592,7.63732394 C12.1760563,7.29225352 11.6830986,7.11971831 11.1778169,7.11971831 C10.5616197,7.11971831 10.056338,7.45246479 10.056338,8.0193662 C10.056338,8.57394366 10.5616197,8.8943662 11.1778169,8.8943662 Z M0.65625,11.125 L13.34375,11.125 C13.7061869,11.125 14,11.4188131 14,11.78125 C14,12.1436869 13.7061869,12.4375 13.34375,12.4375 L0.65625,12.4375 C0.293813133,12.4375 4.43857149e-17,12.1436869 0,11.78125 C-4.43857149e-17,11.4188131 0.293813133,11.125 0.65625,11.125 Z"></path></svg></span>Tarefa</th><th><span class="icon property-icon"><svg viewBox="0 0 14 14" style="width:14px;height:14px;display:block;fill:rgba(55, 53, 47, 0.45);flex-shrink:0;-webkit-backface-visibility:hidden" class="typesRelation"><polygon points="4.5 1 4.5 3 9.586 3 1 11.586 2.414 13 11 4.414 11 9.5 13 9.5 13 1"></polygon></svg></span>Branch do GitHub</th><th><span class="icon property-icon"><svg viewBox="0 0 14 14" style="width:14px;height:14px;display:block;fill:rgba(55, 53, 47, 0.45);flex-shrink:0;-webkit-backface-visibility:hidden" class="typesText"><path d="M7,4.56818 C7,4.29204 6.77614,4.06818 6.5,4.06818 L0.5,4.06818 C0.223858,4.06818 0,4.29204 0,4.56818 L0,5.61364 C0,5.88978 0.223858,6.11364 0.5,6.11364 L6.5,6.11364 C6.77614,6.11364 7,5.88978 7,5.61364 L7,4.56818 Z M0.5,1 C0.223858,1 0,1.223858 0,1.5 L0,2.54545 C0,2.8216 0.223858,3.04545 0.5,3.04545 L12.5,3.04545 C12.7761,3.04545 13,2.8216 13,2.54545 L13,1.5 C13,1.223858 12.7761,1 12.5,1 L0.5,1 Z M0,8.68182 C0,8.95796 0.223858,9.18182 0.5,9.18182 L11.5,9.18182 C11.7761,9.18182 12,8.95796 12,8.68182 L12,7.63636 C12,7.36022 11.7761,7.13636 11.5,7.13636 L0.5,7.13636 C0.223858,7.13636 0,7.36022 0,7.63636 L0,8.68182 Z M0,11.75 C0,12.0261 0.223858,12.25 0.5,12.25 L9.5,12.25 C9.77614,12.25 10,12.0261 10,11.75 L10,10.70455 C10,10.4284 9.77614,10.20455 9.5,10.20455 L0.5,10.20455 C0.223858,10.20455 0,10.4284 0,10.70455 L0,11.75 Z"></path></svg></span>Consideração</th><th><span class="icon property-icon"><svg viewBox="0 0 14 14" style="width:14px;height:14px;display:block;fill:rgba(55, 53, 47, 0.45);flex-shrink:0;-webkit-backface-visibility:hidden" class="typesDate"><path d="M10.8889,5.5 L3.11111,5.5 L3.11111,7.05556 L10.8889,7.05556 L10.8889,5.5 Z M12.4444,1.05556 L11.6667,1.05556 L11.6667,0 L10.1111,0 L10.1111,1.05556 L3.88889,1.05556 L3.88889,0 L2.33333,0 L2.33333,1.05556 L1.55556,1.05556 C0.692222,1.05556 0.00777777,1.75556 0.00777777,2.61111 L0,12.5 C0,13.3556 0.692222,14 1.55556,14 L12.4444,14 C13.3,14 14,13.3556 14,12.5 L14,2.61111 C14,1.75556 13.3,1.05556 12.4444,1.05556 Z M12.4444,12.5 L1.55556,12.5 L1.55556,3.94444 L12.4444,3.94444 L12.4444,12.5 Z M8.55556,8.61111 L3.11111,8.61111 L3.11111,10.1667 L8.55556,10.1667 L8.55556,8.61111 Z"></path></svg></span>Data da entrega</th><th><span class="icon property-icon"><svg viewBox="0 0 14 14" style="width:14px;height:14px;display:block;fill:rgba(55, 53, 47, 0.45);flex-shrink:0;-webkit-backface-visibility:hidden" class="typesCreatedAt"><path d="M7.01356 14.0001C8.8042 14.0001 10.5958 13.3107 11.9575 11.9324C14.681 9.21201 14.6808 4.7603 11.9571 2.04013C9.23336 -0.680043 4.77573 -0.680043 2.05199 2.04013C0.727519 3.36277 0 5.13301 0 6.99553C0 8.8764 0.727811 10.6285 2.05199 11.9509C3.43207 13.3106 5.22243 14.0001 7.01356 14.0001ZM3.72947 7.00914V8.461V8.65543H3.92382H5.34563H8.2794H8.4738V8.461V5.52541V3.37947V3.18502H8.2794H6.82747H6.63307V3.37947V6.81467H3.92382H3.72947V7.00914ZM1.83985 6.99553C1.83985 5.61698 2.38099 4.32597 3.36061 3.3477C5.36746 1.34337 8.64803 1.34062 10.6585 3.33944C10.6613 3.34219 10.6639 3.34494 10.6668 3.3477C12.676 5.3546 12.6763 8.63642 10.6668 10.6434C8.65705 12.6504 5.37031 12.6504 3.36061 10.6434C2.38099 9.66506 1.83985 8.37408 1.83985 6.99553Z"></path></svg></span>Data da inclusao</th><th><span class="icon property-icon"><svg viewBox="0 0 14 14" style="width:14px;height:14px;display:block;fill:rgba(55, 53, 47, 0.45);flex-shrink:0;-webkit-backface-visibility:hidden" class="typesRelation"><polygon points="4.5 1 4.5 3 9.586 3 1 11.586 2.414 13 11 4.414 11 9.5 13 9.5 13 1"></polygon></svg></span>Responsavel</th><th><span class="icon property-icon"><svg viewBox="0 0 14 14" style="width:14px;height:14px;display:block;fill:rgba(55, 53, 47, 0.45);flex-shrink:0;-webkit-backface-visibility:hidden" class="typesSelect"><path d="M7,13 C10.31348,13 13,10.31371 13,7 C13,3.68629 10.31348,1 7,1 C3.68652,1 1,3.68629 1,7 C1,10.31371 3.68652,13 7,13 Z M3.75098,5.32278 C3.64893,5.19142 3.74268,5 3.90869,5 L10.09131,5 C10.25732,5 10.35107,5.19142 10.24902,5.32278 L7.15771,9.29703 C7.07764,9.39998 6.92236,9.39998 6.84229,9.29703 L3.75098,5.32278 Z"></path></svg></span>Status </th></tr></thead><tbody><tr id="dc3a3e2c-a109-4e1d-97f6-643d0915c0c6"><td class="cell-title"><a href="Hackaton%20StartSe%20ff0374d3787c4d1db49e819c5fa12b32/Data%20d55b36b441ae43a3b6c9b724abfc1d23/Quadro%20de%20tarefas%2006f04776f5e94bfcaa68f1789290026a/Elencando%20problema%20dc3a3e2ca1094e1d97f6643d0915c0c6.html">Elencando problema</a></td><td class="cell-Fhbg"></td><td class="cell-JuQr"></td><td class="cell-PIZQ"></td><td class="cell-ZocJ"><time>@July 24, 2022 1:14 AM</time></td><td class="cell-KgMf"></td><td class="cell-xrR?"><span class="selected-value select-value-color-green">Concluido</span></td></tr><tr id="30f61e67-bd20-40f5-8b93-dae68d31989b"><td class="cell-title"><a href="Hackaton%20StartSe%20ff0374d3787c4d1db49e819c5fa12b32/Data%20d55b36b441ae43a3b6c9b724abfc1d23/Quadro%20de%20tarefas%2006f04776f5e94bfcaa68f1789290026a/Elencando%20possi%CC%81veis%20soluc%CC%A7o%CC%83es%2030f61e67bd2040f58b93dae68d31989b.html">Elencando possíveis soluções</a></td><td class="cell-Fhbg"></td><td class="cell-JuQr"></td><td class="cell-PIZQ"></td><td class="cell-ZocJ"><time>@July 24, 2022 1:14 AM</time></td><td class="cell-KgMf"></td><td class="cell-xrR?"><span class="selected-value select-value-color-green">Concluido</span></td></tr><tr id="45301074-d4b0-4ba7-9e9e-57a2c6267a04"><td class="cell-title"><a href="Hackaton%20StartSe%20ff0374d3787c4d1db49e819c5fa12b32/Data%20d55b36b441ae43a3b6c9b724abfc1d23/Quadro%20de%20tarefas%2006f04776f5e94bfcaa68f1789290026a/Escolhendo%20soluc%CC%A7a%CC%83o%2045301074d4b04ba79e9e57a2c6267a04.html">Escolhendo solução</a></td><td class="cell-Fhbg"></td><td class="cell-JuQr"></td><td class="cell-PIZQ"></td><td class="cell-ZocJ"><time>@July 24, 2022 1:15 AM</time></td><td class="cell-KgMf"></td><td class="cell-xrR?"><span class="selected-value select-value-color-green">Concluido</span></td></tr><tr id="f4518705-2899-4f0c-a7ba-7ef61457ab96"><td class="cell-title"><a href="Hackaton%20StartSe%20ff0374d3787c4d1db49e819c5fa12b32/Data%20d55b36b441ae43a3b6c9b724abfc1d23/Quadro%20de%20tarefas%2006f04776f5e94bfcaa68f1789290026a/Discutindo%20modelo%20conceitual%20f451870528994f0ca7ba7ef61457ab96.html">Discutindo modelo conceitual</a></td><td class="cell-Fhbg"></td><td class="cell-JuQr"></td><td class="cell-PIZQ"></td><td class="cell-ZocJ"><time>@July 24, 2022 1:15 AM</time></td><td class="cell-KgMf"></td><td class="cell-xrR?"><span class="selected-value select-value-color-blue">Iniciado</span></td></tr><tr id="9d727ed7-3570-4c57-9440-543e2879dd54"><td class="cell-title"><a href="Hackaton%20StartSe%20ff0374d3787c4d1db49e819c5fa12b32/Data%20d55b36b441ae43a3b6c9b724abfc1d23/Quadro%20de%20tarefas%2006f04776f5e94bfcaa68f1789290026a/Criac%CC%A7a%CC%83o%20de%20modelo%20conceitual%209d727ed735704c579440543e2879dd54.html">Criação de modelo conceitual</a></td><td class="cell-Fhbg"></td><td class="cell-JuQr"></td><td class="cell-PIZQ"></td><td class="cell-ZocJ"><time>@July 24, 2022 1:14 AM</time></td><td class="cell-KgMf"></td><td class="cell-xrR?"><span class="selected-value select-value-color-blue">Iniciado</span></td></tr><tr id="053a5f06-403a-422a-875e-7c5fe59a7d12"><td class="cell-title"><a href="Hackaton%20StartSe%20ff0374d3787c4d1db49e819c5fa12b32/Data%20d55b36b441ae43a3b6c9b724abfc1d23/Quadro%20de%20tarefas%2006f04776f5e94bfcaa68f1789290026a/Criac%CC%A7a%CC%83o%20de%20direto%CC%81rio%20github%20053a5f06403a422a875e7c5fe59a7d12.html">Criação de diretório github</a></td><td class="cell-Fhbg"></td><td class="cell-JuQr"></td><td class="cell-PIZQ"></td><td class="cell-ZocJ"><time>@July 24, 2022 1:13 AM</time></td><td class="cell-KgMf"></td><td class="cell-xrR?"></td></tr><tr id="eb80b3fd-df5f-4e61-9d47-741aa14ed6cc"><td class="cell-title"><a href="Hackaton%20StartSe%20ff0374d3787c4d1db49e819c5fa12b32/Data%20d55b36b441ae43a3b6c9b724abfc1d23/Quadro%20de%20tarefas%2006f04776f5e94bfcaa68f1789290026a/Modelo%20da%20apresentac%CC%A7a%CC%83o%20eb80b3fddf5f4e619d47741aa14ed6cc.html">Modelo da apresentação</a></td><td class="cell-Fhbg"></td><td class="cell-JuQr"></td><td class="cell-PIZQ"></td><td class="cell-ZocJ"><time>@July 24, 2022 1:14 AM</time></td><td class="cell-KgMf"></td><td class="cell-xrR?"></td></tr></tbody></table></div></div><h2 id="43960fd3-9c80-430a-9589-e027c118b7fb" class=""><details close=""><summary>Encontros/ Reuniões</summary></details></h2><div class="indented"><div id="4b32eba0-da9c-4d8c-8b9f-f64be60aaeab" class="collection-content"><h4 class="collection-title">Reuniões</h4><table class="collection-content"><thead><tr><th><span class="icon property-icon"><svg viewBox="0 0 14 14" style="width:14px;height:14px;display:block;fill:rgba(55, 53, 47, 0.45);flex-shrink:0;-webkit-backface-visibility:hidden" class="typesTitle"><path d="M7.73943662,8.6971831 C7.77640845,8.7834507 7.81338028,8.8943662 7.81338028,9.00528169 C7.81338028,9.49823944 7.40669014,9.89260563 6.91373239,9.89260563 C6.53169014,9.89260563 6.19894366,9.64612676 6.08802817,9.30105634 L5.75528169,8.33978873 L2.05809859,8.33978873 L1.72535211,9.30105634 C1.61443662,9.64612676 1.2693662,9.89260563 0.887323944,9.89260563 C0.394366197,9.89260563 0,9.49823944 0,9.00528169 C0,8.8943662 0.0246478873,8.7834507 0.0616197183,8.6971831 L2.46478873,2.48591549 C2.68661972,1.90669014 3.24119718,1.5 3.90669014,1.5 C4.55985915,1.5 5.12676056,1.90669014 5.34859155,2.48591549 L7.73943662,8.6971831 Z M2.60035211,6.82394366 L5.21302817,6.82394366 L3.90669014,3.10211268 L2.60035211,6.82394366 Z M11.3996479,3.70598592 C12.7552817,3.70598592 14,4.24823944 14,5.96126761 L14,9.07922535 C14,9.52288732 13.6549296,9.89260563 13.2112676,9.89260563 C12.8169014,9.89260563 12.471831,9.59683099 12.4225352,9.19014085 C12.028169,9.6584507 11.3257042,9.95422535 10.5492958,9.95422535 C9.60035211,9.95422535 8.47887324,9.31338028 8.47887324,7.98239437 C8.47887324,6.58978873 9.60035211,6.08450704 10.5492958,6.08450704 C11.3380282,6.08450704 12.040493,6.33098592 12.4348592,6.81161972 L12.4348592,5.98591549 C12.4348592,5.38204225 11.9172535,4.98767606 11.1285211,4.98767606 C10.6602113,4.98767606 10.2411972,5.11091549 9.80985915,5.38204225 C9.72359155,5.43133803 9.61267606,5.46830986 9.50176056,5.46830986 C9.18133803,5.46830986 8.91021127,5.1971831 8.91021127,4.86443662 C8.91021127,4.64260563 9.0334507,4.44542254 9.19366197,4.34683099 C9.87147887,3.90316901 10.6232394,3.70598592 11.3996479,3.70598592 Z M11.1778169,8.8943662 C11.6830986,8.8943662 12.1760563,8.72183099 12.4348592,8.37676056 L12.4348592,7.63732394 C12.1760563,7.29225352 11.6830986,7.11971831 11.1778169,7.11971831 C10.5616197,7.11971831 10.056338,7.45246479 10.056338,8.0193662 C10.056338,8.57394366 10.5616197,8.8943662 11.1778169,8.8943662 Z M0.65625,11.125 L13.34375,11.125 C13.7061869,11.125 14,11.4188131 14,11.78125 C14,12.1436869 13.7061869,12.4375 13.34375,12.4375 L0.65625,12.4375 C0.293813133,12.4375 4.43857149e-17,12.1436869 0,11.78125 C-4.43857149e-17,11.4188131 0.293813133,11.125 0.65625,11.125 Z"></path></svg></span>Encontro</th><th><span class="icon property-icon"><svg viewBox="0 0 14 14" style="width:14px;height:14px;display:block;fill:rgba(55, 53, 47, 0.45);flex-shrink:0;-webkit-backface-visibility:hidden" class="typesMultipleSelect"><path d="M4,3 C4,2.447715 4.447715,2 5,2 L12,2 C12.5523,2 13,2.447716 13,3 C13,3.55228 12.5523,4 12,4 L5,4 C4.447715,4 4,3.55228 4,3 Z M4,7 C4,6.447715 4.447715,6 5,6 L12,6 C12.5523,6 13,6.447716 13,7 C13,7.55228 12.5523,8 12,8 L5,8 C4.447715,8 4,7.55228 4,7 Z M4,11 C4,10.447715 4.447715,10 5,10 L12,10 C12.5523,10 13,10.447716 13,11 C13,11.55228 12.5523,12 12,12 L5,12 C4.447715,12 4,11.55228 4,11 Z M2,4 C1.44771525,4 1,3.55228475 1,3 C1,2.44771525 1.44771525,2 2,2 C2.55228475,2 3,2.44771525 3,3 C3,3.55228475 2.55228475,4 2,4 Z M2,8 C1.44771525,8 1,7.55228475 1,7 C1,6.44771525 1.44771525,6 2,6 C2.55228475,6 3,6.44771525 3,7 C3,7.55228475 2.55228475,8 2,8 Z M2,12 C1.44771525,12 1,11.5522847 1,11 C1,10.4477153 1.44771525,10 2,10 C2.55228475,10 3,10.4477153 3,11 C3,11.5522847 2.55228475,12 2,12 Z"></path></svg></span>Escopo</th><th><span class="icon property-icon"><svg viewBox="0 0 14 14" style="width:14px;height:14px;display:block;fill:rgba(55, 53, 47, 0.45);flex-shrink:0;-webkit-backface-visibility:hidden" class="typesCheckbox"><path d="M0,3 C0,1.34314 1.34326,0 3,0 L11,0 C12.6567,0 14,1.34314 14,3 L14,11 C14,12.6569 12.6567,14 11,14 L3,14 C1.34326,14 0,12.6569 0,11 L0,3 Z M3,1.5 C2.17139,1.5 1.5,2.17157 1.5,3 L1.5,11 C1.5,11.8284 2.17139,12.5 3,12.5 L11,12.5 C11.8286,12.5 12.5,11.8284 12.5,11 L12.5,3 C12.5,2.17157 11.8286,1.5 11,1.5 L3,1.5 Z M2.83252,6.8161 L3.39893,6.27399 L3.57617,6.10425 L3.92334,5.77216 L4.26904,6.10559 L4.44531,6.27582 L5.58398,7.37402 L9.28271,3.81073 L9.45996,3.64008 L9.80664,3.3056 L10.1538,3.63989 L10.3311,3.81067 L10.8936,4.35303 L11.0708,4.52399 L11.4434,4.88379 L11.0708,5.24353 L10.8936,5.41437 L6.1084,10.0291 L5.93115,10.2 L5.58398,10.5344 L5.23682,10.2 L5.05957,10.0292 L2.83057,7.87946 L2.65283,7.70801 L2.27832,7.34674 L2.6543,6.98694 L2.83252,6.8161 Z"></path></svg></span>Finalizada ?</th><th><span class="icon property-icon"><svg viewBox="0 0 14 14" style="width:14px;height:14px;display:block;fill:rgba(55, 53, 47, 0.45);flex-shrink:0;-webkit-backface-visibility:hidden" class="typesDate"><path d="M10.8889,5.5 L3.11111,5.5 L3.11111,7.05556 L10.8889,7.05556 L10.8889,5.5 Z M12.4444,1.05556 L11.6667,1.05556 L11.6667,0 L10.1111,0 L10.1111,1.05556 L3.88889,1.05556 L3.88889,0 L2.33333,0 L2.33333,1.05556 L1.55556,1.05556 C0.692222,1.05556 0.00777777,1.75556 0.00777777,2.61111 L0,12.5 C0,13.3556 0.692222,14 1.55556,14 L12.4444,14 C13.3,14 14,13.3556 14,12.5 L14,2.61111 C14,1.75556 13.3,1.05556 12.4444,1.05556 Z M12.4444,12.5 L1.55556,12.5 L1.55556,3.94444 L12.4444,3.94444 L12.4444,12.5 Z M8.55556,8.61111 L3.11111,8.61111 L3.11111,10.1667 L8.55556,10.1667 L8.55556,8.61111 Z"></path></svg></span>Horarios</th><th><span class="icon property-icon"><svg viewBox="0 0 14 14" style="width:14px;height:14px;display:block;fill:rgba(55, 53, 47, 0.45);flex-shrink:0;-webkit-backface-visibility:hidden" class="typesRelation"><polygon points="4.5 1 4.5 3 9.586 3 1 11.586 2.414 13 11 4.414 11 9.5 13 9.5 13 1"></polygon></svg></span>Participantes</th><th><span class="icon property-icon"><svg viewBox="0 0 14 14" style="width:14px;height:14px;display:block;fill:rgba(55, 53, 47, 0.45);flex-shrink:0;-webkit-backface-visibility:hidden" class="typesText"><path d="M7,4.56818 C7,4.29204 6.77614,4.06818 6.5,4.06818 L0.5,4.06818 C0.223858,4.06818 0,4.29204 0,4.56818 L0,5.61364 C0,5.88978 0.223858,6.11364 0.5,6.11364 L6.5,6.11364 C6.77614,6.11364 7,5.88978 7,5.61364 L7,4.56818 Z M0.5,1 C0.223858,1 0,1.223858 0,1.5 L0,2.54545 C0,2.8216 0.223858,3.04545 0.5,3.04545 L12.5,3.04545 C12.7761,3.04545 13,2.8216 13,2.54545 L13,1.5 C13,1.223858 12.7761,1 12.5,1 L0.5,1 Z M0,8.68182 C0,8.95796 0.223858,9.18182 0.5,9.18182 L11.5,9.18182 C11.7761,9.18182 12,8.95796 12,8.68182 L12,7.63636 C12,7.36022 11.7761,7.13636 11.5,7.13636 L0.5,7.13636 C0.223858,7.13636 0,7.36022 0,7.63636 L0,8.68182 Z M0,11.75 C0,12.0261 0.223858,12.25 0.5,12.25 L9.5,12.25 C9.77614,12.25 10,12.0261 10,11.75 L10,10.70455 C10,10.4284 9.77614,10.20455 9.5,10.20455 L0.5,10.20455 C0.223858,10.20455 0,10.4284 0,10.70455 L0,11.75 Z"></path></svg></span>Resumo do encontro</th></tr></thead><tbody><tr id="deef7d56-436a-4ada-926c-d30f25a14456"><td class="cell-title"><a href="Hackaton%20StartSe%20ff0374d3787c4d1db49e819c5fa12b32/Data%20d55b36b441ae43a3b6c9b724abfc1d23/Reunio%CC%83es%20c548e542ff9241c1aa6b34359301aee4/Explicando%20func%CC%A7a%CC%83o%20de%20manager%20deef7d56436a4ada926cd30f25a14456.html">Explicando função de manager</a></td><td class="cell-B^\x"><span class="selected-value select-value-color-pink">Help tools</span></td><td class="cell-tepZ"><div class="checkbox checkbox-on"></div></td><td class="cell-|{@J"><time>@24/07/2022 7:00 PM-7:30 PM</time></td><td class="cell-[;am"><a href="Hackaton%20StartSe%20ff0374d3787c4d1db49e819c5fa12b32/Data%20d55b36b441ae43a3b6c9b724abfc1d23/Equipe%20416c80c198d74e7385d7c380cd4b05c3/Josue%CC%81%20B%20Almeida%20cf94eb5142984a54a300150d23317222.html">Josué B. Almeida</a>, <a href="Hackaton%20StartSe%20ff0374d3787c4d1db49e819c5fa12b32/Data%20d55b36b441ae43a3b6c9b724abfc1d23/Equipe%20416c80c198d74e7385d7c380cd4b05c3/Aline%20e1cb3a1c9d214486b0206deedd4af655.html">Aline</a></td><td class="cell-i=LZ">Testamos algumas funções do notion e conversamos sobre alguns planos para elaborar o problema. </td></tr><tr id="1a6f7d6a-ba6d-4f61-bbeb-399156ebaa95"><td class="cell-title"><a href="Hackaton%20StartSe%20ff0374d3787c4d1db49e819c5fa12b32/Data%20d55b36b441ae43a3b6c9b724abfc1d23/Reunio%CC%83es%20c548e542ff9241c1aa6b34359301aee4/Explicando%20o%20conteu%CC%81do%20que%20ja%CC%81%20temos%201a6f7d6aba6d4f61bbeb399156ebaa95.html">Explicando o conteúdo que já temos</a></td><td class="cell-B^\x"><span class="selected-value select-value-color-purple">Comunicação</span></td><td class="cell-tepZ"><div class="checkbox checkbox-on"></div></td><td class="cell-|{@J"><time>@25/07/2022 7:00 PM-7:30 PM</time></td><td class="cell-[;am"><a href="Hackaton%20StartSe%20ff0374d3787c4d1db49e819c5fa12b32/Data%20d55b36b441ae43a3b6c9b724abfc1d23/Equipe%20416c80c198d74e7385d7c380cd4b05c3/Josue%CC%81%20B%20Almeida%20cf94eb5142984a54a300150d23317222.html">Josué B. Almeida</a>, <a href="Hackaton%20StartSe%20ff0374d3787c4d1db49e819c5fa12b32/Data%20d55b36b441ae43a3b6c9b724abfc1d23/Equipe%20416c80c198d74e7385d7c380cd4b05c3/Daniel%20DIas%2082923aaf40b84889b131ea15e2b956c6.html">Daniel DIas</a></td><td class="cell-i=LZ">Mostrei o conteúdo que juntei e pedi o feedback para eventuais ajustes, somas, exclusões ou inclusões.</td></tr><tr id="34258217-f277-4e43-854e-737b668ed1a0"><td class="cell-title"><a href="Hackaton%20StartSe%20ff0374d3787c4d1db49e819c5fa12b32/Data%20d55b36b441ae43a3b6c9b724abfc1d23/Reunio%CC%83es%20c548e542ff9241c1aa6b34359301aee4/Explicando%20etapas%20em%20andamento%2034258217f2774e43854e737b668ed1a0.html">Explicando etapas em andamento</a></td><td class="cell-B^\x"><span class="selected-value select-value-color-purple">Comunicação</span></td><td class="cell-tepZ"><div class="checkbox checkbox-on"></div></td><td class="cell-|{@J"><time>@25/07/2022 8:35 PM-8:58 PM</time></td><td class="cell-[;am"><a href="Hackaton%20StartSe%20ff0374d3787c4d1db49e819c5fa12b32/Data%20d55b36b441ae43a3b6c9b724abfc1d23/Equipe%20416c80c198d74e7385d7c380cd4b05c3/Josue%CC%81%20B%20Almeida%20cf94eb5142984a54a300150d23317222.html">Josué B. Almeida</a>, <a href="Hackaton%20StartSe%20ff0374d3787c4d1db49e819c5fa12b32/Data%20d55b36b441ae43a3b6c9b724abfc1d23/Equipe%20416c80c198d74e7385d7c380cd4b05c3/Bruno%203c377324755a425a8f34152986aab9e7.html">Bruno</a></td><td class="cell-i=LZ">Conversamos sobre as etapas em andamento. Bruno ficou de dar o feedback e ler o material de apoio.</td></tr><tr id="db03f96b-2777-48f4-b144-ef644a584f26"><td class="cell-title"><a href="Hackaton%20StartSe%20ff0374d3787c4d1db49e819c5fa12b32/Data%20d55b36b441ae43a3b6c9b724abfc1d23/Reunio%CC%83es%20c548e542ff9241c1aa6b34359301aee4/Alinhando%20ideia%20do%20projeto%20e%20fazendo%20proto%CC%81tipo%20de%20db03f96b277748f4b144ef644a584f26.html">Alinhando ideia do projeto e fazendo protótipo de páginas</a></td><td class="cell-B^\x"><span class="selected-value select-value-color-blue">Ação</span><span class="selected-value select-value-color-green">Brainstrom</span></td><td class="cell-tepZ"><div class="checkbox checkbox-on"></div></td><td class="cell-|{@J"><time>@26/07/2022 7:26 PM → 27/07/2022 12:21 PM</time></td><td class="cell-[;am"><a href="Hackaton%20StartSe%20ff0374d3787c4d1db49e819c5fa12b32/Data%20d55b36b441ae43a3b6c9b724abfc1d23/Equipe%20416c80c198d74e7385d7c380cd4b05c3/Josue%CC%81%20B%20Almeida%20cf94eb5142984a54a300150d23317222.html">Josué B. Almeida</a>, <a href="Hackaton%20StartSe%20ff0374d3787c4d1db49e819c5fa12b32/Data%20d55b36b441ae43a3b6c9b724abfc1d23/Equipe%20416c80c198d74e7385d7c380cd4b05c3/Erick%201efa9f31041f4a31a8ec582804ecd808.html">Erick </a>, <a href="Hackaton%20StartSe%20ff0374d3787c4d1db49e819c5fa12b32/Data%20d55b36b441ae43a3b6c9b724abfc1d23/Equipe%20416c80c198d74e7385d7c380cd4b05c3/Daniel%20DIas%2082923aaf40b84889b131ea15e2b956c6.html">Daniel DIas</a>, <a href="Hackaton%20StartSe%20ff0374d3787c4d1db49e819c5fa12b32/Data%20d55b36b441ae43a3b6c9b724abfc1d23/Equipe%20416c80c198d74e7385d7c380cd4b05c3/Aline%20e1cb3a1c9d214486b0206deedd4af655.html">Aline</a></td><td class="cell-i=LZ">Criamos modelos de 3 páginas e faltam mais 3. Também pensamos algumas features futuras e Aline ficou de finalizara logo.</td></tr><tr id="e17d962b-705d-4782-874f-0d2e7440c164"><td class="cell-title"><a href="Hackaton%20StartSe%20ff0374d3787c4d1db49e819c5fa12b32/Data%20d55b36b441ae43a3b6c9b724abfc1d23/Reunio%CC%83es%20c548e542ff9241c1aa6b34359301aee4/Mentoria%20produto%20negocio%20e17d962b705d4782874f0d2e7440c164.html">Mentoria produto/negocio</a></td><td class="cell-B^\x"><span class="selected-value select-value-color-default">MENTORIA</span></td><td class="cell-tepZ"><div class="checkbox checkbox-on"></div></td><td class="cell-|{@J"><time>@28/07/2022 6:00 PM-6:00 PM</time></td><td class="cell-[;am"><a href="Hackaton%20StartSe%20ff0374d3787c4d1db49e819c5fa12b32/Data%20d55b36b441ae43a3b6c9b724abfc1d23/Equipe%20416c80c198d74e7385d7c380cd4b05c3/Josue%CC%81%20B%20Almeida%20cf94eb5142984a54a300150d23317222.html">Josué B. Almeida</a>, <a href="Hackaton%20StartSe%20ff0374d3787c4d1db49e819c5fa12b32/Data%20d55b36b441ae43a3b6c9b724abfc1d23/Equipe%20416c80c198d74e7385d7c380cd4b05c3/Aline%20e1cb3a1c9d214486b0206deedd4af655.html">Aline</a></td><td class="cell-i=LZ"><a href="https://teams.microsoft.com/dl/launcher/launcher.html?url=%2F_%23%2Fl%2Fmeetup-join%2F19%3Ameeting_NTgxNzI5MzQtMTY5OS00YmQ1LWFkZGEtZThkMjkxNTBlMzRi%40thread.v2%2F0%3Fcontext%3D%257b%2522Tid%2522%253a%25225ae55f19-9733-4cc8-aa1d-a3f2e5ba9d93%2522%252c%2522Oid%2522%253a%2522bf4df233-1456-4268-812f-9983646d66c3%2522%257d%26webjoin%3Dtrue%26unified%3Dtrue%26anon%3Dtrue&amp;type=meetup-join&amp;deeplinkId=0a96714c-51f4-499d-b157-08cb6be7a423&amp;directDl=true&amp;msLaunch=true&amp;enableMobilePage=true">Link da reunião</a> com Matheus Migalha (Projeto)</td></tr><tr id="da25ab0a-31cd-43c0-937d-a00cd4e9b2a2"><td class="cell-title"><a href="Hackaton%20StartSe%20ff0374d3787c4d1db49e819c5fa12b32/Data%20d55b36b441ae43a3b6c9b724abfc1d23/Reunio%CC%83es%20c548e542ff9241c1aa6b34359301aee4/Mentoria%20produto%20negocio%20da25ab0a31cd43c0937da00cd4e9b2a2.html">Mentoria produto/negocio</a></td><td class="cell-B^\x"><span class="selected-value select-value-color-default">MENTORIA</span></td><td class="cell-tepZ"><div class="checkbox checkbox-on"></div></td><td class="cell-|{@J"><time>@28/07/2022 5:37 PM-5:37 PM</time></td><td class="cell-[;am"><a href="Hackaton%20StartSe%20ff0374d3787c4d1db49e819c5fa12b32/Data%20d55b36b441ae43a3b6c9b724abfc1d23/Equipe%20416c80c198d74e7385d7c380cd4b05c3/Josue%CC%81%20B%20Almeida%20cf94eb5142984a54a300150d23317222.html">Josué B. Almeida</a></td><td class="cell-i=LZ"><a href="https://teams.microsoft.com/dl/launcher/launcher.html?url=%2F_%23%2Fl%2Fmeetup-join%2F19%3Ameeting_NTgxNzI5MzQtMTY5OS00YmQ1LWFkZGEtZThkMjkxNTBlMzRi%40thread.v2%2F0%3Fcontext%3D%257b%2522Tid%2522%253a%25225ae55f19-9733-4cc8-aa1d-a3f2e5ba9d93%2522%252c%2522Oid%2522%253a%2522bf4df233-1456-4268-812f-9983646d66c3%2522%257d%26webjoin%3Dtrue%26unified%3Dtrue%26anon%3Dtrue&amp;type=meetup-join&amp;deeplinkId=0a96714c-51f4-499d-b157-08cb6be7a423&amp;directDl=true&amp;msLaunch=true&amp;enableMobilePage=true">Link da reunião</a> com Matheus Migalha (Projeto)</td></tr></tbody></table></div><h3 id="d548e06a-36ee-49c4-98a0-8ecdb59d6307" class=""><details close=""><summary><mark class="highlight-gray">Link</mark> para marcar mentorias com a <mark class="highlight-blue">Start</mark>Se</summary></details></h3><div class="indented"><figure id="d4edc956-1209-457b-b4c1-93a92219fa2e"><a href="https://outlook.office365.com/owa/calendar/TechAcademy1@startse.com.br/bookings/" class="bookmark source"><div class="bookmark-info"><div class="bookmark-text"><div class="bookmark-title">Tech Academy - Você pode agendar online!</div><div class="bookmark-description">Agora você pode agendar e gerenciar compromissos usando nossa página de reserva.</div></div><div class="bookmark-href"><img src="https://outlook.office365.com/favicon.ico" class="icon bookmark-icon"/>https://outlook.office365.com/owa/calendar/TechAcademy1@startse.com.br/bookings/</div></div></a></figure><figure id="7552f635-e614-4a7b-961a-cf8d8e74df76" class="link-to-page"><a href="Hackaton%20StartSe%20ff0374d3787c4d1db49e819c5fa12b32/1%C2%B0%20Mentoria%207552f635e6144a7b961acf8d8e74df76.html">1° Mentoria</a></figure></div></div><h3 id="b51653b5-6c10-4dce-98cc-d634446a8f95" class=""><details close=""><summary>Ferramentas :</summary></details></h3><div class="indented"><ul id="b6a12e88-5db9-4e91-b319-1d60f97d4c15" class="toggle"><li><details close=""><summary>Projetos para inspiração ou uso</summary><figure id="1cfd0217-f7e0-4068-b1af-e8856aa9778e"><a href="https://wordwall.net/" class="bookmark source"><div class="bookmark-info"><div class="bookmark-text"><div class="bookmark-title">Wordwall - Create better lessons quicker</div><div class="bookmark-description">Need a fresh teaching resource that fits your class and teaching style? Create a customized pack of interactive and printable activities in just one minute.</div></div><div class="bookmark-href"><img src="https://az779572.vo.msecnd.net/res/content/images/favicon.ico|1evmh0qrg1aqcgft8tddfea2.ico" class="icon bookmark-icon"/>https://wordwall.net/</div></div><img src="http://az779572.vo.msecnd.net/res/content/images/homepage/close-graph.png|1fplfla-ukiy5gtfwljuitw2.png" class="bookmark-image"/></a></figure><figure id="09f23798-d650-476b-ab11-3f9e9fe2bec4"><a href="https://habitica.com/" class="bookmark source"><div class="bookmark-info"><div class="bookmark-text"><div class="bookmark-title">Habitica - Gamify Your Life</div><div class="bookmark-description">Habitica is a free habit and productivity app that treats your real life like a game. Habitica can help you achieve your goals to become healthy and happy.</div></div><div class="bookmark-href"><img src="https://habitica.com/static/icons/favicon_192x192.png" class="icon bookmark-icon"/>https://habitica.com/</div></div><img src="https://habitica.com/static/emails/images/meta-image.png" class="bookmark-image"/></a></figure><figure id="5fd1fabc-fad9-4531-9d4d-2b5b7b257c57"><a href="https://www.beecrowd.com.br/judge/en/login" class="bookmark source"><div class="bookmark-info"><div class="bookmark-text"><div class="bookmark-title"></div></div><div class="bookmark-href">https://www.beecrowd.com.br/judge/en/login</div></div></a></figure></details></li></ul><ul id="be0c0ba4-241c-4fbb-9be7-90a99792f603" class="toggle"><li><details close=""><summary>Para criar protótipos</summary><h3 id="89f9d717-c216-4e99-beea-9955d236b65e" class="">Paleta de cores escolhida</h3><figure id="7afb8651-074a-459b-9506-09939456812f"><a href="https://coolors.co/" class="bookmark source"><div class="bookmark-info"><div class="bookmark-text"><div class="bookmark-title">Coolors - The super fast color palettes generator!</div><div class="bookmark-description">Generate or browse beautiful color combinations for your designs.</div></div><div class="bookmark-href"><img src="https://coolors.co/assets/img/favicon.png" class="icon bookmark-icon"/>https://coolors.co/</div></div><img src="https://coolors.co/assets/img/og_image.png" class="bookmark-image"/></a></figure><figure id="ecca89fd-98ce-47a0-8c87-7487b1d971da"><a href="https://uigradients.com/#AquaMarine" class="bookmark source"><div class="bookmark-info"><div class="bookmark-text"><div class="bookmark-title">uiGradients - Beautiful colored gradients</div><div class="bookmark-description">uiGradients is a handpicked collection of beautiful color gradients for designers and developers.</div></div><div class="bookmark-href"><img src="https://uigradients.com/static/images/favicon-16x16.png" class="icon bookmark-icon"/>https://uigradients.com/#AquaMarine</div></div><img src="http://uigradients.com/static/images/uigradients.jpg" class="bookmark-image"/></a></figure><figure id="bc6845c2-86be-437c-a67b-68c92b525559"><a href="https://codepen.io/pen/" class="bookmark source"><div class="bookmark-info"><div class="bookmark-text"><div class="bookmark-title">Create a New Pen</div><div class="bookmark-description">Add External Stylesheets/Pens Any URL&#x27;s added here will be added as s in order, and before the CSS in the editor. You can use the CSS from another Pen by using it&#x27;s URL and the proper URL extention. JavaScript Preprocessor Babel includes JSX processing.</div></div><div class="bookmark-href"><img src="https://cpwebassets.codepen.io/assets/favicon/favicon-aec34940fbc1a6e787974dcd360f2c6b63348d4b1f4e06c77743096d55480f33.ico" class="icon bookmark-icon"/>https://codepen.io/pen/</div></div></a></figure><figure id="63bfabfb-0bac-4cc1-a8c2-96db07644f6f"><a href="https://www.figma.com/" class="bookmark source"><div class="bookmark-info"><div class="bookmark-text"><div class="bookmark-title">Figma: the collaborative interface design tool.</div><div class="bookmark-description">Figma connects everyone in the design process so teams can deliver better products, faster. Try Figma for free Join other industry-leading organizations pushing boundaries and solving problems in Figma</div></div><div class="bookmark-href"><img src="https://static.figma.com/app/icon/1/favicon.ico" class="icon bookmark-icon"/>https://www.figma.com/</div></div><img src="https://cdn.sanity.io/images/599r6htc/localized/0ee4e52ec34a1aef92e1b2bb7e29820685083b3e-2400x1260.png?w=1200&amp;q=70&amp;fit=max&amp;auto=format" class="bookmark-image"/></a></figure><figure id="5f5f096c-5edf-43bb-bd59-194eeb789797"><a href="https://app.diagrams.net/" class="bookmark source"><div class="bookmark-info"><div class="bookmark-text"><div class="bookmark-title">Flowchart Maker &amp; Online Diagram Software</div><div class="bookmark-description">diagrams.net (formerly draw.io) is free online diagram software. You can use it as a flowchart maker, network diagram software, to create UML online, as an ER diagram tool, to design database schema, to build BPMN online, as a circuit diagram maker, and more. draw.io can import .vsdx, Gliffy™ and Lucidchart™ files .</div></div><div class="bookmark-href"><img src="https://app.diagrams.net/favicon.ico" class="icon bookmark-icon"/>https://app.diagrams.net/</div></div></a></figure><figure id="3da9a8ab-9fda-49cd-afaf-9cad3949660e"><a href="https://miro.com/pt/" class="bookmark source"><div class="bookmark-info"><div class="bookmark-text"><div class="bookmark-title">A Plataforma de Colaboração Visual para Todas as Equipes | Miro</div><div class="bookmark-description">Nossas integrações com as ferramentas mais populares e confiáveis de hoje como Dropbox, Box, Google Suite, JIRA, Slack e Sketch, conectam-se perfeitamente com o seu fluxo de trabalho existente, dentro da nossa infinita lousa digital online.</div></div><div class="bookmark-href"><img src="https://static-website.miro.com/miro-site-lp-build-assets/assets/favicon.ico" class="icon bookmark-icon"/>https://miro.com/pt/</div></div><img src="https://images.ctfassets.net/w6r2i5d8q73s/OxZ08hm5k2id0kjQXmc0L/05bcc2743945b82009e59aa5d9c77c7d/miro.png" class="bookmark-image"/></a></figure></details></li></ul><p id="c3f14234-c0e4-43ca-8ae8-9bedf0603352" class="">
</p></div><h3 id="35f79ae1-0ca8-4c3a-977a-b0d880771291" class=""><details close=""><summary>Help</summary></details></h3><div class="indented"><ul id="0ca71c16-4484-4a88-ac45-9c63d01147d6" class="toggle"><li><details close=""><summary>Documentação complementar</summary><h3 id="2590190e-ed69-4c00-b922-e0023fe5aece" class="">Pitch</h3><figure id="5a87baa3-d76a-46b6-a97b-927da96e15ab"><a href="https://endeavor.org.br/dinheiro/como-elaborar-um-pitch-quase-perfeito/" class="bookmark source"><div class="bookmark-info"><div class="bookmark-text"><div class="bookmark-title">Como Elaborar um Pitch (quase) Perfeito | Endeavor Brasil</div><div class="bookmark-description">Cinco slides eficientes para você se basear quando se apresentar para uma investidora, investidor ou cliente. Saiba como elaborar um pitch perfeito. Cassio Spina Cassio A. Spina foi empreendedor por 25 anos, e atualmente é Investidor-Anjo. É o fundador da Anjos do Brasil e autor do livro &quot;Investidor-Anjo - Guia Prático para Empreendedores e Investidores&quot;.</div></div><div class="bookmark-href"><img src="https://endeavor.org.br/wp-content/themes/endeavor/favicon/favicon.ico" class="icon bookmark-icon"/>https://endeavor.org.br/dinheiro/como-elaborar-um-pitch-quase-perfeito/</div></div><img src="https://images.endeavor.org.br/uploads/2012/08/24132504/pitch-735x336.png" class="bookmark-image"/></a></figure><figure id="de9f87b8-86a2-4f68-b511-9e4f3cb573b9" class="link-to-page"><a href="Hackaton%20StartSe%20ff0374d3787c4d1db49e819c5fa12b32/Como%20Fazer%20um%20Pitch%20de%20Excele%CC%82ncia%20Na%20Pra%CC%81tica%20e%20E%20de9f87b886a24f68b5119e4f3cb573b9.html">Como Fazer um Pitch de Excelência | Na Prática e Exame</a></figure><figure id="9455e696-1b7a-47eb-b630-a60cd19f3c7a" class="link-to-page"><a href="Hackaton%20StartSe%20ff0374d3787c4d1db49e819c5fa12b32/Como%20GANHEI%20o%20Pitch%20Day%20do%20Google%20%F0%9F%9A%80%20Exemplo%20de%20Pit%209455e6961b7a47ebb630a60cd19f3c7a.html">Como GANHEI o Pitch Day do Google 🚀 Exemplo de Pitch</a></figure></details></li></ul><ul id="89fbb0a2-d127-44cc-8bd6-53917df5cf34" class="toggle"><li><details close=""><summary>Tutoriais complementares</summary><h3 id="f1d4c6ae-f327-45c7-ab96-92725e2855bc" class="">Figma</h3><figure id="4bf0fe37-34e9-4e89-a5df-80d4ebd2da35"><a href="https://www.youtube.com/watch?v=vg-INqhKD5c" class="bookmark source"><div class="bookmark-info"><div class="bookmark-text"><div class="bookmark-title">Tutorial Completo de FIGMA - Ferramenta GRÁTIS para Design de Interfaces</div><div class="bookmark-description">Eu criei um curso completo que ensina UX/UI do ZERO para qualquer tipo de pessoa, aprenda como você pode se tornar UX/UI Designer e ganhar um salário a parti...</div></div><div class="bookmark-href"><img src="https://www.youtube.com/s/desktop/ad3ffe7b/img/favicon.ico" class="icon bookmark-icon"/>https://www.youtube.com/watch?v=vg-INqhKD5c</div></div><img src="https://i.ytimg.com/vi/vg-INqhKD5c/hqdefault.jpg" class="bookmark-image"/></a></figure><figure id="70940524-c5ac-40e8-8121-0f1356e85e1c"><a href="https://www.youtube.com/watch?v=oE_08KTRA9w" class="bookmark source"><div class="bookmark-info"><div class="bookmark-text"><div class="bookmark-title">Como Usar o Figma - Tutorial Completo para Iniciantes + Dicas Bônus</div><div class="bookmark-description">Aprenda como usar o Figma, ferramenta de prototipagem e criação de layouts para UI/UX designers.#figma #uidesign #uxdesign🔗 RecursosFigma https://www.figma....</div></div><div class="bookmark-href"><img src="https://www.youtube.com/s/desktop/ad3ffe7b/img/favicon.ico" class="icon bookmark-icon"/>https://www.youtube.com/watch?v=oE_08KTRA9w</div></div><img src="https://i.ytimg.com/vi/oE_08KTRA9w/hqdefault.jpg" class="bookmark-image"/></a></figure><figure id="07d4ba9f-b730-4af1-ab18-0009d615f67b"><a href="https://www.youtube.com/watch?v=l2b4q38qt-I" class="bookmark source"><div class="bookmark-info"><div class="bookmark-text"><div class="bookmark-title">UI Design - Figma: Criando uma tela de cadastro em 20 minutos</div><div class="bookmark-description">Inscreva-se no canal!Siga @fischerafael no Instagram</div></div><div class="bookmark-href"><img src="https://www.youtube.com/s/desktop/ad3ffe7b/img/favicon.ico" class="icon bookmark-icon"/>https://www.youtube.com/watch?v=l2b4q38qt-I</div></div><img src="https://i.ytimg.com/vi/l2b4q38qt-I/hqdefault.jpg" class="bookmark-image"/></a></figure><p id="07ba3975-9e8b-47ef-aa2b-69f7b30a34ae" class="">
</p></details></li></ul></div><p id="0aba1c8a-6394-4559-8bfd-8da2d69861da" class="">
</p></div></article></body></html>
