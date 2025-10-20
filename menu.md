---
layout: default
title: "Menu - NYUMBA Food Concept"
---

<div style="text-align: center; margin: 20px 0;">
    <button onclick="location.href='{{ site.baseurl }}/'">← Voltar para Início</button>
</div>

<h2>Menu NYUMBA Food Concept</h2>

<div id="menu-pt">
    <h3>Pratos Principais</h3>
    <p>(Adicione aqui o seu menu em Português)</p>
    
    <h3>Bebidas</h3>
    <p>(Adicione aqui as suas bebidas)</p>
</div>

<div id="menu-en" style="display: none;">
    <h3>Main Dishes</h3>
    <p>(Add your menu in English here)</p>
    
    <h3>Drinks</h3>
    <p>(Add your drinks here)</p>
</div>

<div style="text-align: center; margin: 20px 0;">
    <button onclick="switchMenuLanguage('pt')">Português</button>
    <button onclick="switchMenuLanguage('en')">English</button>
</div>

<script>
function switchMenuLanguage(lang) {
    if (lang === 'pt') {
        document.getElementById('menu-pt').style.display = 'block';
        document.getElementById('menu-en').style.display = 'none';
    } else {
        document.getElementById('menu-pt').style.display = 'none';
        document.getElementById('menu-en').style.display = 'block';
    }
}
</script>