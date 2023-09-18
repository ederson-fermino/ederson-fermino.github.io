<html lang="en">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap/dist/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-utilities/bootstrap-utilities.min.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/font-awesome/css/font-awesome.min.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@@fortawesome/fontawesome-free/css/brands.min.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@@fortawesome/fontawesome-free/css/fontawesome.min.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@@fortawesome/fontawesome-free/css/regular.min.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@@fortawesome/fontawesome-free/css/solid.min.css">
    <style>
        /* Dark Theme Styles */
        body {
            background-color: #262626; /* Dark gray background */
            color: #000000; /* White text */
        }

        /* Change the primary color to a neutral one */
        .navbar {
            background-color: #333333; /* Slightly darker gray navbar */
        }

        .navbar-dark .navbar-toggler-icon {
            background-color: #ffffff; /* White toggler icon */
        }

        .hero {
            background-color: #444444; /* Darker gray hero background */
        }

            .hero h1, .hero p, .hero a {
                color: #000000; /* White text in hero section */
            }

        .about, .services, .contact {
            background-color: #333333; /* Slightly darker gray section background */
            padding: 20px;
            border-radius: 5px;
        }

        .service-box {
            background-color: #444444; /* Darker gray service box background */
            padding: 20px;
            border-radius: 5px;
        }

        /* Text color in the white background sections */
        .about h2, .about p, .services h2, .services p, .contact h2, .contact p {
            color: #333333; /* Dark gray text on white background */
        }

        /* Improve text contrast on white background in service boxes */
        .service-box h3, .service-box p {
            color: #ffffff; /* White text in service boxes */
        }

        .contact-info {
            background-color: #444444; /* Darker gray contact info background */
            padding: 20px;
            border-radius: 5px;
        }

            /* Improve text contrast on white background in contact info */
            .contact-info p, .contact-info a {
                color: #000000; /* White text in contact info */
            }

        .footer {
            background-color: #333333; /* Slightly darker gray footer background */
            padding: 20px 0;
        }

            .footer p {
                color: #ffffff; /* White text in footer */
            }
    </style>
</head>
<body>
    <header>
        <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
            <div class="container">
                <a class="navbar-brand" href="#">ELF Software Solutions</a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                        aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav ml-auto">
                        <li class="nav-item">
                            <a class="nav-link" href="#about">Sobre Nós</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#services">Nossos Serviços</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#contact">Contato</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
    </header>
    <div class="container">
        <!-- Banner de Destaque -->
        <section class="hero bg-primary text-white text-center py-5">
            <div class="container">
                <h1>Bem-Vindo à ELF Software Solutions</h1>
                <p class="lead">Sua Parceira em Desenvolvimento de Software e Integrações</p>
                <p>Transformamos ideias em soluções tecnológicas</p>
                <a href="#contact" class="btn btn-light btn-lg ">Entre em Contato</a>
            </div>
        </section>
        <!-- Seção "Sobre Nós" -->
        <section class="about bg-light" id="about">
            <div class="container mt-5">
                <div class="row">
                    <div class="col-lg-12">
                        <h2>Sobre Nós</h2>
                        <p>Somos a ELF Software Solutions, uma equipe apaixonada por tecnologia e inovação. Fundada em 20XX, nossa jornada começou com a visão de simplificar a complexidade da tecnologia para nossos clientes.</p>
                        <p>Ao longo dos anos, alcançamos muitos marcos impressionantes. Desde a criação de soluções de software personalizadas que transformam negócios até a construção de integrações SAP de alta eficiência, nossa dedicação à excelência tem sido nossa força motriz.</p>
                        <p>Na ELF, não apenas resolvemos problemas; criamos oportunidades. Com uma equipe talentosa de especialistas em .NET e SAP B1, estamos comprometidos em ajudar nossos clientes a alcançar seus objetivos de forma eficaz e eficiente.</p>
                        <p>Estamos prontos para ser sua parceira em cada passo da sua jornada tecnológica. Seja qual for o desafio, estamos preparados para enfrentá-lo juntos.</p>
                    </div>
                </div>
            </div>
        </section>
        <!-- Seção "Nossos Serviços" -->
        <section class="services bg-light" id="services">
            <div class="container mt-5">
                <h2>Nossos Serviços</h2>
                <div class="row">
                    <div class="col-md-4">
                        <div class="service-box">
                            <i class="fas fa-code"></i>
                            <h3>Desenvolvimento .NET</h3>
                            <p>Nossos desenvolvedores .NET criam aplicativos de alta qualidade, garantindo que atendam aos seus requisitos específicos. Transformamos suas ideias em soluções tecnológicas.</p>
                        </div>
                    </div>
                    <div class="col-md-4">
                        <div class="service-box">
                            <i class="fas fa-cogs"></i>
                            <h3>Integrações SAP</h3>
                            <p>Nossos especialistas em SAP B1 criam integrações eficientes com API REST, Service Layer e DI API para facilitar o acesso e gerenciamento de dados em sistemas SAP. Simplificamos a complexidade da integração.</p>
                        </div>
                    </div>
                    <div class="col-md-4">
                        <div class="service-box">
                            <i class="fas fa-chart-bar"></i>
                            <h3>Relatórios Crystal Reports</h3>
                            <p>Fornecemos suporte na criação e personalização de relatórios Crystal Reports para obter informações precisas e úteis. Transforme seus dados em insights valiosos.</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <!-- Seção "Contato" -->
        <section class="contact bg-light" id="contact">
            <div class="container mt-5">
                <h2>Contato</h2>
                <p>Estamos ansiosos para ouvir você e colaborar em seus projetos de desenvolvimento de software e integrações. Nossa equipe está pronta para atender às suas necessidades.</p>
                <div class="contact-info">
                    <p><i class="fas fa-phone"></i> +55 47 992-850-406</p>
                    <p><i class="fas fa-envelope"></i> <a href="mailto:eder.l.fermino@gmail.com">eder.l.fermino@gmail.com</a></p>
                    <p><i class="fas fa-envelope"></i> <a href="mailto:elfsolutionsme@gmail.com">elfsolutionsme@gmail.com</a></p>
                </div>
            </div>
        </section>
    </div>
    @RenderBody()
    <footer class="border-top footer text-muted">
        <div class="container">
            &copy; 2023 - ELF Software
        </div>
    </footer>
    <script src="https://cdn.jsdelivr.net/npm/jquery/dist/jquery.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap/dist/js/bootstrap.bundle.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@@fortawesome/fontawesome-free/js/all.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@@fortawesome/fontawesome-free/js/brands.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@@fortawesome/fontawesome-free/js/fontawesome.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@@fortawesome/fontawesome-free/js/regular.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@@fortawesome/fontawesome-free/js/solid.min.js"></script>
</body>
</html>
