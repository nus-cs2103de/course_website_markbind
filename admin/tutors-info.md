{% from "_course-" + course + "/studentData-fragment.md" import tutors with context %}

## Staff

<div id="Theivendiram" class="container">
  <div class="row bt-2">
    <div class="col-3">

<img src="https://cde.nus.edu.sg/ece/wp-content/uploads/sites/3/2025/02/Dr-Theivendiram-Pranavan.jpg" width="150" class="mt-1 rounded"/>
    </div>
    <div class="col">

### Theivendiram **PRANAVAN**

**Course Coordinator**<br>
%%:fas-envelope:%% `pranat`[at]`nus.edu.sg`<br>
%%:fas-home:%% https://cde.nus.edu.sg/ece/staff/theivendiram-pranavan/ | %%:fab-github:%% [@Pranavan135](https://github.com/Pranavan135)
    </div>
  </div>
</div>

-----------------------------

<div id="Zikun" class="container">
  <div class="row bt-2">
    <div class="col-3">

<img src="https://cde.nus.edu.sg/ece/wp-content/uploads/sites/3/2025/02/Mr-Zhu-Zikun.jpg" width="150" class="mt-1 rounded"/>
    </div>
    <div class="col">

### Zikun **ZHU**

**Head TA**<br>
%%:fas-envelope:%% `zikun`[at]`nus.edu.sg`<br>
%%:fas-home:%% https://cde.nus.edu.sg/ece/staff/zhu-zikun | %%:fab-github:%% [@zikunz](https://github.com/zikunz)
    </div>
  </div>
</div>

## Tutors
{% for t in tutors %}
<div id="{{ t.nick | replace(" ", "-") }}" class="container">
  <div class="row bt-2">
    <div class="col-3">

<img src="{{ url_course_gihub_io }}/tutor-photos/{{ t.github | lower }}.png" width="150" onerror="this.src='images/placeholder-large.png';" class="mt-1 rounded">
    </div>
    <div class="col">

### {{loop.index}}. {{ t.nick }}

**{{ t.name }}**<br>
%%:fas-envelope:%% `{{ t.nusnet }}[at]u.nus.edu`<br>
%%:fab-github:%% [@{{ t.github }}](https://github.com/{{ t.github }})
    </div>
  </div>
</div>

-----------------------------------------
{% endfor %}
