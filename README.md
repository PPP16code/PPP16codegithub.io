# PPP16codegithub.io

<!DOCTYPE html>
<html lang="pt-PT">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Nome da Empresa | Serviços & Personalização</title>

    <meta
        name="description"
        content="Reprodução de chaves, impressão 3D, molduras, gravações, artigos personalizados e ponto de levantamento de encomendas."
    >

    <style>

        /* ==================================================
           CONFIGURAÇÕES
        ================================================== */

        :root {

            --primary: #1b3478;
            --primary-dark: #122653;

            --accent: #d99a2b;

            --background: #ffffff;
            --light: #f5f6f8;

            --text: #222222;
            --muted: #666666;

            --border: #e5e7eb;

        }


        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }


        html {
            scroll-behavior: smooth;
        }


        body {

            font-family:
                Arial,
                Helvetica,
                sans-serif;

            color: var(--text);

            background: var(--background);

            line-height: 1.6;

        }


        a {
            text-decoration: none;
            color: inherit;
        }


        .container {

            width: 90%;

            max-width: 1200px;

            margin: auto;

        }



        /* ==================================================
           HEADER
        ================================================== */

        header {

            position: sticky;

            top: 0;

            z-index: 1000;

            background: white;

            border-bottom:
                1px solid var(--border);

        }


        .navbar {

            min-height: 76px;

            display: flex;

            align-items: center;

            justify-content: space-between;

        }


        .logo {

            font-size: 23px;

            font-weight: 800;

            color: var(--primary);

        }


        .logo span {

            color: var(--accent);

        }


        nav {

            display: flex;

            align-items: center;

            gap: 28px;

        }


        nav a {

            font-size: 15px;

            font-weight: 600;

            transition: 0.25s;

        }


        nav a:hover {

            color: var(--primary);

        }


        .nav-button {

            background: var(--primary);

            color: white !important;

            padding:
                11px 18px;

            border-radius: 5px;

        }


        .nav-button:hover {

            background:
                var(--primary-dark);

        }



        /* ==================================================
           HERO
        ================================================== */

        .hero {

            min-height: 600px;

            display: flex;

            align-items: center;

            background:

                linear-gradient(
                    rgba(12, 30, 65, 0.82),
                    rgba(12, 30, 65, 0.82)
                ),

                url(
                    "https://images.unsplash.com/photo-1586023492125-27b2c045efd7?auto=format&fit=crop&w=2000&q=85"
                );

            background-size: cover;

            background-position: center;

        }


        .hero-content {

            max-width: 720px;

            color: white;

        }


        .hero-label {

            display: inline-block;

            margin-bottom: 18px;

            color:
                #f1c66d;

            font-size: 13px;

            font-weight: bold;

            letter-spacing: 1.5px;

            text-transform: uppercase;

        }


        .hero h1 {

            font-size:
                clamp(40px, 6vw, 65px);

            line-height: 1.05;

            margin-bottom: 24px;

        }


        .hero p {

            max-width: 620px;

            font-size: 19px;

            color: #eeeeee;

            margin-bottom: 32px;

        }


        .hero-buttons {

            display: flex;

            flex-wrap: wrap;

            gap: 14px;

        }


        .button {

            display: inline-block;

            padding:
                14px 24px;

            border-radius: 5px;

            font-weight: bold;

            transition: 0.25s;

        }


        .button-primary {

            background:
                var(--accent);

            color: white;

        }


        .button-primary:hover {

            background: #b98020;

            transform:
                translateY(-2px);

        }


        .button-secondary {

            border:
                1px solid white;

            color: white;

        }


        .button-secondary:hover {

            background: white;

            color: var(--primary);

        }



        /* ==================================================
           SECÇÕES
        ================================================== */

        section {

            padding:
                85px 0;

        }


        .section-title {

            text-align: center;

            margin-bottom: 50px;

        }


        .section-title span {

            display: block;

            margin-bottom: 9px;

            color:
                var(--accent);

            font-size: 13px;

            font-weight: bold;

            letter-spacing: 1.5px;

            text-transform: uppercase;

        }


        .section-title h2 {

            color:
                var(--primary-dark);

            font-size: 38px;

            margin-bottom: 12px;

        }


        .section-title p {

            max-width: 680px;

            margin: auto;

            color:
                var(--muted);

        }



        /* ==================================================
           SERVIÇOS
        ================================================== */

        .services {

            background:
                var(--light);

        }


        .services-grid {

            display: grid;

            grid-template-columns:
                repeat(5, 1fr);

            gap: 18px;

        }


        .service-card {

            background: white;

            padding:
                30px 22px;

            border:
                1px solid var(--border);

            border-radius: 7px;

            transition: 0.25s;

        }


        .service-card:hover {

            transform:
                translateY(-6px);

            box-shadow:
                0 12px 30px
                rgba(0,0,0,0.08);

        }


        .service-icon {

            width: 55px;

            height: 55px;

            display: flex;

            align-items: center;

            justify-content: center;

            background:
                #e9edf7;

            color:
                var(--primary);

            border-radius: 6px;

            font-size: 25px;

            margin-bottom: 20px;

        }


        .service-card h3 {

            color:
                var(--primary-dark);

            font-size: 18px;

            margin-bottom: 10px;

        }


        .service-card p {

            color:
                var(--muted);

            font-size: 14px;

        }



        /* ==================================================
           PERSONALIZAÇÃO
        ================================================== */

        .custom {

            background: white;

        }


        .custom-grid {

            display: grid;

            grid-template-columns:
                1fr 1fr;

            gap: 60px;

            align-items: center;

        }


        .custom-image {

            min-height: 430px;

            border-radius: 8px;

            background:

                url(
                    "https://images.unsplash.com/photo-1589994965851-a8f479c573a9?auto=format&fit=crop&w=1200&q=85"
                );

            background-size: cover;

            background-position: center;

        }


        .custom-content span {

            color:
                var(--accent);

            font-size: 13px;

            font-weight: bold;

            text-transform: uppercase;

            letter-spacing: 1.5px;

        }


        .custom-content h2 {

            color:
                var(--primary-dark);

            font-size: 38px;

            line-height: 1.15;

            margin:
                12px 0 20px;

        }


        .custom-content p {

            color:
                var(--muted);

            margin-bottom: 18px;

        }


        .custom-list {

            list-style: none;

            margin:
                20px 0 25px;

        }


        .custom-list li {

            margin-bottom: 12px;

            font-weight: 600;

        }


        .custom-list li::before {

            content: "✓";

            color:
                var(--accent);

            font-weight: bold;

            margin-right: 10px;

        }



        /* ==================================================
           PONTO DE LEVANTAMENTO
        ================================================== */

        .pickup {

            background:
                var(--primary);

            color: white;

        }


        .pickup .section-title h2 {

            color: white;

        }


        .pickup .section-title p {

            color:
                #dce3f3;

        }


        .pickup-grid {

            display: grid;

            grid-template-columns:
                repeat(3, 1fr);

            gap: 22px;

        }


        .pickup-card {

            background:
                rgba(255,255,255,0.09);

            border:
                1px solid
                rgba(255,255,255,0.15);

            padding:
                32px;

            border-radius: 7px;

            text-align: center;

            transition: 0.25s;

        }


        .pickup-card:hover {

            background:
                rgba(255,255,255,0.14);

            transform:
                translateY(-4px);

        }


        .pickup-logo {

            height: 65px;

            display: flex;

            align-items: center;

            justify-content: center;

            margin-bottom: 20px;

            font-size: 24px;

            font-weight: bold;

        }


        .pickup-card h3 {

            margin-bottom: 10px;

        }


        .pickup-card p {

            color:
                #dce3f3;

            font-size: 14px;

        }



        /* ==================================================
           SOBRE
        ================================================== */

        .about {

            background:
                var(--light);

        }


        .about-content {

            max-width: 800px;

            margin: auto;

            text-align: center;

        }


        .about-content h2 {

            color:
                var(--primary-dark);

            font-size: 38px;

            margin-bottom: 20px;

        }


        .about-content p {

            color:
                var(--muted);

            margin-bottom: 15px;

        }



        /* ==================================================
           CONTACTOS
        ================================================== */

        .contact {

            background:
                #f7f7f7;

        }


        .contact-grid {

            display: grid;

            grid-template-columns:
                0.9fr 1.1fr;

            gap: 35px;

        }


        .contact-info {

            background:
                var(--primary);

            color: white;

            padding: 40px;

            border-radius: 8px;

        }


        .contact-info h2 {

            font-size: 30px;

            margin-bottom: 12px;

        }


        .contact-info > p {

            color:
                #dce3f3;

            margin-bottom: 30px;

        }


        .contact-item {

            display: flex;

            gap: 14px;

            margin-bottom: 23px;

        }


        .contact-icon {

            width: 43px;

            height: 43px;

            min-width: 43px;

            display: flex;

            align-items: center;

            justify-content: center;

            background:
                rgba(255,255,255,0.12);

            border-radius: 5px;

        }


        .contact-item strong {

            display: block;

            margin-bottom: 2px;

        }


        .contact-item span,
        .contact-item a {

            color:
                #dce3f3;

            font-size: 14px;

        }


        .contact-item a:hover {

            color: white;

        }



        /* ==================================================
           MAPA
        ================================================== */

        .map {

            min-height: 460px;

            overflow: hidden;

            border-radius: 8px;

            background: #ddd;

        }


        .map iframe {

            width: 100%;

            height: 100%;

            min-height: 460px;

            border: 0;

        }



        /* ==================================================
           CTA
        ================================================== */

        .cta {

            text-align: center;

            background:
                var(--light);

        }


        .cta h2 {

            color:
                var(--primary-dark);

            font-size: 36px;

            margin-bottom: 12px;

        }


        .cta p {

            color:
                var(--muted);

            margin-bottom: 25px;

        }



        /* ==================================================
           FOOTER
        ================================================== */

        footer {

            background:
                #101a2d;

            color: white;

            padding:
                35px 0;

        }


        .footer-content {

            display: flex;

            justify-content: space-between;

            align-items: center;

            gap: 20px;

        }


        .footer-logo {

            font-size: 20px;

            font-weight: bold;

        }


        .footer-logo span {

            color:
                var(--accent);

        }


        .footer-text {

            color:
                #aeb7c7;

            font-size: 13px;

        }



        /* ==================================================
           BOTÃO FLUTUANTE
        ================================================== */

        .contact-floating {

            position: fixed;

            right: 20px;

            bottom: 20px;

            width: 55px;

            height: 55px;

            display: flex;

            align-items: center;

            justify-content: center;

            background:
                var(--accent);

            color: white;

            border-radius: 50%;

            font-size: 23px;

            box-shadow:
                0 5px 20px
                rgba(0,0,0,0.2);

            z-index: 999;

        }



        /* ==================================================
           RESPONSIVO
        ================================================== */

        @media (max-width: 1000px) {

            .services-grid {

                grid-template-columns:
                    repeat(3, 1fr);

            }

        }


        @media (max-width: 850px) {

            nav {

                gap: 14px;

            }


            .custom-grid {

                grid-template-columns:
                    1fr;

            }


            .contact-grid {

                grid-template-columns:
                    1fr;

            }


            .pickup-grid {

                grid-template-columns:
                    1fr;

            }

        }


        @media (max-width: 650px) {

            .navbar {

                flex-direction: column;

                padding:
                    18px 0;

                gap: 15px;

            }


            nav {

                flex-wrap: wrap;

                justify-content: center;

            }


            nav a {

                font-size: 13px;

            }


            .hero {

                min-height: 560px;

            }


            .hero h1 {

                font-size: 42px;

            }


            .hero p {

                font-size: 16px;

            }


            section {

                padding:
                    65px 0;

            }


            .section-title h2 {

                font-size: 30px;

            }


            .services-grid {

                grid-template-columns:
                    1fr;

            }


            .about-content h2,
            .custom-content h2 {

                font-size: 30px;

            }


            .footer-content {

                flex-direction: column;

                text-align: center;

            }

        }

    </style>

</head>


<body>



<!-- ==================================================
     HEADER
================================================== -->

<header>

    <div class="container navbar">

        <a
            href="#inicio"
            class="logo">

            NOME<span>EMPRESA</span>

        </a>


        <nav>

            <a href="#inicio">
                Início
            </a>

            <a href="#servicos">
                Serviços
            </a>

            <a href="#encomendas">
                Encomendas
            </a>

            <a href="#sobre">
                Sobre nós
            </a>

            <a href="#contactos">
                Contactos
            </a>

            <a
                href="#contactos"
                class="nav-button">

                Contactar

            </a>

        </nav>

    </div>

</header>



<!-- ==================================================
     HERO
================================================== -->

<section
    class="hero"
    id="inicio">

    <div class="container">

        <div class="hero-content">

            <span class="hero-label">

                Serviços & Personalização

            </span>


            <h1>

                Soluções para
                o seu dia a dia.

            </h1>


            <p>

                Reprodução de chaves, impressão 3D,
                molduras, gravações, artigos personalizados
                e levantamento de encomendas.

            </p>


            <div class="hero-buttons">

                <a
                    href="#servicos"
                    class="button button-primary">

                    Ver serviços

                </a>


                <a
                    href="#contactos"
                    class="button button-secondary">

                    Onde estamos

                </a>

            </div>

        </div>

    </div>

</section>



<!-- ==================================================
     SERVIÇOS
================================================== -->

<section
    class="services"
    id="servicos">

    <div class="container">


        <div class="section-title">

            <span>
                O que fazemos
            </span>

            <h2>
                Os nossos serviços
            </h2>

            <p>

                Um conjunto de serviços práticos
                para particulares, empresas e presentes personalizados.

            </p>

        </div>



        <div class="services-grid">


            <!-- CHAVES -->

            <div class="service-card">

                <div class="service-icon">
                    🔑
                </div>

                <h3>
                    Reprodução de chaves
                </h3>

                <p>

                    Reprodução de chaves para
                    diferentes tipos de utilização.

                </p>

            </div>



            <!-- IMPRESSÃO 3D -->

            <div class="service-card">

                <div class="service-icon">
                    🖨️
                </div>

                <h3>
                    Impressão 3D
                </h3>

                <p>

                    Produção de peças e objetos
                    através de impressão 3D.

                </p>

            </div>



            <!-- MOLDURAS -->

            <div class="service-card">

                <div class="service-icon">
                    🖼️
                </div>

                <h3>
                    Molduras
                </h3>

                <p>

                    Molduras para fotografias,
                    imagens, trabalhos e decoração.

                </p>

            </div>



            <!-- GRAVAÇÕES -->

            <div class="service-card">

                <div class="service-icon">
                    ✒️
                </div>

                <h3>
                    Gravações
                </h3>

                <p>

                    Gravações personalizadas em
                    diferentes materiais e objetos.

                </p>

            </div>



            <!-- PERSONALIZADOS -->

            <div class="service-card">

                <div class="service-icon">
                    🎁
                </div>

                <h3>
                    Artigos personalizados
                </h3>

                <p>

                    Criação de artigos personalizados
                    para presentes e ocasiões especiais.

                </p>

            </div>


        </div>

    </div>

</section>



<!-- ==================================================
     PERSONALIZAÇÃO
================================================== -->

<section class="custom">

    <div class="container">

        <div class="custom-grid">


            <div class="custom-image"></div>


            <div class="custom-content">

                <span>
                    Feito à sua medida
                </span>


                <h2>

                    Dê um toque
                    pessoal às suas ideias.

                </h2>


                <p>

                    Tem uma ideia para um presente,
                    objeto ou peça personalizada?

                    Podemos ajudar a transformar
                    essa ideia num produto concreto.

                </p>


                <ul class="custom-list">

                    <li>
                        Impressão 3D personalizada
                    </li>

                    <li>
                        Gravações
                    </li>

                    <li>
                        Artigos personalizados
                    </li>

                    <li>
                        Molduras
                    </li>

                </ul>


                <a
                    href="#contactos"
                    class="button button-primary">

                    Pedir informações

                </a>

            </div>

        </div>

    </div>

</section>



<!-- ==================================================
     ENCOMENDAS
================================================== -->

<section
    class="pickup"
    id="encomendas">

    <div class="container">


        <div class="section-title">

            <span>
                Ponto de levantamento
            </span>

            <h2>
                Receba as suas encomendas connosco.
            </h2>

            <p>

                Também funcionamos como ponto de
                levantamento de encomendas de vários serviços.

            </p>

        </div>



        <div class="pickup-grid">


            <!-- AMAZON -->

            <div class="pickup-card">

                <div class="pickup-logo">

                    AMAZON

                </div>

                <h3>
                    Encomendas Amazon
                </h3>

                <p>

                    Levante as suas encomendas
                    Amazon no nosso estabelecimento.

                </p>

            </div>



            <!-- INPOST -->

            <div class="pickup-card">

                <div class="pickup-logo">

                    InPost

                </div>

                <h3>
                    InPost
                </h3>

                <p>

                    Utilize o nosso estabelecimento
                    como ponto de levantamento de encomendas.

                </p>

            </div>



            <!-- KANGURU -->

            <div class="pickup-card">

                <div class="pickup-logo">

                    KANGURU

                </div>

                <h3>
                    Kanguru
                </h3>

                <p>

                    Levantamento de encomendas
                    através do serviço Kanguru.

                </p>

            </div>


        </div>

    </div>

</section>



<!-- ==================================================
     SOBRE
================================================== -->

<section
    class="about"
    id="sobre">

    <div class="container">

        <div class="about-content">

            <span
                style="
                    color:var(--accent);
                    font-size:13px;
                    font-weight:bold;
                    letter-spacing:1.5px;
                    text-transform:uppercase;
                ">

                Sobre nós

            </span>


            <h2>

                Um espaço,
                vários serviços.

            </h2>


            <p>

                Somos um estabelecimento dedicado a
                disponibilizar serviços práticos e personalizados
                para o dia a dia.

            </p>


            <p>

                Desde uma simples reprodução de uma chave
                até à criação de uma peça personalizada em 3D,
                procuramos oferecer soluções rápidas,
                acessíveis e adaptadas a cada cliente.

            </p>

        </div>

    </div>

</section>



<!-- ==================================================
     CONTACTOS
================================================== -->

<section
    class="contact"
    id="contactos">

    <div class="container">


        <div class="section-title">

            <span>
                Visite-nos
            </span>

            <h2>
                Contactos e localização
            </h2>

            <p>

                Consulte os nossos contactos
                e encontre-nos facilmente.

            </p>

        </div>



        <div class="contact-grid">


            <!-- INFORMAÇÕES -->

            <div class="contact-info">

                <h2>
                    Fale connosco
                </h2>


                <p>

                    Para informações sobre serviços,
                    personalizados ou encomendas,
                    entre em contacto connosco.

                </p>



                <div class="contact-item">

                    <div class="contact-icon">
                        ☎
                    </div>

                    <div>

                        <strong>
                            Telefone
                        </strong>

                        <a
                            href="tel:+351000000000">

                            +351 000 000 000

                        </a>

                    </div>

                </div>



                <div class="contact-item">

                    <div class="contact-icon">
                        ✉
                    </div>

                    <div>

                        <strong>
                            Email
                        </strong>

                        <a
                            href="mailto:geral@empresa.pt">

                            geral@empresa.pt

                        </a>

                    </div>

                </div>



                <div class="contact-item">

                    <div class="contact-icon">
                        📍
                    </div>

                    <div>

                        <strong>
                            Morada
                        </strong>

                        <span>

                            Rua Exemplo, Nº 00<br>
                            0000-000 Localidade<br>
                            Portugal

                        </span>

                    </div>

                </div>



                <div class="contact-item">

                    <div class="contact-icon">
                        ⏰
                    </div>

                    <div>

                        <strong>
                            Horário
                        </strong>

                        <span>

                            Segunda a sexta:
                            09:00 – 19:00<br>

                            Sábado:
                            09:00 – 13:00

                        </span>

                    </div>

                </div>


            </div>



            <!-- MAPA -->

            <div class="map">

                <iframe

                    src="https://www.google.com/maps?q=Lisboa,Portugal&output=embed"

                    loading="lazy"

                    allowfullscreen>

                </iframe>

            </div>


        </div>

    </div>

</section>



<!-- ==================================================
     CTA
================================================== -->

<section class="cta">

    <div class="container">

        <h2>

            Precisa de alguma coisa?

        </h2>


        <p>

            Passe por cá ou entre em contacto
            connosco para saber mais.

        </p>


        <a
            href="tel:+351000000000"
            class="button button-primary">

            Contactar

        </a>

    </div>

</section>



<!-- ==================================================
     FOOTER
================================================== -->

<footer>

    <div class="container footer-content">


        <div class="footer-logo">

            NOME<span>EMPRESA</span>

        </div>


        <div class="footer-text">

            © 2026 Nome da Empresa.
            Todos os direitos reservados.

        </div>


        <div class="footer-text">

            Serviços · Personalização · Encomendas

        </div>


    </div>

</footer>



<!-- ==================================================
     BOTÃO FLUTUANTE
================================================== -->

<a

    href="tel:+351000000000"

    class="contact-floating"

    aria-label="Contactar">

    ☎

</a>


</body>

</html>
