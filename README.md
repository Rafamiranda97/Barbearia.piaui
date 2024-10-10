<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Barbearia Piauí</title>
    <style>
        /* Estilo geral */
        body {
            font-family: 'Arial', sans-serif;
            background-color: #000; /* Fundo preto */
            color: #f1f1f1; /* Texto claro */
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #111;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            font-size: 48px;
            margin: 0;
            color: #ffb300; /* Cor amarela para contraste */
        }

        nav {
            background-color: #222;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
        }

        nav a:hover {
            color: #ffb300; /* Efeito hover nos links */
        }

        .container {
            width: 90%;
            margin: 20px auto;
        }

        .hero {
            background-color: #333;
            padding: 50px;
            text-align: center;
            border-radius: 10px;
        }

        .hero h2 {
            font-size: 36px;
            margin-bottom: 20px;
        }

        .hero p {
            font-size: 18px;
            line-height: 1.6;
        }

        .services {
            margin-top: 40px;
        }

        .services h2 {
            font-size: 32px;
            text-align: center;
            margin-bottom: 20px;
        }

        .services-list {
            display: flex;
            justify-content: space-between;
            flex-wrap: wrap;
        }

        .services-list div {
            background-color: #444;
            padding: 20px;
            width: 45%;
            margin-bottom: 20px;
            border-radius: 10px;
        }

        .services-list div h3 {
            margin-top: 0;
            color: #ffb300;
        }

        .services-list div p {
            font-size: 16px;
        }

        footer {
            background-color: #111;
            color: #fff;
            text-align: center;
            padding: 20px 0;
            margin-top: 40px;
        }

        footer p {
            margin: 5px 0;
        }

        .hours, .contact {
            margin-top: 40px;
            text-align: center;
        }

        .hours h2, .contact h2 {
            font-size: 28px;
            color: #ffb300;
        }

        .hours p, .contact p {
            font-size: 18px;
        }

        .contact a {
            color: #ffb300;
            text-decoration: none;
        }

        @media (max-width: 768px) {
            .services-list {
                flex-direction: column;
                align-items: center;
            }

            .services-list div {
                width: 90%;
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>Barbearia Piauí</h1>
    </header>

    <nav>
        <a href="#sobre">Sobre Nós</a>
        <a href="#servicos">Serviços</a>
        <a href="#horarios">Horários</a>
        <a href="#contato">Contato</a>
    </nav>

    <div class="container">
        <section id="sobre" class="hero">
            <h2>Bem-vindo à Barbearia Piauí</h2>
            <p>
                Na Barbearia Piauí, acreditamos que cada corte conta uma história. Nossa equipe dedicada combina técnica e criatividade para oferecer cortes sociais, degradês, e serviços de barba que vão além das suas expectativas. Em um ambiente acolhedor e descontraído, você encontrará não apenas um serviço de qualidade, mas uma verdadeira experiência de transformação. Venha nos visitar e saia com um visual que reflita sua personalidade. Agende seu horário e dê o próximo passo para o seu novo estilo!
            </p>
        </section>

        <section id="servicos" class="services">
            <h2>Nossos Serviços</h2>
            <div class="services-list">
                <div>
                    <h3>Cabelo</h3>
                    <p>Oferecemos cortes modernos, clássicos e personalizados para atender ao seu estilo.</p>
                </div>
                <div>
                    <h3>Barba</h3>
                    <p>Tratamentos de barba com precisão, cuidado e técnicas profissionais.</p>
                </div>
                <div>
                    <h3>Bigode</h3>
                    <p>Cuidados com o bigode, incluindo aparo e estilo personalizado.</p>
                </div>
                <div>
                    <h3>Sobrancelha</h3>
                    <p>Modelagem de sobrancelhas para complementar seu visual.</p>
                </div>
            </div>
        </section>

        <section id="horarios" class="hours">
            <h2>Horários de Funcionamento</h2>
            <p>Segunda a sábado: 9:30h às 18:30h</p>
            <p>*Consulte a disponibilidade*</p>
        </section>

        <section id="contato" class="contact">
            <h2>Contato</h2>
            <p>Telefone fixo: (61) 3347-4547</p>
            <p><a href="https://wa.me/5561994390799" target="_blank">Entre em contato pelo WhatsApp</a></p>
            <p>Endereço: CLN 407 BLOCO C LOJA 11 - ASA NORTE</p>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 Barbearia Piauí - Todos os direitos reservados</p>
        <p>Desenvolvido com cuidado para você</p>
    </footer>

</body>
</html>
