<template>
	<!-- CONTACT SECTION -->

	  <div class="container-fluid py-5" id="contact">

	      <h1>Contact</h1>

	      <div class="row d-flex justify-content-center">

	          <div class="col-12 col-md-6 py-3" id="map">
	            <div class="map-responsive">
	              <iframe 
	                src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d209738.78874248857!2d103.69995612291962!3d1.360672865211356!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x31da1130db42d2e7%3A0xbf28593be65d1c05!2sUpper%20Peirce%20Reservoir%20Park!5e1!3m2!1sen!2sph!4v1760268410089!5m2!1sen!2sph"
	                allowfullscreen
	                loading="lazy"
	                referrerpolicy="no-referrer-when-downgrade">
	              </iframe>
	            </div>
	          </div>


	          <div class="col-12 col-md-6 py-3" id="form">

	            <form>

	              <div class="mb-3">
	                  <label for="name" class="form-label">Name</label>
	                  <input type="text" class="form-control form-control-lg" id="name" placeholder="First Name M.I. Last Name">
	              </div>

	              <div class="mb-3">
	                  <label for="email" class="form-label">Email</label>
	                  <input type="email" class="form-control form-control-lg" id="email" placeholder="Email">
	              </div>

	              <div class="mb-3">
	                  <label for="message" class="form-label">Message</label>
	                  <textarea class="form-control" id="message" rows="6" placeholder="Message"></textarea>
	              </div>

	              <div class="d-flex align-items-center justify-content-between">
	                <div class="d-flex gap-1">
	                  <a href="https://www.linkedin.com" target="_blank"><img src="/images/contact/contact_linkedin.png" alt="LinkedIn"></a>
	                  <a href="https://github.com" target="_blank"><img src="/images/contact/contact_github.png" alt="GitHub"></a>
	                  <a href="https://gitlab.com" target="_blank"><img src="/images/contact/contact_gitlab.png" alt="GitLab"></a>
	                </div>
	                <button type="button" class="btn ms-auto" id="submit-button">SUBMIT</button>
	              </div>

	            </form>

	          </div>

	      </div>      
	  </div>
</template>