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
        <p>Conheça o nosso kiosk NYUMBA Food Concept</p>
        
        <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; margin: 30px 0;">
            <img src="{{ '/images/gallery1.jpg' | relative_url }}" alt="NYUMBA Food Concept Espaço 1" style="width: 100%; height: 200px; object-fit: cover; border-radius: 10px;">
            <img src="{{ '/images/gallery2.jpg' | relative_url }}" alt="NYUMBA Food Concept Espaço 2" style="width: 100%; height: 200px; object-fit: cover; border-radius: 10px;">
            <img src="{{ '/images/gallery3.jpg' | relative_url }}" alt="NYUMBA Food Concept Espaço 3" style="width: 100%; height: 200px; object-fit: cover; border-radius: 10px;">
            <img src="{{ '/images/gallery4.jpg' | relative_url }}" alt="NYUMBA Food Concept Espaço 4" style="width: 100%; height: 200px; object-fit: cover; border-radius: 10px;">
        </div>
    </div>
</div>

<div id="gallery-en" style="display: none;">
    <h2>Our Space Gallery</h2>
    
    <div style="text-align: center;">
        <p>Discover our NYUMBA Food Concept kiosk</p>
        
        <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; margin: 30px 0;">
            <img src="{{ '/images/gallery1.jpg' | relative_url }}" alt="NYUMBA Food Concept Space 1" style="width: 100%; height: 200px; object-fit: cover; border-radius: 10px;">
            <img src="{{ '/images/gallery2.jpg' | relative_url }}" alt="NYUMBA Food Concept Space 2" style="width: 100%; height: 200px; object-fit: cover; border-radius: 10px;">
            <img src="{{ '/images/gallery3.jpg' | relative_url }}" alt="NYUMBA Food Concept Space 3" style="width: 100%; height: 200px; object-fit: cover; border-radius: 10px;">
            <img src="{{ '/images/gallery4.jpg' | relative_url }}" alt="NYUMBA Food Concept Space 4" style="width: 100%; height: 200px; object-fit: cover; border-radius: 10px;">
        </div>
    </div>
</div>

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