# Introduction
There are 8 tasks.
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
  * <a href="https://github.com/{{stu.user}}"><img src="{{stu.image}}" style="width: 50px; height: 50px"></a> @{{stu.user}} ({{stu.name}}) 
    * {{stu.content}}
{% endfor %}
