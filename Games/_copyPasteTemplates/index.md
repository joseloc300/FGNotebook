{% include templates/universal/game/index.md %}

<!-- gameIndexLeftPane -->
{% capture gameIndexLeftPane %}
# Characters

- [TODOPlaceholder](./TODOPlaceholder/)
{% endcapture %}

<!-- gameIndexRightPane -->
{% capture gameIndexRightPane %}
# Extras

- [Wiki](){:target="_blank"} <!-- TODO - replace with wiki URL -->
- [Generic Tips](./genericTips.md)
{% endcapture %}

<script>
    const gameIndexLeftPaneHTML = `{{ gameIndexLeftPane | markdownify }}`;
    document.querySelector('.gameIndexLeftPane').innerHTML = gameIndexLeftPaneHTML;

    const gameIndexRightPaneHTML = `{{ gameIndexRightPane | markdownify }}`;
    document.querySelector('.gameIndexRightPane').innerHTML = gameIndexRightPaneHTML;
    
    const gameIndexLogoSrc = "" // TODO - replace with game logo src
    document.querySelector('.gameIndexLogo').src = gameIndexLogoSrc;
</script>