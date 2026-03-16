{% include templates/games/GranBlueFantasyVersusRising/tldr.md %}

<!-- ## Gameplan -->
{% capture tldrGameplan %}
- TODO
{% endcapture %}

<!-- ## Char specific -->
{% capture tldrCharSpecific %}
- TODO
{% endcapture %}

<!-- ## Poke/Spam -->
{% capture tldrPokeSpam %}
- TODO
{% endcapture %}

<!-- ## Pressure - Mid-Screen -->
{% capture tldrPressureMidScreen %}
- TODO
{% endcapture %}

<!-- ## Pressure - Corner -->
{% capture tldrPressureCorner %}
- TODO
{% endcapture %}

<!-- ## Setups -->
{% capture tldrSetups %}
- TODO
{% endcapture %}

<!-- ## Anti-Air -->
{% capture tldrAntiAir %}
- TODO
{% endcapture %}

<!-- ## Corner-Carry -->
{% capture tldrCornerCarry %}
- TODO
{% endcapture %}

<!-- ## Corner Combo -->
{% capture tldrCornerCombo %}
- TODO
{% endcapture %}

<!-- ## Fast Punish -->
{% capture tldrFastPunish %}
- TODO
{% endcapture %}

<!-- ## Slow Punish -->
{% capture tldrSlowPunish %}
- TODO
{% endcapture %}

<script>
    const tldrGameplanHTML = `{{ tldrGameplan | markdownify }}`;
    document.querySelector('.tldrGameplan').innerHTML = tldrGameplanHTML;

    const tldrCharSpecificHTML = `{{ tldrCharSpecific | markdownify }}`;
    document.querySelector('.tldrCharSpecific').innerHTML = tldrCharSpecificHTML;

    const tldrPokeSpamHTML = `{{ tldrPokeSpam | markdownify }}`;
    document.querySelector('.tldrPokeSpam').innerHTML = tldrPokeSpamHTML;

    const tldrPressureMidScreenHTML = `{{ tldrPressureMidScreen | markdownify }}`;
    document.querySelector('.tldrPressureMidScreen').innerHTML = tldrPressureMidScreenHTML;

    const tldrPressureCornerHTML = `{{ tldrPressureCorner | markdownify }}`;
    document.querySelector('.tldrPressureCorner').innerHTML = tldrPressureCornerHTML;

    const tldrSetupsHTML = `{{ tldrSetups | markdownify }}`;
    document.querySelector('.tldrSetups').innerHTML = tldrSetupsHTML;

    const tldrAntiAirHTML = `{{ tldrAntiAir | markdownify }}`;
    document.querySelector('.tldrAntiAir').innerHTML = tldrAntiAirHTML;

    const tldrCornerCarryHTML = `{{ tldrCornerCarry | markdownify }}`;
    document.querySelector('.tldrCornerCarry').innerHTML = tldrCornerCarryHTML;

    const tldrCornerComboHTML = `{{ tldrCornerCombo | markdownify }}`;
    document.querySelector('.tldrCornerCombo').innerHTML = tldrCornerComboHTML;

    const tldrFastPunishHTML = `{{ tldrFastPunish | markdownify }}`;
    document.querySelector('.tldrFastPunish').innerHTML = tldrFastPunishHTML;

    const tldrSlowPunishHTML = `{{ tldrSlowPunish | markdownify }}`;
    document.querySelector('.tldrSlowPunish').innerHTML = tldrSlowPunishHTML;
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
