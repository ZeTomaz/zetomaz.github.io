---
layout: default
title: "Contacto - NYUMBA Food Concept"
---

<div style="text-align: center; margin: 20px 0;">
    <button onclick="location.href='{{ site.baseurl }}/'" style="padding: 10px 20px; background: #333; color: white; border: none; border-radius: 5px;">← Voltar para Início</button>
</div>

<div style="text-align: center; margin: 20px 0;">
    <button onclick="switchContactLanguage('pt')" style="padding: 10px 20px; margin: 5px; background: #333; color: white; border: none; border-radius: 5px;">Português</button>
    <button onclick="switchContactLanguage('en')" style="padding: 10px 20px; margin: 5px; background: #333; color: white; border: none; border-radius: 5px;">English</button>
</div>

<div id="contact-pt">
    <h2>Contacte-nos</h2>

    <h3>Informações de Contacto</h3>
    <p>📧 Email: <a href="mailto:nyumba.maputo@gmail.com" style="color: #d35400;">nyumba.maputo@gmail.com</a></p>
    <p>📞 <a href="https://wa.me/258864663788" target="_blank" style="color: #25D366; text-decoration: none;">WhatsApp: +258 864663788</a></p>
    <p>📞 Telefone: <a href="tel:+258864663788" style="color: #2980b9;">+258 864663788</a></p>
    <p><strong>Localização:</strong> FEIMA, Parque dos Continuadores, Maputo Moçambique</p>
    
    <h3>Horário de Funcionamento</h3>
    <p>🕘 Todos os dias das 9:00 às 22:30</p>
    
    <h3>Envie-nos uma Mensagem</h3>
    <p>Clique abaixo para nos enviar um email diretamente:</p>
    <a href="mailto:nyumba.maputo@gmail.com?subject=Contacto%20NYUMBA%20Food%20Concept&body=Olá,%20gostaria%20de%20saber%20mais%20sobre%20os%20vossos%20serviços..." style="display: inline-block; padding: 12px 25px; background: #d35400; color: white; text-decoration: none; border-radius: 5px; margin: 10px 0; font-size: 16px;">
        📧 Enviar Email
    </a>
    
    <div style="margin-top: 20px;">
        <p>Ou contacte-nos via WhatsApp:</p>
        <a href="https://wa.me/258864663788" target="_blank" style="display: inline-block; padding: 12px 25px; background: #25D366; color: white; text-decoration: none; border-radius: 5px; margin: 10px 0; font-size: 16px;">
            💬 WhatsApp
        </a>
    </div>
</div>

<div id="contact-en" style="display: none;">
    <h2>Contact Us</h2>

    <h3>Contact Information</h3>
    <p>📧 Email: <a href="mailto:nyumba.maputo@gmail.com" style="color: #d35400;">nyumba.maputo@gmail.com</a></p>
    <p>📞 <a href="https://wa.me/258864663788" target="_blank" style="color: #25D366; text-decoration: none;">WhatsApp: +258 864663788</a></p>
    <p>📞 Phone: <a href="tel:+258864663788" style="color: #2980b9;">+258 864663788</a></p>
    <p><strong>Location:</strong> FEIMA, Parque dos Continuadores, Maputo Mozambique</p>
    
    <h3>Opening Hours</h3>
    <p>🕘 Every day from 9:00 AM to 10:30 PM</p>
    
    <h3>Send us a Message</h3>
    <p>Click below to send us an email directly:</p>
    <a href="mailto:nyumba.maputo@gmail.com?subject=NYUMBA%20Food%20Concept%20Inquiry&body=Hello,%20I%20would%20like%20to%20know%20more%20about..." style="display: inline-block; padding: 12px 25px; background: #d35400; color: white; text-decoration: none; border-radius: 5px; margin: 10px 0; font-size: 16px;">
        📧 Send Email
    </a>
    
    <div style="margin-top: 20px;">
        <p>Or contact us via WhatsApp:</p>
        <a href="https://wa.me/258864663788" target="_blank" style="display: inline-block; padding: 12px 25px; background: #25D366; color: white; text-decoration: none; border-radius: 5px; margin: 10px 0; font-size: 16px;">
            💬 WhatsApp
        </a>
    </div>
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

// Initialize Portuguese as default
switchContactLanguage('pt');
</script>