---
layout: default
title: "Galeria - NYUMBA Food Concept"
---

<div style="text-align: center; margin: 20px 0;">
    <button onclick="location.href='{{ site.baseurl }}/'">← Voltar para Início</button>
</div>

<div style="text-align: center; margin: 20px 0;">
    <button onclick="switchGalleryLanguage('pt')" style="padding: 10px 20px; margin: 5px; background: #333; color: white; border: none; border-radius: 5px;">Português</button>
    <button onclick="switchGalleryLanguage('en')" style="padding: 10px 20px; margin: 5px; background: #333; color: white; border: none; border-radius: 5px;">English</button>
</div>

<div id="gallery-pt">
    <h2>Galeria do Nosso Espaço</h2>
    
    <div style="text-align: center;">
        <p>Adicione aqui as suas imagens do kiosk NYUMBA Food Concept</p>
        
        <!-- Example image placeholders - replace with your actual images -->
        <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; margin: 30px 0;">
            <div style="background: #f0f0f0; height: 200px; display: flex; align-items: center; justify-content: center; border-radius: 10px;">
                <p>Imagem 1 do Espaço</p>
            </div>
            <div style="background: #f0f0f0; height: 200px; display: flex; align-items: center; justify-content: center; border-radius: 10px;">
                <p>Imagem 2 da Comida</p>
            </div>
            <div style="background: #f0f0f0; height: 200px; display: flex; align-items: center; justify-content: center; border-radius: 10px;">
                <p>Imagem 3 do Ambiente</p>
            </div>
            <div style="background: #f0f0f0; height: 200px; display: flex; align-items: center; justify-content: center; border-radius: 10px;">
                <p>Imagem 4 dos Clientes</p>
            </div>
        </div>
    </div>
</div>

<div id="gallery-en" style="display: none;">
    <h2>Our Space Gallery</h2>
    
    <div style="text-align: center;">
        <p>Add your NYUMBA Food Concept kiosk images here</p>
        
        <!-- Example image placeholders - replace with your actual images -->
        <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; margin: 30px 0;">
            <div style="background: #f0f0f0; height: 200px; display: flex; align-items: center; justify-content: center; border-radius: 10px;">
                <p>Space Image 1</p>
            </div>
            <div style="background: #f0f0f0; height: 200px; display: flex; align-items: center; justify-content: center; border-radius: 10px;">
                <p>Food Image 2</p>
            </div>
            <div style="background: #f0f0f0; height: 200px; display: flex; align-items: center; justify-content: center; border-radius: 10px;">
                <p>Ambience Image 3</p>
            </div>
            <div style="background: #f0f0f0; height: 200px; display: flex; align-items: center; justify-content: center; border-radius: 10px;">
                <p>Customers Image 4</p>
            </div>
        </div>
    </div>
</div>

<p style="text-align: center;">
    <em>Para adicionar imagens, salve-as na pasta 'images' e use:<br>
    &lt;img src="{{ '/images/nome-da-sua-imagem.jpg' | relative_url }}" alt="Descrição" style="max-width: 100%; border-radius: 10px;"&gt;</em>
</p>

<script>
function switchGalleryLanguage(lang) {
    if (lang === 'pt') {
        document.getElementById('gallery-pt').style.display = 'block';
        document.getElementById('gallery-en').style.display = 'none';
    } else {
        document.getElementById('gallery-pt').style.display = 'none';
        document.getElementById('gallery-en').style.display = 'block';
    }
}

// Initialize Portuguese as default
switchGalleryLanguage('pt');
</script>