<script>
  import Button from "../lib/components/Button/Button.svelte";
</script>

<div class="header">
  <img src="/logo-square.png" alt="The Randomatics Logo" />
  <div class="menu">
    <Button href="https://www.facebook.com/therandomatics" text="Facebook" />
    <Button href="https://www.youtube.com/therandomatics505" text="Videos"></Button>
  </div>
</div>
<div class="main">
  <slot />
</div>
<footer>
<!-- Begin Mailchimp Signup Form -->
<link href="//cdn-images.mailchimp.com/embedcode/classic-071822.css" rel="stylesheet" type="text/css">
<div id="mc_embed_signup">
  <form action="https://gmail.us13.list-manage.com/subscribe/post?u=869a53c212e8a9f597018f607&amp;id=6b9f671aee&amp;f_id=006199e2f0" method="post" id="mc-embedded-subscribe-form" name="mc-embedded-subscribe-form" class="validate" target="_blank" novalidate>
    <div id="mc_embed_signup_scroll">
      <h2>Subscribe to our Mailing List!</h2>
      <div class="indicates-required"><span class="asterisk">*</span> indicates required</div>
      <div class="mc-field-group">
        <label for="mce-EMAIL">Email Address  <span class="asterisk">*</span></label>
        <input type="email" value="" name="EMAIL" class="required email" id="mce-EMAIL" required>
        <span id="mce-EMAIL-HELPERTEXT" class="helper_text"></span>
      </div>
      <div id="mce-responses" class="clear foot">
        <div class="response" id="mce-error-response" style="display:none"></div>
        <div class="response" id="mce-success-response" style="display:none"></div>
      </div>
      <!-- real people should not fill this in and expect good things - do not remove this or risk form bot signups-->
      <div style="position: absolute; left: -5000px;" aria-hidden="true">
        <input type="text" name="b_869a53c212e8a9f597018f607_6b9f671aee" tabindex="-1" value="">
      </div>
      <div class="optionalParent">
        <div class="clear foot">
          <input type="submit" value="Subscribe" name="subscribe" id="mc-embedded-subscribe" class="button">
        </div>
      </div>
    </div>
</form>
</div>
<script type='text/javascript' src='//s3.amazonaws.com/downloads.mailchimp.com/js/mc-validate.js'></script>
<script type='text/javascript'>
(function($) {
  window.fnames = new Array();
  window.ftypes = new Array();
  fnames[0]='EMAIL';
  ftypes[0]='email';
  fnames[1]='FNAME';
  ftypes[1]='text';
  fnames[2]='LNAME';
  ftypes[2]='text';
  fnames[3]='ADDRESS';
  ftypes[3]='address';
  fnames[4]='PHONE';
  ftypes[4]='phone';
  fnames[5]='BIRTHDAY';
  ftypes[5]='birthday';
}(jQuery));
var $mcj = jQuery.noConflict(true);
</script>
<!--End mc_embed_signup-->

</footer>

<style>
  .header {
    text-align: center;
  }

  .menu {
    margin: .5rem;
    padding: .5rem 0;
    background-color: darkturquoise;
  }
  .main {
    width: 75vw;
    margin: 0 auto;
  }
  footer {
    width: 75vw;
    margin: 0 auto;
  }
  #mc_embed_signup {
    max-width: 50%;
  }
</style>