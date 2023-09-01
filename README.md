# Midwater.com

### Blog Postings

<ul>
  {% for post in site.posts %}
    <li>
      {{ post.date | date_to_long_string  }}<br>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>


<!-- Default Statcounter code for my blog
https://www.midwater.com/ -->
<script type="text/javascript">
var sc_project=12917319; 
var sc_invisible=1; 
var sc_security="91777d2e"; 
</script>
<script type="text/javascript"
src="https://www.statcounter.com/counter/counter.js"
async></script>
<noscript><div class="statcounter"><a title="Web Analytics"
href="https://statcounter.com/" target="_blank"><img
class="statcounter"
src="https://c.statcounter.com/12917319/0/91777d2e/1/"
alt="Web Analytics"
referrerPolicy="no-referrer-when-downgrade"></a></div></noscript>
<!-- End of Statcounter Code -->
