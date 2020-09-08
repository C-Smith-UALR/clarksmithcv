<template>
  <div id="home">
    <h1 id="homeName">Curriculum Vitae</h1>
    <div class="container">
      <div class="row" itemscope itemtype="http://schema.org/Person">
        <div class="col-sm-12 col-lg-6">
          <h2 class="visuallyhidden">Personal Details</h2>

          <img src="../assets/img/clarkSmithCVimg.jpeg" alt="professional photograph of Clark Smith"
               class="img-fluid" itemprop="image">
          <p itemprop="description">
            Clark Smith is a medical doctor and full stack web developer at Medzoar LLC.  He has 7 years of
            clinical experience in Hospice and Palliative Medicine.  This is his professional curriculum vitae.
          </p>
        </div>
        <div class="col-sm-12 col-lg-6 pt-3" id="detailsList">
          <dl>
            <dt>Name</dt>
            <dd itemprop="name">
              <span itemprop="givenName">Clark</span> Lander <span itemprop="familyName">Smith</span>, MD
            </dd>
            <dt>Date of Birth</dt>
            <dd itemprop="birthDate">
              <time datetime="1983-07-01">7/1/1983</time>
            </dd>
            <dt>Nationality</dt>
            <dd itemprop="nationality">
              United States
            </dd>
            <dt>Location</dt>
            <dd itemprop="homeLocation">Tennessee</dd>
            <dt>Telephone</dt>
            <dd>
              <a itemprop="telephone" href="tel:5014706812">
                501.470.6812
              </a>
            </dd>
            <dt>Email</dt>
            <dd>
              <a itemprop="email" href="mailto:clarklander1983@gmail.com?subject=Resume&body=I saw your resume online.">
                clarklander1983@gmail.com
              </a>
            </dd>
            <dt>Address</dt>
            <dd itemprop="address" itemscope itemtype="http://schema.org/PostalAddress">
              <span itemprop="streetAddress">
                62 North Main St,
                Apt 1001,
              </span>
              <span itemprop="addressLocality">Memphis, </span>
              <span itemprop="addressRegion">TN, </span>
              <span itemprop="addressCountry">USA</span>
            </dd>


          </dl>
        </div>
      </div> <!--row-->
    </div> <!--container-->
    <div class="container" id="socialContainer">
      <div class="row">
        <div class="col-sm col1 iconContainer">
          <a :href="`${publicPath}ClarkSmithCV2020.pdf`" download>
            <i class="fa fa-file-pdf-o icon" aria-hidden="true"></i>

          </a>
          <div style="text-align: center" class="mt-3 clarkLikeParagraph">
            Resume PDF
          </div>


        </div>

        <div class="col-sm col4 iconContainer">
          <a href="https://github.com/C-Smith-UALR">
            <i class="fa fa-github icon" aria-hidden="true"></i>

          </a>
          <div style="text-align: center" class="mt-3 clarkLikeParagraph">
            Github Profile
          </div>

        </div>


        <div class="col-sm col5 iconContainer">
          <a href="https://www.linkedin.com/in/clark-smith-6095b618b">

            <i class="fa fa-linkedin-square icon" aria-hidden="true"></i>

          </a>
          <div style="text-align: center" class="mt-3 clarkLikeParagraph">
            LinkedIn Profile
          </div>
        </div>








      </div> <!-- row -->
    </div>  <!--container-->
  </div>
</template>

<script>
// @ is an alias to /src


export default {
  name: 'Home',
  data () {
    return {
      publicPath: process.env.BASE_URL
    }
  }

}
</script>
