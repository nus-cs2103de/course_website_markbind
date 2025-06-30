{% from "common/admin.njk" import show_admin_page with context %}

{% call show_admin_page("appendixG-CS2103R") %}
<div id="main">

**CS2103R is an 'R course'** (R stands for Research) that students can take to earn an extra 1 Unit of credit (and can also be used to fulfill requirements of the Turing program). The 1MC is graded (not S/U).

**It is meant for strong programmers who would like to push themselves beyond the achievement bars set by CS2103DE**, keeping in mind that the regular 4-Units course deliberately does not give extra credit for exceeding expectations (reason: to keep the workload manageable for the majority of students). CS2103R is an opportunity to work around that limitation, and get extra 1MC by doing some extra work.

****Deliverables****:
* **Option A**: Propose and implement an enhancement to the [AB3 base project](https://se-education.org/addressbook-level3/).
  * The enhancement can be a change to the current design (the _internal_ design, not the external features), an alternative design, using alternative tools (including different testing/documentation/CI tools), improvements to AB3 learning resources, etc. that can showcase the depth of your SE skills.<br>
  * Simply adding more external features to AB3 is not suitable for this purpose as anyone in the class can do that (as that is what you normally do in the tP anyway) -- here, ==we are looking for things that can make you stand out from the majority of the class in terms of SE skills==. In particular, we want to see your understanding of pros and cons of the current AB3, and to see you explore alternatives to current AB3 choices.
  * The enhancement should be accompanied by a report explaining its rationale, implementation, pros and cons.
  * The proposed enhancement is unlikely (although not impossible) to be incorporated to the actual AB3, as this is more of an opportunity to showcase your SE skills rather than a way to perfect AB3 (using a 'perfect' codebase for the tP may not fit the learning goals of this course after all).
* **Option B**: A deliverable that would result in a non-trivial quality-of-life improvement to CS2103DE students and/or instructors even if it doesn't directly involve AB3, provided it also showcases your SE skills beyond what is normally covered in the course. Examples:
  * Some kind of automation that reduces the manual work for students or instructors.
  * Improved versions of instructional materials e.g., JavaFX tutorial, AB3 tutorials
* **Option C**: An exploration of how AI tools (e.g., ChatGPT, GitHub Copilot, Codex, etc.) can be used in the iP and the tP by students and instructors. For example, how students can use a tool to save time in doing the project. Even better if you also reflect on how the use of the tool affects various aspects (learning outcomes, fairness of grading, plagiarism concerns etc.) of the course.

****Workload**** is expected to be about 50% of your individual tP effort.

****Timeline****:
1. **[Weeks 9-11]**: Submit a brief proposal (~ 1 page):<br>
   Contents: your name, student number, an outline of the proposed change, expected pros/cons.<br>
   Submission: Upload a file `CS2103R-YOUR_NAME.pdf` to the corresponding Canvas assignment.
1. **[Reading week]**: You will be notified if you are accepted for CS2103R. As this is the first time we are offering CS2103R in this manner, the number of slots is likely to be small in this round.
1. **[Within 4 weeks of the end of the exam period]**: submit the implementation and the report. The grade will be given to you soon after.
1. **[Week 1 of the following semester]**: Register for the course, to receive the extra 1 Unit in the following semester. More info about R courses is given [here](https://wiki.nus.edu.sg/pages/viewpage.action?spaceKey=SUW&title=R+Modules) (requires login).

****Grading****:

The grade given is typically the same as the grade you earned for CS2103DE, but can be different if your CS2103R work is substantially better/worse than your CS2103DE performance.

</div>

{% endcall %}
