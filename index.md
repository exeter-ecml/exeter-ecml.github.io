---
layout: page
title: 
---

Welcome to the ECML reading group. The aim of the group is to provide a 
fortnightly meeting where a discussion can take place of an agreed paper
in the area of evolutionary computation and/or machine learning. We also aim to
hold tutorial sessions on topics of interest to the community.

To **lead a paper discussion**, **present a tutorial**, or if you wish to 
**suggest a paper** for discussion then please email
[George De Ath](mailto:g.de.ath@exeter.ac.uk) or 
[Tinkle Chugh](mailto:T.Chugh@exeter.ac.uk).

At each reading group the paper lead will briefly give an overview of the paper,
either verbally or with slides if they wish, and then lead a discussion of each
section of the paper. Note that if a paper is from one of the big machine 
learning conferences, e.g. 
NeurIPS ([#1](https://nips.cc/Conferences/2019/Videos), 
         [#2](https://slideslive.com/neurips/)),
ICLR ([#1](https://iclr.cc/Conferences/2019/Videos),
     [#2](https://slideslive.com/icml/)),
and ICML ([#1](https://icml.cc/Conferences/2019/Videos), 
         [#2](https://slideslive.com/iclr)),
it is very likely that a recording exists of the paper author's presentation.
These recordings can be used as an alternative to the paper lead presenting an
overview of the paper.

Thanks to generous funding from the 
[University of Exeter's Computer Science department](http://emps.exeter.ac.uk/computer-science/), 
we will be offering refreshments 
in the form of tea and coffee along with **cookies**
(once we're back to real-life meetings).

### Upcoming Sessions
<table>
    <tbody>
    <tr>
        <th nowrap width="1%">When and Where</th><th>Session Details</th>
    </tr>
        
    {% for meeting in site.meetings %}
        {% if meeting.status == "upcoming" %}
        <tr>
            <td nowrap><b>Date</b>: {{meeting.date | date_to_long_string}} <br/>
                       <b>Time</b>: {{meeting.time}} <br/>
                       <b>Location</b>: {{meeting.location}} <br/>
                       <b>Presenter</b>: {{meeting.presenter}}
            </td>
            <td>{{meeting.content | remove: '<p>' | remove: '</p>'}}</td>
        </tr>
        {% endif %}
    {% endfor %}

    </tbody>
</table>

### Previous Sessions

<table>
    <tbody>
    <tr>
        <th nowrap width="1%">When and Where</th><th>Session Details</th>
    </tr>
        
    {% for meeting in site.meetings %}
        {% if meeting.status == "happened" %}
        <tr>
            <td nowrap><b>Date</b>: {{meeting.date | date_to_long_string}} <br/>
                       <b>Time</b>: {{meeting.time}} <br/>
                       <b>Location</b>: {{meeting.location}} <br/>
                       <b>Presenter</b>: {{meeting.presenter}}
            </td>
            <td>{{meeting.content | remove: '<p>' | remove: '</p>'}}</td>
        </tr>
        {% endif %}
    {% endfor %}

    </tbody>
</table>
