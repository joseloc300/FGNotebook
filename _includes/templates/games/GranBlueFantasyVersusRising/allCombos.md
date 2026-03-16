{% include templates/universal/character/guideBase.md %}

{% capture charGuideName %}
# All combos

[Return to character](./)
{% endcapture %}

{% capture charGuideContent %}
## Normal Hit

### Mid-Screen

<div class="allCombosNormalMidScreen" markdown="1">

- TODO - BasePlaceholder

</div>

### Corner

<div class="allCombosNormalCorner" markdown="1">

- TODO - BasePlaceholder

</div>

### Cornered

<div class="allCombosNormalCornered" markdown="1">

- TODO - BasePlaceholder

</div>

## Counter Hit

### Mid-Screen

<div class="allCombosCounterMidScreen" markdown="1">

- TODO - BasePlaceholder

</div>

### Corner

<div class="allCombosCounterCorner" markdown="1">

- TODO - BasePlaceholder

</div>

### Cornered

<div class="allCombosCounterCornered" markdown="1">

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
