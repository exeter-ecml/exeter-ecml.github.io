---
layout: page
title: Suggested Papers
sidebar_link: true
---

<table>
    <tbody>
    <tr><th nowrap>Suggester</th><th>Paper</th></tr>
    {% for paper in site.papers %}
        {% if paper.status == "suggested" %}
            <tr>
            <td nowrap>{{paper.who_suggested}}</td>
            <td><a href="{{paper.url}}">{{paper.title}}</a></td>
            </tr>
        {% endif %}
    {% endfor %}
    </tbody>
</table>

# Previously-discussed Papers
<table>
    <tbody>
    <tr><th nowrap>Suggester</th><th>Paper</th></tr>
    {% for paper in site.papers %}
        {% if paper.status == "happened" %}
            <tr>
            <td nowrap>{{paper.who_suggested}}</td>
            <td><a href="{{paper.url}}">{{paper.title}}</a></td>
            </tr>
        {% endif %}
    {% endfor %}
    </tbody>
</table>
