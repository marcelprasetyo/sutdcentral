



the idea is, a github repo (github so that open source and clean and PR and issue available) with different markdown pages ...

. for every topic there is : writeup page; list page (resources)

. there is complementary topic: Technological World ; Design World (in the same vein as Natural world, digital world, physical world; points to the lack of such introductions; aligned with prof pey's vision of Digital Literacy)

. for every important SUTD module (a convenient topical marker) .. we have a writeup and list page (resource) . This is how I've chosen to open source such resources useful to the SUTD community.

. a web viewer allows you to mark your own progress in reading these lists to complete yourself the course. These are like wiki entries .. but lists. and a lot easier to form PR .. etc. in a sense this is the SUTD wiki that's useful for SUTD community.

> /awesome-technology list will redirect to this ... /sutd-collections list.

. do a similar GitHub-based list of projects done by SUTD people. refers to those on opensutd, and refers to whatever elsewhere . . . People, put your project here, not affiliated to anything or anyone, this will be public for SUTD. That's if you just want to be included in the canon of SUTD, a sort of Hall of Fame. Pull request.

. a hall of fame for SUTD academic projects (if you didn't reveal the code etc., the IP is not violated. basic descriptions and even poster. Put them here) .. for 3.007; for 30.007, entre, capstone 1d 2d etc. if the design files are not shared, no IP is shared, nothing is violated.

....   IF we get tired of all these lame formats, we can still keep it, and just need to use a simple character formatting system (like markdown) which when read with our format, translates to nice UI. This website just needs to GET / import the raw formatted text from GitHub, and the github never has to change. This is (pseudo) database but with nice version control.

- 

. SPECIAL!! We can try to launch SUTD discourse .. using GitHub. create a pull request (can you automate, so that, additions are always automatically accepted while deletions not?)

can you query the directory list of the repo dir? then with links to these repos?

https://stackoverflow.com/questions/25022016/get-all-file-names-from-a-github-repo-through-the-github-api

- IF you GET the html of the GitHub repo current dir, form the node tree and find the node with class 'file-wrap', you can extract the list of directories. table js-navigation-container, 2nd tbody, 2nd tr onwards foreach tr, if td icon is folder is dir (see aria label), if td icon is file is file, td 'content' is content with a span with an a href (we can then fetch this href .. fetch the raw)
  - https://stackoverflow.com/questions/4604663/download-single-files-from-github [raw.github.com/:user/:repository/:branch/:filename](http://raw.github.com/:user/:repository/:branch/:filename)
- Automatic PR auto-merge? https://github.com/palantir/bulldozer with https://github.com/palantir/policy-bot
- TESTED: changing innerHTML replaced with html code, will actually change html code

so the 'discourse' can just be read from the outside by querying GitHub and we have a special API that when you post a reply, it will do a PR to github instead ... if automatically approved, add!

. every thread is a dir, and each text file (markdown) consists of a single page of the entire convo, terminates and opens a new page if reach a certain character limit.

What is Technology?  == page 1: technology commentary, topics and writeups

Why do we use technology without really understanding what it is?

- philosophy of technology
- what is technology, simply? means to an end. or a means to itself. science & technology.
- paolo's question of technology - what is the essence of technology
- paolo's consciousness and AI - can AI be conscious? dreyfus - no. human intelligence is not a probabilistic calculating machine, and so computers can't achieve human intelligence. It is being, consciousness. the hard problem of consciousness
- the technological society - jacques ellul
- ethics of technology
- social impacts of technology - see Nina's (Nilanjan) research
  - AI and social life?
  - VR and social life?
  - what happens when human jobs are displaced by robots?
  - the cost of technology: communalism and individualism - durkheim's organic and mechanical solidarity? or psychologically, become more individualistic, become less social
- technological innovations - design; china; sci-fi and innovations (Nazry)
- important questions:
  - are we being overrun by technological progress?
  - is technology driving its own direction, or are we still having control over it?
  - are we slave to technology?

Why technology?

- competitiveness
- technology transforming the whole of society - disruption. industry 4.0 .. quantum revolution.
- smart nation mandate & skillsfuture
- 

Who technology?

authorities (videos, blogs, publications(futurism,inverse,mit tech review etc), journals, organizations (su), companies)

rss

How technology? see page 2.

Where technology? everywhere.