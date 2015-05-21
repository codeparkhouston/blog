This past Saturday, we attended the [City of Houston Hackathon](http://houstonhackathon2015.challengepost.com/submissions) and took on the challenge of building an [interactive way to view restaurant inspection data](http://challengepost.com/software/htx-food-inspection-map).
<!-- more -->

### Highlights
The hackathon was a great learning experience and a lot of fun for our class as we learned about databases, Backbone, and Sass. We got to a quick start with some great ground work laid down by teammate [Ben](https://github.com/bmagnantb) who set up our frontend repo on [github](https://github.com/htx-food-inspection-map).  After getting up to speed on what data we would have from our team's data scientists, [Ian](https://github.com/ianwells) and [Neeraj](https://github.com/neerajt), we sketched up the interface for map and discussed some features.  Then, we got to work.

Getting the development environment set up on different systems took a bit of time, but we got to practice installing Node, using npm, and using git.  After some technical difficulties, we paired students with other team members to implement:

  * The right sliding panel with BackBone, HTML, and Sass
  * Filter and sort fields using Bootstrap
  * Trying out the Leaflet library for mapping
  * Drawing an icon to represent bugs found during inspection in Sketch

### Lessons Learned

Organizing the frontend using the concept of an ["Orchestrator"](https://code.mixpanel.com/2015/04/08/straightening-our-backbone-a-lesson-in-event-driven-ui-development/) was very helpful.  Not only did it help us split up the page into separate views which helped with dividing the work, it made it clear how to get different components to talk to each other.

We struggled with how best to handle the static data.  We wanted to get away with doing as little as possible with our precious hackathon hours.  After some data reshaping and wrangling together a Python script to JSON-ify our data, we got it loaded into a MongoDB.
