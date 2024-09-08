<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfólio de Erike</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Erik - Desenvolvedor Web</h1>
        <nav>
            <ul>
                <li><a href="#sobre">Sobre</a></li>
                <li><a href="#projetos">Projetos</a></li>
                <li><a href="#contato">Contato</a></li>
            </ul>
        </nav>
    </header>
    <section id="sobre">
        <h2>Sobre Mim</h2>
        <p>Olá! Meu nome é Erik e tenho 20 anos. Sou apaixonado por desenvolvimento web e estou sempre em busca de novos desafios para aprimorar minhas habilidades. Tenho experiência sólida em HTML e CSS, que me permite criar layouts responsivos e visualmente atraentes. Além disso, possuo conhecimentos em JavaScript, o que me ajuda a adicionar interatividade e funcionalidades dinâmicas às páginas web. 
            
            Estou sempre em busca de oportunidades para aprender e crescer na área de desenvolvimento. Seja para criar projetos pessoais ou colaborar em equipe, estou entusiasmado com o que o futuro reserva e aberto a novas experiências e desafios.
            
            Se você estiver interessado em conversar mais sobre desenvolvimento web ou tiver oportunidades que gostaria de compartilhar, não hesite em me contatar!</p>
    </section>

    <section id="projetos">
        <h2>Meus Projetos</h2>
        <div class="projeto">
            <h3>Projeto 1</h3>
            <p>Descrição breve do Projeto 1.</p>
        </div>
        <div class="projeto">
            <h3>Projeto 2</h3>
            <p>Descrição breve do Projeto 2.</p>
        </div>
        <div class="icon-container">
            <a href="https://www.instagram.com/eriikzl_?igsh=MTBub24xMG1iM2Rm" target="_blank" title="Instagram">
                <i class="fab fa-instagram"></i>
            </a>
            <a href="eerikggabriel@gmail.com" target="_blank" title="E-mail">
                <i class="fas fa-envelope"></i>
            </a>
            <a href="https://wa.me/5511942106249" target="_blank" title="WhatsApp">
                <i class="fab fa-whatsapp"></i>
            </a>
        </div>
    </section>

    <section id="contato">
        <h2>Contato</h2>
        <form id="form-contato">
            <label for="nome">Nome:</label>
            <input type="text" id="nome" name="nome" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="mensagem">Mensagem:</label>
            <textarea id="mensagem" name="mensagem" required></textarea>
            <button type="submit">Enviar</button>
        </form>
    </section>
    <footer>
        <p>&copy; 2024 Erik. Todos os direitos reservados.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
