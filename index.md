# A demo of a Markdown file including an html including a mermaid file
Using [`include_relative`](https://jekyllrb.com/docs/includes/) Jekyll tag with Github Pages this markdown file includes an html fragment below referencing sources in the mermaid library format.

## Example:
### Actual content
```Liquid
{% raw %}{% include_relative mermaid-fragment.html source="mermaid/flowchart.mmd" %}{% endraw %}
```
### Intermediate result
```html
{% include_relative mermaid-fragment.html source="mermaid/flowchart.mmd" %}
```
### Processed finale
{% include_relative mermaid-fragment.html source="mermaid/flowchart.mmd" %}

## Variery of examples from the [mermaid](https://github.com/knsv/mermaid) page:
{% include_relative mermaid-fragment.html source="mermaid/sequence.mmd" %}
***
{% include_relative mermaid-fragment.html source="mermaid/gantt.mmd" %}
***
{% include_relative mermaid-fragment.html source="mermaid/class.mmd" %}
