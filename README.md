### Education
#### Indiana University, Bloomington, IN, United States					                                                                                                                      August 2022 – May 2024
Master of Science in Data Science									   	                                                                                                                              CGPA: 3.95/4.0
Coursework:
    - Applied Machine Learning
    - Applied Database Technologies
    - Statistics
    - Data Visualization
    - Big Data Technologies
    - Natural Language Processing
    - Music Data Mining
    - Social Media Informatics

#### University of Mumbai, Mumbai, India					           	                 	                                                                                                    July 2014 – May 2018
Bachelor of Engineering in Information Technology					 	                  	                                                                                                          CGPA: 8.58/10 
Coursework:
    - Object Oriented Programming
    - Applied Database Technologies
    - Statistics
    - Data Visualization
    - Big Data Technologies
    - Natural Language Processing
    - Music Data Mining
    - Social Media Informatics

### Work Experience

Research Scientist
- xyz
- 
Apisero
-
-

Accenture
- xyz
- 

### Projects
---
layout: base
---
<ul class="timeline timeline-split">
    {% for period in site.periods %}
      {% if period.name %}
        <li class="timeline-item period">
          <div class="timeline-info"></div>
          <div class="timeline-marker"></div>
          <div class="timeline-content">
            <h2 class="timeline-title">{{ period.name }}</h2>
          </div>
        </li>
      {% endif %}
      {% for event_hash in period.events %}
        {% for event in event_hash %}
        <li class="timeline-item">
          <div class="timeline-info">
            <span>{{ event[0] }}</span>
          </div>
          <div class="timeline-marker"></div>
          <div class="timeline-content">
            <h3 class="timeline-title">{{ event[1] }}</h3>
          </div>
        </li>
        {% endfor %}
      {% endfor %}
    {% endfor %}

    {% if site.show_today %}
      <li class="timeline-item inactive">
        <div class="timeline-info">
          <span>Today</span>
        </div>
        <div class="timeline-marker"></div>
        <div class="timeline-content">
          <h3 class="timeline-title">&nbsp;</h3>
        </div>
      </li>
    {% endif %}
  </ul>
