---
layout: page
title: The Typer
description: Cross-platform desktop application for practicing typing skill
img: assets/img/typer.png
importance: 1
category: work
related_publications:
---



### Project description

TheTyper is a typing speed trainer project that consists of two subprojects: TyperDesktop and TyperWord. TyperDesktop is a cross-platform desktop application written in Qt6, while TyperWord is a server application written in Go using the Gin framework.

The goal of the project is to provide users with a tool to improve their typing skills by practicing typing at different speeds. TyperDesktop provides a simple and intuitive interface for users to practice typing, while TyperWord handles the logic and data storage for the typing exercises.

The project is open-source and contributions are welcome from the community


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/main_page.png" title="The Typer main page" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The Typer main page
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/typing_page.png" title="The Typer typing page" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The Typer typing page
</div>


### How to
To use TheTyper, both TyperDesktop and TyperWord must be running locally. TyperDesktop connects to TyperWord to retrieve typing exercises and submit results.





