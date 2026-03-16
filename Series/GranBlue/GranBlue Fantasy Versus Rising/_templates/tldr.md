
{% include templates/universal/character/guideBase.md %}

{% capture charGuideName %}
# TLDR

[Return to character](./)
{% endcapture %}

{% capture charGuideContent %}
## Gameplan

- TODO

## Char specific

- TODO

## Poke/Spam

- TODO

## Pressure

### Mid-Screen

- TODO

### Corner

- TODO

## Setups

- TODO

## Anti-Air

- TODO

## Corner-Carry

- TODO

## Corner combo

- TODO

## Fast Punish

- TODO

## Slow punish

- TODO

{% endcapture %}

{% capture charGuideTOC %}
Contents

<div class="toc"></div>

* TOC
{:toc}
{% endcapture %}

<script>
    const charGuideNameHTML = `{{ charGuideName | markdownify }}`;
    document.querySelector('.charGuideName').innerHTML = charGuideNameHTML;

    const charGuideContentHTML = `{{ charGuideContent | markdownify }}`;
    document.querySelector('.charGuideContent').innerHTML = charGuideContentHTML;

    const charGuideTocHTML = `{{ charGuideTOC | markdownify }}`;
    document.querySelector('.charGuideTOC').innerHTML = charGuideTocHTML;
</script>



<script src="https://cdn.jsdelivr.net/npm/tocbot/dist/tocbot.min.js"></script>
<script>
tocbot.init({
  tocSelector: '.toc',
  contentSelector: '.charGuideContent',
  headingSelector: 'h2, h3',
  orderedList: false
});
</script>
