{% include templates/games/GranBlueFantasyVersusRising/allCombos.md %}

<!-- Normal Hit - Mid-Screen -->
{% capture allCombosNormalMidScreen %}
- TODO
{% endcapture %}

<!-- Normal Hit - Corner -->
{% capture allCombosNormalCorner %}
- TODO
{% endcapture %}

<!-- Normal Hit - Cornered -->
{% capture allCombosNormalCornered %}
- TODO
{% endcapture %}

<!-- Counter Hit - Mid-Screen -->
{% capture allCombosCounterMidScreen %}
- TODO
{% endcapture %}


<!-- Counter Hit - Corner -->
{% capture allCombosCounterCorner %}
- TODO
{% endcapture %}

<!-- Counter Hit - Cornered -->
{% capture allCombosCounterCornered %}
- TODO
{% endcapture %}

<script>
    const allCombosNormalMidScreenHTML = `{{ allCombosNormalMidScreen | markdownify }}`;
    document.querySelector('.allCombosNormalMidScreen').innerHTML = allCombosNormalMidScreenHTML;

    const allCombosNormalCornerHTML = `{{ allCombosNormalCorner | markdownify }}`;
    document.querySelector('.allCombosNormalCorner').innerHTML = allCombosNormalCornerHTML;

    const allCombosNormalCorneredHTML = `{{ allCombosNormalCornered | markdownify }}`;
    document.querySelector('.allCombosNormalCornered').innerHTML = allCombosNormalCorneredHTML;

    const allCombosCounterMidScreenHTML = `{{ allCombosCounterMidScreen | markdownify }}`;
    document.querySelector('.allCombosCounterMidScreen').innerHTML = allCombosCounterMidScreenHTML;

    const allCombosCounterCornerHTML = `{{ allCombosCounterCorner | markdownify }}`;
    document.querySelector('.allCombosCounterCorner').innerHTML = allCombosCounterCornerHTML;

    const allCombosCounterCorneredHTML = `{{ allCombosCounterCornered | markdownify }}`;
    document.querySelector('.allCombosCounterCornered').innerHTML = allCombosCounterCorneredHTML;
</script>

<script src="https://cdn.jsdelivr.net/npm/tocbot/dist/tocbot.min.js"></script>
<script>
tocbot.init({
  tocSelector: '.toc',
  contentSelector: '.charGuideContent',
  headingSelector: 'h2, h3, h4',
  orderedList: false
});
</script>
