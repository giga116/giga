
<!doctype html>
<!--[if lt ie 7 ]><html class="ie ie6" lang="en"> <![endif]-->
<!--[if ie 7 ]><html class="ie ie7" lang="en"> <![endif]-->
<!--[if ie 8 ]><html class="ie ie8" lang="en"> <![endif]-->
<!--[if (gte ie 9)|!(ie)]><!--><html lang="ru"> <!--<![endif]-->
<head>

    <!-- basic page needs
  ================================================== -->
	<meta charset="utf-8">
	<title>მიუნხენის ბაიერნი</title>
	<meta name="author" content="www.zerotheme.com">
	
    <!-- mobile specific metas
  ================================================== -->
	<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1">
    
    <!-- css
  ================================================== -->
  	<link rel="stylesheet" href="css/zerogrid.css">
	<link rel="stylesheet" href="css/style.css">
	<link rel="stylesheet" href="css/menu.css">
	<link rel="stylesheet" href="css/responsiveslides.css">
	<link href="font-awesome/css/font-awesome.min.css" rel="stylesheet" type="text/css">
	
	<script src="js/jquery-latest.min.js"></script>
	<script src="js/script.js"></script>
    <script src="js/jquery183.min.js"></script>
    <script src="js/responsiveslides.min.js"></script>
    <script>
		// you can also use "$(window).load(function() {"
		$(function () {
		  // slideshow 
		  $("#slider").responsiveslides({
			auto: true,
			pager: false,
			nav: true,
			speed: 500,
			namespace: "callbacks",
			before: function () {
			  $('.events').append("<li>before event fired.</li>");
			},
			after: function () {
			  $('.events').append("<li>after event fired.</li>");
			}
		  });
		});
	</script>
	
	
	<!--[if lt ie 8]>
       <div style=' clear: both; text-align:center; position: relative;'>
         <a href="http://windows.microsoft.com/en-us/internet-explorer/products/ie/home?ocid=ie6_countdown_bannercode">
           <img src="http://storage.ie6countdown.com/assets/100/images/banners/warning_bar_0000_us.jpg" border="0" height="42" width="820" alt="you are using an outdated browser. for a faster, safer browsing experience, upgrade for free today." />
        </a>
      </div>
    <![endif]-->
    <!--[if lt ie 9]>
		<script src="js/html5.js"></script>
		<script src="js/css3-mediaqueries.js"></script>
	<![endif]-->
    
</head>
<body>
<div class="wrap-body">

<!-- /////////////////////////////////////////top -->
<div class="top">
	<div class="zerogrid">
		<div class="row">
			<div class="f-left">
				<span><i class="fa fa-map-marker"></i> brooklyn, ny 10036, united states </span>
				<span><i class="fa fa-phone"></i> 1-800-123-1234; 1-800-123-5678</span>
				<span><i class="fa fa-envelope"></i> example.com</span>
			</div>
			<div class="f-right">
				<span>don't walk through life just playing football.</span>
			</div>
		</div>
	</div>
</div>

<!--////////////////////////////////////header-->
<header>
	<div class="wrap-header zerogrid">
		<div class="row">
			<div id="cssmenu">
				<ul>
				   <li class='active'><a href="index.html">home</a></li>
				   <li><a href="archive.html">blog</a></li>
				   <li><a href="single.html">about</a></li>
				   <li><a href="contact.html">contact</a></li>
				</ul>
			</div>
			<a href='index.html' class="logo"><img src="images/logo.png" /></a>
		</div>
	</div>
</header>
<div class="bg-white">
	<div class="zerogrid">
		<!-- slideshow -->
		<div class="callbacks_container">
			<ul class="rslides" id="slider">
				<li>
					<img src="images/slideshow-image1.jpg" alt="">
					<div class="caption">
						<h1>welcome to myteam</h1>
						<span >lorem ipsum dolor sit amet</span>
					</div>
				</li>
				<li>
					<img src="images/slideshow-image2.jpg" alt="">
					<div class="caption">
						<h1>welcome to myteam</h1>
						<span >lorem ipsum dolor sit amet</span>
					</div>
				</li>
				<li>
					<img src="images/slideshow-image3.jpg" alt="">
					<div class="caption">
						<h1>ბაიერნის ფანები</h1>
						<span >lorem ipsum dolor sit amet</span>
					</div>
				</li>
			</ul>
		</div>
		<div class="clear"></div>
	</div>
</div>

<!--////////////////////////////////////container-->
<section id="container" class="home-page">
	<div class="wrap-container clearfix">
		<div id="main-content">
			<section class="content-box box-1 box-style-1"><!--start box-->
				<div class="wrap-box">
					<div class="zerogrid">
						<div class="row">
							<div class="col-1-3">
								<div class="wrap-col">
									<div class="sub-title">
										<h2>featured news</h2>
									</div>
									<div class="item">
										<img src="images/5.jpg" />
										<div class="item-content">
											<a href="single.html"><h3>texas rangers finish in second place</h3></a>
											<div class="info">posted on june 22, 2010 in: <a href="#">featured</a>, <a href="#">news</a></div>
											<p>black alloys, sat nav, bluetooth, 4 seats, ceramic brakes, power boot, soft closing doors, alcantara roof lining, double glazing, keyless entry, keyless start, carbon fibre dash and door inserts, ipod connection. lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat...</p>
											<a href="#">read more</a>
										</div>
									</div>
								</div>
							</div>
							<div class="col-1-3">
								<div class="wrap-col">
									<div class="sub-title">
										<h2>upcoming events</h2>
									</div>
									<div class="row">
										<div class="item">
											<div class="item-content">
												<a href="single.html"><h3>the most epic match of the season</h3></a>
												<div class="info">posted on june 22, 2010 in: <a href="#">featured</a>, <a href="#">news</a></div>
												<p>don't walk through life just playing football. don't walk through life just being an athlete. athletics will fade. character and integrity are the...</p>
												<a href="#">read more</a>
											</div>
										</div>
									</div>
									<div class="row">
										<div class="item">
											<div class="item-content">
												<a href="single.html"><h3>pre season camp success</h3></a>
												<div class="info">posted on june 22, 2010 in: <a href="#">featured</a>, <a href="#">news</a></div>
												<p>don't walk through life just playing football. don't walk through life just being an athlete. athletics will fade. character and integrity are the...</p>
												<a href="#">read more</a>
											</div>
										</div>
									</div>
									<div class="row">
										<div class="item">
											<div class="item-content">
												<a href="single.html"><h3>nominated club of the year</h3></a>
												<div class="info">posted on june 22, 2010 in: <a href="#">featured</a>, <a href="#">news</a></div>
												<p>don't walk through life just playing football. don't walk through life just being an athlete. athletics will fade. character and integrity are the...</p>
												<a href="#">read more</a>
											</div>
										</div>
									</div>
								</div>
							</div>
							<div class="col-1-3">
								<div class="wrap-col">
									<div class="sub-title">
										<h2>upcoming game</h2>
									</div>
									<h2 style="font-size: 35px;line-height: 1.3;margin-bottom: 10px;">american eagles vs. the washington redskins</h2>
									<img src="images/4.jpg" />
									<p>don't walk through life just playing football. don't walk through life just being an athlete. athletics will fade. character and integrity are the ultimate vision, the</p>
									<a href="#">view all events at this venue</a><br>
									<a href="#" class="button bt1">buy ticket</a>
								</div>
							</div>
						</div>
					</div>
				</div>
			</section>
			<section class="content-box box-2 box-style-3"><!--start box-->
				<div class="wrap-box">
					<div class="zerogrid">
						<div class="title">
							<h2><span>our</span> team</h2>
						</div>	
						<div class="row">
							<div class="col-1-4">
								<div class="wrap-col">
									<div class="item t-center">
										<div class="item-container">
											<a href="single.html">
												<div class="item-caption">
													<div class="item-caption-inner">
														<div class="item-caption-inner1">
															<span class="user-social"><i class="fa fa-facebook"></i><i class="fa fa-twitter"></i><i class="fa fa-google-plus"></i><i class="fa fa-pinterest"></i></span>
														</div>
													</div>
												</div>
												<img src="images/user1.jpg" />
											</a>
										</div>
										<div class="item-content">
											<a href="single.html"><h3>lamborghini gallardo</h3></a>
											<p>defender</p>
										</div>
									</div>
								</div>
							</div>
							<div class="col-1-4">
								<div class="wrap-col">
									<div class="item t-center">
										<div class="item-container">
											<a href="single.html">
												<div class="item-caption">
													<div class="item-caption-inner">
														<div class="item-caption-inner1">
															<span class="user-social"><i class="fa fa-facebook"></i><i class="fa fa-twitter"></i><i class="fa fa-google-plus"></i><i class="fa fa-pinterest"></i></span>
														</div>
													</div>
												</div>
												<img src="images/user2.jpg" />
											</a>
										</div>
										<div class="item-content">
											<a href="single.html"><h3>lamborghini gallardo</h3></a>
											<p>midfielder</p>
										</div>
									</div>
								</div>
							</div>
							<div class="col-1-4">
								<div class="wrap-col">
									<div class="item t-center">
										<div class="item-container">
											<a href="single.html">
												<div class="item-caption">
													<div class="item-caption-inner">
														<div class="item-caption-inner1">
															<span class="user-social"><i class="fa fa-facebook"></i><i class="fa fa-twitter"></i><i class="fa fa-google-plus"></i><i class="fa fa-pinterest"></i></span>
														</div>
													</div>
												</div>
												<img src="images/user3.jpg" />
											</a>
										</div>
										<div class="item-content">
											<a href="single.html"><h3>lamborghini gallardo</h3></a>
											<p>goalkeeper</p>
										</div>
									</div>
								</div>
							</div>
							<div class="col-1-4">
								<div class="wrap-col">
									<div class="item t-center">
										<div class="item-container">
											<a href="single.html">
												<div class="item-caption">
													<div class="item-caption-inner">
														<div class="item-caption-inner1">
															<span class="user-social"><i class="fa fa-facebook"></i><i class="fa fa-twitter"></i><i class="fa fa-google-plus"></i><i class="fa fa-pinterest"></i></span>
														</div>
													</div>
												</div>
												<img src="images/user4.jpg" />
											</a>
										</div>
										<div class="item-content">
											<a href="single.html"><h3>lamborghini gallardo</h3></a>
											<p>sweeper</p>
										</div>
									</div>
								</div>
							</div>
						</div>
					</div>
				</div>
			</section>
			<section class="content-box box-3 box-style-2"><!--start box-->
				<div class="wrap-box t-center">
					<div class="zerogrid">
						<div class="title">
							<h2>welcome <span>to our website</span></h2>
						</div>	
						<strong>lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</strong>
						<p>ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo</p>
						<a href="#" class="button bt1">read more</a>
					</div>
				</div>
			</section>
			<section class="content-box box-4 box-style-1"><!--start box-->
				<div class="wrap-box" >
					<div class="zerogrid">
						<div class="row">
							<div class="col-1-4">
								<div class="wrap-col">
									<div class="sub-title">
										<h2>advertising</h2>
									</div>
									<div class="item">
										<img src="images/banner.jpg" />
									</div>
									<div class="item">
										<img src="images/banner2.jpg" />
									</div>
								</div>
							</div>
							<div class="col-2-4">
								<div class="wrap-col">
									<div class="sub-title">
										<h2>upcoming events</h2>
									</div>
									<div class="row">
										<div class="item">
											<div class="col-1-3">
												<div class="item-date-box">
													<div class="item-caption-inner">
														<div class="item-caption-inner1">
															<h3>30</h3>
															<span>dec,2015</span>
														</div>
													</div>
												</div>
											</div>
											<div class="col-2-3">
												<div class="item-content">
													<a href="single.html"><h3>nominated club of the year</h3></a>
													<div class="info">posted on june 22, 2010 in: <a href="#">featured</a>, <a href="#">news</a></div>
													<p>don't walk through life just playing football. don't walk through life just being an athlete. athletics will fade. character and integrity are the...</p>
												</div>
											</div>
											<div class="clear"></div>
										</div>
									</div>
									<div class="row">
										<div class="item">
											<div class="col-1-3">
												<div class="item-date-box">
													<div class="item-caption-inner">
														<div class="item-caption-inner1">
															<h3>31</h3>
															<span>dec,2015</span>
														</div>
													</div>
												</div>
											</div>
											<div class="col-2-3">
												<div class="item-content">
													<a href="single.html"><h3>nominated club of the year</h3></a>
													<div class="info">posted on june 22, 2010 in: <a href="#">featured</a>, <a href="#">news</a></div>
													<p>don't walk through life just playing football. don't walk through life just being an athlete. athletics will fade. character and integrity are the...</p>
												</div>
											</div>
											<div class="clear"></div>
										</div>
									</div>
									<div class="row">
										<div class="item">
											<div class="col-1-3">
												<div class="item-date-box">
													<div class="item-caption-inner">
														<div class="item-caption-inner1">
															<h3>18</h3>
															<span>jun,2016</span>
														</div>
													</div>
												</div>
											</div>
											<div class="col-2-3">
												<div class="item-content">
													<a href="single.html"><h3>nominated club of the year</h3></a>
													<div class="info">posted on june 22, 2010 in: <a href="#">featured</a>, <a href="#">news</a></div>
													<p>don't walk through life just playing football. don't walk through life just being an athlete. athletics will fade. character and integrity are the...</p>
												</div>
											</div>
											<div class="clear"></div>
										</div>
									</div>
								</div>
							</div>
							<div class="col-1-4">
								<div class="wrap-col">
									<div class="sub-title">
										<h2>lastest post</h2>
									</div>
									<div class="item">
										<img src="images/2.jpg" />
										<div class="item-content">
											<a href="single.html"><h3>nominated club of the year</h3></a>
											<p>black alloys, sat nav, bluetooth, 4 seats, ceramic brakes...</p>
										</div>
									</div>
									<div class="item">
										<img src="images/3.jpg" />
										<div class="item-content">
											<a href="single.html"><h3>nominated club of the year</h3></a>
											<p>black alloys, sat nav, bluetooth, 4 seats, ceramic brakes...</p>
										</div>
									</div>
								</div>
							</div>
						</div>
					</div>
				</div>
			</section>
		</div>
	</div>
</section>

<!--////////////////////////////////////footer-->
<footer>
	<div class="zerogrid top-footer">
		<div class="row">
			<div class="col-1-5">
				<a href="#"><img src="images/15.jpg" /></a>
			</div>
			<div class="col-1-5">
				<a href="#"><img src="images/16.jpg" /></a>
			</div>
			<div class="col-1-5">
				<a href="#"><img src="images/17.jpg" /></a>
			</div>
			<div class="col-1-5">
				<a href="#"><img src="images/18.jpg" /></a>
			</div>
			<div class="col-1-5">
				<a href="#"><img src="images/19.jpg" /></a>
			</div>
		</div>
	</div>
	<div class="zerogrid wrap-footer">
		<div class="row">
			<div class="col-1-4 col-footer-1">
				<div class="wrap-col">
					<h3>about us</h3>
					<p>ut volutpat consectetur aliquam. curabitur auctor in nis ulum ornare. sed consequat, augue condimentum fermentum gravida, metus elit vehicula dui.</p>
					<a href="index.html" class="logo"><img src="images/logo.png" /></a>
				</div>
			</div>
			<div class="col-1-4 col-footer-2">
				<div class="wrap-col">
					<h3>categories</h3>
					<ul>
						<li><a href="#">action</a></li>
						<li><a href="#">romantic</a></li>
						<li><a href="#">cartoon</a></li>
						<li><a href="#">zombies</a></li>
					</ul>
				</div>
			</div>
			<div class="col-1-4 col-footer-3">
				<div class="wrap-col">
					<h3>flickr photos</h3>
					<div class="row">
						<div class="col-1-3">
							<div class="wrap-col">
								<a href="#"><img src="images/6.jpg" /></a>
								<a href="#"><img src="images/7.jpg" /></a>
								<a href="#"><img src="images/8.jpg" /></a>
							</div>
						</div>
						<div class="col-1-3">
							<div class="wrap-col">
								<a href="#"><img src="images/9.jpg" /></a>
								<a href="#"><img src="images/6.jpg" /></a>
								<a href="#"><img src="images/7.jpg" /></a>
							</div>
						</div>
						<div class="col-1-3">
							<div class="wrap-col">
								<a href="#"><img src="images/6.jpg" /></a>
								<a href="#"><img src="images/7.jpg" /></a>
								<a href="#"><img src="images/8.jpg" /></a>
							</div>
						</div>
					</div>
				</div>
			</div>
			<div class="col-1-4 col-footer-4">
				<div class="wrap-col">
					<h3>contact</h3>
					<span><i class="fa fa-envelope"></i> example@sports-club.com</span>
					<span><i class="fa fa-phone"></i> 1-800-123-1234; 1-800-123-5678</span>
					<span><i class="fa fa-map-marker"></i> brooklyn, ny 10036, united states</span>
				</div>
			</div>
		</div>
	</div>
</footer>
<div class="copyright">
	<div class="zerogrid wrapper">
		copyright @ zsoccer - designed by <a href="https://www.zerotheme.com">zerotheme</a>
		<ul class="quick-link f-right">
			<li><a href="#">privacy policy</a></li>
			<li><a href="#">terms of use</a></li>
		</ul>
	</div>
</div>

</div>
</body></html>
