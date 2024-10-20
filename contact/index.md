---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Goran Micevic, MD, PhD
Department of Dermatology
Yale School of Medicine
333 Cedar Streer LCI 501
New Haven, CT 06520
If you are interested in a Postdoctoral, graduate or post-bacc position, please provide the following:
•	a cover letter presenting your own scientific interests
•	curriculum vitae
Please send your inquiry to Dr. Goran Micevic. More details at: https://miceviclab.github.io/postdoc-positions/
If you are interested in being part of the Pathology Graduate Program, please contact graduate.admissions@yale.edu, or visit the Yale Pathology website. 


{%
  include button.html
  type="email"
  text="goran.micevic@yale.edu"
  link="goran.micevic@yale.edu"
%}


{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
