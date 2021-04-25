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

{% for stu in https://csci3251-2021.github.io/project-team-k/.stu %}
  <h2>
    <a href="{{ stu.https://github.com/chuckjee }}">
      {{ stu.user }} - {{ stu.name }}
    </a>
  </h2>
  <p>{{ stu.content | markdownify }}</p>
{% endfor %}

**Please read `tasks.md` to start your work.**
