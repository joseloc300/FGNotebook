{% include templates/universal/character/guideBase.md %}

{% capture charGuideName %}
# Starter

[Return to character](./)
{% endcapture %}

{% capture charGuideContent %}
## Char specific

<div class="starterCharSpecific" markdown="1">

- TODO - BasePlaceholder

</div>

## Safe ender

<div class="starterSafeEnder" markdown="1">

- TODO - BasePlaceholder

</div>

## Pokes/Blockstrings/Frametraps/+Frames

<div class="starterPokesBlockstringsFramtrapsPlusFrames" markdown="1">

- TODO - BasePlaceholder

</div>

## Mixups

<div class="starterMixups" markdown="1">

- TODO - BasePlaceholder

</div>

## Anti-Air

<div class="starterAntiAir" markdown="1">

- TODO - BasePlaceholder

</div>

## Cross-up

<div class="starterCrossUp" markdown="1">

- TODO - BasePlaceholder

</div>

## Corner-Carry/Punish combo

<div class="starterCornerCarryPunishCombo" markdown="1">

- TODO - BasePlaceholder

</div>

## Corner combo

<div class="starterCornerCombo" markdown="1">

- TODO - BasePlaceholder

</div>

{% endcapture %}

{% capture charGuideTOC %}
Contents

<div class="toc"></div>

{% endcapture %}

<script>
    const charGuideNameHTML = `{{ charGuideName | markdownify }}`;
    document.querySelector('.charGuideName').innerHTML = charGuideNameHTML;

    const charGuideContentHTML = `{{ charGuideContent | markdownify }}`;
    document.querySelector('.charGuideContent').innerHTML = charGuideContentHTML;

    const charGuideTocHTML = `{{ charGuideTOC | markdownify }}`;
    document.querySelector('.charGuideTOC').innerHTML = charGuideTocHTML;
</script>
