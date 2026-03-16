{% include templates/universal/character/index.md %}

<!-- charName -->
{% capture charName %}
# Character Name
{% endcapture %}

<!-- charIndexLeftPane -->
<!-- {% capture charIndexLeftPane %}
# TODO - optional
{% endcapture %} -->

<script>
    const charNameHTML = `{{ charName | markdownify }}`;
    document.querySelector('.charIndexCharName').innerHTML = charNameHTML;

    // const charIndexLeftPaneHTML = `{{ charIndexLeftPane | markdownify }}`;
    // document.querySelector('.charIndexLeftPane').innerHTML = charIndexLeftPaneHTML;

    const charWikiUrl= ""; // TODO - might not be supported if the entire left pane is replaced with the code above
    document.querySelector('.charWikiUrl').href = charWikiUrl;

    const charPortraitImgSrc = ""
    document.querySelector('.charIndexCharPortrait').src = charPortraitImgSrc;
</script>