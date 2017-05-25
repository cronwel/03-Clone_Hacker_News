# 03-Clone_Hacker_News

Start Date-5/23/17 End Date-5/25/17

**Purpose:** To practice Ruby on Rails skills and maintain knowledge.

**Methods:** This was an on-line tutorial available through Youtube.

**Ref:** Child, M. "How to buildd a Reddit or Hacker News Style Web App in Rails 4".https://www.youtube.com/watch?v=7-1HCWbu7iU. Sep 7, 2014.

**Results:** Excellent tutorial overall. The main gems used are as follows:
..* Devise-user registration
..* Bootstrap-sass- CSS formatting
..* Act_as_votable- voting capabilities for the main model
..* Simple_form- creating comments section for the main model

I made it through the tutorial over a few days and much longer than the 1:08 minute runtime. I did gain familiarity with how to use different types of gems, not all have the same setup for utilization.

**Blocks:** Quite a few, I had issues with some of the programming because the gems and rails 5 required new syntax to accomplish the same goals. I had to figure it out and surprisingly, I did. Examples are the use of before_action instead of before filter. I was able to accomplish the same thing with different wording.
Another example, there was the use of the form_for method which was removed for Rails 5. I installed an additional gem called record_tag_helper to be able to complete the project.
Another issue occured with Bootstrap and how it worked. There a point in which I had to get chevrons for the voting component to work. I tried using older versions, redownloading, reinstalling, and downgrading Bootstrap to no affect. I spent a lot of time on this. At a loss, I updated Bootstrap through npm and that seemed to work. How? I am not sure yet, but in many years from now I will understand....I hope. I did have a few points in which my typing was the culprit, but not as much as I would have thought. The blocks came primarily from using an older version of Rails within the tutorial and using the msot current version.

**Lessons:** Figuring out each block was helpful. Also, I learned a little more about git and how merging works. I had initialized the repo outside of the main folders. In order to push to github, I had to be in the same folder in order for github to register the changes. On github, it shows up as 4 commits, when in fact, I had made many more commits but within the main folders. I learned to use the branching and merging features of git for each main section.  Lesson is to ensure init and all other commands come from the same folder section.
