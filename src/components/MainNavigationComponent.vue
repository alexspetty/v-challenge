<template>
<header class="usa-header usa-header--basic" aria-label="Main navigation">
	<div class="usa-nav-container">
		<div class="usa-navbar">
		  <div class="usa-logo" id="basic-logo">
		    <a href="/" title="Home" aria-label="Home">
		      <img src='/assets/images/agency/challenge-logo.svg' alt="Challenge Gov wordmark." title="Challenge Gov wordmark" class="height-5 header__challenge-logo">
		    </a>
		  </div>
		<button class="usa-menu-btn" aria-label="menu">Menu</button>
		</div>
		<nav class="usa-nav usa-header__actions">
		  <ul class="usa-nav__primary usa-accordion">
		    <li class="usa-nav__primary-item">
		      <a href="/#active-challenges" class="menulink usa-nav__link" title="Active challenges" aria-label="Active challenges" data-anchor="active-challenges">Find a Challenge</a>
		    </li>
		    <li class="usa-nav__primary-item">
		      <a class="menulink usa-nav__link" href="/#resources-people" title="Resources for innovators and managers" aria-label="Resources">Resources</a>
		    </li>
		    <li class="usa-nav__primary-item">
		      <a class="menulink usa-nav__link" href="/events" title="Events for innovators and managers" aria-label="Events">Events</a>
		    </li>
		    <li class="usa-nav__primary-item">
		      <a class="menulink usa-nav__link" href="/contact" title="Contact page with email and social links" aria-label="Contact">Contact</a>
		    </li>
		  </ul>
		  
		<form id="search_form" class="usa-search usa-search--small" action="https://search.usa.gov/search" accept-charset="UTF-8" method="get">
			<input name="utf8" type="hidden" value="&#x2713;">
			<input type="hidden" name="affiliate" id="affiliate" value="challenge.gov">
			<div role="search">
				<label class="usa-sr-only" for="extended-search-field-small">Search small</label>
				<input class="usa-input usagov-search-autocomplete" id="extended-search-field-small" aria-label="Search Challenge.gov" type="search" name="query" autocomplete="off">
				<button class="usa-button" type="submit"><span class="usa-sr-only">Search</span></button>
			</div>
		</form>
		  
		  <a style="width: 6rem;" class="float-right usa-button usa-button--outline tablet:margin-left-2 tablet:float-right font-sans-xs" href="https://portal.challenge.gov/sign-in/new"><span style="color:#005ea2;">Login</span></a>
		  <a style="width: 10rem;" class="float-right usa-button usa-button tablet:margin-left-1 tablet:float-right font-sans-xs" href="https://secure.login.gov/sign_up/enter_email?request_id=6ab5f3e4-a3e5-4cb7-90a3-3a777fee8967"><span style="color: #ffffff;">Create Account</span></a>  
		</nav>
	</div>
</header>
</template>

<script>
</script>

<style>
</style>