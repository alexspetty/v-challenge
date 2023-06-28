<template>
<main id="main-content">
	<!-- Hero -->
	<div class="usa-hero bg-base-lightest text-black display:flex flex-justify-center">
		<div class="usa-hero__inner2">
			<div class="grid-container">
				<div class="display-flex flex-column flex-align-center">
					<div class="hero-logo"><img style="height: 3.8rem;" class="margin-bottom-2" src="/assets/images/agency/challenge-logo-white-orange.svg" alt=""> </div>
				</div>
				<div>&nbsp;</div>
				<div class="display-flex flex-column flex-align-center usa-hero__description">
					<h1 class="hero-headline" style="text-align: center;">Where <span style="color:#fa9441">public innovators</span> are inspired to meet challenges <span style="color:#fa9441">big</span> &amp; <span style="color:#fa9441">small</span>.</h1>
					<div class="grid-container">
						<div class="grid-row">
							<div class="tablet:grid-col" style="text-align: center;">
								<div class="container">
									<a href="/#active-challenges" class="usa-button usa-button--small-orange" aria-label="Active challenges" data-anchor="active-challenges" id="js-explore-challenges1">Find a Challenge</a> 
									<a href="/events" class="usa-button usa-button--small-orange">Join an Event</a> 
									<a href="https://public.govdelivery.com/accounts/USGSATTS/subscriber/new?qsp=USGSATTS_6" class="usa-button usa-button--small-orange">Stay Informed</a> 
								</div>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>

	<!-- Video-->
	<div class="grid-container-video video">
		<div class="grid-container">
			<div class="grid-row">
				<div class="tablet:grid-col">
					<div class="video-left">
						<h2 class="learn-video">Learn how YOU can participate and make a difference.</h2>
						<hr style="height:4px; border:none; color:#FA9541; background-color:#FA9541; width:100%; text-align:center; margin: 10px 5px;">
						<div class=".tablet:grid-col-12" style="padding-bottom: 50px;">
							<div> 
								<a href="https://www.twitter.com/ChallengeGov" class="margin-right-1 usa-footer__social_link" aria-label="Twitter"> <i class="fab fa-twitter"></i></a> 
								<a href="https://www.facebook.com/ChallengeGov" class="margin-right-1 usa-footer__social_link" aria-label="Facebook"><i class="fab fa-facebook"></i></a> 
								<a href="https://www.linkedin.com/company/challengegov/" class="margin-right-1 usa-footer__social_link" aria-label="LinkedIn"><i class="fab fa-linkedin-in"></i></a> 
								<a href="https://github.com/GSA/Challenge_gov" class="margin-right-1 usa-footer__social_link" aria-label="Github"><i class="fab fa-github"></i></a> 
								<a href="https://public.govdelivery.com/accounts/USGSATTS/subscriber/new?qsp=USGSATTS_6" class="margin-right-1 usa-footer__social_link" aria-label="Newsletter"><i class="fa fa-envelope"></i></a>
							</div>
						</div>
					</div>
				</div>
				<div class="video video-css tablet:grid-col" style="padding-bottom: 40px; text-align: center;">
					<a href="/challenge-gov-overview-video/"><img src="/assets/images/video-placeholder.png" alt="Watch the Challenge.Gov Overview Video" width="600"><span class="usa-button usa-button--small-orange" style="margin-top: 20px;">Watch overview video</span></a> 
				</div>
			</div>      
		</div>
	</div>

	<!-- Challenges -->
	<div class="challenges-bg challenges-header challenges">
		<div class="grid-row">
			<div class="container">
				<div class="tablet:grid-col">
					<h2 class="text-white">Find a Challenge</h2>
					<h3 class="challenge-banner-text">Browse through challenges and submit your ideas for a chance to win.</h3>
				</div>
				<div class="tablet:grid-col"></div>
			</div>
		</div>
	</div>

	<!-- React app -->
	<div id="challenge-gov-react-app" data-api-url="http://portal.challenge.gov" data-public-url=""></div>
	<div id="challenge-gov-react-app" data-api-url="http://localhost:4000/api/challenges" data-public-url=""></div>
	<!-- <div id="react-app-container"></div> -->
	<!-- http://localhost:4000/api/challenges -->


	<!-- Newsletter -->
	<div class="newsletter-bg newsletter">
		<div class="grid-row">
			<div class="container">
				<div class="tablet:grid-col">
					<h2 class="text-white">Stay Informed!</h2>
					<h3 style="color: #ffffff">Stay up to date on the latest Challenge.Gov news!</h3>
					<a href="https://public.govdelivery.com/accounts/USGSATTS/subscriber/topics?qsp=USGSATTS_6" class="usa-button usa-button--small-orange" data-anchor="active-challenges">Subscribe</a>
				</div>
				<div class="tablet:grid-col"></div>
			</div>
		</div>
	</div>

	<!-- Resources -->
	<div class="grid-container-resources help-section" id="resources-people">
		<div class="grid-container">
			<div class="grid-row">
				<div class="tablet:grid-col" style="text-align: center;">
					<h2>Are you a<br>Public Innovator?</h2>
					<div class="container"><img class="people responsive" src="/assets/images/banners/orange-people.png" alt=""></div> 
					<a href="/resources" class="usa-button usa-button--small-orange" data-anchor="active-challenges">Innovator Resources</a>
				</div>
				<div class="tablet:grid-col" style="text-align: center;">
					<h2 class="resources-title">Are you a<br>Federal Innovation Manager?</h2>
					<div class="container"><img class="people responsive" src="/assets/images/banners/blue-people.png" alt=""></div>
					<a class="usa-button usa-button--small-orange" href="/resources-managers">Manager Resources</a>
				</div>
			</div>
		</div>
	</div>
</main>
</template>

<script>
export default {
  mounted() { // this lifecycle hook is called after the component's DOM has been updated
    const apiUrl = "https://portal.challenge.gov";
    const iframe = document.createElement("iframe"); 
    iframe.src = apiUrl; 
    document.getElementById("challenge-gov-react-app").appendChild(iframe);
  }
};
</script>


<style>

</style>