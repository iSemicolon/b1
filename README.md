# b1

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TSL</title>
</head>
<body>
    <!--BOOTSTRAP STARTER-->
    <!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-eOJMYsd53ii+scO/bJGFsiCZc+5NDVN2yr8+0RDqr0Ql0h+rP48ckxlpbzKgwra6" crossorigin="anonymous">

    <title>Hello, world!</title>
  </head>
  <body>
    <!--NAV BAR-->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container-fluid">
          <a class="navbar-brand" href="#">TSL</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="/">Home</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="/about.html">About</a>
              </li>
              
              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                  Dropdown
                </a>
                <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                  <li><a class="dropdown-item" href="#">Technology</a></li>
                  <li><a class="dropdown-item" href="#">Web Development</a></li>
                  <li><hr class="dropdown-divider"></li>
                  <li><a class="dropdown-item" href="#">Support</a></li>
                  <li><a class="dropdown-item" href="#">Write for us</a></li>
                </ul>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="/contact.html">Contacts us</a>
              </li>
              
              
            </ul>
            <form class="d-flex">
              <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
              <button class="btn btn-outline-success" type="submit">Search</button>
            </form>

            <div class="mx-2">
              <button class="btn btn-danger" data-bs-toggle="modal" data-bs-target="#loginModal">LogIn</button>
              <button class="btn btn-danger" data-bs-toggle="modal" data-bs-target="#signupModal">SignUp</button>
            </div>
          </div>
        </div>
      </nav>

      <!--Modal Part-->

      

<!-- LogIn Modal -->
<div class="modal fade" id="loginModal" tabindex="-1" aria-labelledby="loginModalLabel" aria-hidden="true">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title" id="loginModalLabel">Login to TSL Account</h5>
        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body">

        <!--Login Form-->
        <form>
          <div class="form-group">
            <label for="exampleInputEmail1">Email address</label>
            <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
            <small id="emailHelp" class="form-text text-muted">We'll never share your email with anyone else.</small>
          </div>
          <div class="form-group">
            <label for="exampleInputPassword1">Password</label>
            <input type="password" class="form-control" id="exampleInputPassword1">
          </div>
          <div class="form-group form-check">
            <input type="checkbox" class="form-check-input" id="exampleCheck1">
            <label class="form-check-label" for="exampleCheck1">Check me out</label>
          </div>
          <button type="submit" class="btn btn-primary">Submit</button>
        </form>

      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
        
      </div>
    </div>
  </div>
</div>




<!-- SignUp Modal -->
<div class="modal fade" id="signupModal" tabindex="-1" aria-labelledby="signupModalLabel" aria-hidden="true">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title" id="signupModalLabel">Get an TSL Account</h5>
        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body">

        <!--SignUp Form-->
        <form>
          <div class="form-group">
            <label for="exampleInputEmail1">Email address</label>
            <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
            <small id="emailHelp" class="form-text text-muted">We'll never share your email with anyone else.</small>
          </div>
          
          <div class="form-group">
            <label for="exampleInputPassword1">Password</label>
            <input type="password" class="form-control" id="exampleInputPassword1">
          </div>
          <div class="form-group">
            <label for="exampleInputPassword1">Confirm Password</label>
            <input type="password" class="form-control" id="exampleInputPassword1">
          </div>
          <br>
          <button type="submit" class="btn btn-primary">Create Account</button>
        </form>

      </div>
      <div class="modal-footer">
        
        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
        
      </div>
      
    </div>
  </div>
</div>




      <!--Slider part-->
      <div id="carouselExampleCaptions" class="carousel slide carousel-fade" data-bs-ride="carousel">
        <div class="carousel-indicators">
          <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
          <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
          <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
        </div>
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="./Images/photo-1553216431-be7493703ffa.jpeg" class="d-block w-100" alt="...">
            <div class="carousel-caption d-none d-md-block">
              <h2>Welcome to TSL</h2>
              <p>Technology News, Development & Trends</p>
              <button class="btn btn-danger">Technology</button>
              <button class="btn btn-primary">Web Development</button>
              <button class="btn btn-success">Web fun</button>
            </div>
          </div>
          <div class="carousel-item">
            <img src="./Images/photo-1617391550185-14ffe8b75fd5 (1).jpeg" class="d-block w-100" alt="...">
            <div class="carousel-caption d-none d-md-block">
                <h2>Welcome to best Coding blog</h2>
                <p>Technology News, Development & Trends</p>
                <button class="btn btn-danger">Technology</button>
                <button class="btn btn-primary">Web Development</button>
                <button class="btn btn-success">Web fun</button>
            </div>
          </div>
          <div class="carousel-item">
            <img src="./Images/photo-1617601280975-d5470038585a.jpeg" class="d-block w-100" alt="...">
            <div class="carousel-caption d-none d-md-block">
                <h2>Award Wining Blog</h2>
                <p>Technology News, Development & Trends</p>
                <button class="btn btn-danger">Technology</button>
                <button class="btn btn-primary">Web Development</button>
                <button class="btn btn-success">Web fun</button>
            </div>
          </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>

      <!--Small Blocks-->

      <!--1/2-1 thumb nail-->
      <div class="container my-5">
        <div class="row mb-2">
            <div class="col-md-6">
              <div class="row no-gutters border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative">
                <div class="col p-4 d-flex flex-column position-static">
                  <strong class="d-inline-block mb-2 text-primary">World</strong>
                  <h3 class="mb-0">Telesuite IP Logger</h3>
                  <div class="mb-1 text-muted">Nov 12</div>
                  <p class="card-text mb-auto">Telesuite IP CRS is a professional voice-recording solution used for IP telephone trunks/extension recording. It can record all the connected audio channels simultaneously with automatic start and stop and along with caller ID for incoming calls & dialed numbers for outgoing calls.</p>
                  <a href="#" class="stretched-link">Continue reading</a>
                </div>
                <div class="col-auto d-none d-lg-block">
                 <img  class="bd-placeholder-img" width="200" height="250" xmlns="http://www.w3.org/2000/svg " src="./Images/ipLogger.png" alt="">
        
                </div>
              </div>
            </div>

            <!--2/2-1-->
            <div class="col-md-6">
              <div class="row no-gutters border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative">
                <div class="col p-4 d-flex flex-column position-static">
                  <strong class="d-inline-block mb-2 text-success">Design</strong>
                  <h3 class="mb-0">Call Center Solution </h3>
                  <div class="mb-1 text-muted">Nov 11</div>
                  <p class="mb-auto">The Telesuite Outbound Call Center solution is based upon one of the most versatile, consistent progressive dialer . This powerful solution isn’t predetermined by a set of rigid constraints that many dialer dictate. Self-application (IVRS) helps maximize the agent resources.</p>
                  <a href="#" class="stretched-link">Continue reading</a>
                </div>
                <div class="col-auto d-none d-lg-block">
                    <img  class="bd-placeholder-img" width="200" height="250" xmlns="http://www.w3.org/2000/svg " src="./Images/callCenter.png" alt="">
        
                </div>
              </div>
            </div>
          </div>


          <!--1/2-2 Thumnail-->
          <div class="row mb-2">
            <div class="col-md-6">
              <div class="row no-gutters border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative">
                <div class="col p-4 d-flex flex-column position-static">
                  <strong class="d-inline-block mb-2 text-primary">World</strong>
                  <h3 class="mb-0">Call Audit System</h3>
                  <div class="mb-1 text-muted">Nov 12</div>
                  <p class="card-text mb-auto">Telesuite Call Audit (Call Accounting)
                    Telesuite Call Audit is a call accounting software which is designed to work with various PBXs. Multiple PBX clients can be connected to a single system to work as a central server. Telesuite Call Audit Call Accounting software lets you choose from a variety of reports to assist you in managing your business more effectively. Call Audit menus give you the flexibility of selecting criteria for each report to provide the specific information you need</p>
                  <a href="#" class="stretched-link">Continue reading</a>
                </div>
                <div class="col-auto d-none d-lg-block">
                 <img  class="bd-placeholder-img" width="200" height="250" xmlns="http://www.w3.org/2000/svg " src="./Images/callAudit.png" alt="">
        
                </div>
              </div>
            </div>

            <!--2/2-2 Thumbnail-->
            <div class="col-md-6">
              <div class="row no-gutters border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative">
                <div class="col p-4 d-flex flex-column position-static">
                  <strong class="d-inline-block mb-2 text-success">Design</strong>
                  <h3 class="mb-0">Global Conferences </h3>
                  <div class="mb-1 text-muted">Nov 11</div>
                  <p class="mb-auto">This is a wider card with supporting text below as a natural lead-in to additional content.</p>
                  <a href="#" class="stretched-link">Continue reading</a>
                </div>
                <div class="col-auto d-none d-lg-block">
                    <img  class="bd-placeholder-img" width="200" height="250" xmlns="http://www.w3.org/2000/svg " src="./Images/photo-1617422088163-916c42e39083.jpeg" alt="">
        
                </div>
              </div>
            </div>
          </div>

      </div>

      <!--footer Section-->
      <footer class="container">
        <p class="float-end"><a href="#">Back to top</a></p>
        <p>© 2021–2022 Company, TSL. · <a href="#">Privacy</a> · <a href="#">Terms</a></p>
      </footer>

    <!-- Optional JavaScript; choose one of the two! -->

    <!-- Option 1: Bootstrap Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta3/dist/js/bootstrap.bundle.min.js" integrity="sha384-JEW9xMcG8R+pH31jmWH6WWP0WintQrMb4s7ZOdauHnUtxwoG2vI5DkLtS3qm9Ekf" crossorigin="anonymous"></script>

    <!-- Option 2: Separate Popper and Bootstrap JS -->
    <!--
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.1/dist/umd/popper.min.js" integrity="sha384-SR1sx49pcuLnqZUnnPwx6FCym0wLsk5JZuNx2bPPENzswTNFaQU1RDvt3wT4gWFG" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta3/dist/js/bootstrap.min.js" integrity="sha384-j0CNLUeiqtyaRmlzUHCPZ+Gy5fQu0dQ6eZ/xAww941Ai1SxSY+0EQqNXNE6DZiVc" crossorigin="anonymous"></script>
    -->
  </body>
</html>
</body>
</html>
