{% include templates/universal/character/index.md %}

<!-- charName -->
{% capture charName %}
# Zeta
{% endcapture %}

<script>
    const charNameHTML = `{{ charName | markdownify }}`;
    document.querySelector('.charIndexCharName').innerHTML = charNameHTML;
    
    const charWikiUrl= "https://www.dustloop.com/w/GBVSR/Zeta";
    document.querySelector('.charWikiUrl').href = charWikiUrl;
    
    const charPortraitImgSrc = "https://www.dustloop.com/wiki/images/f/f1/GBVSR_Zeta_Portrait.png"
    document.querySelector('.charIndexCharPortrait').src = charPortraitImgSrc;
</script>