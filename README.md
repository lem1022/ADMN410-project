# ADMN410-project
ADMN 410 Project
body { 
  font: .875em/1.618 Calibri, Arial; 
}

p {
  font-size: 16px;
}
h1 {
      font-size: 24px;
      text-align:center;
      font-family:Cambria;
    }
    
h2 {
    font-size: 22px;
    text-align:left;
    font-family: Cambria;
}

h3 {
  font-size: 18px;
  text-align: center;
  font-family: Cambria;
  font-style: bold;
}

ul {
  font-size: 16px;
}
   
  /* insert  */   
table.center {
    margin-left:auto; 
    margin-right:auto;
}

td {
  text-align: center;
}

#navigation {
  background-color: #A9FCDA;
}
#navigation ul {
  margin: 10;
  padding: 0; 
}
#navigation li {
  border-right: 1px solid #ddd;
  display: block;
  float: left;
  margin: 5;
}
#navigation li:last-child {
  border-right-width: 0;
}
#navigation a {
  background-color: #A9FCDA;
  color: #000000;
  display: block;
  padding: .75em 1.5em;
  text-decoration: none;
  transition: all .25s ease-in-out;
  
}
#navigation a:hover {
  background-color: #ddd;
}

#banner {
    height: 147px;
    background: url("../images/banner.png");
    background-size:100% 100%;
    background-repeat: no-repeat;
}
#wrap {
      width: 1059px;
      margin: 0 auto;
      background-color: #e6fff2; }
      
#content {
      padding: 0 50px 50px;
      min-height:100%;
      
      }
#post {
    border:1px solid grey;
    margin: 5px;margin-bottom:15px;padding:8px;
}

#footer {
    border:1px solid grey;
    text-align:center;
	background-color: black;
	color:black;
	text-shadow:1px 1px 0 rgba(255,255,255,0.6);
}

table {
        width: 900px;
        alignment-baseline:  center;}
      th, td {
        padding: 7px 10px 10px 10px;}
      th {
        text-transform: uppercase;
        letter-spacing: 1px;
        font-size: 90%;
        border-bottom: 2px solid #B8B8B8;
        text-align: center;
      }

IMG.displayed {
    display: block;
    margin-left: auto;
    margin-right: auto;
    align: center;
    
}

ol {
  font-size: 16px;
}

.myButton {
	-moz-box-shadow: 3px 4px 0px 0px #899599;
	-webkit-box-shadow: 3px 4px 0px 0px #899599;
	box-shadow: 3px 4px 0px 0px #899599;
	background:-webkit-gradient(linear, left top, left bottom, color-stop(0.05, #a9fcd9), color-stop(1, #ebf0ee));
	background:-moz-linear-gradient(top, #a9fcd9 5%, #ebf0ee 100%);
	background:-webkit-linear-gradient(top, #a9fcd9 5%, #ebf0ee 100%);
	background:-o-linear-gradient(top, #a9fcd9 5%, #ebf0ee 100%);
	background:-ms-linear-gradient(top, #a9fcd9 5%, #ebf0ee 100%);
	background:linear-gradient(to bottom, #a9fcd9 5%, #ebf0ee 100%);
	filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#a9fcd9', endColorstr='#ebf0ee',GradientType=0);
	background-color:#a9fcd9;
	-moz-border-radius:15px;
	-webkit-border-radius:15px;
	border-radius:15px;
	border:2px solid #000000;
	display:inline-block;
	cursor:pointer;
	color:#000000;
	font-family:Calibi;
	font-size:20px;
	padding:12px 36px;
	text-decoration:none;
	text-shadow:0px 1px 0px #a9fcd9;
    margin-left: 450px;
    margin-right: 450px;
}
.myButton:hover {
	background:-webkit-gradient(linear, left top, left bottom, color-stop(0.05, #ebf0ee), color-stop(1, #a9fcd9));
	background:-moz-linear-gradient(top, #ebf0ee 5%, #a9fcd9 100%);
	background:-webkit-linear-gradient(top, #ebf0ee 5%, #a9fcd9 100%);
	background:-o-linear-gradient(top, #ebf0ee 5%, #a9fcd9 100%);
	background:-ms-linear-gradient(top, #ebf0ee 5%, #a9fcd9 100%);
	background:linear-gradient(to bottom, #ebf0ee 5%, #a9fcd9 100%);
	filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#ebf0ee', endColorstr='#a9fcd9',GradientType=0);
	background-color:#ebf0ee;
}
.myButton:active {
	position:relative;
	top:1px;
}
