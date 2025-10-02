

# My Resources

<div class="tabs">
  <button class="tablink" onclick="openTab('Reading')">Reading List</button>
  <button class="tablink" onclick="openTab('Courses')">Courses</button>
</div>

<div id="Reading" class="tabcontent">
  
<h1>My Reading List</h1>

<h3>Machine Learning & AI</h3>
<ul>
  <li><a href="https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/">Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow</a></li>
  <li><a href="https://www.oreilly.com/library/view/deep-learning-with/9781617294433/">Deep Learning with Python</a></li>
</ul>


<h3>Programming & Python</h3>
<ul>
  <li><a href=href="https://www.oreilly.com/library/view/automate-the-boring/9798341620094/">Automate the Boring Stuff with Python</a></li>
  <li><a href="https://www.oreilly.com/library/view/beyond-the-basic/9781098128203/">Beyond the Basic Stuff with Python</a></li>
  <li><a href="https://www.amazon.co.uk/You-Look-Like-Thing-Love/dp/0316525243">You Look Like a Thing & I Love You</a></li>()
</ul>


<h3>Web Development</h3>
<ul>
  <li><a href="https://leanpub.com/djangoforbeginners">Django for Beginners</a></li>
  <li><a href="https://leanpub.com/djangoforprofessionals">Django for Professionals</a></li>
  <li><a href="https://learndjango.com/courses/django-for-apis/">Django for APIs</a></li>
  <li><a href="https://www.oreilly.com/library/view/django-in-action/9781633438163/">Django in Action</a></li>
</ul>

<h3>Data, SQL & Databases</h3>
<ul>
  <li><a href="https://www.oreilly.com/library/view/learning-sql-3rd/9781492057604/">Learning SQL</a></li>
  <li><a href="https://www.oreilly.com/library/view/mysql-crash-course/9781098156824/">MySQL Crash Course</a></li>
  <li><a href="https://www.oreilly.com/library/view/practical-sql-2nd/9781098129866/">Practical SQL</a></li>
  <li><a href="https://www.oreilly.com/library/view/beginning-database-design/9781394155729/">Beginning Database Design Solutions</li>
</ul>

<h3>Web Scraping & Data Engineering</h3>
<ul>
  <li><a href="https://www.oreilly.com/library/view/hands-on-web-scraping/9781789533392/">Hands-On Web Scraping with Python</a></li>
  <li><a href="https://www.oreilly.com/library/view/apache-hadoop-3/9781788999830/">Apache Hadoop 3 Quickstart Guide</a></li>
</ul>
   
<h3>Data Visualization</h3>
<ul>
  <li><a href="https://www.oreilly.com/library/view/learning-tableau-2022/9781801072328/">Learning Tableau 2022</a></li>
  <li><a href="https://www.oreilly.com/library/view/tableau-desktop-cookbook/9781492090106/">Tableau Desktop Cookbook</a></li>
  <li><a href="https://www.oreilly.com/library/view/practical-tableau/9781491977309/">Practical Tableau</a></li>
</ul>

<h3>DevOps, Cloud, and Containers</h3>
<ul>
  <li><a href="https://www.oreilly.com/library/view/accelerate/9781457191435/">Accelerate: The Science of Lean Software and DevOps</a></li>
  <li><a href="https://www.oreilly.com/library/view/the-devops-handbook/9781098182281">The DevOps Handbook</a></li>
  <li><a href="https://www.oreilly.com/library/view/docker-deep-dive/9781835884386/">Docker Deep Dive</a></li>
  <li><a href="https://www.oreilly.com/library/view/the-kubernetes-book/9781835880302/">The Kubernetes Book</a></li>
  <li><a href="https://www.oreilly.com/library/view/quick-start-kubernetes/9781836208655/">QuickStart Kubernetes</a></li>
  <li><a href="https://www.oreilly.com/library/view/keras-to-kubernetes/9781119564836/">Keras to Kubernetes</a></li>
  <li><a href="https://www.oreilly.com/library/view/introducing-mlops/9781492083283/"></a>Introducing MLOps: How to Scale Machine Learning in the Enterprise</li>
</ul>

<h3>Git & GitHub</h3>
<ul>
  <li><a href="https://www.amazon.com/Git-Humans-David-Demaree-ebook/dp/B0CW2YHHMY">Git for Humans</a></li>
  <li><a href="https://www.oreilly.com/library/view/github-for-dummies/9781394159161/">GitHub For Dummies</a></li>
</ul>


<h3>Other Links</h3>
<ul>
    <li><a href="https://github.com/{{ site.github_username }}">GitHub</a></li>
    <li><a href="https://www.linkedin.com/in/ruairi-o-donohoe-4a74632a5/">LinkedIn</a></li>
</ul>
</div>

<div id="Courses" class="tabcontent" style="display:none">
- Course 1
- Course 2
- Course 3
</div>

<script>
function openTab(tabName) {
  var i, x;
  x = document.getElementsByClassName("tabcontent");
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none";
  }
  document.getElementById(tabName).style.display = "block";
}
</script>
