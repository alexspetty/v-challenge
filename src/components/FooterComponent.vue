<template>
<footer class="usa-footer site-footer text-white">
  <div class="grid-container padding-top-15 padding-bottom-5" >
    <div class="grid-row">
      <div class="tablet:grid-col footer__left">
        <img class="height-5 margin-bottom-2" src="/assets/images/agency/challenge-logo-white-orange.svg" alt="Challenge Gov wordmark in footer" title="Challenge Gov wordmark">
        <hr class="border-orange margin-bottom-5">
        <div class="grid-row">
          <div class="tablet:grid-col">
            <ul class="add-list-reset">
              <li class="margin-bottom-1"><a class="footerlink text-no-underline" href="/about"><span style="text-decoration: none;">About</span></a></li>
              <li class="margin-bottom-1"><a class="footerlink text-no-underline" href="/contact">Contact</a></li>
              <li class="margin-bottom-1"><a class="footerlink text-no-underline" href="/terms">Terms of Use</a></li>
             <li class="margin-bottom-1"><a class="footerlink text-no-underline" href="/privacy-policy">Privacy Policy</a></li> 
            </ul>
          </div>
           <div class="tablet:grid-col">
            <ul class="add-list-reset">
              <li class="margin-bottom-1"><a class="footerlink text-no-underline" href="/resources">Innovator Resources</a></li>
              <li class="margin-bottom-1"><a class="footerlink text-no-underline" href="/resources-managers">Agency Resources</a></li>
              <li class="margin-bottom-1" id="js-archived-challenges"><a class="footerlink text-no-underline" href="/?state=archived">Archived Challenges</a></li>
              <li class="margin-bottom-1" id="active-challenges-footer"><a class="footerlink text-no-underline" href="/#active-challenges">Active Challenges</a></li>
            </ul>
          </div>
          <div class="tablet:grid-col">
            <ul class="add-list-reset">
              
              <li class="margin-bottom-1"><a class="footerlink text-no-underline" href="https://www.gsa.gov/website-information/website-policies#privacy">GSA Privacy Policy</a></li>
              <li class="margin-bottom-1"><a class="footerlink text-no-underline" href="https://www.gsa.gov/website-information/accessibility-aids">Accessibility</a></li>
              <li class="margin-bottom-1"><a class="footerlink text-no-underline" href="https://www.gsa.gov/reference/freedom-of-information-act-foia">FOIA</a></li>
              <li class="margin-bottom-1"><a class="footerlink text-no-underline" href="https://www.usa.gov">USA.gov</a></li>
            </ul>
          </div>
          <div class="tablet:grid-col">
            <div class="grid-row usa-footer__social_links">
              <a href="https://www.twitter.com/ChallengeGov" class="margin-right-1 usa-footer__social_link" target="_blank" rel="noopener" aria-label="Twitter">
                <i class="fab fa-twitter"></i>
              </a>
              <a href="https://www.facebook.com/ChallengeGov" class="margin-right-1 usa-footer__social_link" aria-label="Facebook">
                <i class="fab fa-facebook"></i>
              </a>
               <a href="https://www.linkedin.com/company/challengegov/" class="margin-right-1 usa-footer__social_link" aria-label="LinkedIn">
                <i class="fab fa-linkedin-in"></i>
              </a>
              <a href="https://github.com/GSA/Challenge_gov" class="margin-right-1 usa-footer__social_link" aria-label="GitHub">
                <i class="fab fa-github"></i>
              </a>
              <a href="https://public.govdelivery.com/accounts/USGSATTS/signup/30826" class="margin-right-1 usa-footer__social_link" aria-label="Newsletter Signup">
                <i class="fa fa-envelope" aria-hidden="true"></i>
              </a>
            </div>
          </div>
        </div>
      </div>

      <div class="tablet:grid-col-2 text-right">
        <img src="/assets/images/agency/challenge-logo-square-white.svg" alt="GSA Star Mark." title="GSA Star Mark" class="height-10 footer__gsa-logo-square">
      </div>
    </div>
  </div>
  <div>
  <a href="#" class="top">Back to Top ^</a>
  </div>
  <div>&nbsp;</div>
</footer>
</template>

<script>
export default {
  name: 'FooterComponent',
  data() {
    return {
      // any needed data members here
    };
  },
  methods: {
    // any needed methods here
  }
}
</script>

<style scoped>

</style>