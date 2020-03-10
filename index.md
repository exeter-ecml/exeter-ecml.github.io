---
layout: default
title: Home
---

Welcome to the ECML reading group.

To **lead a paper discussion** or if you wish to **suggest a paper** for the 
group to read then please email
[George De Ath](mailto:g.de.ath@exeter.ac.uk) or [Tinkle Chugh](mailto:T.Chugh@exeter.ac.uk).

At each reading group the paper lead will briefly give an overview of the paper,
either verbally or with slides if they wish, and then lead a discussion of each
section of the paper. Note that if a paper is from one of the big machine 
learning conferences, e.g. NeurIPS or ICML, it is very likely that a recording
exists of the paper's author's presentation. These recordings can be used as an 
alternative to the paper lead presenting an overview of the paper.

Thanks to generous funding from the Computer Science department, we will be
offering refreshments in the form of tea and coffee along with **cookies**.

### Upcoming Sessions
<table>
    <tbody>
    <tr>
        <th nowrap width="1%">When and Where</th><th>Session Details</th>
    </tr>
        
    {% for session in site.upcomming %}
    <tr>
        <td nowrap><b>Date</b>: {{session.date | date_to_long_string}} <br/>
                   <b>Time</b>: {{session.time}} <br/>
                   <b>Location</b>: {{session.location}}
        </td>
        <td> {{session.content}} </td>
    </tr>
    {% endfor %}

    </tbody>
</table>

### Previous Sessions

<table>
    <tbody>
    <tr>
        <th nowrap width="1%">When and Where</th><th>Session Details</th>
    </tr>
        
    {% for session in site.previous %}
    <tr>
        <td nowrap><b>Date</b>: {{session.date | date_to_long_string}} <br/>
                   <b>Time</b>: {{session.time}} <br/>
                   <b>Location</b>: {{session.location}}
        </td>
        <td> {{session.content}} </td>
    </tr>
    {% endfor %}

    </tbody>
</table>
