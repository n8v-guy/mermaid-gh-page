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
<code>{% include_relative mermaid-fragment.html source="mermaid/flowchart.mmd" %}</code>

## Variery of examples from the [mermaid](https://github.com/knsv/mermaid) page:
<code>{% include_relative mermaid-fragment.html source="mermaid/sequence.mmd" %}</code>

<code>{% include_relative mermaid-fragment.html source="mermaid/gantt.mmd" %}</code>

<code>{% include_relative mermaid-fragment.html source="mermaid/class.mmd" %}</code>
