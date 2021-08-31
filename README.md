# Personal-Portfolio---Bootstrap-5
portfolio using bootstrap 5
<!DOCTYPE html>
<html lang="en">
<head>
  <title>Personal Portfolio - Bootstrap 5</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="css/font-awesome.min.css">
  <link rel="stylesheet" href="css/bootstrap.min.css">
</head>
<body class="bg-light">
 

 <!-- navbar start -->
 <nav class="navbar navbar-light fixed-top bg-light shadow-sm">
   <div class="container-lg">
     <a class="navbar-brand text-danger fw-bold fs-4" href="#">SUSHANT</a>
     <div class="dropdown">
        <button class="btn btn-secondary btn-danger px-3" type="button" id="dropdownMenuButton" data-bs-toggle="dropdown" aria-expanded="false">
        <i class="fas fa-bars"></i>
        </button>
       <ul class="dropdown-menu dropdown-menu-end" aria-labelledby="dropdownMenuButton">
         <li><a class="dropdown-item" href="#home">Home</a></li>
         <li><a class="dropdown-item" href="#about">About</a></li>
         <li><a class="dropdown-item" href="#services">Services</a></li>
         <li><a class="dropdown-item" href="#portfolio">Portfolio</a></li>
         <li><a class="dropdown-item" href="#testimonials">Testimonials</a></li>
         <li><a class="dropdown-item" href="#contact">Contact</a></li>
       </ul>
    </div>
  </div>
</nav>
 <!-- navbar end -->

 <!-- home section start -->
 <section class="home py-5" id="home">
    <div class="container-lg">
        <div class="row min-vh-100 align-items-center align-content-center">
            <div class="col-md-6 mt-5 mt-md-0">
               <div class="home-img text-center">
                  <img src="img/profile.jpg" class="rounded-circle mw-100" alt="profile img">
               </div>
            </div>
            <div class="col-md-6 mt-5 mt-md-0 order-md-first">
               <div class="home-text">
                  <p class="text-muted mb-1">Hello I'm</p>
                  <h1 class="text-danger text-uppercase fs-1 fw-bold">Software Engineer</h1>
                  <h2 class="fs-4">Sushant Gautam</h2>
                  <p class="mt-4 text-muted">Born in Chandigarh (India), now living in Melbourne. Studied Master of Technology in Software Engineering from Federation University, Ballarat(2021).</p>
                  <a href="#portfolio" class="btn btn-danger px-3 mt-3">My Work</a>
               </div>
            </div>
        </div>
    </div>
 </section>
 <!-- home section end -->

 <!-- about section start -->
 <section class="about py-5" id="about">
    <div class="container-lg py-4">
        <div class="row justify-content-center">
            <div class="col-lg-8">
                <div class="section-title text-center">
                    <h2 class="fw-bold mb-5">About Me</h2>
                </div>
            </div>
        </div>
        <div class="row">
           <div class="col-md-6">
              <div class="about-text">
                 <h3 class="fs-4 mb-3">Interested in Front-End Development</h3>
                 <p class="text-muted">I am a hardworking, punctual,focused,dedicated and a friendly person.I am an optimist and highly focused with a Masters degree in Software Engineering from the Federation University. I am looking for a Software Engineer position to make good use of my programming skills and further enhance my knowledge.</p>
              </div>
              <div class="row text-center text-uppercase my-3">
                  <div class="col-sm-4">
                      <div class="fact-item">
                         <h4 class="fs-1 fw-bold">50</h4>
                         <p class="text-muted">Projects Completed</p>
                      </div>
                  </div>
                  <div class="col-sm-4">
                      <div class="fact-item">
                         <h4 class="fs-1 fw-bold">40</h4>
                         <p class="text-muted">Happy clients</p>
                      </div>
                  </div>
                  <div class="col-sm-4">
                      <div class="fact-item">
                         <h4 class="fs-1 fw-bold">40</h4>
                         <p class="text-muted">Positive Reviews</p>
                      </div>
                  </div>
              </div>
              <div class="row">
                  <div class="col-lg-12 d-flex align-items-center">
                      <a href="#" class="btn px-3 btn-danger me-5">Download Resume</a>
                      <div class="social-links">
                         <a href="#" class="text-dark me-2"><i class="fab fa-facebook-f"></i></a>
                         <a href="#" class="text-dark me-2"><i class="fab fa-twitter"></i></a>
                         <a href="#" class="text-dark me-2"><i class="fab fa-instagram"></i></a>
                         <a href="#" class="text-dark me-2"><i class="fab fa-linkedin-in"></i></a>
                      </div>
                  </div>
              </div>
           </div>
           <div class="col-md-6 mt-5 mt-md-0">
              <div class="skill-item mb-4">
                  <h3 class="fs-6">Html</h3>
                  <div class="progress" style="height: 5px;">
                     <div class="progress-bar bg-danger" role="progressbar" style="width: 25%;" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
                  </div>
              </div>
              <div class="skill-item mb-4">
                  <h3 class="fs-6">Css</h3>
                  <div class="progress" style="height: 5px;">
                     <div class="progress-bar bg-danger" role="progressbar" style="width: 50%;" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100"></div>
                  </div>
              </div>
              <div class="skill-item mb-4">
                  <h3 class="fs-6">Javascript</h3>
                  <div class="progress" style="height: 5px;">
                     <div class="progress-bar bg-danger" role="progressbar" style="width: 75%;" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100"></div>
                  </div>
              </div>
              <div class="skill-item">
                  <h3 class="fs-6">Bootstrap</h3>
                  <div class="progress" style="height: 5px;">
                     <div class="progress-bar bg-danger" role="progressbar" style="width: 100%;" aria-valuenow="100" aria-valuemin="0" aria-valuemax="100"></div>
                  </div>
              </div>
           </div>
        </div>
    </div>
 </section>
 <!-- about section end -->

 <!-- service section start -->
 <section class="services py-5" id="services">
    <div class="container-lg py-4">
       <div class="row justify-content-center">
            <div class="col-lg-8">
                <div class="section-title text-center">
                    <h2 class="fw-bold mb-5">What I Do</h2>
                </div>
            </div>
        </div>
        <div class="row text-center">
            <div class="col-md-6 col-lg-4 mb-4">
                <div class="service-item shadow-sm p-4 rounded bg-white">
                    <div class="icon my-3 text-danger fs-2">
                      <i class="fas fa-code"></i>
                    </div>
                    <h3 class="fs-5 py-2">Web Development</h3>
                    <p class="text-muted">Using different platforms doing front-end development for the website.</p>
                </div>
            </div>
            <div class="col-md-6 col-lg-4 mb-4">
                <div class="service-item shadow-sm p-4 rounded bg-white">
                    <div class="icon my-3 text-danger fs-2">
                      <i class="fas fa-lightbulb"></i>
                    </div>
                    <h3 class="fs-5 py-2">Creative Design</h3>
                    <p class="text-muted">Creating logos and designes using different tools.</p>
                </div>
            </div>
            <div class="col-md-6 col-lg-4 mb-4">
                <div class="service-item shadow-sm p-4 rounded bg-white">
                    <div class="icon my-3 text-danger fs-2">
                      <i class="fas fa-image"></i>
                    </div>
                    <h3 class="fs-5 py-2">Word processing</h3>
                    <p class="text-muted">Making Reports, presentations, writeup, user stories etcetera.</p>
                </div>
            </div>
        </div>
    </div>
 </section>
 <!-- service section end -->

 <!-- portfolio section start -->
 <section class="portfolio py-5" id="portfolio">
    <div class="container-lg py-4">
       <div class="row justify-content-center">
            <div class="col-lg-8">
                <div class="section-title text-center">
                    <h2 class="fw-bold mb-5">Latest Works</h2>
                </div>
            </div>
       </div>
       <div class="row">
          <div class="col-md-6 col-lg-4">
              <div class="portfolio-item">
                 <img src="img/portfolio/1.jpg" class="w-100 img-thumbnail" alt="portfolio item">
                 <h3 class="text-capitalize fs-5 my-2">team section</h3>
                 <p class="mb-4"><a href="#" class="text-danger text-decoration-none">Live Demo</a></p>
              </div>

        
          </div>
          <div class="col-md-6 col-lg-4">
              <div class="portfolio-item">
                 <img src="img/portfolio/3.jpg" class="w-100 img-thumbnail" alt="portfolio item">
                 <h3 class="text-capitalize fs-5 my-2">bootstrap 5 image gallery</h3>
                 <p class="mb-4"><a href="#" class="text-danger text-decoration-none">Live Demo</a></p>
              </div>
          </div>
          <div class="col-md-6 col-lg-4">
              <div class="portfolio-item">
                 <img src="img/portfolio/4.jpg" class="w-100 img-thumbnail" alt="portfolio item">
                 <h3 class="text-capitalize fs-5 my-2">filterable image gallery</h3>
                 <p class="mb-4"><a href="#" class="text-danger text-decoration-none">Live Demo</a></p>
              </div>
          </div>
       </div>
    </div>
 </section>
 <!-- portfolio section end -->

 <!-- freelancer available section start -->
 <section class="freelancer-available py-5 bg-danger">
    <div class="container-lg py-4">
       <div class="row justify-content-center">
          <div class="col-lg-8 text-center">
              <p class="text-light fs-5">Do you have any job ?</p>
              <h2 class="fs-1 text-white mb-4">I'm looking for a job</h2>
              <a href="#contact" class="btn btn-outline-light">Hire Me</a>
          </div>
       </div>
    </div>
 </section>
 <!-- freelancer available section end -->

 <!-- testimonials section start -->
 <section class="testimonials py-5" id="testimonials">
    <div class="container-lg py-4">
        <div class="row justify-content-center">
            <div class="col-lg-8">
                <div class="section-title text-center">
                    <h2 class="fw-bold mb-5">Testimonials</h2>
                </div>
            </div>
        </div>
        <div class="row justify-content-center">
            <div class="col-lg-8 col-xl-7">
              <div id="carousel1" class="carousel slide" data-bs-ride="carousel">
                <ol class="carousel-indicators">
                   <li data-bs-target="#carousel1" data-bs-slide-to="0" class="active bg-danger"></li>
                   <li class="bg-danger" data-bs-target="#carousel1" data-bs-slide-to="1"></li>
                   <li class="bg-danger" data-bs-target="#carousel1" data-bs-slide-to="2"></li>
                </ol>
                <div class="carousel-inner p-1">
                <!-- testi item start -->
                <div class="testi-item carousel-item active bg-white shadow-sm rounded p-4 mb-5">
                    <div class="testi-author-info d-flex align-items-center">
                        <img src="img/testimonial/1.jpg" class="img-thumbnail rounded-circle" alt="author img">
                        <div class="author ms-3">
                           <h3 class="fs-6 mb-1">Christian</h3>
                           <p class="text-muted m-0">reesby</p>
                        </div>
                    </div>
                    <p class="text-muted mt-3">Sushant is one of the most talented designers we've had the opportunity to work with at Cinematique. His classy, elegant design execution comes with great precision, insight, and understanding of the user experience.</p>
                    <div class="rating text-danger">
                       <i class="fas fa-star"></i>
                       <i class="fas fa-star"></i>
                       <i class="fas fa-star"></i>
                       <i class="fas fa-star"></i>
                       <i class="fas fa-star"></i>
                    </div>
                </div>
                <!-- testi item end -->
                <!-- testi item start -->
                <div class="testi-item carousel-item bg-white shadow-sm rounded p-4 mb-5">
                    <div class="testi-author-info d-flex align-items-center">
                        <img src="img/testimonial/2.jpg" class="img-thumbnail rounded-circle" alt="author img">
                        <div class="author ms-3">
                           <h3 class="fs-6 mb-1">Jessica</h3>
                           <p class="text-muted m-0">reesby</p>
                        </div>
                    </div>
                    <p class="text-muted mt-3">Sushant is exceptionally talented and very well-versed in both design and web technologies. I highly recommend him as a standout creative talent knowing that he will be an asset to anyone he works with.</p>
                    <div class="rating text-danger">
                       <i class="fas fa-star"></i>
                       <i class="fas fa-star"></i>
                       <i class="fas fa-star"></i>
                       <i class="fas fa-star"></i>
                       <i class="fas fa-star"></i>
                    </div>
                </div>
                <!-- testi item end -->
                <!-- testi item start -->
                <div class="testi-item carousel-item bg-white shadow-sm rounded p-4 mb-5">
                    <div class="testi-author-info d-flex align-items-center">
                        <img src="img/testimonial/3.jpg" class="img-thumbnail rounded-circle" alt="author img">
                        <div class="author ms-3">
                           <h3 class="fs-6 mb-1">Mathew</h3>
                           <p class="text-muted m-0">reesby </p>
                        </div>
                    </div>
                    <p class="text-muted mt-3">Sushant is one of the most creative and versatile designers I’ve ever had the chance to collaborate with and brings with him an energy that is truly contagious to all those around him. He is incredibly well-rounded and able to overcome any challenge.</p>
                    <div class="rating text-danger">
                       <i class="fas fa-star"></i>
                       <i class="fas fa-star"></i>
                       <i class="fas fa-star"></i>
                       <i class="fas fa-star"></i>
                       <i class="fas fa-star"></i>
                    </div>
                </div>
                <!-- testi item end -->
                </div>
              </div>
            </div>
        </div>
    </div>
 </section>
 <!-- testimonials section end -->

 <!-- contact section start -->
 <section class="contact py-5" id="contact">
    <div class="container-lg py-4">
        <div class="row justify-content-center">
            <div class="col-lg-8">
                <div class="section-title text-center">
                    <h2 class="fw-bold mb-5">Contact Me</h2>
                </div>
            </div>
        </div>
        <div class="row">
            <div class="col-md-5">
                <div class="contact-item d-flex mb-3">
                   <div class="icon fs-4 text-danger">
                      <i class="fas fa-envelope"></i>
                   </div>
                   <div class="text ms-3">
                      <h3 class="fs-5">Email</h3>
                      <p class="text-muted">sushantgautam59@gmail.com</p>
                   </div>
                </div>
                <div class="contact-item d-flex mb-3">
                   <div class="icon fs-4 text-danger">
                      <i class="fas fa-phone"></i>
                   </div>
                   <div class="text ms-3">
                      <h3 class="fs-5">Phone</h3>
                      <p class="text-muted">0431137222</p>
                   </div>
                </div>
                <div class="contact-item d-flex mb-3">
                   <div class="icon fs-4 text-danger">
                      <i class="fas fa-map-marker-alt"></i>
                   </div>
                   <div class="text ms-3">
                      <h3 class="fs-5">Address</h3>
                      <p class="text-muted">4 Codrington Road, Truganina, Melbourne (3029)</p>
                   </div>
                </div>
            </div>
            <div class="col-md-7">
                <div class="contact-form">
                   <form>
                      <div class="row">
                         <div class="col-lg-6 mb-4">
                            <input type="text" placeholder="Your Name" class="form-control form-control-lg fs-6 border-0 shadow-sm">
                         </div>
                         <div class="col-lg-6 mb-4">
                           <input type="text" placeholder="Your Email" class="form-control form-control-lg fs-6 border-0 shadow-sm">
                         </div>
                      </div>
                      <div class="row">
                          <div class="col-lg-12 mb-4">
                              <input type="text" placeholder="Subject" class="form-control form-control-lg fs-6 border-0 shadow-sm">
                          </div>
                      </div>
                      <div class="row">
                          <div class="col-lg-12 mb-4">
                              <textarea rows="5" placeholder="Your Message" class="form-control form-control-lg fs-6 border-0 shadow-sm"></textarea>
                          </div>
                      </div>
                      <div class="row">
                         <div class="col-lg-12">
                            <button type="submit" class="btn btn-danger px-3">Send Message</button>
                         </div>
                      </div>
                   </form>
                </div>
            </div>
        </div>
    </div>
 </section>
 <!-- contact section end -->

 <!-- footer start -->
 <footer class="footer border-top py-4">
    <div class="container-lg">
        <div class="row">
            <div class="col-lg-12">
                <p class="m-0 text-center text-muted">&copy; 2021 Sushant Gautam</p>
            </div>
        </div>
    </div>
 </footer>
 <!-- footer end -->
  

<script src="js/bootstrap.bundle.min.js"></script>
</body>
</html>
