---
layout: default
title: "NYUMBA Food Concept"
---

<div style="text-align: center; margin: 20px 0;">
    <!-- Language Switcher -->
    <button onclick="switchLanguage('pt')" style="padding: 10px 20px; margin: 5px; background: #333; color: white; border: none; border-radius: 5px;">Português</button>
    <button onclick="switchLanguage('en')" style="padding: 10px 20px; margin: 5px; background: #333; color: white; border: none; border-radius: 5px;">English</button>
</div>

<div id="portugues">
    <h2>Bem-vindo ao NYUMBA Food Concept</h2>
    <p>Localizado no FEIMA, Parque dos Continuadores, Maputo Moçambique</p>
    
    <h3>Horário de Funcionamento</h3>
    <p>Todos os dias das 9:00 às 22:30</p>
    
    <h3>Contactos</h3>
    <p>📧 Email: nyumba.maputo@gmail.com</p>
    <p>📞 Telefone/WhatsApp: +258 864663788</p>
    
    <h3>Localização</h3>
    <p>FEIMA, Parque dos Continuadores, Maputo Moçambique</p>
    <a href="https://maps.google.com/?q=-25.9665,32.5802" target="_blank" style="display: inline-block; padding: 10px 20px; background: #4285f4; color: white; text-decoration: none; border-radius: 5px; margin: 10px 0;">
        📍 Ver no Google Maps
    </a>
    
    <!-- Navigation Buttons -->
    <div style="margin: 30px 0;">
        <button onclick="location.href='{{ site.baseurl }}/menu'" style="padding: 12px 25px; margin: 10px; background: #d35400; color: white; border: none; border-radius: 5px; font-size: 16px;">Ver Menu</button>
        <button onclick="location.href='{{ site.baseurl }}/gallery'" style="padding: 12px 25px; margin: 10px; background: #27ae60; color: white; border: none; border-radius: 5px; font-size: 16px;">Galeria</button>
        <button onclick="location.href='{{ site.baseurl }}/contact'" style="padding: 12px 25px; margin: 10px; background: #2980b9; color: white; border: none; border-radius: 5px; font-size: 16px;">Contacto</button>
    </div>
</div>

<div id="english" style="display: none;">
    <h2>Welcome to NYUMBA Food Concept</h2>
    <p>Located at FEIMA, Parque dos Continuadores, Maputo Mozambique</p>
    
    <h3>Opening Hours</h3>
    <p>Every day from 9:00 AM to 10:30 PM</p>
    
    <h3>Contact Information</h3>
    <p>📧 Email: nyumba.maputo@gmail.com</p>
    <p>📞 Phone/WhatsApp: +258 864663788</p>
    
    <h3>Location</h3>
    <p>FEIMA, Parque dos Continuadores, Maputo Mozambique</p>
    <a href="https://maps.google.com/?q=-25.9665,32.5802" target="_blank" style="display: inline-block; padding: 10px 20px; background: #4285f4; color: white; text-decoration: none; border-radius: 5px; margin: 10px 0;">
        📍 View on Google Maps
    </a>
    
    <!-- Navigation Buttons -->
    <div style="margin: 30px 0;">
        <button onclick="location.href='{{ site.baseurl }}/menu'" style="padding: 12px 25px; margin: 10px; background: #d35400; color: white; border: none; border-radius: 5px; font-size: 16px;">View Menu</button>
        <button onclick="location.href='{{ site.baseurl }}/gallery'" style="padding: 12px 25px; margin: 10px; background: #27ae60; color: white; border: none; border-radius: 5px; font-size: 16px;">Gallery</button>
        <button onclick="location.href='{{ site.baseurl }}/contact'" style="padding: 12px 25px; margin: 10px; background: #2980b9; color: white; border: none; border-radius: 5px; font-size: 16px;">Contact</button>
    </div>
</div>

<script>
function switchLanguage(lang) {
    if (lang === 'pt') {
        document.getElementById('portugues').style.display = 'block';
        document.getElementById('english').style.display = 'none';
    } else {
        document.getElementById('portugues').style.display = 'none';
        document.getElementById('english').style.display = 'block';
    }
}

// Initialize Portuguese as default
switchLanguage('pt');
</script>