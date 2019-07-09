# This is a demo of mermaid diagrams and flowcharts 
Using [`include_relative`](https://jekyllrb.com/docs/includes/) Jekyll tag this markdown includes an html fragment below referencing [mermaid-format](https://github.com/knsv/mermaid) files.

## Example:
### Actual content
```
{ % include_relative mermaid-fragment.html source="example.mermaid" % }
```
### Intermediate result
```
{% include_relative mermaid-fragment.html source="example.mermaid" %}
```
### Processed finale
{% include_relative mermaid-fragment.html source="example.mermaid" %}

## Variery from the [mermaid](https://github.com/knsv/mermaid) page:
{% include_relative mermaid-fragment.html source="example.mermaid" %}
{% include_relative mermaid-fragment.html source="example.mermaid" %}
{% include_relative mermaid-fragment.html source="example.mermaid" %}
