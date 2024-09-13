# hakes
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="css/bootstrap.min.css">
    <script src="js/bootstrap.bundle.min.js"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    <title>Document</title>
</head>
<body>
    
    <div class="container bg-success">
        <div class="row">
            <div class="col-lg-1">
                <nav class="navbar">
                    <div class="container-fluid">
                      <button class="navbar-toggler" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasNavbar" aria-controls="offcanvasNavbar" aria-label="Toggle navigation">
                        <span class="navbar-toggler-icon"></span>
                      </button>
                      <div class="offcanvas offcanvas-start" tabindex="-1" id="offcanvasNavbar" aria-labelledby="offcanvasNavbarLabel">
                        <div class="offcanvas-header">
                          <h5 class="offcanvas-title" id="offcanvasNavbarLabel">Offcanvas</h5>
                          <button type="button" class="btn-close" data-bs-dismiss="offcanvas" aria-label="Close"></button>
                        </div>
                        <div class="offcanvas-body">
                          <ul class="navbar-nav justify-content-end flex-grow-1 pe-3">
                            <li class="nav-item">
                              <a class="nav-link active" aria-current="page" href="#">Home</a>
                            </li>
                            <li class="nav-item">
                              <a class="nav-link" href="#">Link</a>
                            </li>
                            <li class="nav-item dropdown">
                              <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                                Dropdown
                              </a>
                              <ul class="dropdown-menu">
                                <li><a class="dropdown-item" href="#">Action</a></li>
                                <li><a class="dropdown-item" href="#">Another action</a></li>
                                <li>
                                  <hr class="dropdown-divider">
                                </li>
                                <li><a class="dropdown-item" href="#">Something else here</a></li>
                              </ul>
                            </li>
                          </ul>
                        </div>
                      </div>
                    </div>
                  </nav>
            </div>
            <div class="col-lg-3 mt-2">
                <form class="d-flex" role="search">
                    <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                    <button class="btn btn-outline-danger" type="submit">Search</button>
                  </form>
            </div>
            <div class="col-lg-8 text-end mt-2">
                <a href="" class="text-decoration-none text-white">Bangla</a>
            </div>
        </div>
    </div>
    <div class="container">
        <div class="row position-relative">
            <div class="col-lg-12 px-0">
                <img src="img/bb_banner.jpg" class="w-100">
            </div>
            <div class="col-lg-6 px-0 position-absolute end-0 bottom-0 mb-2">
                <nav class="navbar navbar-expand-lg bg-body-tertiary">
                    <div class="container-fluid">
                      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                        <span class="navbar-toggler-icon"></span>
                      </button>
                      <div class="collapse navbar-collapse" id="navbarSupportedContent">
                        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                          <li class="nav-item dropdown">
                            <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                              Dropdown
                            </a>
                            <ul class="dropdown-menu">
                              <li><a class="dropdown-item" href="#">Action</a></li>
                              <li><a class="dropdown-item" href="#">Another action</a></li>
                              <li><hr class="dropdown-divider"></li>
                              <li><a class="dropdown-item" href="#">Something else here</a></li>
                            </ul>
                          </li>
                        </ul>

                        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                            <li class="nav-item dropdown">
                              <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                                Dropdown
                              </a>
                              <ul class="dropdown-menu">
                                <li><a class="dropdown-item" href="#">Action</a></li>
                                <li><a class="dropdown-item" href="#">Another action</a></li>
                                <li><hr class="dropdown-divider"></li>
                                <li><a class="dropdown-item" href="#">Something else here</a></li>
                              </ul>
                            </li>
                          </ul>

                          
                        
                      </div>
                    </div>
                  </nav>
            </div>
        </div>
    </div>
    <div class="container mt-3">
        <div class="row">
            <div class="col-lg-9 shadow px-5">
                <div id="carouselExample" class="carousel slide">
                    <div class="carousel-inner">
                      <div class="carousel-item active">
                        <img src="img/offshore-banking-law-2024.jpg" class="d-block w-100" alt="...">
                      </div>
                      <div class="carousel-item">
                        <img src="img/rfcd.jpg" class="d-block w-100" alt="...">
                      </div>
                      <div class="carousel-item">
                        <img src="img/web---2.jpg" class="d-block w-100" alt="...">
                      </div>
                    </div>
                    <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev">
                      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                      <span class="visually-hidden">Previous</span>
                    </button>
                    <button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next">
                      <span class="carousel-control-next-icon" aria-hidden="true"></span>
                      <span class="visually-hidden">Next</span>
                    </button>
                  </div>
            </div>
            <div class="col-lg-3 shadow">
                <h4 class="text-white bg-success fs-5">Honorable Govornor</h4>
                <img src="img/ahsanhmansur.jpg" class="w-50 float-start">
                <b class="fs-6">Dr. Ahsan H. Mansur</b>
                <span>Honorable Governor of Bangladesh Bank</span>
                <br>
                <a href="" class="text-decoration-none text-dark d-flex">More</a>
            </div>
        </div>
    </div>
    <div class="container mt-2">
        <div class="row">
            <div class="col-lg-2 px-0">
                <button class="btn btn-success">Recent News</button>
            </div>
            <div class="col-lg-10 p-2">
                <marquee behavior="" direction="up"> Python is a computer programming language often used to build websites and software, automate tasks, and conduct data analysis. Python is a general-purpose language, meaning it can be used to create a variety of different programs and isn't specialized for any specific problems.</marquee>
            </div>
        </div>
    </div>
    <div class="container">
        <div class="row">
            <div class="col-lg-9">
                <div class="row">
                    <div class="col-lg-6 ">
                        <div class="promo border-top shadow border-danger p-2 border-4">
                            <h2 class="fs-3 border-start border-success border-4 ps-2">Monetary Policy</h2>
                            <i class="bi bi-bank2 text-danger me-2 float-start" style="font-size: 70px;"></i>
                            <ul class="list-unstyled mt-2">
                                <li><a href="" class="text-decoration-none text-dark"><i class="bi bi-chevron-right"></i>MPS (July-December, 2024)  </a></li>
                                <li><a href="" class="text-decoration-none text-dark"><i class="bi bi-chevron-right"></i>MPS (July-December, 2024)  </a></li>
                                <li><a href="" class="text-decoration-none text-dark"><i class="bi bi-chevron-right"></i>MPS (July-December, 2024)  </a></li>
                                <li><a href="" class="text-decoration-none text-dark"><i class="bi bi-chevron-right"></i>MPS (July-December, 2024)  </a></li>
                            </ul>
                        </div>
                    </div>
                    <div class="col-lg-6 ">
                        <div class="promo border-top shadow border-danger p-2 border-4">
                            <h2 class="fs-3 border-start border-success border-4 ps-2">Monetary Policy</h2>
                            <i class="bi bi-bank2 text-danger me-2 float-start" style="font-size: 70px;"></i>
                            <ul class="list-unstyled mt-2">
                                <li><a href="" class="text-decoration-none text-dark"><i class="bi bi-chevron-right"></i>MPS (July-December, 2024)  </a></li>
                                <li><a href="" class="text-decoration-none text-dark"><i class="bi bi-chevron-right"></i>MPS (July-December, 2024)  </a></li>
                                <li><a href="" class="text-decoration-none text-dark"><i class="bi bi-chevron-right"></i>MPS (July-December, 2024)  </a></li>
                                <li><a href="" class="text-decoration-none text-dark"><i class="bi bi-chevron-right"></i>MPS (July-December, 2024)  </a></li>
                            </ul>
                        </div>
                    </div>
                    <div class="col-lg-6 ">
                        <div class="promo border-top shadow border-danger p-2 border-4">
                            <h2 class="fs-3 border-start border-success border-4 ps-2">Monetary Policy</h2>
                            <i class="bi bi-bank2 text-danger me-2 float-start" style="font-size: 70px;"></i>
                            <ul class="list-unstyled mt-2">
                                <li><a href="" class="text-decoration-none text-dark"><i class="bi bi-chevron-right"></i>MPS (July-December, 2024)  </a></li>
                                <li><a href="" class="text-decoration-none text-dark"><i class="bi bi-chevron-right"></i>MPS (July-December, 2024)  </a></li>
                                <li><a href="" class="text-decoration-none text-dark"><i class="bi bi-chevron-right"></i>MPS (July-December, 2024)  </a></li>
                                <li><a href="" class="text-decoration-none text-dark"><i class="bi bi-chevron-right"></i>MPS (July-December, 2024)  </a></li>
                            </ul>
                        </div>
                    </div>
                    <div class="col-lg-6 ">
                        <div class="promo border-top shadow border-danger p-2 border-4">
                            <h2 class="fs-3 border-start border-success border-4 ps-2">Monetary Policy</h2>
                            <i class="bi bi-bank2 text-danger me-2 float-start" style="font-size: 70px;"></i>
                            <ul class="list-unstyled mt-2">
                                <li><a href="" class="text-decoration-none text-dark"><i class="bi bi-chevron-right"></i>MPS (July-December, 2024)  </a></li>
                                <li><a href="" class="text-decoration-none text-dark"><i class="bi bi-chevron-right"></i>MPS (July-December, 2024)  </a></li>
                                <li><a href="" class="text-decoration-none text-dark"><i class="bi bi-chevron-right"></i>MPS (July-December, 2024)  </a></li>
                                <li><a href="" class="text-decoration-none text-dark"><i class="bi bi-chevron-right"></i>MPS (July-December, 2024)  </a></li>
                            </ul>
                        </div>
                    </div>
                    <div class="col-lg-6 ">
                        <div class="promo border-top shadow border-danger p-2 border-4">
                            <h2 class="fs-3 border-start border-success border-4 ps-2">Monetary Policy</h2>
                            <i class="bi bi-bank2 text-danger me-2 float-start" style="font-size: 70px;"></i>
                            <ul class="list-unstyled mt-2">
                                <li><a href="" class="text-decoration-none text-dark"><i class="bi bi-chevron-right"></i>MPS (July-December, 2024)  </a></li>
                                <li><a href="" class="text-decoration-none text-dark"><i class="bi bi-chevron-right"></i>MPS (July-December, 2024)  </a></li>
                                <li><a href="" class="text-decoration-none text-dark"><i class="bi bi-chevron-right"></i>MPS (July-December, 2024)  </a></li>
                                <li><a href="" class="text-decoration-none text-dark"><i class="bi bi-chevron-right"></i>MPS (July-December, 2024)  </a></li>
                            </ul>
                        </div>
                    </div>
                    <div class="col-lg-6 ">
                        <div class="promo border-top shadow border-danger p-2 border-4">
                            <h2 class="fs-3 border-start border-success border-4 ps-2">Monetary Policy</h2>
                            <i class="bi bi-bank2 text-danger me-2 float-start" style="font-size: 70px;"></i>
                            <ul class="list-unstyled mt-2">
                                <li><a href="" class="text-decoration-none text-dark"><i class="bi bi-chevron-right"></i>MPS (July-December, 2024)  </a></li>
                                <li><a href="" class="text-decoration-none text-dark"><i class="bi bi-chevron-right"></i>MPS (July-December, 2024)  </a></li>
                                <li><a href="" class="text-decoration-none text-dark"><i class="bi bi-chevron-right"></i>MPS (July-December, 2024)  </a></li>
                                <li><a href="" class="text-decoration-none text-dark"><i class="bi bi-chevron-right"></i>MPS (July-December, 2024)  </a></li>
                            </ul>
                        </div>
                    </div>
                    <div class="col-lg-6 ">
                        <div class="promo border-top shadow border-danger p-2 border-4">
                            <h2 class="fs-3 border-start border-success border-4 ps-2">Monetary Policy</h2>
                            <i class="bi bi-bank2 text-danger me-2 float-start" style="font-size: 70px;"></i>
                            <ul class="list-unstyled mt-2">
                                <li><a href="" class="text-decoration-none text-dark"><i class="bi bi-chevron-right"></i>MPS (July-December, 2024)  </a></li>
                                <li><a href="" class="text-decoration-none text-dark"><i class="bi bi-chevron-right"></i>MPS (July-December, 2024)  </a></li>
                                <li><a href="" class="text-decoration-none text-dark"><i class="bi bi-chevron-right"></i>MPS (July-December, 2024)  </a></li>
                                <li><a href="" class="text-decoration-none text-dark"><i class="bi bi-chevron-right"></i>MPS (July-December, 2024)  </a></li>
                            </ul>
                        </div>
                    </div>
                    <div class="col-lg-6 ">
                        <div class="promo border-top shadow border-danger p-2 border-4">
                            <h2 class="fs-3 border-start border-success border-4 ps-2">Monetary Policy</h2>
                            <i class="bi bi-bank2 text-danger me-2 float-start" style="font-size: 70px;"></i>
                            <ul class="list-unstyled mt-2">
                                <li><a href="" class="text-decoration-none text-dark"><i class="bi bi-chevron-right"></i>MPS (July-December, 2024)  </a></li>
                                <li><a href="" class="text-decoration-none text-dark"><i class="bi bi-chevron-right"></i>MPS (July-December, 2024)  </a></li>
                                <li><a href="" class="text-decoration-none text-dark"><i class="bi bi-chevron-right"></i>MPS (July-December, 2024)  </a></li>
                                <li><a href="" class="text-decoration-none text-dark"><i class="bi bi-chevron-right"></i>MPS (July-December, 2024)  </a></li>
                            </ul>
                        </div>
                    </div>
                </div>

              
                

            </div>
            <div class="col-lg-3">

            </div>
        </div>
    </div>
</body>
</html>
