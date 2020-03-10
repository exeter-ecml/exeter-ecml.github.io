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
    
    {% for paper in site.suggested %}
    <tr>
        <td nowrap>{{paper.who_suggested}}</td>
        <td><a href="{{paper.url}}">{{paper.title}}</a></td>
    </tr>
    {% endfor %}
    
    </tbody>
</table>

