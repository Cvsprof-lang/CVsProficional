<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CV Profissional - Emílio em Pemba</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>CV Profissional por Emílio</h1>
        <p>Serviços de criação de CVs prontos e atualizado, Pemba, Cabo Delgado, Moçambique. Envie seus dados e,receba um CV profissional!</p>
    </header>

    <section id="servicos">
        <h2>Nossos Serviços</h2>
        <ul>
            <li><strong>CV Básico</strong>: 200 MZN - Inclui formatação profissional com seus dados.</li>
            <li><strong>CV Avançado</strong>: 500 MZN - Com carta de apresentação e otimização para ATS (sistemas de recrutamento).</li>
            <li><strong>Pacote Completo</strong>: 800 MZN - CV, carta e perfil LinkedIn otimizado.</li>
        </ul>
        <p>Processo: Você envia seus dados via formulário abaixo. Eu confirmo pagamento via M-Pesa ou PayPal, faço o CV em 24-48 horas e envio por e-mail em PDF/Word.</p>
    </section>

    <section id="formulario">
        <h2>Envie Seus Dados para Criar o CV</h2>
        <form action="https://formspree.io/f/SEU_EMAIL_FORMSPREE" method="POST"> <!-- Substitua por seu link Formspree -->
            <label for="nome">Nome Completo:</label>
            <input type="text" id="nome" name="nome" required>

            <label for="email">E-mail:</label>
            <input type="email" id="email" name="email" required>

            <label for="telefone">Telefone/M-Pesa:</label>
            <input type="text" id="telefone" name="telefone" required>

            <label for="pacote">Pacote Escolhido:</label>
            <select id="pacote" name="pacote" required>
                <option value="basico">CV Básico (200 MZN)</option>
                <option value="avancado">CV Avançado (500 MZN)</option>
                <option value="completo">Pacote Completo (800 MZN)</option>
            </select>

            <label for="dados">Seus Dados Profissionais (experiência, educação, habilidades):</label>
            <textarea id="dados" name="dados" rows="10" required></textarea>

            <button type="submit">Enviar Dados e Solicitar CV</button>
        </form>
    </section>

    <section id="sobre">
        <h2>Sobre Mim</h2>
        <p>Olá, sou Emílio de Pemba. Especializo-me em criar CVs que destacam suas habilidades para empregos em Moçambique e além. Garantia de satisfação ou reembolso!</p>
    </section>

    <footer>
        <p>Contato: emilio.cv@example.com | +258 123 456 789 | Quelimane, Zambezia</p>
        <p>&copy; 2026 CV Profissional. Todos os direitos reservados.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
