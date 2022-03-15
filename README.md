<!DOCTYPE html>
<html lang="ko">
<head>
<meta charset="UTF-8">
<title>응애</title>
<style>
   ul { list-style:none; }
	 li {
		 display:inline-block;
		 margin:10px;
	  }
		li a {
			padding: 5px 20px;
			font-size: 14px;
			color: blue;
			text-decoration: none;
		}
		.flat {
      background:#eee;
      border:1px solid #222;
		}
		a[class ~=button] {           
      box-shadow:rgba(0,0,0,0.5) 4px 4px; /* 그림자 지정 */
      border-radius: 5px;  /* 테두리를 둥글게 */
      border:1px solid #222;
		}
</style>
</head>
<body>
	<ul>
		<li><a href="#" class="flat">메뉴 1</a></li>
		<li><a href="#" class="flat">메뉴 2</a></li>
		<li><a href="#" class="button">메뉴 응</a></li>
		<li><a href="#" class="flat button" >메뉴 애</a></li>
	</ul>
  </body>
 </html>
