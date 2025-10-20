---
layout: default
title: "Contacto - NYUMBA Food Concept"
---

<div style="text-align: center; margin: 20px 0;">
    <button onclick="location.href='{{ site.baseurl }}/'">← Voltar para Início</button>
</div>

<h2>Contacte-nos</h2>

<div id="contact-pt">
    <h3>Informações de Contacto</h3>
    <p><strong>Email:</strong> nyumba.maputo@gmail.com</p>
    <p><strong>Telefone/WhatsApp:</strong> +258 864663788</p>
    <p><strong>Localização:</strong> FEIMA, Parque dos Continuadores, Maputo Moçambique</p>
    
    <h3>Horário de Funcionamento</h3>
    <p>🕘 Todos os dias das 9:00 às 22:30</p>
    
    <h3>Envie-nos uma Mensagem</h3>
    <form action="https://formspree.io/f/your-form-id" method="POST">
        <input type="text" name="name" placeholder="Seu nome" required style="margin: 5px; padding: 10px; width: 300px;"><br>
        <input type="email" name="email" placeholder="Seu email" required style="margin: 5px; padding: 10px; width: 300px;"><br>
        <textarea name="message" placeholder="Sua mensagem" required style="margin: 5px; padding: 10px; width: 300px; height: 150px;"></textarea><br>
        <button type="submit" style="margin: 5px; padding: 10px 20px;">Enviar Mensagem</button>
    </form>
</div>

<div id="contact-en" style="display: none;">
    <h3>Contact Information</h3>
    <p><strong>Email:</strong> nyumba.maputo@gmail.com</p>
    <p><strong>Phone/WhatsApp:</strong> +258 864663788</p>
    <p><strong>Location:</strong> FEIMA, Parque dos Continuadores, Maputo Mozambique</p>
    
    <h3>Opening Hours</h3>
    <p>🕘 Every day from 9:00 AM to 10:30 PM</p>
    
    <h3>Send us a Message</h3>
    <form action="https://formspree.io/f/your-form-id" method="POST">
        <input type="text" name="name" placeholder="Your name" required style="margin: 5px; padding: 10px; width: 300px;"><br>
        <input type="email" name="email" placeholder="Your email" required style="margin: 5px; padding: 10px; width: 300px;"><br>
        <textarea name="message" placeholder="Your message" required style="margin: 5px; padding: 10px; width: 300px; height: 150px;"></textarea><br>
        <button type="submit" style="margin: 5px; padding: 10px 20px;">Send Message</button>
    </form>
</div>

<div style="text-align: center; margin: 20px 0;">
    <button onclick="switchContactLanguage('pt')">Português</button>
    <button onclick="switchContactLanguage('en')">English</button>
</div>

<script>
function switchContactLanguage(lang) {
    if (lang === 'pt') {
        document.getElementById('contact-pt').style.display = 'block';
        document.getElementById('contact-en').style.display = 'none';
    } else {
        document.getElementById('contact-pt').style.display = 'none';
        document.getElementById('contact-en').style.display = 'block';
    }
}
</script>