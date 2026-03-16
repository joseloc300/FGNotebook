{% include templates/universal/character/guideBase.md %}

{% capture charGuideName %}
# TLDR

[Return to character](./)
{% endcapture %}

{% capture charGuideContent %}
## Gameplan

<div class="tldrGameplan" markdown="1">

- TODO - BasePlaceholder

</div>

## Char specific

<div class="tldrCharSpecific" markdown="1">

- TODO - BasePlaceholder

</div>

## Poke/Spam

<div class="tldrPokeSpam" markdown="1">

- TODO - BasePlaceholder

</div>

## Pressure

### Mid-Screen

<div class="tldrPressureMidScreen" markdown="1">

- TODO - BasePlaceholder

</div>

### Corner

<div class="tldrPressureCorner" markdown="1">

- TODO - BasePlaceholder

</div>

## Setups

<div class="tldrSetups" markdown="1">

- TODO - BasePlaceholder

</div>

## Anti-Air

<div class="tldrAntiAir" markdown="1">

- TODO - BasePlaceholder

</div>

## Corner-Carry

<div class="tldrCornerCarry" markdown="1">

- TODO - BasePlaceholder

</div>

## Corner Combo

<div class="tldrCornerCombo" markdown="1">

- TODO - BasePlaceholder

</div>

## Fast Punish

<div class="tldrFastPunish" markdown="1">

- TODO - BasePlaceholder

</div>

## Slow Punish

<div class="tldrSlowPunish" markdown="1">

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
