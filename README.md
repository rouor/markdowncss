# markdown_here 插件 紫色主题的css
# 具体风格可查微信公众号：兔子公园

.markdown-here-wrapper {
  font-size: 15px;
  line-height: 1.55em;
  letter-spacing: 0.05em; 
  color:#595959
}


pre, code {
  font-size: 15px;
  font-family: Consolas, Inconsolata, Courier, monospace;
  margin: auto 5px;
}

code {
  white-space: pre-wrap;
  border-radius: 2px;
  display: inline;
}

pre {
  font-size: 15px;
  line-height: 1.4em;
  display: block; !important;
}

pre code {
  white-space: pre;
  overflow: auto;
  border-radius: 3px;
  padding: 1px 1px;
  display: block !important;
}

strong, b{color:#773098;}

hr {
  border: 1px solid #773098;
  margin: 1.5em auto;
}

p {
  margin: 1em 4px !important;
}

table, pre, dl, blockquote, q, ul, ol {
  margin: 10px 5px;
}

ul ul ol, ul ol ol, ol ul ol, ol ol ol {
    list-style-type: disc !important;
   
}

li {
  margin: 10px;
}

li p {
  margin: 10px 0 !important;
}

ul ul, ul ol, ol ul, ol ol {
  margin: 0;
  padding-left: 10px;
}

ul {
  list-style-type: square;
}

dl {
  padding: 0;
}

dl dt {
  font-size: 1em;
  font-weight: bold;
  font-style: italic;
}

dl dd {
  margin: 0 0 10px;
  padding: 0 10px;
}

blockquote, q {
  border-left: 5px solid #9654B5;
  border-right: 1px solid #9654B5;
  padding: 1px;
  color: #616161;
  quotes: none;
  margin-left: 0.7em; 
  margin-top: 3 px;
  background:#FBF9FD
}

blockquote::before, blockquote::after, q::before, q::after {
  content: none;
}

h1, h2, h3, h4, h5, h6 {
  margin: 1.2em 0 1em;
  padding: 0;
  font-weight: bold;
  font-color:#773098;
}


h1 {
  font-size: 22px;
}

h2 {
  min-height: 32px;
  line-height: 28px;
  border-bottom: solid 1px #000000;
  color: #773098;
  display: inline-block;
  border-bottom-width: 1px;
  border-bottom-style: solid;
  border-color: #773098;
  padding-top: 5px; 
  padding-right: 0.5em; 
  padding-left: 0.5em;
  margin-bottom: -3px;
  font-size: 18px;
  margin:1em auto;
  padding: 0.5em 0;
  text-align: center;
  width: 85%;
  font-weight: bold;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

h3 {
  font-size: 16px;
  padding-right: 0.5em; 
  padding-left: 0.5em;
}

h4 {
  font-size: 16px;
  padding-right: 0.5em; 
  padding-left: 0.5em;
}

h5 {
  font-size: 14px;
  padding-right: 0.5em; 
  padding-left: 0.5em;
}

h6 {
  font-size: 16px;
  color: #777;
  padding-right: 0.5em; 
  padding-left: 0.5em;
}

table {
  padding: 0;
  border-collapse: collapse;
  border-spacing: 0;
  font-size: 1em;
  font: inherit;
  border: 0;
}

tbody {
  margin: 0;
  padding: 0;
  border: 0;
}

table tr {
  border: 0;
  border-top: 1px solid #CCC;
  background-color: white;
  margin: 0;
  padding: 0;
}

table tr:nth-child(2n) {
  background-color: #F8F8F8;
}

table tr th, table tr td {
  font-size: 1em;
  border: 1px solid #CCC;
  margin: 0;
  padding: 0.5em 1em;
}

table tr th {
 font-weight: bold;
  background-color: #F0F0F0;
}

p {
  font-size: 15px;
  line-height: 1.75em;
  padding-right: 0.5em; 
  padding-left: 0.5em;
}

