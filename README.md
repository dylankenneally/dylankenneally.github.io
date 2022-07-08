<!--
add build status badge: https://docs.github.com/en/actions/monitoring-and-troubleshooting-workflows/adding-a-workflow-status-badge
    click it - go to build logs
 -->

# [dylankenneally.github.io](https://dylankenneally.github.io/)

[github pages](https://docs.github.com/en/pages)' experiments with  [jekyll](https://jekyllrb.com/). nothing to see here.

this repo is just a playground to help me get familiar with [jekyll](https://jekyllrb.com/) and the updated automation pipeline in github.

anything interesting will be shown in the site that gets [deployed from this repo](https://dylankenneally.github.io/).

of more interest would be my [site](https://www.dylankenneally.com) & my [link tree](http://dylankenneally.com/).

## notes

- the jekyll theme i selected when creating the repo in github was [minimal](https://github.com/orderedlist/minimal)
- switched to this version of minimal as
  - more recently active
  - larger community, from the above link
  - more doco
  - easier to interpret demo [available](https://orderedlist.github.io/minimal/)

## findings

1. first thing i spot is that it's markdown processor/interpreter is not playing ball with <kbd>crlf</kbd> like my current go to/preferred tooling does (markdown preview enhanced[^md-prev-enhanced] + markdown all in one[^md-all-in-one] as extensions in visual studio code)
  1. i hope i'm right in thinking that can be configured; a key reason to look as jekyll (& others, like ghost) is another project needing to render 100's of markdown files
  1. hmmm, don't often find people/tools drifting far from gfm, seems really odd

<!-- footnotes used in this document -->
[^md-prev-enhanced]: markdown preview enhanced on the <a href="https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced" title="vs code's marketplace (new tab)" target="_blank">vs code market place</a> & <a href="https://github.com/shd101wyy/vscode-markdown-preview-enhanced" title="source code (new tab)" target="_blank">source code</a>.
[^md-all-in-one]: markdown all in one on the <a href="https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one" title="vs code's marketplace (new tab)" target="_blank">vs code market place</a> & <a href="https://github.com/yzhang-gh/vscode-markdown" title="source code (new tab)" target="_blank">source code</a>.

<!-- footnotes used in this document -->
[^md-prev-enhanced]: markdown preview enhanced on the <a href="https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced" title="vs code's marketplace (new tab)" target="_blank">vs code market place</a> & <a href="https://github.com/shd101wyy/vscode-markdown-preview-enhanced" title="source code (new tab)" target="_blank">source code</a>.
[^md-all-in-one]: markdown all in one on the <a href="https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one" title="vs code's marketplace (new tab)" target="_blank">vs code market place</a> & <a href="https://github.com/yzhang-gh/vscode-markdown" title="source code (new tab)" target="_blank">source code</a>.

<!-- abbreviations used in this document -->
*[gfm]: github flavoured markdown
