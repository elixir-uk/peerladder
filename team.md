---
layout: default
title: PeerLadder Team
permalink: /team/
navbar:
  type: dark_menu
---

{% assign co_leads  = site.people | where: "role", "co-lead"  %}
{% assign mentees   = site.people | where: "role", "mentee"   %}
{% assign reviewers = site.people | where: "role", "reviewer" %}

<section class="team-page-header breadcrumb_area_three">
  <div class="container">
    <div class="breadcrumb_content text-center">
      <h1>PeerLadder Team</h1>
      <p>The people behind the ELIXIR-UK PeerLadder initiative.</p>
    </div>
  </div>
</section>

<section class="team-page-body">
  <div class="container">

    <!-- Co-Leads -->
    <div class="team-group" id="co-leads">
      <h2 class="team-group-title">Co-Leads</h2>
      <div class="people-grid people-grid--co-leads row">
        {% for member in co_leads %}
        <div class="col-lg-4 col-md-6">
          {% include person-card.html person=member %}
        </div>
        {% endfor %}
      </div>
    </div>

    <!-- Mentees -->
    {% if mentees.size > 0 %}
    <div class="team-group" id="mentees">
      <h2 class="team-group-title">Mentees</h2>
      <div class="people-grid people-grid--mentees row">
        {% for member in mentees %}
        <div class="col-lg-3 col-md-4 col-sm-6">
          {% include person-card.html person=member %}
        </div>
        {% endfor %}
      </div>
    </div>
    {% endif %}

    <!-- Reviewers -->
    {% if reviewers.size > 0 %}
    <div class="team-group" id="reviewers">
      <h2 class="team-group-title">Reviewers</h2>
      <div class="people-grid people-grid--reviewers row">
        {% for member in reviewers %}
        <div class="col-lg-3 col-md-4 col-sm-6">
          {% include person-card.html person=member %}
        </div>
        {% endfor %}
      </div>
    </div>
    {% endif %}

  </div>
</section>
