# bitcom

<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
  <meta name="description" content="The blockchain and the tokenomics Created a diversified ecological system While also the important elements of the birth of BS system">
  <meta name="author" content="Creative Tim">
  <title>Bitcom Beta Ver 1.0</title>
  <meta name="keywords" content="Bitcom,BS Bitcom Shares,Exchange">
  <!-- Favicon -->
  <link href="./assets/img/brand/favicon.ico" rel="icon" type="image/png">
  <!-- Fonts -->
  <link href="https://fonts.googleapis.com/css?family=Open+Sans:300,400,600,700" rel="stylesheet">
  <!-- Icons -->
  <link href="./assets/vendor/nucleo/css/nucleo.css" rel="stylesheet">
  <link href="./assets/vendor/font-awesome/css/font-awesome.min.css" rel="stylesheet">
  <!-- Argon CSS -->
  <link type="text/css" href="./assets/css/argon.css?v=1.0.0" rel="stylesheet">
  <!-- Docs CSS -->
  <link type="text/css" href="./assets/css/docs.min.css" rel="stylesheet">
  <link rel="stylesheet" type="text/css" href="./assets/css/video.css">
  <link rel="stylesheet" href="css/magnific-popup.css">
  <script src="./assets/vendor/jquery/jquery.min.js"></script>
  <script src="./assets/js/pingzi_video.js" type="text/javascript" charset="utf-8"></script>
  <style>
  	/* *{
			padding: 0;
			margin: 0;
			list-style: none;
			text-decoration: none;
		} */
		.cent-box{
			width: 300px;
			height: 440px;
			vertical-align: middle;
			white-space: normal;
			margin: 0 auto;
			position: absolute;
			z-index: 2;
			left: 50%;
			margin-left: -150px;
			
		}
		.register-box{
			height: 490px;
			margin-top: -270px;
		}
		.cent-box-header{
			text-align: center;
		}
		.index-tab{
			text-align: center;
			font-size: 18px;
			margin-bottom: 10px;
		}
		.index-tab .index-slide-nav{
			display: inline-block;
			position: relative;
		}
		.index-tab .index-slide-nav a{
			float: left;
			line-height: 35px;
			opacity: 0.7;
			-webkit-transition: opacity .15s,color .15s;
    		transition: opacity .15s,color .15s;
    		color: #555;
		}
		.index-tab .index-slide-nav a:hover{
			color: #0171f2
			opacity: 1;
		}
		.index-tab .index-slide-nav a.active{
			opacity: 1;
			color: #0171f2;
		}
		.slide-bar{
			position: absolute;
    		left: 0;
    		bottom: 0;
    		margin: 0 .8em;
    		width: 10em;
    		height: 2px;
    		background: #0171f2;
		}
		.slide-bar1{
			left: 4em;
		}
		.form{
			float: none;
			margin: auto;
			text-align: left;
			width: 300px;
		}
		.form .group{
			padding: 1px 0;
    		border: 1px solid #d5d5d5;
    		border-radius: 3px;
		}
		.form .group .group-ipt{
			position: relative;
    		margin: 0;
    		overflow: hidden;
		}
		.form .group .group-ipt input{
			padding: 1em .8em;
    		width: 100%;
    		box-sizing: border-box;
    		border: 0;
    		border-radius: 0;
    		box-shadow: none;
    		background: rgba(255,255,255,0.5);
    		font-family: 'Microsoft Yahei';
    		color: #666;
    		height: 45px;
    		position: relative;
		}
		#password,#verify,#user,#password1{
			border-top: 1px solid #e8e8e8;
		}
		
		.tr_border123123{
			border-top: 1px solid #e8e8e8;
		}
		
		.button{
			margin-top:18px; 
		}
		#button{
			width: 100%;
			background: #0171f2;
		    		box-shadow: none;
		    		border: 0;
		    		border-radius: 3px;
		    		line-height: 41px;
		    		color: #fff;
		    		display: block;
		    		font-size: 15px;
		    		cursor: pointer;
		    		font-family: 'Microsoft Yahei';
		}
		#button:hover{
			background: #80c3f7;
		}
		#button2222{
			width: 100%;
			background: #0171f2;
		    		box-shadow: none;
		    		border: 0;
		    		border-radius: 3px;
		    		line-height: 41px;
		    		color: #fff;
		    		display: block;
		    		font-size: 15px;
		    		cursor: pointer;
		    		font-family: 'Microsoft Yahei';
		}
		#button2222:hover{
			background: #80c3f7;
		}
		
		.button_ok{
			width: 100%;
			background: #0171f2;
		    		box-shadow: none;
		    		border: 0;
		    		border-radius: 3px;
		    		line-height: 41px;
		    		color: #fff;
		    		display: block;
		    		font-size: 15px;
		    		cursor: pointer;
		    		font-family: 'Microsoft Yahei';
		}
		.button_ok_22{
			width: 100%;
			background: #0171f2;
		    		box-shadow: none;
		    		border: 0;
		    		border-radius: 3px;
		    		line-height: 41px;
		    		color: #fff;
		    		font-size: 15px;
		    		cursor: pointer;
		    		font-family: 'Microsoft Yahei';
		}
		.button_ok:hover{
			background: #80c3f7;
		}
		.remember{
			margin-top: 10px;
			line-height: 30px;
		}
		
		/* .icon{
			width: 11px;
			height: 11px;
			display: block;
			border: 1px solid #ccc;
			float: left;
			margin-top: 8px;
			margin-right: 5px;
			cursor: pointer;
		} */
		.zt{
			width: 9px;
			height: 9px;
			background: #0171f2;
			margin: 1px;
			display: block;
		}
		#remember-me{
			position: absolute;
			left: 0;
			top: 8px;
			opacity: 0;
			cursor: pointer;
		}
		.forgot-password{
			float: right;
			font-size: 14px;
		}
		.forgot-password a{
			color: #555;
		}
		.forgot-password a:hover{
			text-decoration: underline;
		} 
		
	#menu {
	  width: 420px;
	  margin: 0 auto;
	}
	#menu button {
	  position: relative;
	  width: 28%;
	  float: left;
	  margin: 1%;
	  text-align: center;
	  
	}
	#menu button a {
		display: block;
		padding: 1%;
		border: 1px solid #ccc;
		border-radius: 5px;
	}


	.arrow_box {
	  display: none;
	  position: absolute;
	  padding: 10px;
	  -webkit-border-radius: 8px;
	  -moz-border-radius: 8px;  
	  border-radius: 8px;
	  background: #333;
	  color: #fff;
	}
	.arrow_box:after {
	  position: absolute;
	  bottom: 100%;
	  left: 50%;
	  width: 0;
	  height: 0;
	  margin-left: -10px;
	  border: solid transparent;
	  border-color: rgba(51, 51, 51, 0);
	  border-bottom-color: #333;
	  border-width: 10px;
	  pointer-events: none;
	}
	span:hover + p.arrow_box { display: block; }
  	/* modal */
	.modal {
		display: none; /* Hidden by default */
		position: fixed; /* Stay in place */
		z-index: 9999; /* Sit on top */
		left: 0;
		top: 0;
		width: 100%; /* Full width */
		height: 100%; /* Full height */
		overflow: auto; /* Enable scroll if needed */
		background-color: rgb(0,0,0); /* Fallback color */
		background-color: rgba(0,0,0,0.4); /* Black w/ opacity */
	}
	/* Modal Content/Box */
	.modal-content {
		background-color: #fefefe;
		margin: 157px auto; /* 15% from the top and centered */
		padding: 45px;
		border-radius:10px;
		width: 400px; /* Could be more or less, depending on screen size */   
		height: 300px;                       
	}
	/* The Close Button */
	.close {
		color: #aaa;
		float: right;
		font-size: 28px;
		font-weight: bold;
	}
	.close22 {
		color: #aaa;
		float: right;
		font-size: 20px;
		font-weight: bold;
	}
  </style>
</head>

<body>
  <header class="header-global">
    <nav id="navbar-main" class="navbar navbar-main navbar-expand-lg navbar-transparent navbar-light">
      <div class="container">
        <a class="navbar-brand mr-lg-5" href="./index.html">
          <img src="./assets/img/brand/white.png">
        </a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbar_global" aria-controls="navbar_global" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="navbar-collapse collapse" id="navbar_global">
          <div class="navbar-collapse-header">
            <div class="row">
              <div class="col-6 collapse-brand">
                <a href="./index.html">
                  <img src="./assets/img/brand/blue.png">
                </a>
              </div>
              <div class="col-6 collapse-close">
                <button type="button" class="navbar-toggler" data-toggle="collapse" data-target="#navbar_global" aria-controls="navbar_global" aria-expanded="false" aria-label="Toggle navigation">
                  <span></span>
                  <span></span>
                </button>
              </div>
            </div>
          </div>
          <ul class="navbar-nav navbar-nav-hover align-items-lg-center">
            <li class="nav-item dropdown">
              <a href="#" class="nav-link" data-toggle="dropdown" href="#" role="button">
                <i class="ni ni-ui-04 d-lg-none"></i>
                <span class="nav-link-inner--text">Main Menu</span>
              </a>
              <div class="dropdown-menu dropdown-menu-xl">
                <div class="dropdown-menu-inner">
                  <a href="#exchange" class="media d-flex align-items-center">
                    <div class="icon icon-shape bg-gradient-primary rounded-circle text-white">
                      <i style="font-size: 18px;font-weight:bold;">EX</i>
                    </div>
                    <div class="media-body ml-3">
                      <h6 class="heading text-primary mb-md-1">Exchange</h6>
                      <p class="description d-none d-md-inline-block mb-0">For fast and effective trading, bringing new experience to users of simple design and easy to operate.</p>
                    </div>
                  </a>
                  <a href="#app" class="media d-flex align-items-center">
                    <div class="icon icon-shape bg-gradient-warning rounded-circle text-white">
                      <i class="ni ni-app"></i>
                    </div>
                    <div class="media-body ml-3">
                      <h5 class="heading text-warning mb-md-1">BS Application</h5>
                      <p class="description d-none d-md-inline-block mb-0">Special app management system for BS holders</p>
                    </div>
                  </a>
                </div>
              </div>
            </li>
            <li class="nav-item dropdown">
              <a href="#" class="nav-link" data-toggle="dropdown" href="#" role="button">
                <i class="ni ni-collection d-lg-none"></i>
                <span class="nav-link-inner--text">BS White Paper</span>
              </a>
              <div class="dropdown-menu">
                <a href="paper/white_paper_ver_eng.pdf" target="_blank" class="dropdown-item">English View</a>
                <a href="paper/white_paper_ver_cn.pdf" target="_blank" class="dropdown-item">Chinese View</a>
                <a href="paper/white_paper_ver_kor.pdf" target="_blank" class="dropdown-item">Korean View</a>
                <a href="paper/white_paper_ver_jp.pdf" target="_blank" class="dropdown-item">Japan View</a>
              </div>
            </li>
          </ul>
          <ul class="navbar-nav align-items-lg-center ml-lg-auto">
            <li class="nav-item">
              <a class="nav-link nav-link-icon" href="#" title="Translation of English" style="background-color: #FFFFFF;" id="y_English" onclick=yuyan_b('English')>
                <i class="fa" id="fa_English" style="color: #5e72e4;">EN</i>
              </a>
            </li>
            <li class="nav-item">
              <a class="nav-link nav-link-icon" href="#" title="Translation of Chinese" id="y_Chinese" onclick=yuyan_b('Chinese')>
                <i class="fa" id="fa_Chinese">CN</i>
              </a>
            </li>
            <li class="nav-item">
              <a class="nav-link nav-link-icon" href="#" title="Translation of Korean" id="y_Korean" onclick=yuyan_b('Korean')>
               <i class="fa" id="fa_Korean">KR</i>
              </a>
            </li>
            <li class="nav-item d-none d-lg-block ml-lg-4">
              <a href="javascript:join_private_method();"  class="btn btn-neutral btn-icon" id="myBtn">
                <span class="nav-link-inner--text" id="Join_private_id">Join private placement</span>
              </a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </header>

  <div id="myModal" class="modal">
		<div class="modal-content">
			<div class="cent-box">
				<div>
					<div class="index-tab">
						<span class="close"><label>×</label></span> 
						<div class="index-slide-nav">
							<a href="#" class="active">Join BS - BITCOM SHARES</a>	
						</div>
						<div class="index-slide-nav">
							<!-- <span class="active" id="ckck_span_span_id" style="font-size: 14px;">Can be private placement from USDT20000</span> -->
						</div>
					</div>
					 <span id="login_ckck">
						<div class="login form">
							<div class="group">
								<div class="group-ipt email">
									<input type="text" name="email" id="email" class="ipt" placeholder="Confirm E-mail" required="">
								</div>
							</div>
						</div>

						<div class="button">
							<button type="submit" class="login-btn register-btn" id="button" onclick="submit_login();">Next</button>
						</div>
					</span>
					<span id="login_ckck_22" style="display: none;">
						<div class="login form">
							<div class="group">
								<div class="group-ipt email" id="cccc_copy_id">
									<span><input type="text" name="input_box" id="input_box" value="" readonly class="ipt" style="width: 80%;"></span><span><a href='javascript:fuzhi_button();' style="width: 20%; font-size: 80%;" id="copy_button_id">Copy</a></span>
								</div>
								<div class="group-ipt email" style="border-top: 1px solid #e8e8e8;">
									<span><input type="text" name="shuliang" placeholder="USDT Number" id="shuliang" value="" class="ipt" style="width: 80%;"></span><span id="add_disan_id"></span>
								</div>
							</div>
						</div>
						<p id="p1" style="display: none;"></p>
						
						<div class="button">
							<button type="submit" class="login-btn register-btn button_ok" id="submit_shuliang" onclick="button_sumbit_count();">submit</button>
						</div>
					</span>
				</div>
			</div>	
		</div>
	</div>

	<div id="myModal1" class="modal">
		<div class="modal-content">
			<div class="cent-box">
				<div>
					<div class="index-tab">
						<span class="close"><label>×</label></span> 
						<div class="index-slide-nav">
							<a href="#" class="active">Join BS - BITCOM SHARES</a>	
						</div>
					</div>
					 <span id="login_ckck">
						<div class="login form">
							<div class="group">
								<div class="group-ipt email">
									<input type="text" name="email" id="email" class="ipt" placeholder="Confirm E-mail" required="">
								</div>
							</div>
						</div>

						<div class="button">
							<button type="submit" class="login-btn register-btn" id="button" onclick="submit_login();">Next</button>
						</div>
					</span>
					<span id="login_ckck_22" style="display: none;">
						<div class="login form">
							<div class="group">
								<div class="group-ipt email" id="cccc_copy_id">
									<span><input type="text" name="input_box" id="input_box" value="" readonly class="ipt" style="width: 80%;"></span><span><a href='javascript:fuzhi_button();' style="width: 20%; font-size: 80%;" id="copy_button_id">Copy</a></span>
								</div>
								<div class="group-ipt email" style="border-top: 1px solid #e8e8e8;">
									<span><input type="text" name="shuliang" placeholder="USDT Number" id="shuliang" value="" class="ipt" style="width: 80%;"></span><span id="add_disan_id"></span>
								</div>
							</div>
						</div>
						<p id="p1" style="display: none;"></p>
						
						<div class="button">
							<button type="submit" class="login-btn register-btn button_ok" id="submit_shuliang" onclick="button_sumbit_count();">submit</button>
						</div>
					</span>
				</div>
			</div>	
		</div>
	</div>

	<div id="myModal222" class="modal">
		<div class="modal-content" style="height: 700px;">
			<div class="cent-box">
				<div>
					<div class="index-tab">
						<span class="close22"><label>×</label></span> 
						<div class="index-slide-nav">
							<a href="#" class="active">BITCOM SHARES</a>	
						</div>
					</div>
					 <span id="login_ckck">
						<div class="login form">
							<div class="group">
								<div class="group-ipt email">
									<div class="group-ipt email">
										<span style="color: #5e72e4; display: none;" id="add_html_renzheng"></span>
										<span><input type="text" name="shuliang" placeholder="E-mail" id="send_count_id_input" value="" class="ipt" style="width: 70%;"></span>
										<span id="disp_id_ck"><a href="javascript:send_count_id_button();" style="width: 30%; font-size: 80%;" id="send_count_id"></a></span>
									</div>
								</div>
								<div class="group-ipt email">
									<div class="group-ipt email" style="border-top: 1px solid #e8e8e8;">
									<span><input type="text" name="shuliang" placeholder="enter verification code" id="queren_renzheng_id_input" value="" class="ipt" style="width: 70%;"></span>
									<span id=""><a href="javascript:queren_renzheng_id_button();" style="width: 30%; font-size: 80%;" id="queren_renzheng_id"></a></span>
									</div>
								</div>
								<div class="group-ipt email">
									<div class="group-ipt email" style="border-top: 1px solid #e8e8e8;">
										<span style="color: #5e72e4; display: none;" id="add_html_renzheng"></span>
										<span><input type="password" name="shuliang" placeholder="password" id="send_count_id_password" value="" class="ipt" style="width: 70%;"></span>
									</div>
								</div>

								<div class="group-ipt email">
									<div class="group-ipt email" style="border-top: 1px solid #e8e8e8;">
										<span style="color: #5e72e4; display: none;" id="add_html_renzheng"></span>
										<span><input type="password" name="shuliang" placeholder="password confirm" id="send_count_id_password_ck" value="" class="ipt" style="width: 70%;"></span>
									</div>
								</div>
							</div>
						</div>

						<br>

					  <div class="card shadow" style="padding-top: 20px;">
		                <div class="card-body">
		                  <div class="tab-content" id="myTabContent">
		                    <div class="tab-pane fade show active" id="tabs-text-1" role="tabpanel" aria-labelledby="tabs-text-1-tab">
		                      <p class="description" id="content_next_01"></p>
							  <p class="description" id="content_next_02"> </p>
							  <p class="description" id="content_next_03"></p>
		                    </div>
		                    <div class="tab-pane fade" id="tabs-text-2" role="tabpanel" aria-labelledby="tabs-text-2-tab">

		                    </div>
		                    <div class="tab-pane fade" id="tabs-text-3" role="tabpanel" aria-labelledby="tabs-text-3-tab">
		                      
		                    </div>
		                  </div>
		                </div>
		              </div>
		     <div class="custom-control custom-checkbox mb-3" style="text-align: center; padding-top: 10px;">
              <input class="custom-control-input" id="customCheck2" type="checkbox" checked="">
              <label class="custom-control-label" for="customCheck2">
                <span id="ckckckck_id">Checked</span>
              </label>
            </div>

						<div class="button">
							<button type="submit" class="login-btn register-btn " id="button2222" onclick="" style="background-color: #BDBDBD;">사전등록</button>
						</div>
					</span>
				</div>
			</div>	
		</div>
	</div>


  <main>
    <div class="position-relative">
      <!-- shape Hero -->
      <section class="section-shaped my-0">
        <div class="shape shape-style-1 shape-default shape-skew">
          <span></span>
          <span></span>
          <span></span>
          <span></span>
          <span></span>
          <span></span>
          <span></span>
          <span></span>
          <span></span>
        </div>
        <div class="container shape-container d-flex">
          <div class="col px-0">
            <div class="row">
              <div class="col-lg-6">
                <h1 class="display-2  text-white" id="Build_id">Build Fintech</h1>
                <h1 class="display-2  text-white"><span style="font-size: 24px;"><b id="Ecological_id">Ecological Community Of Future</b></span></h1>
                <p class="lead  text-white" id="content_01">The blockchain and the tokenomics Created a diversified ecological system While also the important elements of the birth of BS system.</p>
                <div class="btn-wrapper">
                  <a href="#qa" class="btn btn-white btn-icon mb-3 mb-sm-0">
                    <span class="btn-inner--icon"><i class="ni ni-email-83"></i></span>
                    <span class="btn-inner--text" id="Download_HTML_id">Submit a message</span>
                  </a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
      <!-- 1st Hero Variation -->
    </div>
    <section class="section section-lg pt-lg-0 mt--200">
      <div class="container">
        <div class="row justify-content-center">
          <div class="col-lg-12">
            <div class="row row-grid">
              <div class="col-lg-4">
                <div class="card card-lift--hover shadow border-0">
                  <div class="card-body py-5">
                    <div class="icon icon-shape icon-shape-success rounded-circle mb-4">
                      <i style="font-size: 18px;font-weight:bold;">1</i>
                    </div>
                    <h6 class="text-success text-uppercase" id="join_event_id_04">Join private placement</h6>
                    <p class="description mt-3" id="yuyan_shezhi_id">Singapore time 14 noon on September 1st,open</p>
                    <!-- <a href="javascript:join_private_method();" class="btn btn-success mt-4" id="join_event_id_03">Join private placement</a> -->
					<button class="btn btn-success mt-4" id="join_event_id_03" style="border-color: #EAEAEA; background-color: #EAEAEA;">Join private placement</button>
                  </div>
                </div>
              </div>
			  <div class="col-lg-4">
                <div class="card card-lift--hover shadow border-0">
                  <div class="card-body py-5">
                    <div class="icon icon-shape icon-shape-primary rounded-circle mb-4">
                      <i style="font-size: 18px;font-weight:bold;">2</i>
                    </div>
                    <h6 class="text-primary text-uppercase" id="participate_in_id_02">Pre-registration</h6>
                    <p class="description mt-3" id="yuyan_shezhi_id_02">Singapore time 12 noon on September 10st,open</p>
                    <a href="javascript:join_private_method222('');" class="btn btn-primary mt-4" id="participate_in_id">Pre-registration</a>  
                  </div>
                </div>
              </div>
              <div class="col-lg-4">
                <div class="card card-lift--hover shadow border-0">
                  <div class="card-body py-5">
                    <div class="icon icon-shape icon-shape-warning rounded-circle mb-4">
                      <i style="font-size: 18px;font-weight:bold;">3</i>
                    </div>

                    <h6 class="text-warning text-uppercase" id="join_event_id_02_01">Experience the functionality</h6>
                    <p class="description mt-3" id="yuyan_shezhi_id_03">Singapore time 12 noon on September 21st,open</p>
                    <a href="javascript:join_private_method333('met_03');" class="btn btn-warning mt-4" id="join_event_id_02">Experience the functionality</a>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="section section-lg" id="exchange">
      <div class="container">
        <div class="row row-grid align-items-center">
          <div class="col-md-6 order-md-2">
            <img src="./assets/img/theme/promo-1.png" class="img-fluid floating">
          </div>
          <div class="col-md-6 order-md-1">
            <div class="pr-md-5">
              <div class="icon icon-lg icon-shape icon-shape-success shadow rounded-circle mb-5">
                <i style="font-size: 18px;font-weight:bold;">EX</i>
              </div>
              <h3 id="Bitcom_Exchange_id">Bitcom Exchange</h3>
              <p id="content_02">For fast and effective trading, bringing new experience to users of simple design and easy to operate.</p>
              <ul class="list-unstyled mt-5">
                <li class="py-2">
                  <div class="d-flex align-items-center">
                    <div>
                      <div class="badge badge-circle badge-success mr-3">
                        <i style="font-size: 18px;font-weight:bold;">1</i>
                      </div>
                    </div>
                    <div>
                      <h6 class="mb-0" id="content_03">“A Market” of BS you will be able to get the rewards.</h6>
                    </div>
                  </div>
                </li>
                <li class="py-2">
                  <div class="d-flex align-items-center">
                    <div>
                      <div class="badge badge-circle badge-success mr-3">
                        <i style="font-size: 18px;font-weight:bold;">2</i>
                      </div>
                    </div>
                    <div>
                      <h6 class="mb-0" id="content_04">“B Market” of platform only pay 0.01%!</h6>
                    </div>
                  </div>
                </li>
                <li class="py-2">
                  <div class="d-flex align-items-center">
                    <div>
                      <div class="badge badge-circle badge-success mr-3">
                        <i style="font-size: 18px;font-weight:bold;">3</i>
                      </div>
                    </div>
                    <div>
                      <h6 class="mb-0" id="content_05">My smart currency storehouse.</h6>
                    </div>
                  </div>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="section bg-secondary">
      <div class="container">
        <div class="row row-grid align-items-center">
          <div class="col-md-6">
            <div class="card bg-default shadow border-0">
              <img src="./assets/img/theme/img-1-1200x1000.jpg" class="card-img-top">
              <blockquote class="card-blockquote">
                <svg preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 583 95" class="svg-bg">
                  <polygon points="0,52 583,95 0,95" class="fill-default"></polygon>
                  <polygon points="0,42 583,95 683,0 0,95" opacity=".2" class="fill-default"></polygon>
                </svg>
                <h4 class="display-3 font-weight-bold text-white" id="Ecosystem_id">Ecosystem</h4>
                <p class="lead text-italic text-white" id="content_06">Embrace the innovations divined from blockchain, while also creating together the ecological home of community mechanism of blockchain.</p>
              </blockquote>
            </div>
          </div>
          <div class="col-md-6">
            <div class="pl-md-5">
              <div class="icon icon-lg icon-shape icon-shape-warning shadow rounded-circle mb-5">
                <i style="font-size: 18px;font-weight:bold;">BS</i>
              </div>
              <h3 id="What_is_BS_id">What is BS</h3>
              <p class="lead" id="content_07">The BS is a polymorphic digital asset, which means that it can morph into many different types of assets</p>
              <p class="lead" id="content_08">The BS has all of the properties of the digital currency with the additional property that, BS holders enjoy the corresponding rights such as community governance and the shares</p>
             View: <a href="paper/white_paper_ver_eng.pdf" target="_blank" class="font-weight-bold text-warning mt-5" id="BSWhite_Paper_More_id">English</a> - <a href="paper/white_paper_ver_cn.pdf" class="font-weight-bold text-warning mt-5" target="_blank" id="BSWhite_Paper_More_id">Chinese</a> - <a href="paper/white_paper_ver_kor.pdf" target="_blank" class="font-weight-bold text-warning mt-5" id="BSWhite_Paper_More_id">Korean</a> - <a href="paper/white_paper_ver_jp.pdf" target="_blank" class="font-weight-bold text-warning mt-5" id="BSWhite_Paper_More_id">Japan</a>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="section section section-shaped my-0 overflow-hidden" id="app">
      <div class="shape shape-style-1 bg-gradient-warning shape-skew">
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
      </div>
      <div class="container py-0">
        <div class="row row-grid align-items-center">
          <div class="col-md-6 order-lg-2 ml-lg-auto">
            <div class="position-relative pl-md-5">
              <img src="./assets/img/ill/city.png" class="img-center img-fluid">
            </div>
          </div>
          <div class="col-lg-6 order-lg-1">
            <div class="d-flex px-3">
              <div>
                <div class="icon icon-lg icon-shape bg-gradient-white shadow rounded-circle text-primary">
                  <i class="ni ni-app"></i>
                </div>
              </div>
              <div class="pl-4">
                <h4 class="display-3 text-white">BS Application</h4>
                <p class="text-white">Special app management system for BS holders</p>
              </div>
            </div>
            <div class="card shadow shadow-lg--hover mt-5">
              <div class="card-body">
                <div class="d-flex px-3">
                  
                  <div class="pl-4">
                    <h5 class="title text-success">App Ver 1.0</h5>
                    <p id="content_09">Version provides details of the community's shares, details of assets, income distribution details and the transaction function</p>
                    <a href="#" class="text-success">Learn more</a>
                  </div>
                </div>
              </div>
            </div>
            <div class="card shadow shadow-lg--hover mt-5">
              <div class="card-body">
                <div class="d-flex px-3">
              
                  <div class="pl-4">
                    <h5 class="title text-warning">App Ver 2.0</h5>
                    <p id="content_10">In order to protect the interests and rights of BS holders, the version version will be launched community committees, instant messaging (IM),voting and community functions</p>
                    <a href="#" class="text-warning">Learn more</a>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
      <section class="section section-lg section-nucleo-icons pb-250" style="padding-bottom: 8rem;">
      <div class="container">
        <div class="row justify-content-center">
          <div class="col-lg-8 text-center">
            <h2 class="display-3" id="BS_Future_id">BS - Future</h2>
            <p class="lead" id="content_11">
              BS holders will be enjoy 100% of all the revenue from Bitcom trading platform as well as from the new projects forever.
            </p>
            
          </div>

        </div>

        <div class="blur--hover">
          <a href="#">
            <div class="icons-container blur-item mt-5 on-screen" data-toggle="on-screen">
              <!-- Center -->
              <i><img src="./assets/img/brand/logo_icon.png" width="68"></i>
              <!-- Right 1 -->
              <i class="icon icon-sm ni ni-album-2"></i>
              <i class="icon icon-sm ni ni-app"></i>
              <i class="icon icon-sm ni ni-atom"></i>
              <!-- Right 2 -->
              <i class="icon ni ni-bag-17"></i>
              <i class="icon ni ni-bell-55"></i>
              <i class="icon ni ni-credit-card"></i>
              <!-- Left 1 -->
              <i class="icon icon-sm ni ni-briefcase-24"></i>
              <i class="icon icon-sm ni ni-building"></i>
              <i class="icon icon-sm ni ni-button-play"></i>
              <!-- Left 2 -->
              <i class="icon ni ni-calendar-grid-58"></i>
              <i class="icon ni ni-camera-compact"></i>
              <i class="icon ni ni-chart-bar-32"></i>
            </div>
            <span class="blur-hidden h5 text-success" id="content_12">The BS holders will vote for future projects and plans.</span>
          </a>
        </div>
      </div>
    </section>

    <section class="section section-shaped my-0 overflow-hidden">
      <div class="shape shape-style-3 bg-gradient-default shape-skew">
        <span></span>
        <span></span>
        <span></span>
        <span></span>
      </div>
      <div class="container pt-lg pb-300">
        <div class="row text-center justify-content-center">
          <div class="col-lg-10">
            <h2 class="display-3 text-white" id="Submit_request_id">Submit a message</h2>
            <p class="lead text-white" id="content_13">Please enter the details of your request. A member of our support staff will respond as soon as possible.</p>
          </div>
        </div>
        
      </div>
    </section>
    <section class="section section-lg pt-lg-0 section-contact-us" id="qa">
      <div class="container">
        <div class="row justify-content-center mt--300">
          <div class="col-lg-8">
            <div class="card bg-gradient-secondary shadow">
              <div class="card-body p-lg-5">
                <h4 class="mb-1" id="content_14">Your project is very important to us.</h4>
                <p class="mt-0" id="content_15">Contact personnel name,e-mail, and proposal details.</p>
                <div class="form-group mt-5">
                  <div class="input-group input-group-alternative">
                    <div class="input-group-prepend">
                      <span class="input-group-text"><i class="ni ni-user-run"></i></span>
                    </div>
                    <input class="form-control" placeholder="Your name" type="text" id="your_name">
                  </div>
                </div>
                <div class="form-group">
                  <div class="input-group input-group-alternative">
                    <div class="input-group-prepend">
                      <span class="input-group-text"><i class="ni ni-email-83"></i></span>
                    </div>
                    <input class="form-control" placeholder="Email address" type="email" id="email_address">
                  </div>
                </div>
                <div class="form-group mb-4">
                  <textarea class="form-control form-control-alternative" name="name" rows="4" cols="80" placeholder="Type a message..." id="textarea_name"></textarea>
                </div>
                <div>
                  <button type="button" class="btn btn-default btn-round btn-block btn-lg" onclick="send_message_method();">Send Message</button>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
   

  </main>
  <footer class="footer has-cards">
  <section class="section" style="padding-bottom: 1px;"><div class="container"><div class="row row-grid justify-content-center"><div class="col-lg-8 text-center"><h2 class="display-3" id="content_16">Video</h2>
                       <p class="lead" id="content_18">Our presentations, interviews and updates.</p></div></div></div></section>
    <div class="container container-lg">
      <div class="row">
        <div class="col-md-6 mb-5 mb-md-0">
          <div class="card card-lift--hover shadow border-0">
			<img src="./movie/play_1.jpg" class="card-img m-video" data-src="movie/1.mp4" style="cursor: pointer;">
          </div>
        </div>
        <div class="col-md-6 mb-5 mb-lg-0">
          <div class="card card-lift--hover shadow border-0">
			<img src="./movie/play_2.jpg" class="card-img m-video" data-src="movie/2.mp4" style="cursor: pointer;">
          </div>
        </div>
      </div>
    </div>
    <div class="container">
      <div class="row row-grid align-items-center my-md">
        <div class="col-lg-6">
          <p class="text-primary font-weight-light mb-2">Thank you for supporting us!</p>
          <p class="mb-0 font-weight-light">Let's get in touch on any of these platforms.</p>
        </div>
        <div class="col-lg-6 text-lg-right btn-wrapper">
          <a target="_blank" href="#" class="btn btn-neutral btn-icon-only btn-twitter btn-round btn-lg" data-toggle="tooltip" data-original-title="Follow us">
            <i class="fa fa-twitter"></i>
          </a>
          <a target="_blank" href="#" class="btn btn-neutral btn-icon-only btn-facebook btn-round btn-lg" data-toggle="tooltip" data-original-title="Like us">
            <i class="fa fa-facebook-square"></i>
          </a>
          <a target="_blank" href="#" class="btn btn-neutral btn-icon-only btn-dribbble btn-lg btn-round" data-toggle="tooltip" data-original-title="Follow us">
            <i class="fa fa-dribbble"></i>
          </a>
        </div>
      </div>
      <hr>
      <div class="row align-items-center justify-content-md-between">
        <div class="col-md-6">
          <div class="copyright">
            &copy; 2018
            <a href="" target="_blank">Bitcom Ver 1.0</a>.
          </div>
        </div>
        <div class="col-md-6">
          <ul class="nav nav-footer justify-content-end">
            <li class="nav-item">
              <a href="#" class="nav-link" onclick="top_method();">Top</a>
            </li>
            <li class="nav-item">
              <a href="mailto:a@invno.com" class="nav-link">Send E-mail</a>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </footer>
  <!-- Core -->
 
  <script src="./assets/vendor/popper/popper.min.js"></script>
  <script src="./assets/vendor/bootstrap/bootstrap.min.js"></script>
  <script src="./assets/vendor/headroom/headroom.min.js"></script>
  <script src="./js/jquery-3.2.1.min.js"></script>
  <!-- Argon JS -->
  <script src="./assets/js/argon.js?v=1.0.0"></script>
  
<script>
	var object = "";
	var total_send_msg = 0;
	var fanyi_total = "English";
	$.getJSON('./fanyi/fanyi.json', function(result) {
		object = JSON.stringify(result);
		if(navigator.language == "zh-CN"){ yuyan_b("Chinese"); }
		else if(navigator.language == "zh"){ yuyan_b("Chinese"); }
		else if(navigator.language == "ko-KR"){ yuyan_b("Korean"); }
		else if(navigator.language == "ko"){ yuyan_b("Korean"); }
		else { yuyan_b("English"); }
	});
	var modal = document.getElementById('myModal');
	var btn = document.getElementById("myBtn");
	var span = document.getElementsByClassName("close")[0];
	span.onclick = function() { modal.style.display = "none"; }
	window.onclick = function(event) {  if (event.target == modal) { 	modal.style.display = "none";  }   }

	var myModal222 = document.getElementById('myModal222');
	var span = document.getElementsByClassName("close22")[0];
	span.onclick = function() { myModal222.style.display = "none"; }
	window.onclick = function(event) {  if (event.target == myModal222) { 	myModal222.style.display = "none";  }   }
	

	function yuyan_b(result){
		fanyi_total = result;
		var data = JSON.parse(object);
		var data_guojia = JSON.stringify(data[result]);
		data_guojia = JSON.parse(data_guojia);
		if(result == "English"){
			$("#y_English").css("background-color", "#FFFFFF");
			$("#fa_English").css("color", "#5e72e4");
			$("#y_Chinese").css("background-color", "");
			$("#fa_Chinese").css("color", "");
			$("#y_Korean").css("background-color", "");
			$("#fa_Korean").css("color", "");
			$("#Join_private_id").html("Inquiries");
			// $("#ckck_span_span_id").html("Can be private placement from USDT20000");
			$("#ckckckck_id").html("Agee to Receive our updates news");
			$("#button2222").html("sign up");
			$("#send_count_id").html("send code");
			$("#content_next_01").html("Registration is now available:");
			$("#content_next_02").html("- Priority experience BITCOM exchange");
			$("#content_next_03").html("- Additional rewards for BITCOM exchange earnings");
			$("#queren_renzheng_id").html("code confirm");
		}else if(result == "Chinese"){
			$("#y_Chinese").css("background-color", "#FFFFFF");
			$("#fa_Chinese").css("color", "#5e72e4");
			$("#y_English").css("background-color", "");
			$("#fa_English").css("color", "");
			$("#y_Korean").css("background-color", "");
			$("#fa_Korean").css("color", "");
			$("#Join_private_id").html("查询");
			// $("#ckck_span_span_id").html("20000USDT起可加入私募");
			$("#ckckckck_id").html("同义收发通知邮件");
			$("#button2222").html("预约加入");
			$("#send_count_id").html("发送验证码");
			$("#content_next_01").html("现在加入可获得：");
			$("#content_next_02").html("- 优先体验BITCOM功能");
			$("#content_next_03").html("- 获得交易所收益的额外奖励");
			$("#queren_renzheng_id").html("确认验证码");
		}else if(result == "Korean"){
			$("#y_Korean").css("background-color", "#FFFFFF");
			$("#fa_Korean").css("color", "#5e72e4");
			$("#y_Chinese").css("background-color", "");
			$("#fa_Chinese").css("color", "");
			$("#y_English").css("background-color", "");
			$("#fa_English").css("color", "");
			$("#Join_private_id").html("찾아보기");
			// $("#ckck_span_span_id").html("10000USDT부터 사모펀드 가입 가능");  
			$("#ckckckck_id").html("알림메일 수신 동의");
			$("#button2222").html("사전예약");
			$("#send_count_id").html("인증번호 받기");
			$("#content_next_01").html("사전예약 참여자 혜택:");
			$("#content_next_02").html("- 빗컴 거래소 기능 우선 체험");
			$("#content_next_03").html("- 빗컴 거래소 수익 보상금 추가 획득");
			$("#queren_renzheng_id").html("인증번호 확인");
		}
		$("#Build_id").html(data_guojia[0].Build_id);
		$("#Ecological_id").html(data_guojia[0].Ecological_id);
		$("#content_01").html(data_guojia[0].content_01);
		$("#Download_HTML_id").html(data_guojia[0].Download_HTML_id);
		$("#Bitcom_Exchange_id").html(data_guojia[0].Bitcom_Exchange_id);
		$("#content_02").html(data_guojia[0].content_02);
		$("#content_03").html(data_guojia[0].content_03);
		$("#content_04").html(data_guojia[0].content_04);
		$("#content_05").html(data_guojia[0].content_05);
		$("#Ecosystem_id").html(data_guojia[0].Ecosystem_id);
		$("#content_06").html(data_guojia[0].content_06);
		$("#What_is_BS_id").html(data_guojia[0].What_is_BS_id);
		$("#content_07").html(data_guojia[0].content_07);
		$("#content_08").html(data_guojia[0].content_08);
		$("#BSWhite_Paper_More_id").html(data_guojia[0].BSWhite_Paper_More_id);
		$("#content_09").html(data_guojia[0].content_09);
		$("#content_10").html(data_guojia[0].content_10);
		$("#BS_Future_id").html(data_guojia[0].BS_Future_id);
		$("#content_11").html(data_guojia[0].content_11);
		$("#content_12").html(data_guojia[0].content_12);
		$("#Submit_request_id").html(data_guojia[0].Submit_request_id);
		$("#content_13").html(data_guojia[0].content_13);
		$("#content_14").html(data_guojia[0].content_14);
		$("#join_event_id_03").html(data_guojia[0].join_event_id_03);
		$("#join_event_id_04").html(data_guojia[0].join_event_id_03);
		$("#join_event_id_02").html(data_guojia[0].join_event_id);
		$("#join_event_id_02_01").html(data_guojia[0].join_event_id);
		$("#yuyan_shezhi_id").html(data_guojia[0].yuyan_shezhi);
		$("#yuyan_shezhi_id_02").html(data_guojia[0].yuyan_shezhi22);
		$("#yuyan_shezhi_id_03").html(data_guojia[0].yuyan_shezhi33);
		$("#participate_in_id").html(data_guojia[0].participate_in_id);
		$("#participate_in_id_02").html(data_guojia[0].participate_in_id);
		$("#content_15").html(data_guojia[0].content_15);
	}

	function join_private_method(){
		$("#login_ckck").css("display", "block");
		$("#login_ckck_22").css("display", "none");
		modal.style.display = "block";
		$("#login_id").val("");
		$("#login_password").val("");
	}


	function join_private_method222(result){
		$("#myModal222").css("display", "block");
	}

	function join_private_method333(result){
		if(result == "met_03"){
			if(fanyi_total == "English"){ alert("Singapore time 12 noon on September 21st,open"); }
			else if(fanyi_total == "Chinese"){ alert("新加坡时间9月21日中午12点"); }
			else if(fanyi_total == "Korean"){ alert("싱가포르 시간 9 월 21 일 점심 12시 개통"); }
		}
	}

	function fuzhi_button(){
		 copyToClipboard('#p1');
	}

	function copyToClipboard(element) {
		  var $temp = $("<input>");
		  $("body").append($temp);
		  $temp.val($(element).text()).select();
		  document.execCommand("copy");
		  $temp.remove();
		  alert("copy ok");
	}

	function submit_login(){
		$("#shuliang").val("");
		if($("#email").val() == ""){
			if(fanyi_total == "English"){
				alert("Please enter your email address");
			}else if(fanyi_total == "Chinese"){
				alert("请输入您的邮箱地址");
			}else if(fanyi_total == "Korean"){
				alert("이메일 주소를 입력하세요.");
			}
			return;
		}
		var total_data = {
			email_addrs: $("#email").val()
		};
		$.ajax({
		  type: "POST",
		  url:  "email_login_ck.php",
		  data : total_data,
		  async : false,
		  error: function(){   

		 }, 
		  success: function(data,status){
			if(data == 0){
			}else if(data == "FAIL"){
				if(fanyi_total == "English"){
					alert("For unregistered emails, please contact the referrer to activate the email.");
				}else if(fanyi_total == "Chinese"){
					alert("未注册的邮箱，请联系推荐人以激活邮箱。");
				}else if(fanyi_total == "Korean"){
					alert("미활성화된 이메일 주소입니다. 추천인을 통하여 활성화 시켜주세요");
				}
				modal.style.display = "none";
				$("#email").val("");
				location.href="#qa";
			}else{
				$("#login_ckck").css("display", "none");
				$("#login_ckck_22").css("display", "block");
				obje2 = JSON.parse(data);

				if(obje2.row_select_33 == "A"){
					$("#shuliang").val("");
					$("#shuliang").attr("type", "text");
					$("#shuliang").attr("readonly", "readonly");
					$("#submit_shuliang").attr("onclick", "");
					if(obje2.row_select_55 == 0 && obje2.usdt_count == 0){ 
						$("#shuliang").val(obje2.row_select_44 + " ETH wait for");
					}else{ 
						var aaaa = obje2.row_select_44 * 5000;
						var bbbb = obje2.usdt_count * 10;
						var cccc = parsePrice(aaaa + bbbb);
						var cccc_split = cccc.split('.');
						if(cccc_split[1] == 0000 || cccc_split[1] == "0000"){ cccc = cccc_split[0]; }
						// if(obje2.money_ck == "E"){ aaaa = obje2.row_select_44 * 5000; }
						// else if(obje2.money_ck == "U"){ aaaa = obje2.row_select_44 * 10; }
						// $("#shuliang").val(cccc + " BS -> " + obje2.row_select_55 + " ETH wait for");
						$("#shuliang").val("BS:" + cccc + " -> (USDT:" + obje2.usdt_count + ", ETH:" + obje2.row_select_44+")");
						$("#cccc_copy_id").css("display", "none");
					}
					$("#submit_shuliang").html("Waiting...");
					$("#add_disan_id").html('');
				}else if(obje2.row_select_33 == "D"){
					$("#shuliang").attr("type", "number");
					$("#input_box").attr("value", obje2.row_select_22);
					$("#p1").html(obje2.row_select_22);
					// $("#submit_shuliang").attr("onclick", "button_sumbit_count()");
					$("#shuliang").removeAttr("readonly");
					$("#submit_shuliang").html("submit");
					$("#add_disan_id").html('');
				}else if(obje2.row_select_33 == "O"){
					$("#shuliang").val("");
					$("#shuliang").attr("type", "text");
					$("#shuliang").attr("readonly", "readonly");
					$("#submit_shuliang").attr("onclick", "");
					$("#submit_shuliang").css("border-color", "#EAEAEA");
					$("#submit_shuliang").css("background-color", "#EAEAEA");
					var aaaa = obje2.row_select_44 * 5000;
					var bbbb = obje2.usdt_count * 10;
					var cccc = parsePrice(aaaa + bbbb);
					var cccc_split = cccc.split('.');
					if(cccc_split[1] == 0000 || cccc_split[1] == "0000"){ cccc = cccc_split[0]; }
					
					$("#shuliang").val(cccc + " BS");
					$("#submit_shuliang").html("OK");
					// $("#add_disan_id").html('<a href="javascript:add_button();" style="width: 20%; font-size: 80%;" id="add_button_id">Add</a>');
					$("#cccc_copy_id").css("display", "none");
					/*
					if(obje2.money_ck == "E"){ aaaa = obje2.row_select_44 * 5000; }
					else if(obje2.money_ck == "U"){ aaaa = obje2.row_select_44 * 10; }
					$("#shuliang").val(aaaa + " BS");
					$("#submit_shuliang").html("OK");
					$("#add_disan_id").html('<a href="javascript:add_button();" style="width: 20%; font-size: 80%;" id="add_button_id">Add</a>');
					*/
				}
			}
		  }
		});
	}

	function button_sumbit_count(count_result){
		var ck_ck_result = 0;
		if(count_result == 2) ck_ck_result = count_result;
		if($("#shuliang").val() == ""){
			if(fanyi_total == "English"){
				alert("Please enter USDT Number");
			}else if(fanyi_total == "Chinese"){
				alert("请输入USDT数量");
			}else if(fanyi_total == "Korean"){
				alert("USDT 갯수를 입력하세요.");
			}
			return;
		}
		if(0 < $("#shuliang").val()){
			var total_data = {
				eth_shuliang: $("#shuliang").val(),
				ck_ck_result: ck_ck_result,
				pk_id: obje2.row_select
			};
			$.ajax({
			  type: "POST",
			  url:  "email_login_ck.php",
			  data : total_data,
			  async : false,
			  error: function(){   

			 }, 
			  success: function(data,status){
				if(data == "SUCC"){
					if(fanyi_total == "English"){
						alert("Charging is complete.");
					}else if(fanyi_total == "Chinese"){
						alert("成功充值");
					}else if(fanyi_total == "Korean"){
						alert("충전이 완료 되었습니다.");
					}
					$("#shuliang").attr("value", "");
					$("#submit_shuliang").attr("onclick", "");
				}
			  }
			});
		}else{
			if(fanyi_total == "English"){
				alert("You can't enter 0 numbers");
			}else if(fanyi_total == "Chinese"){
				alert("不能输入0一下数字");
			}else if(fanyi_total == "Korean"){
				alert("정상적인 값을 입력하세요.");
			}
			return;
		}
	}

	function add_button(){
		$("#cccc_copy_id").css("display", "block");
		$("#p1").html("17KiguySNLQTMScXarnSgC3G3k5uSzG8KG");
		$("#input_box").attr("value", "17KiguySNLQTMScXarnSgC3G3k5uSzG8KG");
		$("#submit_shuliang").attr("onclick", "button_sumbit_count(2)");
		$("#shuliang").attr("type", "number");
		$("#shuliang").removeAttr("readonly");
	}

	function send_message_method(){
		var your_name = $("#your_name").val();
		var email_address = $("#email_address").val();
		var textarea_name = $("#textarea_name").val();

		if(your_name == ""){
			alert("Please enter your name");
			return;
		}
		if(email_address == ""){
			alert("Enter your email address");
			return;
		}
		if(textarea_name == ""){
			alert("Please type your message");
			return;
		}
		var total_data = { 
			your_name: your_name,
			email_address: email_address,
			result: "send_mss",
			textarea_name: textarea_name
		};
		$.ajax({
			type: "POST",
			url:  "send_message.php",
			data : total_data,
			async : false,
			error: function(){
			}, 
			success: function(data,status){
			  if(data == "SUCC"){
				  alert("Joined");
		      }else{
				  alert("Already Existing Email");
			  }
			  $('html').scrollTop(0);
			  $("#your_name").val("");
			  $("#email_address").val("");
			  $("#textarea_name").val("");
			}
		});
	}

	function send_count_id_button(){
		var emailVal = $("#send_count_id_input").val();
		var regExp = /^[0-9a-zA-Z]([-_.]?[0-9a-zA-Z])*@[0-9a-zA-Z]([-_.]?[0-9a-zA-Z])*.[a-zA-Z]{2,3}$/i;
		var msg = {
			user_mail: emailVal,
			result: "ckckck"
		};
		$.ajax({
			type: "POST",
			url:  "email_login_ck.php",
			data : msg,
			async : false,
			error: function(){
			}, 
			success: function(data,status){
			  if(data == "SUCC"){
				    $("#button2222").attr("onclick", "");
					$("#button2222").css("background-color", "#BDBDBD");
					if (emailVal.match(regExp) != null) {
						var input_msg = "Verification Code";
						var result = Math.floor(Math.random() * 1000000)+100000;
						if(result>1000000){ result = result - 100000; }

						var total_data2 = {
							user_mail: emailVal,
							title: input_msg,
							textarea_name: "index_test",
							content: "Safety verification:" + result
						};
						
						$.ajax({
							type: "POST",
							url:  "mail/test.php",
							data : total_data2,
							async : false,
							error: function(){
							}, 
							success: function(data,status){
								if(fanyi_total == "English"){
									alert("Send your email");
								}else if(fanyi_total == "Chinese"){
									alert("已发至您的邮箱");
								}else if(fanyi_total == "Korean"){
									alert("메일로 인증번호를 전송하였습니다.");
								}
								total_send_msg = result;
								$("#send_count_id").attr("href", "javascript:nononono();");
								/*
								$("#send_count_id").click(function(e){
									e.preventDefault();
								});
								*/
								resetTime(60);
							}
						});
					}else {
						if(fanyi_total == "English"){
							alert("confirm your email address.");
						}else if(fanyi_total == "Chinese"){
							alert("请确认邮箱地址");
						}else if(fanyi_total == "Korean"){
							alert('잘못된 이메일입니다');
						}
					}
			  }else{
					if(fanyi_total == "English"){
						alert("Your mail has been registered.");
					}else if(fanyi_total == "Chinese"){
						alert("您的邮箱已被注册");
					}else if(fanyi_total == "Korean"){
						alert("이미 등록된 이메일 입니다.");
					}
			  }
			}
		});
	}
	function nononono(){}

	function resetTime(time){
		  var timer=null;
		  var t=time;
		  var m=0;
		  var s=0;
		  m=Math.floor(t/60%60);
		  m<10&&(m='0'+m);
		  s=Math.floor(t%60);
		  function countDown(){
		   s--;
		   s<10&&(s='0'+s);
		   if(s.length>=3){
		    s=59;
		    m="0"+(Number(m)-1);
		   }
		   if(m.length>=3){
		    m='00';
		    s='00';
		    clearInterval(timer);
		   }
			if(s == "00"){
				if(fanyi_total == "English"){
					$("#send_count_id").html("send code");
				}else if(fanyi_total == "Chinese"){
					$("#send_count_id").html("发送验证码");
				}else if(fanyi_total == "Korean"){
					$("#send_count_id").html("인증번호 받기");
				}
				total_send_msg = 0;
				$("#send_count_id").attr("href", "javascript:send_count_id_button();");
			}else{
				$("#send_count_id").html(s+"S");
			}
		  }
		  timer=setInterval(countDown,1000);
	}

	function queren_renzheng_id_button(){
		var queren_renzheng_id_input = $("#queren_renzheng_id_input").val();		
		if(queren_renzheng_id_input == total_send_msg && total_send_msg != 0){
			$("#button2222").attr("onclick", "shiqiandenglu();");
			$("#button2222").css("background-color", "#0171f2");
			$("#disp_id_ck").css("display", "none");
			
			if(fanyi_total == "English"){
				alert("verification");
			}else if(fanyi_total == "Chinese"){
				$("#queren_renzheng_id").html("已认证");
			}else if(fanyi_total == "Korean"){
				$("#queren_renzheng_id").html("인증완료");
			}
			$("#queren_renzheng_id_input").attr("disabled", true);
			$("#send_count_id_input").attr("disabled", true);
			$("#queren_renzheng_id").click(function(e){
				e.preventDefault();
			});
		}else{
			if(fanyi_total == "English"){
				alert("confirm your code");
			}else if(fanyi_total == "Chinese"){
				alert("验证码不正确");
			}else if(fanyi_total == "Korean"){
				alert("인증번호가 일치하지 않습니다.");
			}
			
		}
	}

	function shiqiandenglu(){
		if($("#customCheck2").prop("checked")){
			if($("#queren_renzheng_id_input").val() != ""){
				var pass = $("#send_count_id_password").val();
				var ck_pass = $("#send_count_id_password_ck").val();
				if(pass == ""){
					
if(fanyi_total == "English"){
				alert("Enter your password");
			}else if(fanyi_total == "Chinese"){
				alert("请输入密码");
			}else if(fanyi_total == "Korean"){
				alert("비밀번호를 입력하세요.");
			}
					return;
				}
				if(pass != ck_pass){
					
if(fanyi_total == "English"){
				alert("password inconsistent");
			}else if(fanyi_total == "Chinese"){
				alert("密码不一致");
			}else if(fanyi_total == "Korean"){
				alert("비밀번호 확인이 일치하지않습니다.");
			}
					return;
				}
				var total_data = {
					pass: pass,
					last_email: $("#send_count_id_input").val()
				};

				$.ajax({
					type: "POST",
					url:  "email_login_ck.php",
					data : total_data,
					async : false,
					error: function(){
					}, 
					success: function(data,status){
					  if(data == "SUCC"){
						  
if(fanyi_total == "English"){
				alert("Finish");
			}else if(fanyi_total == "Chinese"){
				alert("完成注册");
			}else if(fanyi_total == "Korean"){
				alert("사전 등록 되었습니다.");
			}
						  location.reload();
					  }else{
						  
if(fanyi_total == "English"){
						alert("Your mail has been registered.");
					}else if(fanyi_total == "Chinese"){
						alert("您的邮箱已被注册");
					}else if(fanyi_total == "Korean"){
						alert("이미 등록된 이메일 입니다.");
					}
					  }
					}
				});

			}else{
if(fanyi_total == "English"){
						alert("confirm your verification code.");
					}else if(fanyi_total == "Chinese"){
						alert("请确认验证码");
					}else if(fanyi_total == "Korean"){
						alert("인증번호 확인해주세요.");
					}
				
			}
		}else{
if(fanyi_total == "English"){
						alert("Agree to Receive our email.");
					}else if(fanyi_total == "Chinese"){
						alert("请选择同意收发邮件");
					}else if(fanyi_total == "Korean"){
						alert("체크여부를 확인하세요.");
					}
			
		}
	}

	function parsePrice(money){
		var n=4;
  		money=parseFloat((money+"").replace(/[^\d\.-]/g,"")).toFixed(n)+""; 
  		var l=money.split(".")[0].split(""); 
  		var r=money.split(".")[1]; 
  		var t=""; 
  		for(i=0;i<l.length;i++) { t+=l[i]; } 
  		return t+"."+r; 
	}

	function top_method(){ $('html').scrollTop(0); }
</script>
</body>
<iframe src="count.html" width="0" height="0"></iframe>
</html>
