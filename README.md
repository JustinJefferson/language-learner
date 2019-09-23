# language-learner

An app that allows language instructors to create study material easily and distribute it over the internet. 
We will focus on actual comprehension through, reading, writing, listening and speaking.

Notes:

- ability to create assessments, along with study materials.
- each assessment would have to be a different type of test (reading writing, listening, speaking)
  - Ability to create a multiple choice question and grade (auto-grading or manual)
- we will need to support the ability for the user to upload and play audio files
  - AWS has tools and services we should consider for managing storage and playback of audio
  - PostGreSQL may also already have more resources out-of-the-box than alternatives such as MySQL.
- many languages will use other scripts not included in standard ASCII
  - investigate what tools are already available to facilitate using Unicode.
- We plan to use Angular and Java (SpringBoot) for the front and middle
- Often, "the best strategy for learning is teaching"
  - pair learning?
  - are there specific technologies or tools to facilitate co-learning for two students?
- We need to support user authentication, so that a user can be designated as the owner of their materials, and determine if/when to publish those materials for access by other specific users, or the general public.
  - JWT seems like a good way to support user authentication, potentially including multiple different levels of access. It will be more efficient to build in JWT from the outset, rather than trying to add it later.
- Interactive design schematic for Angular front-end
  - Meetup with group: Angular Developers - Philadelphia!
