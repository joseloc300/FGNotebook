{% include templates/games/GranBlueFantasyVersusRising/starter.md %}

<!-- ## Char specific -->
{% capture starterCharSpecific %}
- TODO
{% endcapture %}

<!-- ## Safe ender -->
{% capture starterSafeEnder %}
- TODO - whenever you are using triple attack, if it is blocked, always use this at the end to make sure you're safe. you still lose your turn.
{% endcapture %}

<!-- ## Pokes/Blockstrings/Frametraps/+Frames -->
{% capture starterPokesBlockstringsFramtrapsPlusFrames %}
- starter
  - TODO - true block string (special can't be dodged or reversal)
  - TODO - frametrap
- TODO - +Frames
- 66L >
  - corner carry combo
  - corner combo
  - frametrap
  - blockstring
  - steal turn with +Frames or 66L
  - walk up and grab - also beats dodge
{% endcapture %}

<!-- ## Mixups -->
{% capture starterMixups %}
- +Frames into strike/throw
- TODO
{% endcapture %}

<!-- ## Anti-Air -->
{% capture starterAntiAir %}
- 2H
{% endcapture %}

<!-- ## Cross-up -->
{% capture starterCrossUp %}
- TODO
{% endcapture %}

<!-- ## Corner-Carry/Punish combo -->
{% capture starterCornerCarryPunishCombo %}
- c.MXX > 
  - TODO - use the time of the triple attack to confirm your hit, even the opponent blocked it use safe ender instead
  - super - if you confirmed you are hitting your opponent and have super you can always combo into super after triple attack
{% endcapture %}

<!-- ## Corner combo -->
{% capture starterCornerCombo %}
- c.XXX > TODO > 
  - super - if you have it
  - TODO - if you don't
{% endcapture %}

<script>
    const starterCharSpecificHTML = `{{ starterCharSpecific | markdownify }}`;
    document.querySelector('.starterCharSpecific').innerHTML = starterCharSpecificHTML;

    const starterSafeEnderHTML = `{{ starterSafeEnder | markdownify }}`;
    document.querySelector('.starterSafeEnder').innerHTML = starterSafeEnderHTML;

    const starterPokesBlockstringsFramtrapsPlusFramesHTML = `{{ starterPokesBlockstringsFramtrapsPlusFrames | markdownify }}`;
    document.querySelector('.starterPokesBlockstringsFramtrapsPlusFrames').innerHTML = starterPokesBlockstringsFramtrapsPlusFramesHTML;

    const starterMixupsHTML = `{{ starterMixups | markdownify }}`;
    document.querySelector('.starterMixups').innerHTML = starterMixupsHTML;

    const starterAntiAirHTML = `{{ starterAntiAir | markdownify }}`;
    document.querySelector('.starterAntiAir').innerHTML = starterAntiAirHTML;

    const starterCrossUpHTML = `{{ starterCrossUp | markdownify }}`;
    document.querySelector('.starterCrossUp').innerHTML = starterCrossUpHTML;

    const starterCornerCarryPunishComboHTML = `{{ starterCornerCarryPunishCombo | markdownify }}`;
    document.querySelector('.starterCornerCarryPunishCombo').innerHTML = starterCornerCarryPunishComboHTML;

    const starterCornerComboHTML = `{{ starterCornerCombo | markdownify }}`;
    document.querySelector('.starterCornerCombo').innerHTML = starterCornerComboHTML;
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
