---
layout: page
title: Suggested Papers
sidebar_link: true
---

<table>
    <tbody>
    <tr>
        <th nowrap>Suggester</th><th>Paper</th>
    </tr>
    
    {% for paper in site.papers %}
        <tr>
        {% if paper.status == "suggested" %}
            <td nowrap>{{paper.who_suggested}}</td>
            <td><a href="{{paper.url}}">{{paper.title}}</a></td>
        {% elsif paper.status == "happened" %}
            <td nowrap><s>{{paper.who_suggested}}</s></td>
            <td><s><a href="{{paper.url}}">{{paper.title}}</a></s></td>
        {% endif %}
        </tr>
    {% endfor %}
    
    </tbody>
</table>

