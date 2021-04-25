# This team hasn't started yet...
# Introduction
There are 8 tasks
-  Task 1: Starting issues
-  Task 2: Project board
-  Task 3: Set up readme.md
-  Task 4: Show your team to the Internet
-  Task 5: Keep checking...
-  Task 6: Write C code
-  Task 7: Get a status badge
-  Task 8: Promote your repo
# Code

# Contributors

{% for stu in site.stu %}
  <h2>{{ stu.image }}</h2>
  <h2>
    <a href="{{ stu.url }}">
      {{ stu.user }} - {{ stu.name }}
    </a>
  </h2>
  <p>{{ stu.content | markdownify }}</p>
{% endfor %}

**Please read `tasks.md` to start your work.**
