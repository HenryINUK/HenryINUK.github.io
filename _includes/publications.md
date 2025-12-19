## Publications

<h4 style="margin:0 10px 0;">Book Chapters</h4>

<ul style="margin:0 0 20px;">
  <li>
    <autocolor><strong>Convolutional Neural Network Accelerators: From Basic Design Principles to Advanced Security Applications</strong></autocolor>
    <br>
    Editor: Basel Halak | <em>Contributing Author (3 Chapters): <strong>Haoyu Wang</strong></em>
    <br>
    Springer, 2025. ISBN: 978-3-032-08513-9
    <a href="https://www.amazon.co.uk/dp/3032085136">[Amazon]</a>
  </li>
</ul>

<h4 style="margin:0 10px 0;">Selected Publications</h4>

<ul style="margin:0 0 5px;">
  {% for publication in site.data.publications.main %}
  <li>
    <autocolor>{{ publication.title }}</autocolor>
    <br>
    <em>{{ publication.authors }}</em>
    <br>
    {{ publication.conference }}
    {% if publication.notes %}
    <span style="color:#9a9a9a;"> ({{ publication.notes }})</span>
    {% endif %}
    {% if publication.pdf %}
    <a href="{{ publication.pdf }}">[PDF]</a>
    {% endif %}
    {% if publication.code %}
    <a href="{{ publication.code }}">[Code]</a>
    {% endif %}
  </li>
  {% endfor %}
</ul>
