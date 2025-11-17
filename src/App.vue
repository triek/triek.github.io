<template>
  <div>
    <section class="preloader">
      <div class="spinner">
        <span class="spinner-rotate"></span>
      </div>
    </section>

    <nav class="navbar navbar-expand-lg">
      <div class="container">
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarNav"
          aria-controls="navbarNav"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>

        <a href="#section_1" class="navbar-brand mx-auto mx-lg-0">Tristan K.</a>

        <div class="d-flex align-items-center d-lg-none">
          <a class="custom-btn btn" href="#section_6">Contact</a>
        </div>

        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav ms-auto">
            <li class="nav-item">
              <a class="nav-link click-scroll" href="#section_1">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link click-scroll" href="#section_2">About</a>
            </li>
            <li class="nav-item">
              <a class="nav-link click-scroll" href="#section_3">Services</a>
            </li>
            <li class="nav-item">
              <a class="nav-link click-scroll" href="#section_4">Projects</a>
            </li>
            <li class="nav-item">
              <a class="nav-link click-scroll" href="#section_5">Experiences</a>
            </li>
          </ul>

          <div class="d-lg-flex align-items-center d-none ms-auto">
            <a class="custom-btn btn" href="#section_6">Contact</a>
          </div>
        </div>
      </div>
    </nav>

    <main>
      <section class="hero d-flex justify-content-center align-items-center" id="section_1">
        <svg width="100%" height="100px">
          <rect width="100%" height="85px" fill="var(--secondary-color)" />
        </svg>
        <div class="container">
          <div class="row">
            <div class="col-lg-7 col-12">
              <div class="hero-text">
                <div class="hero-title-wrap d-flex align-items-center mb-4">
                  <img src="/images/profile-picture.jpg" class="avatar-image avatar-image-large img-fluid" alt="" />

                  <h1 class="hero-title ms-3 mb-0">Welcome!</h1>
                </div>

                <h2 class="mb-4">I'm open for software industry.</h2>
                <p class="mb-4">
                  <a class="custom-btn btn custom-link" href="#section_2">Let's begin</a>
                </p>
              </div>
            </div>

            <div class="col-lg-5 col-12 position-relative">
              <div class="hero-image-wrap"></div>
              <img src="/images/profile-transparent-bg.png" class="hero-image img-fluid" alt="" style="width: 300px; height: auto" />
            </div>
          </div>
        </div>
      </section>

      <section class="about section-padding" id="section_2">
        <div class="svg-container">
          <h3 class="about-heading">ABOUT</h3>
        </div>

        <div class="container">
          <div class="row">
            <div class="col-lg-6 col-12">
              <div class="about-thumb">
                <div class="row">
                  <div class="col-lg-6 col-6 featured-border-bottom py-2">
                    <strong class="featured-numbers">1+</strong>

                    <p class="featured-text">Years of Experiences</p>
                  </div>

                  <div class="col-lg-6 col-6 featured-border-start featured-border-bottom ps-5 py-2">
                    <strong class="featured-numbers">1</strong>

                    <p class="featured-text">Happy Customer</p>
                  </div>

                  <div class="col-lg-6 col-6 pt-4">
                    <strong class="featured-numbers">3</strong>

                    <p class="featured-text">Project Finished</p>
                  </div>

                  <div class="col-lg-6 col-6 featured-border-start ps-5 pt-4">
                    <strong class="featured-numbers">0</strong>

                    <p class="featured-text">Digital Awards</p>
                  </div>
                </div>
              </div>
            </div>

            <div class="col-lg-6 col-12 mt-5 mt-lg-0">
              <div class="about-thumb">
                <h3 class="pt-2 mb-3">Get to know Tristan</h3>

                <p>
                  Passionate in Object Oriented Programming and Game Design, willing to gain new skills and experience in the software development field. As a content creation enjoyer, I also like to bring new breeze into the gaming industry.
                </p>
                <p>
                  I am currently pursuing BEng degree in Computer Science and actively seeking an internship in game and web development field. I will assure to adapt to the job well and act responsibly in the given role, being enthusiactic and fast learning.
                </p>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section class="services section-padding" id="section_3">
        <div class="svg-container">
          <h3 class="about-heading">SERVICES</h3>
        </div>

        <div class="container">
          <div class="row">
            <div class="col-lg-10 col-12 mx-auto">
              <div class="row pt-lg-5">
                <div class="col-lg-6 col-12">
                  <div class="services-thumb">
                    <div class="d-flex flex-wrap align-items-center border-bottom mb-4 pb-3">
                      <h3 class="mb-0">Websites</h3>

                      <div class="services-price-wrap ms-auto">
                        <p class="services-price-text mb-0">$1,200</p>
                        <div class="services-price-overlay"></div>
                      </div>
                    </div>

                    <p>I design websites like this, for commercial and personal uses. I am well-versed in HTML, CSS, JS with Bootstrap and Jquery.</p>

                    <a href="#" class="custom-btn custom-border-btn btn mt-3">Discover More</a>

                    <div class="services-icon-wrap d-flex justify-content-center align-items-center">
                      <i class="services-icon bi-globe"></i>
                    </div>
                  </div>
                </div>

                <div class="col-lg-6 col-12">
                  <div class="services-thumb services-thumb-up">
                    <div class="d-flex flex-wrap align-items-center border-bottom mb-4 pb-3">
                      <h3 class="mb-0">Game design</h3>

                      <div class="services-price-wrap ms-auto">
                        <p class="services-price-text mb-0">$1,800</p>
                        <div class="services-price-overlay"></div>
                      </div>
                    </div>

                    <p>I'm familiar with popular game engines like Unity and Godot, using C#, C++, Python and Java. I'm practicing 3D models and visual design.</p>

                    <a href="#" class="custom-btn custom-border-btn btn mt-3">Discover More</a>

                    <div class="services-icon-wrap d-flex justify-content-center align-items-center">
                      <i class="services-icon bi-lightbulb"></i>
                    </div>
                  </div>
                </div>

                <div class="col-lg-6 col-12">
                  <div class="services-thumb">
                    <div class="d-flex flex-wrap align-items-center border-bottom mb-4 pb-3">
                      <h3 class="mb-0">Media specialist</h3>

                      <div class="services-price-wrap ms-auto">
                        <p class="services-price-text mb-0">$800</p>
                        <div class="services-price-overlay"></div>
                      </div>
                    </div>

                    <p>If you need a specialist in digital design, photography, videography, and editing, feel free to discuss with me. I have extensive experience in Adobe tools.</p>

                    <a href="#" class="custom-btn custom-border-btn btn mt-3">Discover More</a>

                    <div class="services-icon-wrap d-flex justify-content-center align-items-center">
                      <i class="services-icon bi-phone"></i>
                    </div>
                  </div>
                </div>

                <div class="col-lg-6 col-12">
                  <div class="services-thumb services-thumb-up">
                    <div class="d-flex flex-wrap align-items-center border-bottom mb-4 pb-3">
                      <h3 class="mb-0">Content writing</h3>

                      <div class="services-price-wrap ms-auto">
                        <p class="services-price-text mb-0">$400</p>
                        <div class="services-price-overlay"></div>
                      </div>
                    </div>

                    <p>To make your posts more attractive to future customers, we will work together. I know my way around with catchy and trendy contents.</p>

                    <a href="#" class="custom-btn custom-border-btn btn mt-3">Discover More</a>

                    <div class="services-icon-wrap d-flex justify-content-center align-items-center">
                      <i class="services-icon bi-google"></i>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section class="projects section-padding" id="section_4">
        <div class="svg-container">
          <h3 class="about-heading">PROJECTS</h3>
        </div>

        <div class="container">
          <div class="row">
            <div class="clearfix"></div>

            <div class="col-lg-4 col-md-6 col-12">
              <div class="projects-thumb">
                <div class="projects-info">
                  <small class="projects-tag">Game</small>
                  <a href="https://github.com/triek/Minimos" target="_blank">
                    <h3 class="projects-title">Minimos</h3>
                  </a>
                </div>

                <a href="/images/projects/minimos_icon.png" class="popup-image">
                  <img src="/images/projects/minimos_icon.png" class="projects-image img-fluid" alt="" />
                </a>
              </div>
            </div>

            <div class="col-lg-4 col-md-6 col-12">
              <div class="projects-thumb">
                <div class="projects-info">
                  <small class="projects-tag">Game</small>
                  <a href="https://github.com/triek/Selaphobia" target="_blank">
                    <h3 class="projects-title">Selaphobia</h3>
                  </a>
                </div>

                <a href="/images/projects/selaphobia.jpg" class="popup-image">
                  <img src="/images/projects/selaphobia.jpg" class="projects-image img-fluid" alt="" />
                </a>
              </div>
            </div>

            <div class="col-lg-4 col-md-6 col-12">
              <div class="projects-thumb">
                <div class="projects-info">
                  <small class="projects-tag">Website</small>

                  <a href="https://github.com/triek/triek.github.io" target="_blank">
                    <h3 class="projects-title">Tristan's Porfolio</h3>
                  </a>
                </div>

                <a href="/images/projects/portfolio.jpg" class="popup-image">
                  <img src="/images/projects/portfolio.jpg" class="projects-image img-fluid" alt="" />
                </a>
              </div>
            </div>

            <div class="col-lg-4 col-md-6 col-12">
              <div class="projects-thumb">
                <div class="projects-info">
                  <small class="projects-tag">Design</small>

                  <a href="https://www.behance.net/trietkhuongminh" target="_blank">
                    <h3 class="projects-title">Graphic Design</h3>
                  </a>
                </div>

                <a href="/images/projects/behance.jpg" class="popup-image">
                  <img src="/images/projects/behance.jpg" class="projects-image img-fluid" alt="" />
                </a>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section class="clients section-padding" id="section_5">
        <div class="container">
          <div class="row align-items-center">
            <div class="col-lg-12 col-12">
              <h3 class="text-center mb-5">Companies I've had worked</h3>
            </div>
          </div>
        </div>
      </section>

      <section class="contact section-padding" id="section_6">
        <div class="svg-container">
          <h3 class="about-heading">Say hi</h3>
        </div>

        <div class="container">
          <div class="row">
            <div class="clearfix"></div>

            <div class="col-lg-3 col-md-6 col-12 pe-lg-0">
              <div class="contact-info contact-info-border-start d-flex flex-column">
                <strong class="site-footer-title d-block mb-3">Services</strong>

                <ul class="footer-menu">
                  <li class="footer-menu-item"><a href="#section_3" class="footer-menu-link">Websites</a></li>

                  <li class="footer-menu-item"><a href="#section_3" class="footer-menu-link">Game</a></li>

                  <li class="footer-menu-item"><a href="#section_3" class="footer-menu-link">Media</a></li>

                  <li class="footer-menu-item"><a href="#section_3" class="footer-menu-link">Content</a></li>
                </ul>

                <strong class="site-footer-title d-block mt-4 mb-3">Stay connected</strong>

                <ul class="social-icon">
                  <li class="social-icon-item"><a href="https://github.com/triek" target="_blank" class="social-icon-link bi-github"></a></li>

                  <li class="social-icon-item">
                    <a href="https://www.linkedin.com/in/trietkhuong/" target="_blank" class="social-icon-link bi-linkedin"></a>
                  </li>

                  <li class="social-icon-item">
                    <a href="https://www.behance.net/trietkhuongminh" target="_blank" class="social-icon-link bi-behance"></a>
                  </li>

                  <li class="social-icon-item">
                    <a href="https://www.facebook.com/mingtriet.khuong/" target="_blank" class="social-icon-link bi-facebook"></a>
                  </li>
                </ul>

                <strong class="site-footer-title d-block mt-4 mb-3">Start a project</strong>

                <p class="mb-0">I’m available for freelance projects</p>
              </div>
            </div>

            <div class="col-lg-3 col-md-6 col-12 ps-lg-0">
              <div class="contact-info d-flex flex-column">
                <strong class="site-footer-title d-block mb-3">About</strong>

                <p class="mb-2">Tristan is an intern developer. Feel free to get in touch with me.</p>

                <strong class="site-footer-title d-block mt-4 mb-3">Email</strong>

                <p class="mb-2">
                  <a href="mailto:ITITDK22041@student.hcmiu.edu.vn"> ITITDK22041 @student.hcmiu.edu.vn </a>
                </p>

                <strong class="site-footer-title d-block mt-4 mb-3">Call</strong>

                <p class="mb-0">
                  <a href="tel: +84 333 222 111"> +84 333 222 111 </a>
                </p>
              </div>
            </div>

            <div class="col-lg-6 col-12 mt-5 mt-lg-0">
              <form action="#" method="get" class="custom-form contact-form" role="form">
                <div class="row">
                  <div class="col-lg-6 col-md-6 col-12">
                    <div class="form-floating">
                      <input type="text" name="name" id="name" class="form-control" placeholder="Name" required />

                      <label for="floatingInput">Name</label>
                    </div>
                  </div>

                  <div class="col-lg-6 col-md-6 col-12">
                    <div class="form-floating">
                      <input
                        type="email"
                        name="email"
                        id="email"
                        pattern="[^ @]*@[^ @]*"
                        class="form-control"
                        placeholder="Email address"
                        required
                      />

                      <label for="floatingInput">Email address</label>
                    </div>
                  </div>

                  <div class="col-lg-3 col-md-6 col-6">
                    <div class="form-check form-check-inline">
                      <input name="website" type="checkbox" class="form-check-input" id="inlineCheckbox1" value="1" />

                      <label class="form-check-label" for="inlineCheckbox1">
                        <i class="bi-globe form-check-icon"></i>
                        <span class="form-check-label-text">Websites</span>
                      </label>
                    </div>
                  </div>

                  <div class="col-lg-3 col-md-6 col-6">
                    <div class="form-check form-check-inline">
                      <input name="branding" type="checkbox" class="form-check-input" id="inlineCheckbox2" value="1" />

                      <label class="form-check-label" for="inlineCheckbox2">
                        <i class="bi-lightbulb form-check-icon"></i>
                        <span class="form-check-label-text">Game</span>
                      </label>
                    </div>
                  </div>

                  <div class="col-lg-3 col-md-6 col-6">
                    <div class="form-check form-check-inline">
                      <input name="ecommerce" type="checkbox" class="form-check-input" id="inlineCheckbox3" value="1" />

                      <label class="form-check-label" for="inlineCheckbox3">
                        <i class="bi-phone form-check-icon"></i>
                        <span class="form-check-label-text">Media</span>
                      </label>
                    </div>
                  </div>

                  <div class="col-lg-3 col-md-6 col-6">
                    <div class="form-check form-check-inline me-0">
                      <input name="seo" type="checkbox" class="form-check-input" id="inlineCheckbox4" value="1" />

                      <label class="form-check-label" for="inlineCheckbox4">
                        <i class="bi-google form-check-icon"></i>
                        <span class="form-check-label-text">Content</span>
                      </label>
                    </div>
                  </div>

                  <div class="col-lg-12 col-12">
                    <div class="form-floating">
                      <textarea class="form-control" id="message" name="message" placeholder="Tell me about the project"></textarea>

                      <label for="floatingTextarea">Tell me about the project</label>
                    </div>
                  </div>

                  <div class="col-lg-3 col-12 ms-auto">
                    <button type="submit" class="form-control">Send</button>
                  </div>
                </div>
              </form>
            </div>
          </div>
        </div>
      </section>
    </main>

    <footer class="site-footer">
      <div class="container">
        <div class="row">
          <div class="col-lg-12 col-12">
            <div class="copyright-text-wrap">
              <p class="mb-0">
                <span class="copyright-text">
                  Copyright © 2025 <a href="#">Uphill</a> Project. All rights reserved.
                </span>
                Design:
                <a rel="sponsored" href="https://www.linkedin.com/in/trietkhuong/" target="_blank">Tristan K.</a>
              </p>
            </div>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>

<script setup></script>
