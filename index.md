# A demo of mermaid lib usage with Github Pages and Markdown
Using [`include_relative`](https://jekyllrb.com/docs/includes/) Jekyll tag this markdown includes an html fragment below referencing [mermaid-format](https://github.com/knsv/mermaid) files.

## Example:
### Actual content
```Liquid
{% raw %}
{% include_relative mermaid-fragment.html source="mermaid/flowchart.mmd" %}
{% endraw %}
```
### Intermediate result
```html
{% include_relative mermaid-fragment.html source="mermaid/flowchart.mmd" %}
```
### Processed finale
{% include_relative mermaid-fragment.html source="mermaid/flowchart.mmd" %}

## Variery from the [mermaid](https://github.com/knsv/mermaid) page:
{% include_relative mermaid-fragment.html source="mermaid/sequence.mmd" %}
{% include_relative mermaid-fragment.html source="mermaid/gantt.mmd" %}
{% include_relative mermaid-fragment.html source="mermaid/class.mmd" %}
