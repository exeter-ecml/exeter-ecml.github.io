---
layout: page
title:
---

**Note: The ECML reading group is currently on hiatus. This site is maintained as an archive.**

The ECML reading group was a fortnightly meeting where a discussion took place of
an agreed paper in the area of evolutionary computation and/or machine learning.
The group also held tutorial sessions on topics of interest to the community.
It ran from 2020 to 2023 at the University of Exeter.

At each reading group the paper lead would briefly give an overview of the paper,
either verbally or with slides, and then lead a discussion of each
section of the paper. If a paper was from one of the big machine
learning conferences, e.g.
NeurIPS ([#1](https://nips.cc/Conferences/2019/Videos),
         [#2](https://slideslive.com/neurips/)),
ICLR ([#1](https://iclr.cc/Conferences/2019/Videos),
     [#2](https://slideslive.com/iclr/)),
and ICML ([#1](https://icml.cc/Conferences/2019/Videos),
         [#2](https://slideslive.com/icml)),
recordings of the paper author's presentations were often used as an
alternative to the paper lead presenting an overview.

### Previous Sessions
<table>
    <tbody>
    <tr>
        <th nowrap width="1%">When and Where</th><th>Session Details</th>
    </tr>

    {% for meeting in site.meetings reversed %}
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
