<template>
	<div class="wrapper">
		<Header></Header>
		<Nav></Nav>
		<Banner></Banner>
		<Main></Main>
		<Footer></Footer>
	</div>
</template>

<script>
import Header from './Header'
import Nav from './Nav'
import Banner from './Banner'
import Main from './Main'
import Footer from './Footer'

export default {
  name: 'Index',
  components: {
    'Header': Header,
    'Nav': Nav,
    'Banner': Banner,
    'Main': Main,
    'Footer': Footer,
  }
}
</script>

<style>
html {
  font-family: sans-serif;
  -webkit-text-size-adjust: 100%;
      -ms-text-size-adjust: 100%;
}
body {
  font-size: 14px;
  color: #333;
  min-width: 320px;
  margin: 0;
}
article,aside,details,figcaption,figure,footer,header,hgroup,main,menu,nav,section,summary {
  display: block;
}
li {
	list-style-type: none;
}
ol, ul {
    margin-top: 0;
    margin-bottom: 0;
}
a,a:link,a:visited,a:hover,a:focus,a:active {
	text-decoration: none;
}
address, cite, dfn, em, i, var {
    font-style: normal;
}
h1,h2,h3,h4,h5,h6{font-size:100%;font-weight:normal}
input,textarea{outline:none;border: none;}
.btn-group-vertical>.btn-group:after, .btn-group-vertical>.btn-group:before, .btn-toolbar:after, .btn-toolbar:before, .clearfix:after, .clearfix:before, .container-fluid:after, .container-fluid:before, .container:after, .container:before, .dl-horizontal dd:after, .dl-horizontal dd:before, .form-horizontal .form-group:after, .form-horizontal .form-group:before, .modal-footer:after, .modal-footer:before, .modal-header:after, .modal-header:before, .nav:after, .nav:before, .navbar-collapse:after, .navbar-collapse:before, .navbar-header:after, .navbar-header:before, .navbar:after, .navbar:before, .pager:after, .pager:before, .panel-body:after, .panel-body:before, .row:after, .row:before {
    display: table;
    content: " ";
}
.btn-group-vertical>.btn-group:after, .btn-toolbar:after, .clearfix:after, .container-fluid:after, .container:after, .dl-horizontal dd:after, .form-horizontal .form-group:after, .modal-footer:after, .modal-header:after, .nav:after, .navbar-collapse:after, .navbar-header:after, .navbar:after, .pager:after, .panel-body:after, .row:after {
    clear: both;
}
.fl {
	float: left;
}
.fr {
	float: right;
}
.clearfix {
    clear: both;
}
@media only screen and (max-width: 575px) {
	.container {
		width: 100%;
	}
	.header-top,
	.header-con-logo,
	.header-con-info,
	.banner-right {
		display: none;
	}
}
</style>