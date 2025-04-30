<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>King Clean - Higienização Profunda</title>
  <style>
    :root {
      --azul-marinho: #002b5b;
      --amarelo: #ffd700;
      --branco: #ffffff;
    }
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: var(--branco);
      color: var(--azul-marinho);
    }
    header {
      background-color: var(--azul-marinho);
      color: var(--branco);
      padding: 20px;
      text-align: center;
      position: relative;
    }
    .header-social-icons {
      position: absolute;
      top: 20px;
      right: 20px;
    }
    .header-social-icons a {
      margin-left: 10px;
      color: var(--branco);
      text-decoration: none;
      font-size: 1.2rem;
    }
    section {
      padding: 40px 20px;
      max-width: 900px;
      margin: auto;
    }
    h2 {
      color: var(--azul-marinho);
    }
    ul {
      list-style: none;
      padding: 0;
    }
    ul li::before {
      content: '\2714';
      margin-right: 8px;
      color: green;
    }
    .services, .benefits, .testimonials {
      background-color: var(--branco);
      margin: 20px 0;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.05);
    }
    .contact {
      background-color: #f4f9ff;
      padding: 20px;
      border-radius: 8px;
    }
    .btn-orcamento {
      display: inline-block;
      background-color: var(--amarelo);
      color: var(--azul-marinho);
      padding: 12px 20px;
      margin-top: 15px;
      border: none;
      border-radius: 5px;
      text-decoration: none;
      font-weight: bold;
      transition: background-color 0.3s;
    }
    .btn-orcamento:hover {
      background-color: #e6c200;
    }
    .social-icons {
      margin-top: 10px;
    }
    .social-icons a {
      margin: 0 10px;
      color: var(--branco);
      text-decoration: none;
      font-size: 1.5rem;
    }
    footer {
      background-color: var(--azul-marinho);
      color: var(--branco);
      text-align: center;
      padding: 10px;
    }
    .testimonial {
      margin-bottom: 20px;
      padding: 10px;
      border-left: 4px solid var(--amarelo);
      background-color: #f9f9f9;
    }
    .testimonial p {
      margin: 5px 0;
    }
    .testimonial strong {
      color: var(--azul-marinho);
    }
  </style>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
</head>
<body>
  <header>
    <div class="header-social-icons">
      <a href="https://wa.me/5511984008851" target="_blank"><i class="fab fa-whatsapp"></i></a>
      <a href="mailto:contato@kingclean.com" target="_blank"><i class="fas fa-envelope"></i></a>
      <a href="https://www.instagram.com/kingclean" target="_blank"><i class="fab fa-instagram"></i></a>
      <a href="https://www.facebook.com/kingclean" target="_blank"><i class="fab fa-facebook"></i></a>
    </div>
    <h1>King Clean</h1>
    <p>Higienização Profunda para o Conforto do Seu Ambiente</p>
  </header>
  <section class="services">
    <h2>Nossos Serviços</h2>
    <ul>
      <li><strong>Higienização de Sofás e Poltronas:</strong> Remoção de sujeiras, manchas e odores, com técnicas para cada tipo de tecido.</li>
      <li><strong>Limpeza de Carpetes e Tapetes:</strong> Eliminação de ácaros e sujeira profunda, mantendo o aspecto de novo.</li>
      <li><strong>Desinfecção Profunda:</strong> Limpeza com eliminação de germes e bactérias.</li>
      <li><strong>Tratamento de Manchas Difíceis:</strong> Eficiente contra manchas de óleo, café, vinho e mais.</li>
      <li><strong>Proteção e Impermeabilização:</strong> Produtos que aumentam a durabilidade dos estofados.</li>
    </ul>
  </section>
  <section class="services">
    <h2>Por que Escolher a King Clean?</h2>
    <ul>
      <li>Atendimento rápido e eficiente com horários flexíveis.</li>
      <li>Equipe profissional e treinada.</li>
      <li>Produtos e técnicas modernas.</li>
      <li>Compromisso com a saúde do seu lar.</li>
    </ul>
  </section>
  <section class="benefits">
    <h2>Benefícios da Higienização</h2>
    <ul>
      <li>Redução de ácaros e bactérias.</li>
      <li>Eliminação de odores desagradáveis.</li>
      <li>Renovação visual dos móveis.</li>
      <li>Aumento da durabilidade dos estofados.</li>
    </ul>
  </section>
  <section class="testimonials">
    <h2>O que dizem nossos clientes</h2>
    <div class="testimonial">
      <p>"Excelente serviço! Meu sofá ficou como novo. Profissionais pontuais e atenciosos."</p>
      <p><strong>— Mariana S.</strong></p>
    </div>
    <div class="testimonial">
      <p>"Já utilizei a King Clean duas vezes. Sempre muito satisfeita com o resultado e atendimento!"</p>
      <p><strong>— João R.</strong></p>
    </div>
    <div class="testimonial">
      <p>"Super recomendo! Tiraram manchas antigas do meu tapete e ainda deixaram um cheirinho ótimo."</p>
      <p><strong>— Ana L.</strong></p>
    </div>
  </section>
  <section class="contact">
    <h2>Entre em Contato</h2>
    <p><strong>Telefone / WhatsApp:</strong> (11) 98400-8851</p>
    <p>Solicite um orçamento sem compromisso!</p>
    <a class="btn-orcamento" href="https://wa.me/5511984008851" target="_blank">Pedir Orçamento</a>
  </section>
  <footer>
    <p>&copy; 2025 King Clean - Todos os direitos reservados.</p>
    <div class="social-icons">
      <a href="https://wa.me/5511984008851" target="_blank"><i class="fab fa-whatsapp"></i></a>
      <a href="mailto:contato@kingclean.com" target="_blank"><i class="fas fa-envelope"></i></a>
      <a href="https://www.instagram.com/kingclean" target="_blank"><i class="fab fa-instagram"></i></a>
      <a href="https://www.facebook.com/kingclean" target="_blank"><i class="fab fa-facebook"></i></a>
    </div>
  </footer>
</body>
</html>
