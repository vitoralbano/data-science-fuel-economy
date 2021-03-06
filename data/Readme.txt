<!DOCTYPE html>
<html lang="en">
<head>

	<meta charset="ISO-8859-1">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="keywords" content="fuel economy data, fuel economy guide, MPG, gas mileage, EPA, DOE, mileage guide, mileage, cars, trucks">
    <meta name="description" content="Fuel economy Fuel Economy Datafiles (1978-present), Fuel Economy Guides (1996-present)">
	
	<title>Download Fuel Economy Data</title>
	
	<!-- Core CSS files for fueleconomy.gov -->

<!-- CSS for Bootstrap -->
<link rel="stylesheet" href="/feg/assets/bs3/dist/css/bootstrap.min.css">

<link rel="stylesheet" href="//code.jquery.com/ui/1.10.4/themes/smoothness/jquery-ui.css">

<!-- CSS for FEG-specific content -->
<link rel="stylesheet" type="text/css" href="/feg/assets/css/feg.css">

<!--[if IE 8 ]> <html class="ie8"> <![endif]-->

<link rel="apple-touch-icon" href="/apple-touch-icon-144x144.png"/>
<link rel="apple-touch-icon-precomposed" href="/apple-touch-icon-144x144.png"/>

	
	<style type="text/css">
		table.std-table {width: 100%; max-width: 700px}
		.std-table td, .std-table th {border: 1px solid #ccc}
		.warning {color:#cc0000;}
	</style>

</head>

<body>

	<!-- Header and Top Navigation -->
<!-- Uses Bootstrap-based Mega Menu -->

<!-- Skip navigation for accessbility -->
<div class="skipnav"><a href="#main-content">Skip to main content</a></div>
	
	
<!-- Main Site Header -->	

<header>
	<div class="sponsor">
	<!--Sponsor row-->
		<div class="container">
			<div class="row hidden-xs" id="sponsor-head" style="margin-bottom: 4px; margin-top: 7px">
				<div class="col-sm-12">
					<a href="https://www.eere.energy.gov" target="_parent" class="pull-left"><img src="/feg/images/home/eere_logo_horiz_gray.png" alt="U.S. Department of Energy - Energy Efficiency and Renewable Energy" style="max-height: 24px"></a>
					<a href="https://www.epa.gov/otaq/" target="_parent" class="pull-right"><img src="/feg/images/home/epa_logo_gray.png" alt="U.S. Environmental Protection Agency - Office of Transportation and Air Quality" style="max-height: 24px"></a>
				</div>
			</div><!-- End of Sponsor row -->
		</div>
	</div>
	
	<!-- Logo & mini menu -->
	<div class="logo-row hidden-xs">
		<div class="container">
			<div class="row hidden-xs" id="hd">
			
				<div id="feg-logo" class="col-sm-6">
					<a href="https://www.fueleconomy.gov" target="_parent" style="text-decoration: none;"><img class="img-responsive" style="text-decoration: none;" src="/feg/images/home/fe-logo-bs.png" alt="www.fueleconomy.gov - the official government source for fuel economy information"></a>
				</div>

				<!-- Mini Menu -->
				<div id="mini-menu" class="col-sm-6 hidden-xs">
					<nav>
						<ul class="inline text-right">
							<li><a href="https://fueleconomy.gov/m">Mobile</a></li>
							<li><a href="https://www.fueleconomy.gov/feg/esIndex.shtml">Espa&ntilde;ol</a></li>
							<li><a href="https://www.fueleconomy.gov/feg/sitemap.shtml">Site Map</a></li>
							<li><a href="https://www.fueleconomy.gov/feg/links.shtml"><span class="sr-only">General </span>Links</a></li>
							<li><a href="https://www.fueleconomy.gov/feg/info.shtml">FAQ</a></li>
							<li><a href="https://www.fueleconomy.gov/feg/motorweek.jsp">Videos</a></li>
						</ul>
					</nav>
				</div><!-- end of #mini-menu -->
			  
			</div><!-- End of .row #hd -->  
		</div>
	</div><!-- End of Logo & mini menu -->  
	
</header>	

<!-- Mega Menu -->
<nav>
<div class="main-nav navbar navbar-default" role="navigation">
 <div class="container nav-container">
  <!-- Brand and toggle get grouped for better mobile display -->
  <div class="navbar-header">
	<button type="button" class="navbar-toggle" data-toggle="collapse" data-target=".navbar-ex1-collapse">
	  <span class="sr-only">Toggle navigation</span>
	  <span class="icon-bar"></span>
	  <span class="icon-bar"></span>
	  <span class="icon-bar"></span>
	</button>
	<a class="navbar-brand visible-xs" href="index.shtml"><img class="img-responsive" src="/feg/images/home/fe-brand-1a558f.png" alt="www.fueleconomy.gov - the official government source for fuel economy information"></a>
  </div>

  <!-- Collect the nav links, forms, and other content for toggling -->
  <div class="collapse navbar-collapse navbar-ex1-collapse">
	<ul class="nav navbar-nav">
	
	  <!-- Find a Car Dropdown -->
	  <li class="dropdown">
		<a href="https://www.fueleconomy.gov/feg/findacar.shtml" class="dropdown-toggle" data-toggle="dropdown">Find a Car</a>
		<ul id="searches" class="dropdown-menu row">
			<li class="col-sm-4">
			  <ul class="submenu">
				<li class="header hidden-xs">Searches</li>
				<li><a href="https://www.fueleconomy.gov/feg/findacar.shtml">Find a Car &ndash; Home</a></li>
				<li><a href="https://www.fueleconomy.gov/feg/Find.do?action=sbsSelect">Compare Side by Side</a></li>
				<li><a href="https://www.fueleconomy.gov/feg/powerSearch.jsp">Power Search</a></li>
				<li><a href="https://www.fueleconomy.gov/feg/make.shtml">Search by Make</a></li>
				<li><a href="https://www.fueleconomy.gov/feg/alternatives.shtml">Hybrids, Diesels, and Alternative Fuel Cars</a></li>
				<li><a href="https://www.fueleconomy.gov/feg/SmartWay.do">Find a SmartWay Vehicle</a></li>
				<li><a href="https://www.fueleconomy.gov/feg/best-worst.shtml">Best and Worst Vehicles</a></li>
				<li><a href="https://www.fueleconomy.gov/feg/topten.jsp">Fueleconomy.gov Top Ten</a></li>
				<li><a href="https://www.fueleconomy.gov/feg/mostViewed.shtml">Today's Most Viewed Vehicles</a></li>
				<li class="visible-xs"><a href="https://www.fueleconomy.gov/feg/UsedCarLabel.jsp">Used Car Label</a></li>
			  </ul>
			  <ul class="submenu">
				<li class="header hidden-xs">Fuel Economy Guides</li>
				<li><a href="https://www.fueleconomy.gov/feg/printGuides.shtml">Print the Guide</a></li>
				<li><a href="https://www.fueleconomy.gov/feg/guides.shtml">Help Promote Fuel Economy</a></li>
			  </ul>
			</li>
			<li class="col-sm-4 hidden-xs">
			  <ul class="submenu">
				<li class="header"><a href="https://www.fueleconomy.gov/feg/findacar.shtml">Find a Car &ndash; Home</a></li>
				<li class="hidden-xs">
					<div class="img-caption" style="width: 15.385em; height: 14.23em; *width: 15em; *height: 13.875em;">
						<a href="https://www.fueleconomy.gov/feg/findacar.shtml">
							<img src="/feg/images/topnav/findacar2_mm.jpg" alt="Photo: Couple shopping for car">
							<div class="mmcap">Find a fuel efficient vehicle that meets your needs</div>
						</a>
					</div>
				</li>
			  </ul>
			</li>
			<li class="col-sm-4 hidden-xs">
			  <ul class="submenu">
				<li class="header"><a href="https://www.fueleconomy.gov/feg/UsedCarLabel.jsp">Used Car Label</a>
				<li class="hidden-xs">
					<div class="img-caption" style="width: 15.385em; height: 14.23em; *width: 15em; *height: 13.875em;">
						<a href="https://www.fueleconomy.gov/feg/UsedCarLabel.jsp">
							<img src="/feg/images/topnav/used-label-med.png" alt="Used Car Label">
							<div class="mmcap">Selling your car? We can help you advertise its mpg.</div>
						</a>
					</div>
				</li>
			  </ul>
			</li>
		</ul>
	  </li>
	  <!-- end of Find a Car dropdown -->
	  
	  <!-- Find a Save Money and Fuel dropdown -->
	  <li class="dropdown">
		<a href="javascript:void(0);" class="dropdown-toggle" data-toggle="dropdown">Save Money & Fuel</a>
		<ul id="save" class="dropdown-menu row">
			<li class="col-sm-4">
			  <ul class="submenu">
				<li class="header"><a href="https://www.fueleconomy.gov/feg/drive.shtml">Gas Mileage Tips</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/driveHabits.jsp">Driving More Efficiently</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/maintain.jsp">Keeping Your Car in Shape</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/planning.shtml">Planning and Combining Trips</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/choosing.jsp">Choosing a More Efficient Vehicle</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/evtips.shtml">Tips for Hybrids, Plug-in Hybrids, and Electric Vehicles</a></li>		
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/coldweather.shtml">Fuel Economy in Cold Weather</a></li>	
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/hotweather.shtml">Fuel Economy in Hot Weather</a></li>	
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/moinfo.shtml">More Information</a></li>
			  </ul>
			</li>
			<li class="col-sm-4">
			  <ul class="submenu">
				<li class="header"><a href="https://www.fueleconomy.gov/feg/taxcenter.shtml">Tax Incentives</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/taxevb.shtml">All-Electric and Plug-in Hybrid Vehicles</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/taxfaqs.shtml">Frequently Asked Questions</a></li>
			 </ul>
			  <ul class="submenu">
				<li class="header"><a href="https://www.fueleconomy.gov/feg/gasprices/index.shtml">Gasoline Prices</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/gasprices/states/index.shtml">Local Prices</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/gasprices/faq.shtml">Questions About Gas Prices</a></li>
			  </ul>
			</li>
			<li class="col-sm-4">
			  <ul class="submenu">
				<li class="header hidden-xs">Cost Calculators</li>
				<li><a href="https://www.fueleconomy.gov/feg/savemoney.jsp">Fuel Savings Calculator</a></li>
				<li><a href="https://www.fueleconomy.gov/trip/">Trip Calculator</a></li>
				<li><a href="https://www.fueleconomy.gov/feg/hybridCompare.jsp">Can a Hybrid Save Me Money?</a></li>
				<li><a href="https://www.fueleconomy.gov/feg/Find.do?action=phev1Prompt">My Plug-in Hybrid Calculator</a></li>
			  </ul>
			</li>
		</ul>
	  </li>
	  <!-- end of Save Money and Fuel dropdown -->
	  
	  <!-- Benefits Dropdown -->
	  <li class="dropdown">
		<a href="https://www.fueleconomy.gov/feg/why.shtml" class="dropdown-toggle" data-toggle="dropdown">Benefits</a>
		<ul id="benefits" class="dropdown-menu row">
			<li class="col-sm-5">
			  <ul class="submenu">
				<li class="header"><a href="https://www.fueleconomy.gov/feg/why.shtml">Why is fuel economy important?</a></li>
				<li><a href="https://www.fueleconomy.gov/feg/savemoney.jsp">Save Money</a></li>
				<li><a href="https://www.fueleconomy.gov/feg/climate.shtml">Climate Change</a></li>
				<li><a href="https://www.fueleconomy.gov/feg/oildep.shtml">Oil Dependence Costs</a></li>
				<li><a href="https://www.fueleconomy.gov/feg/consres.shtml">Sustainability</a></li>
			  </ul>
			</li>
			<li class="col-sm-7 hidden-xs">
			  <ul class="submenu">
				<li class="header">
					<div class="img-caption" style="width: 19.23em; *width: 18.75em">
						<a href="https://www.fueleconomy.gov/feg/climate.shtml">
							<img class="img-responsive" src="/feg/images/topnav/HouseholdCO2Pie_mm.jpg" alt="Pie chart showing that vehicles account for about 51% of a household's carbon footprint.">
							<div class="mmcap">Vehicles produce about half of the greenhouse gases from a typical U.S. household.</div>
						</a>
					</div>
				</li>
			  </ul>
			</li>
		</ul>
	  </li>
	  <!-- end of Benefits dropdown -->		

	  <!-- My MPG Dropdown -->
	  <li class="dropdown">
		<a href="https://www.fueleconomy.gov/mpg/MPG.do" class="dropdown-toggle" data-toggle="dropdown">My MPG</a>
		<ul id="mympg" class="dropdown-menu row">
			<li class="col-sm-6">
			  <ul class="submenu">
				<li class="header"><a href="https://www.fueleconomy.gov/mpg/MPG.do">My MPG - Home</a></li>
				<li class="hidden-xs">
					<div class="img-caption" style="width: 15.385em;  height: 16.385em; *width: 15em; *height: 15.975em;">
						<a href="https://www.fueleconomy.gov/mpg/MPG.do">
							<img class="img-responsive" src="/feg/images/topnav/fuel_pump_mm.jpg" alt="Woman at fuel pump">
							<div class="mmcap">We can help you calculate and track your fuel economy.</div>
						</a>
					</div>
				</li>
			  </ul>
			</li>
			<li class="col-sm-6">
			  <ul class="submenu">
				<li class="header"><a href="https://www.fueleconomy.gov/mpg/MPG.do?action=browseList">MPG Estimates from Others</a></li>
				<li class="hidden-xs">
					<div class="img-caption" style="width: 19.23em;  height: 16.385em; *width: 18.75em; *height: 15.975em;">
						<a href="https://www.fueleconomy.gov/mpg/MPG.do?action=browseList">
							<img class="img-responsive" src="/feg/images/topnav/realworldmpg_mm.jpg" alt="Example chart showing real-world MPG">
							<div class="mmcap">MPG estimates from drivers like you!</div>
						</a>
					</div>
				</li>
			  </ul>
			</li>
		</ul>
	  </li>
	  <!-- end of My MPG dropdown -->	

	  <!-- Advanced Vehicles and Fuels dropdown -->
	  <li class="dropdown">
		<a href="javascript:void(0);" class="dropdown-toggle" data-toggle="dropdown">Advanced Cars &amp; Fuels</a>
		<ul id="advanced-vehicles" class="dropdown-menu row">
			<li class="col-sm-3">
			  <ul class="submenu">
				<li class="header"><a href="/feg/evsplash.shtml">About Hybrid and Electric Cars</a></li>
				<li class="hidden-xs">
					<a href="/feg/evsplash.shtml">
						<img class="thumbnail img-responsive" src="/feg/images/icon_plugin.gif" style="width: 80px" alt="Icon showing electrical plug-in and gas pump">
						<small>A quick guide to the different kinds of hybrids and electric vehicles.</small>
					</a>
				</li>
				
				<li class="header"><a href="https://www.fueleconomy.gov/feg/hybridtech.shtml">Hybrids</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/hybrids.jsp">Compare Side by Side</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/hybridtech.shtml">How Hybrids Work</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/hybridCompare.jsp">Can a Hybrid Can Save Me Money?</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/hybrid_news.shtml">New &amp; Upcoming</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/hybrid_links.shtml">Hybrid Links</a></li>
			  </ul>
			</li>
			
			<li class="col-sm-3">
			  <ul class="submenu">
				<li class="header"><a href="https://www.fueleconomy.gov/feg/evsbs.shtml">All-Electric Vehicles</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/evsbs.shtml">Compare Side by Side</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/evtech.shtml">About Electrics</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/evnews.shtml">New &amp; Upcoming</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/taxevb.shtml">Tax Incentives</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/evlinks.shtml">Electric Vehicle Links</a></li>
				
				<li class="header"><a href="https://www.fueleconomy.gov/feg/phevsbs.shtml">Plug-In Hybrids</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/phevsbs.shtml">Compare Side by Side</a></li>               
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/phevtech.shtml">About Plug-in Hybrids</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/phevanim.shtml">How Plug-in Hybrids Save Money <span class="glyphicon glyphicon-facetime-video"></span></a></li>
				<li><a href="https://www.fueleconomy.gov/feg/Find.do?action=phev1Prompt">My Plug-in Hybrid Calculator</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/phevnews.shtml">New &amp; Upcoming</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/taxevb.shtml">Tax Incentives</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/phevlinks.shtml">Plug-in Hybrid Links</a></li>
			  </ul>
			</li>
			
			<li class="col-sm-3">
			  <ul class="submenu">
				<li class="header"><a href="https://www.fueleconomy.gov/feg/di_diesels.shtml">Diesels</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/diesels.jsp">Compare Side by Side</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/di_diesels.shtml">About Diesels</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/dieselnews.shtml">New &amp; Upcoming</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/lowsulfurdiesel.shtml">Ultra-Low Sulfur Diesel</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/biodiesel.shtml">Biodiesel</a></li> 
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/diesellinks.shtml">Diesel Links</a></li>
					
				<li class="header"><a href="https://www.fueleconomy.gov/feg/flextech.shtml">Flex-Fuel Vehicles</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/flextech.shtml">Flex-Fuel Vehicles</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/flexlinks.shtml">Flex-Fuel Links</a></li>
			  </ul>
			</li>
			
			<li class="col-sm-3">
			  <ul class="submenu">
				<li class="header"><a href="https://www.fueleconomy.gov/feg/current.shtml">Alternative Fuels</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/ethanol.shtml">Ethanol</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/electricity.shtml">Electricity</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/biodiesel.shtml">Biodiesel</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/bifueltech.shtml">Natural Gas</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/hydrogen.shtml">Hydrogen</a></li> 
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/lpg.shtml">Propane</a></li>
				
				
				<li class="header"><a href="https://www.fueleconomy.gov/feg/fuelcell.shtml">Fuel Cell Vehicles</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/fcv_sbs.shtml">Compare Side by Side</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/fcv_PEM.shtml">How They Work</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/fcv_benefits.shtml">Benefits and Challenges</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/fcv_whatsnew.jsp">Videos </a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/fcv_links.shtml">Fuel Cell Links</a></li>
			  </ul>
			</li>
		</ul>
	  </li>
	  <!-- end of Advanced Vehicles and Fuels dropdown -->
	  
	  <!-- About EPA Ratings dropdown -->
	  <li class="dropdown">
		<a href="javascript:void(0);" class="dropdown-toggle" data-toggle="dropdown">About EPA Ratings</a>
		<ul id="epa-ratings" class="dropdown-menu row">
		
			<li class="col-sm-4">
			  <ul class="submenu">
				<li class="header"><a href="https://www.fueleconomy.gov/feg/label/">New Window Sticker</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/label/">About the New Label</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/Find.do?action=bt2">Beyond Tailpipe Emissions</a></li>
				<li class="hidden-xs"><span style="font-size: 90%">Sample Labels:</span>
					<ul style="margin-left: 2px; padding: 0 0 0 20px; font-size: 90%">
						<li><a href="https://www.fueleconomy.gov/feg/label/learn-more-gasoline-label.shtml">Gasoline Vehicles</a></li>
						<li><a href="https://www.fueleconomy.gov/feg/label/learn-more-PHEV-label.shtml">Plug-in Hybrid Vehicles</a></li>
						<li><a href="https://www.fueleconomy.gov/feg/label/learn-more-electric-label.shtml">Electric Vehicles</a></li>
					</ul>
				</li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/label/video.shtml">QR Codes</a></li>      
			  </ul>
			</li>
			
			<li class="col-sm-4">
			  <ul class="submenu">
				<li class="header"><a href="https://www.fueleconomy.gov/feg/ratings.shtml">New vs. Old Ratings</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/ratings.shtml">2017 Ratings Changes</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/comparempg.shtml">Compare Old and New MPG</a></li>
			
				<li class="header"><a href="https://www.fueleconomy.gov/feg/how_tested.shtml">Fuel Economy Tests</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/how_tested.shtml">How Vehicles Are Tested</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/which_tested.shtml">Which Vehicles Are Tested</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/fe_test_schedules.shtml">Detailed Test Information</a></li>
			  </ul>
			</li>
			
			<li class="col-sm-4">
			  <ul class="submenu">
				<li class="header"><a href="https://www.fueleconomy.gov/feg/why_differ.shtml">Your Mileage Will Vary</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/why_differ.shtml">Your Mileage Will Vary</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/factors.shtml">Factors That Affect MPG</a></li>
			  </ul>
			</li>
			
		</ul>
	  </li>
	  <!-- end of About EPA Ratings dropdown -->

	  <!-- My MPG Dropdown -->
	  <li class="dropdown">
		<a href="javascript:void(0);" class="dropdown-toggle" data-toggle="dropdown">More<span class="sr-only"> Topics</span></a>
		<ul id="more" class="dropdown-menu row">
		
			<li class="col-sm-6">
			  <ul class="submenu">
				<li class="header"><a href="https://www.fueleconomy.gov/feg/atv.shtml">Where the Energy Goes</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/atv.shtml">Gasoline Vehicles</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/atv-hev.shtml">Hybrids</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/atv-ev.shtml">Electric Cars</a></li>
				<li class="header"><a href="https://www.fueleconomy.gov/feg/tech_adv.shtml">Fuel-Saving Technologies</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/tech_engine_more.shtml">Engine Technologies</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/tech_transmission.shtml">Transmission Technologies</a></li>
				<li class="hidden-xs"><a href="https://www.fueleconomy.gov/feg/tech-other.shtml">Other Technologies</a></li>
			  </ul>
			  <ul class="submenu">
				<li class="header"><a href="https://www.fueleconomy.gov/feg/extremeMPG.jsp">Extreme MPG</a></li>
			  </ul>
			  <ul class="submenu">
				<li class="header"><a href="https://www.fueleconomy.gov/feg/toolkit.shtml">Fuel Economy Toolkit</a></li>
			  </ul>
			</li>
			
			<li class="col-sm-6">
			  <ul class="submenu">
				<li class="header"><a href="https://www.fueleconomy.gov/feg/octane.shtml">Selecting the Right Octane Fuel</a></li>
				<li class="header hidden-xs">
					<div class="img-caption" style="width: 17.5em">
						<a href="https://www.fueleconomy.gov/feg/octane.shtml">
							<img class="img-responsive" src="/feg/images/octane.jpg" alt="">
							<div class="mmcap">Answers to frequently asked questions about octane.</div>
						</a>
					</div>
				</li>
			  </ul>
			</li>
			
		</ul>
	  </li>
	  <!-- end of My MPG dropdown -->
	  
	  <!-- start of Search dropdown -->
	  <li id="searchDdParent" class="dropdown">
		<a id="search-link-menu" href="javascript: void(0);" class="dropdown-toggle" data-toggle="dropdown" style="padding-top: 8px; padding-bottom: 8px"><div id="search-icon" class="search-icon-topnav hidden-xs" style="margin-left: 5px; margin-right: 5px"></div><div class="visible-xs">Search</div></a>
		<ul id="search" class="dropdown-menu row">
			<li class="col-sm-12" style="padding-top: 1em">
				<form class="form-inline" method="get" action="/feg/search.shtml">
					<div class="form-group">
						<label for="search-text" class="sr-only">Enter vehicle or phrase.</label>
						<input id="search-text" name="words" class="form-control input-sm" type="text" placeholder="Enter vehicle or phrase">
					</div>
					<button id="go-search" class="btn btn-primary btn-sm" type="submit">Go</button>
				</form>
			</li>
		</ul>
	  
	</ul><!-- end of .nav .navbar-nav -->

  </div><!-- /.navbar-collapse -->
 </div>
 </div><!-- End of #main-nav -->
</nav>
	
	<div class="container" id="main-container">
		<div class="row">

			<div class="col-sm-12" id="main-content">	

				<a id="content"></a><a id="top"></a>
				
				<h1>Download Fuel Economy Data</h1>
                
                <p>Fuel economy data are the result of vehicle testing done at the Environmental Protection Agency's National Vehicle and Fuel Emissions Laboratory in Ann Arbor, Michigan, and by vehicle manufacturers with oversight by EPA.</p>
				<div class="well">
				<p class="warning"><img src="/feg/images/findacar/info.gif" alt="" width="16" height="16" /> EPA has issued a <a href="https://www.epa.gov/fca">Notice of Violation</a> to Fiat Chrysler Automobiles N.V. and FCA US LLC for Model Year 2014-2016 light-duty diesel 
				vehicles (Ram 1500 and Jeep Grand Cherokee). All relevant data from the affected vehicles has been removed from this website until further information is available. </p> 
				</div>
				
				<div class="well">
				<p class="warning"><img src="/feg/images/findacar/info.gif" alt="" width="16" height="16" /> In 2016, the Department of Justice alleged <a href="https://www.epa.gov/vw">violations of the Clean Air Act by Volkswagen</a> (including Audi and Porsche) covering all of Volkswagen's 2.0L and 3.0L diesel vehicles sold in the United States since model year 2009. 
								All relevant data from the affected vehicles have been removed from this website until there is an EPA-approved emissions modification. </p> 
				</div>
				<h2>Attention! Revised Estimates</h2>
                <p><a href="https://www.epa.gov/recalls/fuel-economy-label-updates#bmw">EPA Revises MPG Estimates for 2014 MINI Cooper and Cooper S</a></p>
                <p><a href="https://www.epa.gov/recalls/fuel-economy-label-updates#mercedes">EPA Revises MPG Estimates for 2013&ndash;14 Mercedes C300 4matic</a></p>
                <p><a href="https://www.epa.gov/recalls/fuel-economy-label-updates#ford">EPA Revises MPG Estimates for 2013&ndash;14 Ford Vehicles</a></p>
                <p><a href="https://www.epa.gov/recalls/fuel-economy-label-updates#hyundai">2012&ndash;13 Hyundai Data Revised (November 2, 2012)</a></p>
                <p><a href="https://www.epa.gov/recalls/fuel-economy-label-updates#kia">2012&ndash;13 Kia Data Revised (November 2, 2012)</a></p>
				
				<h2>Datasets for All Model Years (1984&ndash;2019)</h2>
				<p>(Updated: Wednesday June 13 2018)</p>
				<p class="warning"><img src="/feg/images/findacar/info.gif" alt="" width="16" height="16" /> In order to make estimates comparable across model years, the MPG estimates for all 1984-2007 model year vehicles and some 2011-2016 model year vehicles have been revised.<a href="/feg/ratings.shtml"> Learn More</a></p> 
				<p><a href="/ws/">Fueleconomy.gov Web Services for Developers</a></p> 
                <p><a href="/feg/epadata/vehicles.csv.zip">Zipped CSV File</a> (<a href="/feg/ws/index.shtml#vehicle">Documentation</a>)</p>
                <p><a href="/feg/epadata/vehicles.xml.zip">Zipped XML File</a> (<a href="/feg/ws/index.shtml#vehicle">Documentation</a>)</p>
				
				<h2>Datasets and Guides for Individual Model Years</h2>
				<p class="warning"><img src="/feg/images/findacar/info.gif" alt="" width="16" height="16" /> The MPG estimates in the files below reflect the original estimates shown on the EPA fuel Economy Label</p> 
				
				<table class="std-table">
                    <caption>Downloadable Fuel Economy Data</caption>
					<col style="width: 16%">
					<col style="width: 16%">
					<col style="width: 16%">
					<col style="width: 16%">
					<col style="width: 16%">
					<col style="width: 16%">
                    <tr class="table-header-first"> 
                        <th colspan="2">Fuel Economy Guide</th>
                        <th colspan="2">EPA Green Vehicle Guide</th>
						<th colspan="2">SmartWay Vehicle List</th>
                    </tr>
                    <tr class="table-header-first"> 
						<th>Datafile<sup>1</sup></th>
						<th>Printed Guide<sup>2</sup></th>
						<th>Datafile<sup>3</sup></th>
						<th>Printed Guide</th>
						<th>Datafile<sup>3</sup></th>
						<th>Printed Guide</th>
                    </tr>
					<tr>
						<td><a href="epadata/19data.zip">2019 Datafile<img src="/feg/images/icons/icon_zip.gif" alt="Zip File Icon" class="icon"></a></td>
						<td><a href="pdfs/guides/FEG2019.pdf">2019 Guide(Preliminary)<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
						<td><a href="EPAGreenGuide/xls/all_alpha_19.xlsx">2019 Guide<img src="/feg/images/icons/icon_excel.gif" alt="Excel Icon" class="icon"></a> /
							<a href="EPAGreenGuide/txt/all_alpha_19.txt">(TXT)</a></td>
						<td><a href="EPAGreenGuide/pdf/all_alpha_19.pdf">2019 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
						<td><a href="/feg/EPAGreenGuide/Smartway/xls/SmartWay Vehicle List for MY 2019.xlsx">2019 Data<img src="/feg/images/icons/icon_excel.gif" alt="Excel Icon" class="icon"></a></td>
						<td><a href="/feg/EPAGreenGuide/Smartway/pdf/SmartWay Vehicle List for MY 2019.pdf">2019 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
                    </tr>
                    <tr>
						<td><a href="epadata/18data.zip">2018 Datafile<img src="/feg/images/icons/icon_zip.gif" alt="Zip File Icon" class="icon"></a></td>
						<td><a href="pdfs/guides/FEG2018.pdf">2018 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
						<td><a href="EPAGreenGuide/xls/all_alpha_18.xlsx">2018 Guide<img src="/feg/images/icons/icon_excel.gif" alt="Excel Icon" class="icon"></a> /
							<a href="EPAGreenGuide/txt/all_alpha_18.txt">(TXT)</a></td>
						<td><a href="EPAGreenGuide/pdf/all_alpha_18.pdf">2018 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
						<td><a href="/feg/EPAGreenGuide/Smartway/xls/SmartWay Vehicle List for MY 2018.xlsx">2018 Data<img src="/feg/images/icons/icon_excel.gif" alt="Excel Icon" class="icon"></a></td>
						<td><a href="/feg/EPAGreenGuide/Smartway/pdf/SmartWay Vehicle List for MY 2018.pdf">2018 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
                    </tr>
                    <tr>
						<td><a href="epadata/17data.zip">2017 Datafile<img src="/feg/images/icons/icon_zip.gif" alt="Zip File Icon" class="icon"></a></td>
						<td><a href="pdfs/guides/FEG2017.pdf">2017 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
						<td><a href="EPAGreenGuide/xls/all_alpha_17.xlsx">2017 Guide<img src="/feg/images/icons/icon_excel.gif" alt="Excel Icon" class="icon"></a> /
							<a href="EPAGreenGuide/txt/all_alpha_17.txt">(TXT)</a></td>
						<td><a href="EPAGreenGuide/pdf/all_alpha_17.pdf">2017 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
						<td><a href="/feg/EPAGreenGuide/Smartway/xls/SmartWay Vehicle List for MY 2017.xlsx">2017 Data<img src="/feg/images/icons/icon_excel.gif" alt="Excel Icon" class="icon"></a></td>
						<td><a href="/feg/EPAGreenGuide/Smartway/pdf/SmartWay Vehicle List for MY 2017.pdf">2017 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
                    </tr>
                    <tr>
						<td><a href="epadata/16data.zip">2016 Datafile<img src="/feg/images/icons/icon_zip.gif" alt="Zip File Icon" class="icon"></a></td>
						<td><a href="pdfs/guides/FEG2016.pdf">2016 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
						<td><a href="EPAGreenGuide/xls/all_alpha_16.xlsx">2016 Guide<img src="/feg/images/icons/icon_excel.gif" alt="Excel Icon" class="icon"></a> /
							<a href="EPAGreenGuide/txt/all_alpha_16.txt">(TXT)</a></td>
						<td><a href="EPAGreenGuide/pdf/all_alpha_16.pdf">2016 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
						<td><a href="/feg/EPAGreenGuide/Smartway/xls/SmartWay Vehicle List for MY 2016.xlsx">2016 Data<img src="/feg/images/icons/icon_excel.gif" alt="Excel Icon" class="icon"></a></td>
						<td><a href="/feg/EPAGreenGuide/Smartway/pdf/SmartWay Vehicle List for MY 2016.pdf">2016 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
                    </tr>
                    <tr>
						<td><a href="epadata/15data.zip">2015 Datafile<img src="/feg/images/icons/icon_zip.gif" alt="Zip File Icon" class="icon"></a></td>
						<td><a href="pdfs/guides/FEG2015.pdf">2015 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
						<td>
							<a href="EPAGreenGuide/xls/all_alpha_15.xlsx">2015 Guide<img src="/feg/images/icons/icon_excel.gif" alt="Excel Icon" class="icon"></a> /
							<a href="EPAGreenGuide/txt/all_alpha_15.txt">(TXT)</a>
						</td>
						<td><a href="EPAGreenGuide/pdf/all_alpha_15.pdf">2015 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
						<td><a href="/feg/EPAGreenGuide/Smartway/xls/SmartWay Vehicle List for MY 2015.xlsx">2015 Data<img src="/feg/images/icons/icon_excel.gif" alt="Excel Icon" class="icon"></a></td>
						<td><a href="/feg/EPAGreenGuide/Smartway/pdf/SmartWay Vehicle List for MY 2015.pdf">2015 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
                    </tr>
                    <tr>
						<td><a href="epadata/14data.zip">2014 Datafile<img src="/feg/images/icons/icon_zip.gif" alt="Zip File Icon" class="icon"></a></td>
						<td><a href="pdfs/guides/FEG2014.pdf">2014 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
						<td>
							<a href="EPAGreenGuide/xls/all_alpha_14.xlsx">2014 Guide<img src="/feg/images/icons/icon_excel.gif" alt="Excel Icon" class="icon"></a> /
							<a href="EPAGreenGuide/txt/all_alpha_14.txt">(TXT)</a>
						</td>
						<td><a href="EPAGreenGuide/pdf/all_alpha_14.pdf">2014 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
						<td><a href="/feg/EPAGreenGuide/Smartway/xls/SmartWay Vehicle List for MY 2014.xlsx">2014 Data<img src="/feg/images/icons/icon_excel.gif" alt="Excel Icon" class="icon"></a></td>
						<td><a href="/feg/EPAGreenGuide/Smartway/pdf/SmartWay Vehicle List for MY 2014.pdf">2014 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
                    </tr>
                    <tr>
						<td><a href="epadata/13data.zip">2013 Datafile<img src="/feg/images/icons/icon_zip.gif" alt="Zip File Icon" class="icon"></a></td>
						<td><a href="pdfs/guides/FEG2013.pdf">2013 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
						<td>
							<a href="EPAGreenGuide/xls/all_alpha_13.xlsx">2013 Guide<img src="/feg/images/icons/icon_excel.gif" alt="Excel Icon" class="icon"></a> /
							<a href="EPAGreenGuide/txt/all_alpha_13.txt">(TXT)</a>
						</td>
						<td><a href="EPAGreenGuide/pdf/all_alpha_13.pdf">2013 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
						<td><a href="/feg/EPAGreenGuide/Smartway/xls/SmartWay Vehicle List for MY 2013.xlsx">2013 Data<img src="/feg/images/icons/icon_excel.gif" alt="Excel Icon" class="icon"></a></td>
						<td><a href="/feg/EPAGreenGuide/Smartway/pdf/SmartWay Vehicle List for MY 2013.pdf">2013 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
                    </tr>
                    <tr>
						<td><a href="epadata/12data.zip">2012 Datafile<img src="/feg/images/icons/icon_zip.gif" alt="Zip File Icon" class="icon"></a></td>
						<td><a href="pdfs/guides/FEG2012.pdf">2012 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
						<td>
							<a href="EPAGreenGuide/xls/all_alpha_12.xlsx">2012 Guide<img src="/feg/images/icons/icon_excel.gif" alt="Excel Icon" class="icon"></a> /
							<a href="EPAGreenGuide/txt/all_alpha_12.txt">(TXT)</a>
						</td>
						<td><a href="EPAGreenGuide/pdf/all_alpha_12.pdf">2012 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
						<td><a href="/feg/EPAGreenGuide/Smartway/xls/SmartWay Vehicle List for MY 2012.xlsx">2012 Data<img src="/feg/images/icons/icon_excel.gif" alt="Excel Icon" class="icon"></a></td>
						<td><a href="/feg/EPAGreenGuide/Smartway/pdf/SmartWay Vehicle List for MY 2012.pdf">2012 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
                    </tr>
                    <tr>
						<td><a href="epadata/11data.zip">2011 Datafile<img src="/feg/images/icons/icon_zip.gif" alt="Zip File Icon" class="icon"></a></td>
						<td><a href="pdfs/guides/FEG2011.pdf">2011 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
						<td>
							<a href="EPAGreenGuide/xls/all_alpha_11.xlsx">2011 Guide<img src="/feg/images/icons/icon_excel.gif" alt="Excel Icon" class="icon"></a> /
							<a href="EPAGreenGuide/txt/all_alpha_11.txt">(TXT)</a>
						</td>
						<td><a href="EPAGreenGuide/pdf/all_alpha_11.pdf">2011 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
						<td><a href="/feg/EPAGreenGuide/Smartway/xls/SmartWay Vehicle List for MY 2011.xlsx">2011 Data<img src="/feg/images/icons/icon_excel.gif" alt="Excel Icon" class="icon"></a></td>
						<td><a href="/feg/EPAGreenGuide/Smartway/pdf/SmartWay Vehicle List for MY 2011.pdf">2011 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
                    </tr>
                    <tr>
						<td><a href="epadata/10data.zip">2010 Datafile<img src="/feg/images/icons/icon_zip.gif" alt="Zip File Icon" class="icon"></a></td>
						<td><a href="pdfs/guides/FEG2010.pdf">2010 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
						<td>
							<a href="EPAGreenGuide/xls/all_alpha_10.xls">2010 Guide<img src="/feg/images/icons/icon_excel.gif" alt="Excel Icon" class="icon"></a> /
							<a href="EPAGreenGuide/txt/all_alpha_10.txt">(TXT)</a>
						</td>
						<td><a href="EPAGreenGuide/pdf/all_alpha_10.pdf">2010 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
						<td><a href="/feg/EPAGreenGuide/Smartway/xls/SmartWay Vehicle List MY 2010.xls">2010 Data<img src="/feg/images/icons/icon_excel.gif" alt="Excel Icon" class="icon"></a></td>
						<td><a href="/feg/EPAGreenGuide/Smartway/pdf/SmartWay Vehicle List MY 2010.pdf">2010 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
                    </tr>
                    <tr>
						<td><a href="epadata/09data.zip">2009 Datafile<img src="/feg/images/icons/icon_zip.gif" alt="Zip File Icon" class="icon"></a></td>
						<td><a href="pdfs/guides/FEG2009.pdf">2009 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
						<td>
							<a href="EPAGreenGuide/xls/all_alpha_09.xls">2009 Guide<img src="/feg/images/icons/icon_excel.gif" alt="Excel Icon" class="icon"></a> /
							<a href="EPAGreenGuide/txt/all_alpha_09.txt">(TXT)</a>
						</td>
						<td><a href="EPAGreenGuide/pdf/all_alpha_09.pdf">2009 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
						<td><a href="/feg/EPAGreenGuide/Smartway/xls/SmartWay Vehicle List MY 2009.xls">2009 Data<img src="/feg/images/icons/icon_excel.gif" alt="Excel Icon" class="icon"></a></td>
						<td><a href="/feg/EPAGreenGuide/Smartway/pdf/SmartWay Vehicle List MY 2009.pdf">2009 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
                    </tr>
                    <tr> 
						<td><a href="epadata/08data.zip">2008 Datafile<img src="/feg/images/icons/icon_zip.gif" alt="Zip File Icon" class="icon"></a></td>
						<td><a href="pdfs/guides/FEG2008.pdf">2008 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
						<td>
							<a href="EPAGreenGuide/xls/all_alpha_08.xls">2008 Guide<img src="/feg/images/icons/icon_excel.gif" alt="Excel Icon" class="icon"></a> /
							<a href="EPAGreenGuide/txt/all_alpha_08.txt">(TXT)</a>
						</td>
						<td><a href="EPAGreenGuide/pdf/all_alpha_08.pdf">2008 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
						<td><a href="/feg/EPAGreenGuide/Smartway/xls/SmartWay Vehicle List MY 2008.xls">2008 Data<img src="/feg/images/icons/icon_excel.gif" alt="Excel Icon" class="icon"></a></td>
						<td><a href="/feg/EPAGreenGuide/Smartway/pdf/SmartWay Vehicle List MY 2008.pdf">2008 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
                    </tr>
                    <tr>
						<td><a href="epadata/07data.zip">2007 Datafile<img src="/feg/images/icons/icon_zip.gif" alt="Zip File Icon" class="icon"></a></td>
						<td><a href="pdfs/guides/FEG2007.pdf">2007 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
						<td>
							<a href="EPAGreenGuide/xls/all_alpha_07.xls">2007 Guide<img src="/feg/images/icons/icon_excel.gif" alt="Excel Icon" class="icon"></a> /
							<a href="EPAGreenGuide/txt/all_alpha_07.txt">(TXT)</a>
						</td>
						<td><a href="EPAGreenGuide/pdf/all_alpha_07.pdf">2007 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
						<td><a href="/feg/EPAGreenGuide/Smartway/xls/SmartWay Vehicle List MY 2007.xls">2007 Data<img src="/feg/images/icons/icon_excel.gif" alt="Excel Icon" class="icon"></a></td>
						<td><a href="/feg/EPAGreenGuide/Smartway/pdf/SmartWay Vehicle List MY 2007.pdf">2007 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
                    </tr>
                    <tr> 
						<td><a href="epadata/06data.zip">2006 Datafile<img src="/feg/images/icons/icon_zip.gif" alt="Zip File Icon" class="icon"></a></td>
						<td><a href="pdfs/guides/FEG2006.pdf">2006 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
						<td>
							<a href="EPAGreenGuide/xls/all_alpha_06.xls">2006 Guide<img src="/feg/images/icons/icon_excel.gif" alt="Excel Icon" class="icon"></a> /
							<a href="EPAGreenGuide/txt/all_alpha_06.txt">(TXT)</a>
						</td>
						<td><a href="EPAGreenGuide/pdf/all_alpha_06.pdf">2006 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
						<td><a href="/feg/EPAGreenGuide/Smartway/xls/SmartWay Vehicle List MY 2006.xls">2006 Data<img src="/feg/images/icons/icon_excel.gif" alt="Excel Icon" class="icon"></a></td>
						<td><a href="/feg/EPAGreenGuide/Smartway/pdf/SmartWay Vehicle List MY 2006.pdf">2006 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
                    </tr>
                    <tr> 
						<td><a href="epadata/05data.zip">2005 Datafile<img src="/feg/images/icons/icon_zip.gif" alt="Zip File Icon" class="icon"></a></td>
						<td><a href="pdfs/guides/FEG2005.pdf">2005 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
						<td>
							<a href="EPAGreenGuide/xls/all_alpha_05.xls">2005 Guide<img src="/feg/images/icons/icon_excel.gif" alt="Excel Icon" class="icon"></a> /
							<a href="EPAGreenGuide/txt/all_alpha_05.txt">(TXT)</a>
						</td>
						<td><a href="EPAGreenGuide/pdf/all_alpha_05.pdf">2005 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
						<td><a href="/feg/EPAGreenGuide/Smartway/xls/SmartWay Vehicle List MY 2005.xls">2005 Data<img src="/feg/images/icons/icon_excel.gif" alt="Excel Icon" class="icon"></a></td>
						<td><a href="/feg/EPAGreenGuide/Smartway/pdf/SmartWay Vehicle List MY 2005.pdf">2005 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
                    </tr>
                    <tr> 
						<td><a href="epadata/04data.zip">2004 Datafile<img src="/feg/images/icons/icon_zip.gif" alt="Zip File Icon" class="icon"></a></td>
						<td><a href="pdfs/guides/FEG2004.pdf">2004 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
						<td>
							<a href="EPAGreenGuide/xls/all_alpha_04.xls">2004 Guide<img src="/feg/images/icons/icon_excel.gif" alt="Excel Icon" class="icon"></a> /
							<a href="EPAGreenGuide/txt/all_alpha_04.txt">(TXT)</a>
						</td>
						<td><a href="EPAGreenGuide/pdf/all_alpha_04.pdf">2004 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
						<td><a href="/feg/EPAGreenGuide/Smartway/xls/SmartWay Vehicle List MY 2004.xls">2004 Data<img src="/feg/images/icons/icon_excel.gif" alt="Excel Icon" class="icon"></a></td>
						<td><a href="/feg/EPAGreenGuide/Smartway/pdf/SmartWay Vehicle List MY 2004.pdf">2004 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
                    </tr>
                    <tr> 
						<td><a href="epadata/03data.zip">2003 Datafile<img src="/feg/images/icons/icon_zip.gif" alt="Zip File Icon" class="icon"></a></td>
						<td><a href="pdfs/guides/FEG2003.pdf">2003 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
						<td>
							<a href="EPAGreenGuide/xls/all_alpha_03.xls">2003 Guide<img src="/feg/images/icons/icon_excel.gif" alt="Excel Icon" class="icon"></a> /
							<a href="EPAGreenGuide/txt/all_alpha_03.txt">(TXT)</a>
						</td>
						<td><a href="EPAGreenGuide/pdf/all_alpha_03.pdf">2003 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
						<td><a href="/feg/EPAGreenGuide/Smartway/xls/SmartWay Vehicle List MY 2003.xls">2003 Data<img src="/feg/images/icons/icon_excel.gif" alt="Excel Icon" class="icon"></a></td>
						<td><a href="/feg/EPAGreenGuide/Smartway/pdf/SmartWay Vehicle List MY 2003.pdf">2003 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
                    </tr>
                    <tr> 
						<td><a href="epadata/02data.zip">2002 Datafile<img src="/feg/images/icons/icon_zip.gif" alt="Zip File Icon" class="icon"></a></td>
						<td><a href="pdfs/guides/FEG2002.pdf">2002 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
						<td>
							<a href="EPAGreenGuide/xls/all_alpha_02.xls">2002 Guide<img src="/feg/images/icons/icon_excel.gif" alt="Excel Icon" class="icon"></a> /
							<a href="EPAGreenGuide/txt/all_alpha_02.txt">(TXT)</a>
						</td>
						<td><a href="EPAGreenGuide/pdf/all_alpha_02.pdf">2002 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
						<td><a href="/feg/EPAGreenGuide/Smartway/xls/SmartWay Vehicle List MY 2002.xls">2002 Data<img src="/feg/images/icons/icon_excel.gif" alt="Excel Icon" class="icon"></a></td>
						<td><a href="/feg/EPAGreenGuide/Smartway/pdf/SmartWay Vehicle List MY 2002.pdf">2002 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
                    </tr>
                    <tr> 
						<td><a href="epadata/01data.zip">2001 Datafile<img src="/feg/images/icons/icon_zip.gif" alt="Zip File Icon" class="icon"></a></td>
						<td><a href="pdfs/guides/FEG2001.pdf">2001 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a>
						<br>
						<a href="pdfs/guides/2001volume.PDF">Interior Volumes<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
						<td>
							<a href="EPAGreenGuide/xls/all_alpha_01.xls">2001 Guide<img src="/feg/images/icons/icon_excel.gif" alt="Excel Icon" class="icon"></a> /
							<a href="EPAGreenGuide/txt/all_alpha_01.txt">(TXT)</a>
						</td>
						<td><a href="EPAGreenGuide/pdf/all_alpha_01.pdf">2001 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
						<td><a href="/feg/EPAGreenGuide/Smartway/xls/SmartWay Vehicle List MY 2001.xls">2001 Data<img src="/feg/images/icons/icon_excel.gif" alt="Excel Icon" class="icon"></a></td>
						<td><a href="/feg/EPAGreenGuide/Smartway/pdf/SmartWay Vehicle List MY 2001.pdf">2001 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
                    </tr>
                    <tr> 
						<td><a href="epadata/00data.zip">2000 Datafile<img src="/feg/images/icons/icon_zip.gif" alt="Zip File Icon" class="icon"></a></td>
						<td>
							<a href="pdfs/guides/FEG2000.pdf">2000 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a>
							<br>
							<a href="pdfs/guides/volume.pdf">Interior Volumes<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a>
						</td>
						<td>
							<a href="EPAGreenGuide/xls/all_alpha_00.xls">2000 Guide<img src="/feg/images/icons/icon_excel.gif" alt="Excel Icon" class="icon"></a> /
							<a href="EPAGreenGuide/txt/all_alpha_00.txt">(TXT)</a>
						</td>
						<td><a href="EPAGreenGuide/pdf/all_alpha_00.pdf">2000 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
						<td><a href="/feg/EPAGreenGuide/Smartway/xls/SmartWay Vehicle List MY 2000.xls">2000 Data<img src="/feg/images/icons/icon_excel.gif" alt="Excel Icon" class="icon"></a></td>
						<td><a href="/feg/EPAGreenGuide/Smartway/pdf/SmartWay Vehicle List MY 2000.pdf">2000 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
                    </tr>
                    <tr> 
						<td><a href="epadata/99guide.zip">1999 Datafile<img src="/feg/images/icons/icon_zip.gif" alt="Zip File Icon" class="icon"></a></td>
						<td><a href="epadata/99feg.pdf">1999 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
						<td></td>
						<td></td>
						<td></td>
						<td></td>
                    </tr>
                    <tr> 
						<td><a href="epadata/98guide6.zip">1998 Datafile<img src="/feg/images/icons/icon_zip.gif" alt="Zip File Icon" class="icon"></a></td>
						<td><a href="epadata/98feg.pdf">1998 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
						<td></td>
						<td></td>
						<td></td>
						<td></td>
                    </tr>
                    <tr> 
						<td><a href="epadata/97mfgui.zip">1997 Datafile<img src="/feg/images/icons/icon_zip.gif" alt="Zip File Icon" class="icon"></a></td>
						<td><a href="epadata/97feg.pdf">1997 Guide<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></td>
						<td></td>
						<td></td>
						<td></td>
						<td></td>
                    </tr>
                    <tr> 
						<td><a href="epadata/96mfgui.zip">1996 Datafile<img src="/feg/images/icons/icon_zip.gif" alt="Zip File Icon" class="icon"></a></td>
						<td><a href="epadata/96guide.txt">1996 Guide (TXT)</a></td>
						<td></td>
						<td></td>
						<td></td>
						<td></td>
                    </tr>
                    <tr> 
						<td><a href="epadata/95mfgui.zip">1995 Datafile<img src="/feg/images/icons/icon_zip.gif" alt="Zip File Icon" class="icon"></a></td>
						<td><a href="epadata/95guide.txt">1995 Guide (TXT)</a></td>
						<td></td>
						<td></td>
						<td></td>
						<td></td>
                    </tr>
                    <tr> 
						<td><a href="epadata/94mfgui.zip">1994 Datafile<img src="/feg/images/icons/icon_zip.gif" alt="Zip File Icon" class="icon"></a></td>
						<td><a href="epadata/94guide.txt">1994 Guide (TXT)</a></td>
						<td></td>
						<td></td>
						<td></td>
						<td></td>
                    </tr>
                    <tr> 
						<td><a href="epadata/93mfgui.zip">1993 Datafile<img src="/feg/images/icons/icon_zip.gif" alt="Zip File Icon" class="icon"></a></td>
						<td><a href="epadata/93guide.txt">1993 Guide (TXT)</a></td>
						<td></td>
						<td></td>
						<td></td>
						<td></td>
                    </tr>
                    <tr> 
						<td><a href="epadata/92mfgui.zip">1992 Datafile<img src="/feg/images/icons/icon_zip.gif" alt="Zip File Icon" class="icon"></a></td>
						<td><a href="epadata/92guide.txt">1992 Guide (TXT)</a></td>
						<td></td>
						<td></td>
						<td></td>
						<td></td>
                    </tr>
                    <tr> 
						<td><a href="epadata/91mfgui.zip">1991 Datafile<img src="/feg/images/icons/icon_zip.gif" alt="Zip File Icon" class="icon"></a></td>
						<td><a href="epadata/91guide.txt">1991 Guide (TXT)</a></td>
						<td></td>
						<td></td>
						<td></td>
						<td></td>
                    </tr>
                    <tr> 
						<td><a href="epadata/90mfgui.zip">1990 Datafile<img src="/feg/images/icons/icon_zip.gif" alt="Zip File Icon" class="icon"></a></td>
						<td><a href="epadata/90guide.txt">1990 Guide (TXT)</a></td>
						<td></td>
						<td></td>
						<td></td>
						<td></td>
                    </tr>
                    <tr> 
						<td><a href="epadata/89mfgui.zip">1989 Datafile<img src="/feg/images/icons/icon_zip.gif" alt="Zip File Icon" class="icon"></a></td>
						<td><a href="epadata/89guide.txt">1989 Guide (TXT)</a></td>
						<td></td>
						<td></td>
						<td></td>
						<td></td>
                    </tr>
                    <tr> 
						<td><a href="epadata/88mfgui.zip">1988 Datafile<img src="/feg/images/icons/icon_zip.gif" alt="Zip File Icon" class="icon"></a></td>
						<td><a href="epadata/88guide.txt">1988 Guide (TXT)</a></td>
						<td></td>
						<td></td>
						<td></td>
						<td></td>
                    </tr>
                    <tr> 
						<td><a href="epadata/87mfgui.zip">1987 Datafile<img src="/feg/images/icons/icon_zip.gif" alt="Zip File Icon" class="icon"></a></td>
						<td><a href="epadata/87guide.txt">1987 Guide (TXT)</a></td>
						<td></td>
						<td></td>
						<td></td>
						<td></td>
                    </tr>
                    <tr> 
						<td><a href="epadata/86mfgui.zip">1986 Datafile<img src="/feg/images/icons/icon_zip.gif" alt="Zip File Icon" class="icon"></a></td>
						<td><a href="epadata/86guide.txt">1986 Guide (TXT)</a></td>
						<td></td>
						<td></td>
						<td></td>
						<td></td>
                    </tr>
                    <tr> 
						<td><a href="epadata/85mfgui.zip">1985 Datafile<img src="/feg/images/icons/icon_zip.gif" alt="Zip File Icon" class="icon"></a></td>
						<td><a href="epadata/85guide.txt">1985 Guide (TXT)</a></td>
						<td></td>
						<td></td>
						<td></td>
						<td></td>
                    </tr>
                    <tr> 
						<td><a href="epadata/84mfgui.zip">1984 Datafile<img src="/feg/images/icons/icon_zip.gif" alt="Zip File Icon" class="icon"></a></td>
						<td><a href="epadata/84guide.txt">1984 Guide (TXT)</a></td>
						<td></td>
						<td></td>
						<td></td>
						<td></td>
                    </tr>
                    <tr> 
						<td><a href="epadata/83data.zip">1983 Datafile<img src="/feg/images/icons/icon_zip.gif" alt="Zip File Icon" class="icon"></a></td>
						<td><a href="epadata/83guide.txt">1983 Guide (TXT)</a></td>
						<td></td>
						<td></td>
						<td></td>
						<td></td>
                    </tr>
                    <tr> 
						<td><a href="epadata/82data.zip">1982 Datafile<img src="/feg/images/icons/icon_zip.gif" alt="Zip File Icon" class="icon"></a></td>
						<td><a href="epadata/82guide.txt">1982 Guide (TXT)</a></td>
						<td></td>
						<td></td>
						<td></td>
						<td></td>
                    </tr>
                    <tr> 
						<td><a href="epadata/81data.zip">1981 Datafile<img src="/feg/images/icons/icon_zip.gif" alt="Zip File Icon" class="icon"></a></td>
						<td><a href="epadata/81guide.txt">1981 Guide (TXT)</a></td>
						<td></td>
						<td></td>
						<td></td>
						<td></td>
                    </tr>
                    <tr> 
						<td><a href="epadata/80data.zip">1980 Datafile<img src="/feg/images/icons/icon_zip.gif" alt="Zip File Icon" class="icon"></a></td>
						<td><a href="epadata/80guide.txt">1980 Guide (TXT)</a></td>
						<td></td>
						<td></td>
						<td></td>
						<td></td>
                    </tr>
                    <tr> 
						<td><a href="epadata/79data.zip">1979 Datafile<img src="/feg/images/icons/icon_zip.gif" alt="Zip File Icon" class="icon"></a></td>
						<td><a href="epadata/79guide.txt">1979 Guide (TXT)</a></td>
						<td></td>
						<td></td>
						<td></td>
						<td></td>
                    </tr>
                    <tr> 
						<td><a href="epadata/78data.zip">1978 Datafile<img src="/feg/images/icons/icon_zip.gif" alt="Zip File Icon" class="icon"></a></td>
						<td><a href="epadata/78guide.txt">1978 Guide (TXT)</a></td>
						<td></td>
						<td></td>
						<td></td>
						<td></td>
                    </tr>
                    <tr> 
						<td></td>
						<td><a href="pdfs/guides/FEG1977.pdf">1977 Guide (PDF)</a></td>
						<td></td>
						<td></td>
						<td></td>
						<td></td>
                    </tr>
                    <tr> 
						<td></td>
						<td><a href="pdfs/guides/FEG1976.pdf">1976 Guide (PDF)</a></td>
						<td></td>
						<td></td>
						<td></td>
						<td></td>
                    </tr>
                    <tr> 
						<td></td>
						<td><a href="pdfs/guides/FEG1975.pdf">1975 Guide (PDF)</a></td>
						<td></td>
						<td></td>
						<td></td>
						<td></td>
                    </tr>
                    <tr> 
						<td></td>
						<td><a href="pdfs/guides/FEG1974.pdf">1974 Guide (PDF)</a></td>
						<td></td>
						<td></td>
						<td></td>
						<td></td>
                    </tr>
                    
                    
                  </table>
				  
				  <p class="table-note"><sup>1</sup>Data files have been <a href="http://windows.microsoft.com/en-us/windows/compress-uncompress-files-zip-files#1TC=windows-7">compressed</a> into *.zip files, which must be downloaded to your computer/device and unzipped before they can be used. The data files are formatted as comma-separated value files (*.csv) for import into database or spreadsheet tables (<a href="epadata/Readme.txt">documentation</a>). The 1998 and 1999 data are also available as  Excel spreadsheets&#8212;included in their respective *.zip files.</p>
				  <p class="table-note"><sup>2</sup>Annual fuel costs shown in 1997-2014 Fuel Economy Guides are based on fuel prices when the guide was originally printed. Annual fuel cost estimates based on current prices are available in <a href="findacar.shtml">Find and Compare Cars</a>  </p>
				  <p class="table-note"><sup>3</sup><a href="EPAGreenGuide/GreenVehicleGuideDocumentation.pdf">EPA Green Vehicle Guide and SmartWay List Documentation<img src="/feg/images/icons/icon_pdf.gif" alt="Adobe Acrobat Icon" class="icon"></a></p>	
			</div><!-- end of #main-content -->		

		</div><!-- end of .row -->

		<div id="ft" role="contentinfo">
	<nav>
		<span class="visible-xs" style="display: inline">
			  <a href="//www.fueleconomy.gov/m/">Mobile</a>
			| <a href="//www.fueleconomy.gov/feg/esIndex.shtml">Espa&ntilde;ol</a>
			| <a href="//www.fueleconomy.gov/feg/sitemap.shtml">Site Map</a>
			| <a href="//www.fueleconomy.gov/feg/links.shtml"><span class="sr-only">General </span>Links</a>
			| <a href="//www.fueleconomy.gov/feg/info.shtml">FAQ</a>
			| <a href="//www.fueleconomy.gov/feg/contacts.shtml">Contacts</a>
			| <a href="//www.usa.gov">USA.gov</a>
			| <a href="//www.fueleconomy.gov/feg/ORNL-disclaimer.htm">Privacy/Security</a>
			| <a href="mailto:fueleconomy@ornl.gov">Feedback</a>
		</span>
		<span class="hidden-xs" style="display: inline">
			  <a href="//www.fueleconomy.gov/feg/contacts.shtml">Contacts</a>
			| <a href="//www.fueleconomy.gov/feg/download.shtml">Download&nbsp;EPA's&nbsp;MPG Ratings</a> 
			| <a href="//www.fueleconomy.gov/feg/bymake/bymanuNF.shtml">Find&nbsp;and&nbsp;Compare&nbsp;Cars</a>
			| <a href="//www.usa.gov">USA.gov</a>
			| <a href="//www.fueleconomy.gov/feg/dealers.shtml">Info&nbsp;for&nbsp;Auto&nbsp;Dealers</a>
			| <a href="//www.fueleconomy.gov/feg/ORNL-disclaimer.htm">Privacy/Security</a>
			| <a href="mailto:fueleconomy@ornl.gov">Feedback</a>
		</span>
	</nav>
</div><!-- end of #ft -->

<!--Sponsor row-->
<div class="row sponsor-foot visible-xs">

	<div class="col-xs-7">
		<a href="//www.eere.energy.gov" target="_parent"><img class="img-responsive" src="/feg/images/home/eere_logo_horiz_gray.png" alt="U.S. Department of Energy - Energy Efficiency and Renewable Energy" style="max-height: 24px"></a>
	</div>
	<div class="col-xs-5">
		<a href="//www.epa.gov/otaq/" target="_parent"><img class="img-responsive pull-right" src="/feg/images/home/epa_logo_gray.png" alt="U.S. Environmental Protection Agency - Office of Transportation and Air Quality" style="max-height: 24px"></a>
	</div>

</div><!-- End of Sponsor row -->
<div style="height: 2.5em"></div>

	</div><!-- end of main-container -->

	<!-- Core Script for FE.gov -->

<!-- Base script for jQuery -->
<script src="//ajax.googleapis.com/ajax/libs/jquery/1.10.2/jquery.min.js"></script>

<!-- Base script for Bootstrap -->
<script src="//netdna.bootstrapcdn.com/bootstrap/3.0.0/js/bootstrap.min.js"></script>

<!-- HTML5 shim and Respond.js IE8 support of HTML5 elements and media queries -->
<!--[if lt IE 9]>
  <script src="//cdnjs.cloudflare.com/ajax/libs/html5shiv/3.6.2/html5shiv.min.js"></script>
  <script src="//cdnjs.cloudflare.com/ajax/libs/respond.js/1.2.0/respond.min.js"></script>
<![endif]-->

<script src="//ajax.aspnetcdn.com/ajax/jquery.validate/1.11.1/jquery.validate.min.js"></script>

<script src="/feg/assets/FitVids.js/jquery.fitvids.js"></script>

<!-- Search.  -->
<script src="//code.jquery.com/ui/1.10.4/jquery-ui.js"></script>
<script src="/feg/assets/js/search/jquery.search.js"></script>

<script type="text/javascript">
	$(document).ready(
			// Configure the validator globally.
			function() {
				jQuery.validator.setDefaults({
					errorPlacement : function(error, element) {
						// if the input has a prepend or append element, put the validation msg after the parent div
						if (element.parent().hasClass('input-prepend')
								|| element.parent().hasClass('input-append')) {
							error.insertAfter(element.parent());
						} else {
							// else just place the validation message immediately after the input
							error.insertAfter(element);
						}
					},
					highlight : function(element) {
						$(element).closest('.control-group').addClass('error');
					},
					unhighlight : function(element) {
						$(element).closest('.control-group').removeClass('error');
					}
				});
			});
</script>

<!-- 
<script type="text/javascript" src="//s7.addthis.com/js/300/addthis_widget.js#pubid=fueleconomy#async=1"></script>
<script type="text/javascript">
	// Intialize AddThis
	$(window).load(function initAddThis() {
		addthis.init();
	})
</script>
-->

<script type="text/javascript">
	// Highlights current page on side nav based on URL path and name 
    $(document).ready(function () {
		// Setup search autocomplete.
		$('#search-text').setup_autocomplete();

		// Activates (shades dark gray) subnav item that matches file name & path
        $('a[href="' + this.location.pathname + '"]').parent().addClass('active');

		// Automotically sizes videos using FitVids plug-in
		$('.video').fitVids();

		// Initializes dropdowns 
		$('.dropdown-toggle').dropdown();

		// Activates tooltips
		$('.tool-tip').tooltip();

		// Activates popovers
		$('.pop-over').popover();

		// Buttons for state gas prices
		$('#go-state-btn').on('click', function () {
			var stateSelection = $('#state').val();
			if (stateSelection != "None") {
				newPage="/feg/gasprices/states/"+stateSelection+".shtml";
				window.location = newPage;
			}
		});

		// Give search textbox focus on dropdown.
		$('#searchDdParent').on('shown.bs.dropdown', function () {
			setTimeout(function() {
				$('#search-text').focus();
			}, 10);
		});
	});
</script>

<!-- Go to www.addthis.com/dashboard to customize your tools -->
<script type="text/javascript" src="//s7.addthis.com/js/300/addthis_widget.js#pubid=ra-587e8f71196bf1c3"></script>

</body>
</html>
