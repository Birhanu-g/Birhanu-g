<?php
session_start();
?>
<!DOCTYPE html>
<html xmlns="http://www.w3.org/1999/xhtml">
	<head>
	
	  <div class="alert alert-info">
      <button type="button" class="close" data-dismiss="alert">&times;</button>
      <center>WELCOME TO LOGIN PAGE.</center>
                </div>
<meta charset="UTF-8">
<title>OJPS</title>
			 <link rel="stylesheet" href="css/alert.css">
			 <link rel="stylesheet" href="css/style.css">
    		 <link href="css/responsive.css" rel="stylesheet">
			 <link href="css/main.css" rel="stylesheet">
			 <link href="css/font-awesome.min.css" rel="stylesheet">
             <link rel="stylesheet" href="css/sty2log.css">
             <link href="css/animate.min.css" rel="stylesheet">
             <link href="css/prettyPhoto.css" rel="stylesheet">
		     <link href="css/bootstrap.min.css" rel="stylesheet">
			 <link rel="shortcut icon" href="images/amharicicon.png" type="image/x-icon" />
			 <link href="stylesheet.css" rel="stylesheet" type="text/css" />
			<script>
function change(){
var element = document.getElementById("loginE");
var element2 = document.getElementById("forgotpassword");
element.innerHTML = "You Entered Invalid UserName or Password. Please try Again!";
element2.innerHTML = "<a href = 'forgotpassword.php'>Forgot your password ?</a>";
		}
                    </script>
			
<script>
function changes(){
var element = document.getElementById("loginE");
element.innerHTML = "Your are not approved";
		}
	</script>
	
<style type="text/css">
.reg_form{
width:1200px;
margin:10px 10px 10px auto;
position:absolute;
right:-10%;
}
body {
margin: 0;
padding: 0;
line-height: 1.5em;
/*font-family: Tahoma, Geneva, sans-serif;*/
font-family: Georgia, "Times New Roman", Times, serif;
font-size: 14px;
color: blue;
background-color: #90857c;
background-repeat: repeat-x;
background-position: top;
}


.con{
width:970px;
height:850px;
margin:1px auto;
padding:0px;
border:1px solid #ccc;
background-image:url('img/gold.jpg');
}

a:link, a:visited { color: #073475; text-decoration: none; font-weight: normal; } 
a:active, a:hover { color: #073475; text-decoration: underline; }

h3 {
color: #b12213;
font-size: 16px;
font-weight: bold;
}
h2{
color: #B35900;
}
p { margin: 0px; padding: 0px; }
b {color: blue;}
img { margin: 0px; padding: 0px; border: none; }
.cleaner { clear: both; width: 100%; height: 0px; font-size: 0px;  }
.cleaner_h30 { clear: both; width:100%; height: 30px; }
.cleaner_h40 { clear: both; width:100%; height: 40px; }
.float_l { float: left; }
.float_r { float: right; }
.margin_r20 { margin-right: 20px; }


#body_wrapper {

}

#wrapper {
	
}

/* header */
#header {
clear: both;
width:  890px;
height: 60px;
padding: 20px 40px
}
#header  #site_title {
float: left;
padding-top: 40px;
}
#header #site_title  p{
font-family: Georgia, "Times New Roman", Times, serif, nyala;
}
#site_title a {
font-size: 50pt;
color: #FFCC33;
font-style:italic;
font-weight: bold;
text-decoration: none;
}
#site_title span{
visibility:hidden;
}
#site_title a:hover {
font-weight: bold;	
text-decoration: none;
}
#site_title a span {
display: block;
margin-top: 5px;
font-size: 14px;
color: #fff;
font-weight: bold;
letter-spacing: 2px;
}

/* end of header */

/* menu */

#menu {
clear: both;
width: 970px;
height: 70px;
/*position:fixed;*/
}

#menu ul li a:active{
background-color:#FF9999;
}

#menu  li a:hover {
background-color: white;
border-radius: 3px;
}

#menu ul li a{
	padding: 0 20px;
}
#search_box {
	width: 970px;
	height: 35px;
	text-align: right;
}

#search_box form {
	margin: 0;
	padding: 5px 40px;
}

#search_box #input_field {
height: 20px;
width: 300px;
color: #000000;
font-size: 12px;
font-variant: normal;
line-height: normal;
border: 1px solid #CCCCCC;
background: #FFFFFF;
box-sizing:border-box;
border-radius:4px;
}

#search_box #submit_btn {
height: 24px;
width: 100px;
cursor: pointer;
font-size: 12px;
text-align: center;
vertical-align: bottom;
white-space: pre;
outline: none;
color:#666666;
border: 1px solid #CCCCCC;
background: #FFFFFF;
}

/* contetnt */
#content_wrapper {
clear: both;
padding: 0px;
position:relative; 
}

#content #content_middle {
width: 510px;
padding: 5px 20px 0px 20px;
background: url(images/content_middle.png) repeat-y;
}
#content_middle p {
text-align: justify;
}

.sidebar {
position:absolute;
width: 197px;
padding-right: 30px;
background: url(images/sidebar_middle.png) repeat-y;
}

.sidebar_bottom {
width: 200px;
height: 20px;
background: url(images/sidebar_bottom.png) no-repeat;
}
.sidebar .sidebar_box {
clear: both;
padding-bottom: 10px;
}
.sidebar_box h2 {
color: #b12213;
font-size: 16px;
padding-left: 25px;
font-weight: bold;
margin: 0 0 10px 10px;
}
.sidebar_box .sidebar_box_content {
padding: 15px;
background: url(images/sidebar_box_top.png) top repeat-x;
}

.sidebar_box .discount {
	margin: 5px 0 0 0;
	font-weight: bold;
}

.sidebar_box .discount span {
	color: #C00;
}

.left_sidebar_box .discount a {
	font-weight: bold;
	color: #000;
}

.sidebar_box .categories_list {
	margin: 0;
	padding: 0;
	list-style: none;
}

.categories_list li {
	padding: 0;
	margin: 0;
}

.categories_list li a {
	display: block;
	color: #201f1c;
	padding: 5px 0 5px 20px;
	background: url(images/list.png) center left no-repeat;
}
.categories_list li a:hover {
	color: #e37615;
	text-decoration: none;
}
.jobBox{
	float: center;
	width: 485px;
	padding: 5px;
	margin-bottom: 5px;
	border: 1px solid #CCC;
	text-align: justify;
	font-size:10pt;
	border-radius: 10pt;
}

.detail{
	float: right;
	border-radius: 4pt;
	color: white;
	font-style: bold;
}

.jobBox h4{
	margin: 5px 0px;
	}
	
.jobBox p{
	margin: 5px 0px;
	}
.jobBox h4 a{
	color: blue;
	text-align: justify;
	text-decoration: underline;
	}
	.product_box  {
	float: left;
	width: 223px;
	padding: 10px;
	margin-bottom: 20px;
	border: 1px solid #CCC;
	text-align: center;
	border-radius: 10pt;
	
}
.product_box h3 {
	color: #2a2522;
	font-size: 12px;
	margin: 0 0 10px;
	
}

/* end of content */

/* footer */

#footer_wrapper {
	
	
	/*height: 200px;*/
	
	
}

#footer {
	
	
}
#footer a {
	color: #A8A8B7;
	font-weight: normal;
}

#footer a:hover {
	text-decoration: none;
	color: #FFFF33;
	background-color:#686859;
	border-radius:3px;
}


#footer .footer_menu {
	margin: 0 0 30px 0;
	padding: 0px;
	list-style: none;
	color:blue;
	
}

.footer_menu li {
	margin: 0px;
	padding: 0 20px;
	display: inline;
	border-right: 1px solid #d7d1cc;
	
}


.footer_menu .last_menu {
	
	
}


/* STRUCTURE */



#content {
	width: 290px;
	float: left;
	padding: 5px 15px;
}



#content #content_top {
	width: 550px;
	height: 0px;
	background: url(images/content_top.png) no-repeat;
}

#sidebar {
	background: #f0efef;
}

.dat{
	width:200px;
	position:relative;
		right:-80%;
		
}

	</style>
<script>
function notice(x)
{
x.style.color="red";
}
function noticee(x)
{
x.style.color="black";
}
</script>
</head>
<body>
<div class="con">
<div id="body_wrapper">
<div id="wrapper">
<?php include('slider/gg.html');?>
<!-- end of header -->
	
 <div id="menu1">
 <nav class="navbar navbar-inverse" style="background-color:lightblue; role="banner" >
<div class="dat" >
<form>
<b style = ""><?php print date("l   F   Y");?></b> 
 </form>
 </div>
 
<div class="container">
<div class="navbar-header">
<button type="button" class="navbar-toggle" data-toggle="collapse" data-target=".navbar-collapse">
<span class="sr-only">Toggle navigation</span>
 <span class="icon-bar"></span>
 <span class="icon-bar"></span>
  <span class="icon-bar"></span>
    </button>
      </div>

	  
<div class="menu-bar">
<ul>
<li class="active"><a href="index.php"><i class="fa fa-home" aria-hidden="true"><font color="yellow"><strong>Home</strong></a></font></i></li> 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</ul>
</div>
</div><!--/.container-->
 </nav><!--/nav-->
</div> <!-- end of menu -->     
 <div class="reg_form">
<div id="content_wrapper">		  
<div id="content" >
<div id="content_top"></div>
<div id="content_middle" >
<div id = "registrationForm">
<div class="panel panel-warning">
<div class="panel-heading"><center><img src="img/1l.gif" width="120" height="150"><br>
</center></div>


<div class="panel-body">
<form class="form-horizontal"  method = "post" action = "<?php echo htmlspecialchars($_SERVER["PHP_SELF"]);?>">
<div class="form-group">
<label class="col-md-3 control-label" for="uName"><b>User Name</b></label>
<div class="col-md-9">
<div class="input-group">
<div class="input-group-addon">
<span class="glyphicon glyphicon-user"></span>
</div>


<input id="userName" name="userName" type="text" placeholder="Enter UserName Here" class = "form-control" required >
 </div>
</div>
</div>
			
			  <div class="form-group">
              <label class="col-md-3 control-label" for="password"><b>Password</b></label>
              <div class="col-md-9">
			  <div class="input-group">
			  <div class="input-group-addon">
			  <span class="glyphicon glyphicon-lock"></span>
			  </div>
			  
<input id="password" name="password" type="password" placeholder="Enter Your Password Here" pattern=".{4,}" title="Four or More characters"  class = "form-control" required >
</div>
</div>
</div>

			<div class="form-group">
			<label class="col-md-3 control-label" for="region"><b>Login As:</b></label>
			<div class="col-md-9">
			<div class="input-group">
			  <div class="input-group-addon">
			  <span class="glyphicon glyphicon"></span>
			  </div>
			<select name = "usertype" class="form-control" id="region" required>
						<option value="" ><b>Please Select User Type</b></option>	
		                <option value = "Admin"><b>Admininstrator</b></option>
                        <option value = "employer"><b>Employer</b></option>						
						<option value = "jobseeker"><b>Job seeker</b></option>
				

								<!--<option value = "staff">Staff</option> -->
						
							
			</select>
			</div>
			</div>
			</div>
			
			<td style="text-align: left"><p id = "loginE" style = "color:red;"></p></td>
			
			 <label for="reg" class="control-label col-md-3"></label>
<button class="btn btn-success" type = "submit" value = "Login" name = "sub" >Login</button>
    <label for"reset" class="control-label"> </label>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
	&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
	&nbsp;&nbsp;&nbsp;&nbsp;
     <button class="btn btn-danger" type="reset" id="reset"> Reset </button>	
	 <br><br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
	 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
	 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
	<!--<a href="forget.php"><button><font color="blue">Forgot Password?</font></button></a><br><br>&nbsp;&nbsp;&nbsp;&nbsp; -->
		 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
	 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<center><font color="gray"><b>Don't have an Account?</b></font></center>
	 
	 
	 <a href="registerJobseeker.php"><br>
	 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 
<center><img src="img/reg.png" width="100" height="60"></center>

<!-- <button><font color="green">Register</button></font></a> -->

					</form>
					</div>
				</div>
	<?php				
			if ($_SERVER["REQUEST_METHOD"] == "POST") {
				include("mysqlConnect.php");// connection page
				$Uname = $_POST["userName"];
				$Pass = $_POST["password"];
				$uType = $_POST["usertype"];
				if($uType == 'employer'){
				$result = mysql_query("select * from employer",$con);
				while($row = mysql_fetch_array($result))
					{
						//session_start();

						if($row["userName"] == $Uname && $row["password"] == $Pass){
							$email = $row["email"];
							$_SESSION['emId']= $row["emId"];
						$_SESSION['login_useremp']=$Uname; // Initializing Session
						$_SESSION['login_passemp']=$Pass; // Initializing Session
						$_SESSION['login_emailemp']=$email;
						$_SESSION["type"] = $row['usertype'];
						header("Location:employer.php?msg=success");
						//echo "<h1>congra</h1>";
					}
				else{
						echo '<script>
								change();
							</script>
							';
					}
				}	
				
				}
				else if($uType == 'jobseeker'){
				$result = mysql_query("select * from registerdjobseeker",$con);
				
				while($row = mysql_fetch_array($result))
					{
						//session_start();
						
						if($row["userName"] == $Uname && $row["password"] == $Pass){
							
						$email = $row["email"];
						$_SESSION['user_id'] = $row["user_id"];
						$_SESSION['login_userjs']=$Uname; // Initializing Session
						$_SESSION['login_passjs']=$Pass; // Initializing Session
						$_SESSION['login_emailjs']=$email;
						$_SESSION["type"] = $row['usertype'];
						header("Location:jobSeeker.php?msg=success");
						//echo "<h1>congra</h1>";
					}
				else{
						echo '<script>
								change();
							</script>
							';
					}
					}
				}
				
					else if($uType == 'Admin'){
				$result = mysql_query("select * from admin",$con);
				while($row = mysql_fetch_array($result))
					{
						$admId = $row["adminId"];
						$email = $row["email"];
						if($row["userName"] == $Uname && $row["password"] == $Pass){
						$_SESSION['login_user']=$Uname; // Initializing Session
						$_SESSION['login_pass']=$Pass; // Initializing Session
						$_SESSION['login_email']=$email;
						echo "<script>location.replace('login.php');</script>";
						header("Location:admin.php?id=$admId");
						//echo "<h1>congra</h1>";
					}
				else{
						echo '<script>
								change();
							</script>
							';
					}
				}	
				
				}
				else{ 
						echo '<script>
								change();
							</script>
							';	
							//echo "faild to login";
				}

			}
?>		
				</div></div>
					
                  <div class="cleaner"></div>
				  <br />
				  <br />
				  <br />

                        
                        <div class="cleaner"></div>
                    </div>
                    
                  <div class="cleaner"></div>
                                
                </div>
                <div id="content_bottom"></div>
           
            </div> 
                
   <div class="sidebar_wrapper float_r">
                <div class="sidebar_top"></div>
                <div class="sidebar">
                   
                           
                        </div> <!-- end of sidebar_box_content -->
                    </div> <!-- end of sidebar_box ( news ) -->
                   <!-- end of sidebar_box ( news ) -->
                    

               
            </div> <!-- end of sidebar_wrapper --> 
          <div class="cleaner"></div>
           
      </div> <!-- end of content_wrapper -->
        
    </div> <!-- end of wrapper -->
	    
    <div class="cleaner"></div>
</div> <!-- end of body_wrapper -->

<div id="footer_wrapper">

	<div id="footer">

        Copyright © 20<?php echo date("y");?> | 
        Designd by 
        <a href = "#">Computer Science Students</a>
        
    	<div class="cleaner"></div>
    </div> <!-- end of footer -->
</div> <!-- end of templatmeo_footer_wrapper -->

<script>
function change(){
	
	alert("Wrong UserName or Password");
}
</script>

</body>

</html>
