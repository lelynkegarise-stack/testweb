---
layout: default
title: "Welcome to Downsville Ruritan"
hero_heading: "Improving Our Community Through Fellowship"
---

## About Our Club

The Downsville Ruritan Club brings community members together to support local causes, youth programs, and community growth in Washington County, Maryland.

<Image src="image_agent_tag_17799299108104778788" alt="Downsville Maryland community area" caption="Downsville, MD Community Area" />

---

### Upcoming Events & Community Meetings

Our regular meetings take place on the **{{ site.meeting_schedule }}**.

{% for event in site.posts limit:3 %}
  <div class="event-card">
    <h4><a href="{{ event.url }}">{{ event.title }}</a></h4>
    <p><strong>Date:</strong> {{ event.date | date: "%B %d, %Y" }}</p>
    <p>{{ event.excerpt | strip_html | truncatewords: 25 }}</p>
  </div>
{% endfor %}

---

### Community Hall Rentals

Looking for a location for a family reunion, birthday party, or local meeting? 

* **Capacity:** Up to 150 guests
* **Amenities:** Kitchen facilities, tables, chairs, and ample parking
* **Inquiries:** Contact us at **{{ site.phone }}** or email **{{ site.email }}** for availability.
