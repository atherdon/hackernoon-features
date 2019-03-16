#### an import story

an import story from other websites function (requested by one of our writers!)

> an import story from other websites function (requested by one of our writers!)

Importing stories is tricky, but I’d love to support Google Drive integration at some point, and Word documents (although we might have to play fast and loose there – that file format is capital-I-Insane from what I’ve read). I want the editor to be a killer feature, but at the same time, I understand writers have their preferred tools. Personally, I love writing in Word.

----


#### stats

Stats like Medium has - but maybe with more statistic. Or figure out how make people read more


Thanks Austin,
Regarding additional stats, I was thinking of readers’ locations and where readers who did not read the entire post stopped reading for example.


As for stats, there’s definitely a lot more we can do than we provide today. What sort of stats would you like to see @arthur.tkachenko @patriciadehemricourt? Any and all ideas are appreciated!

Trello: https://trello.com/c/8gX3LhpV/1-post-metrics


#### Events

well done search and filterable with alerts global calendar of conferences and events with confirmed attendees. this is pretty useful for me.

>> well done search and filterable with alerts global calendar of conferences and events with confirmed attendees. this is pretty useful for me.

Yes! We’re thinking of building something like a marketplace on events.hackernoon.com where conferences/events could give contributors free press entry and contributors can sign up to go and write a story. Recently one of our contributors David Choi went to Davos and covered the Blockchain Economic Forum on behalf of Hacker Noon. We get media partnership invites from all sorts of tech conferences on a daily basis. If we do it right, we can get to a point where every single tech event would have a HN rep/attendee, and we will be able to build out a filter-able calendar.


#### Newsletter digest

Some sort of newsletter digest. Check TechMemo or Sip from ProductHunt.

+1 upvote on the digest

Data viz of the day or week

We’ve been talking about newsletters as well. @arthur.tkachenko what sort of content would you like to see in the newsletter? Top posts? Or more of a hand-curated collection of interesting stories? Just curious what you have in mind here.

Trello: https://trello.com/c/52rilkLz/5-newsletter-digest


#### Editorial calendar

Editorial calendar with ability to see the queue of pending articles. Like where is my post in a line?

Yep #1 is a MUST have…
I submitted an article before the weekend and what’s usually a 24hr turn around is now 3 days in - so would be great to have some visibility in that backlog.


All great ideas! I’ll talk over all of these with @Dane when he gets back, but I wanted to address a few of these ideas in particular below:
We definitely want to give you more feedback on the editorial process, and we will have a “Recent Activity” feed in 2.0 that will tell you when an editor has opened, edited, or approved your story. Of course, that doesn’t tell you when an editor will actually open it – it will be difficult, but I think it’s doable to give you an estimate. It won’t be there from day 1, but I’ll talk to Dane about it as soon as he gets back.


#### Title/headline creator

Would love to see story title/headline creator. This might be something similar to https://coschedule.com/headline-analyzer 1 but very specific to hackernoon.
Based on the topic and some data science magic, it would be a killer feature to see hackernoon help writers craft an inviting title/headline



(Arthur note): I think at this doc we have some sort of help. I mean list of categories/tags are really helpful.

> When in doubt, refer to the tags you’ll find attached the top stories featured on our homepage... (https://docs.google.com/document/d/1XfgCHnRe1fiSuBS6iHzG6_A8GTizP6JTraypXjT18pA/edit)



this is a really cool idea. co-schedule is an OK tool. have to give a ton of information to use, including answering this question where this is not an option to “get a better headline”
[img]
but I do like how it previews headline in different formats, does a light breakdown of word types and sentence structure, as well as, providing a baseline against average headline length.
ultimately, a tool like this should suggest better headlines. machine learning of all published stories would help. and so would identification of SEO opportunities based on the content in the draft and the search volume of long tail terms. additionally, the use of the tool could also indicate that a human editor should write new headline suggestions for you.

unsure what/when the solution looks like, but improving headlines is important.



Sounds like a job for… :superhero: Python!

I love the idea of analyzing stories like this. We could do simple entity extraction (i.e. keyword-finding) on the story content, and use Tensorflow or something similar to learn how titles are related to content, suggesting titles with some simple machine learning. This is harder than I’m making it sound – the titles wouldn’t be very good without a lot of training on existing content, but if nothing else it would be an interesting project for Hacker Noon Labs. :wink:




That does sound like a really cool project. I created a project like this in the past, that took tons of data from online articles and extracted topics from the articles using the NLTK packages and some topic modeling. Of course, mine was a little sloppy and not super reliable. But that would be something fun to tackle. I wonder if you could even tie it into a Google Search API thing, so the title generator could return several possible titles, with a summary of how each will rank on Search results, or something like that.


Trello link: https://trello.com/c/f1mLPmoq/11-title-headline-creator


#### Small F

1) If you will have Voice-To-Text ability -> it will be awesome. BEcause I'm lazy to type it

2) What do you think about Po.et thing? Can it be helpful for HN?

3) I think HN need to use more help and more tools. Like code can be shared between people, editorial work too. I think form + email should be updated with form+ slack+bots, etc…

4) New feature: I want to have an advanced bookmarks. Where i can have tags or something. Because my bookmarks at Medium looks bad
Trello: https://trello.com/c/Z0rdw3Zg/4-bookmarks-with-tags

5) You can collaborate with ProductHunt Makers. They have a separated place, related to goal on blogging. And I think Its a dream for a lot of people to being published on HN. https://www.producthunt.com/makers/34-writers-bloggers


6) I propose to create a trello board(https://trello.com/b/RGLhzDc2/hacker-noon-feature-requests) with features, or github page with upvote/downvote or at least Google Spreedsheat with ability to add +1.And I think it’s time to split goals in 2 sections “Going to Mars”, “Sub-orbital flights”. Because I think with big amount of tools, that we have right now on market - we can easily help to editors solve a real time problem.Like spend 1 day and launch something that will be useful right now. But for sure, we need big goals too. https://canny.io/?ref=producthunt

7) Any thought on using the ActivityPub 3 protocol?
I’m not an expert, but it would be great if content edited on HackerNoon 2.0 were part of a federation.


#### API

Some sort of an API and maybe React component, that will help to fetch all author articles and display a “List of Cards” with links to articles. (I find it’s hard to grab all my stuff from Medium and place links at my Gatsby/Docusaurus website)

We’ve actually been talking about an API, and that’s a perfect use case, Arthur! It won’t be there from day 1, but an API is a part of our long-term strategy. Giving authors access to their posts alone would be incredibly valuable – thanks for that idea!

API -> use a GraphQL please. And start with some developed before solution. It will save some time.


(Arthur note): I start to google "graphql cms open source" and have bunch of results.


#### Social Media tools
2 Maybe also a wy to leverage the community’s social media network to expand articles reach. Something along the lines of triberr.com
3
An option to edit the default text displayed when sharing on social media


I’ll personally make sure point #3 is addressed in 2.0.  As for point #2, triberr looks interesting, and we’re always looking for ways to amplify the publish button. I’ll bring this up with the team, for sure.

Trello link: https://trello.com/c/Gb5NYZv8/2-customize-social-media-sharing-text


#### GitHub integration

Let’s integrate Github with HN, so new article will be at \*.md format and queued articles will have ability to receive comments/edits i agree, it’s so nerd-like


>Let’s integrate Github with HN, so new article will be at \*.md format and queued articles will have ability to receive comments/edits i agree, it’s so nerd-like

Awesome idea!We’ve talked about doing this and I think there are a lot of interesting Github integration options. In addition to pulling content from Github, I’d also love to push content to repos. This could be great for teams that want to cobble together a “best practices” doc in their repo composed of snippets from a variety of Hacker Noon and other sources.

t will save time, and not only developers use Github, i know that scientists(astrophysicists) use it as collaboration tool. And markdown is an easy format and have a new wave of attention recently.

next point : i think it’ll give cool marketing value for HN
next point :
- roles
- kanban
- labels
from GitHub default coding flow




I’m definitely interested in Github integration as well, not only for markdown support, but for some wild future collaborative writing project that only exists in my head at the moment (it sounds like @dane is on the same wavelength, though).  It would be super interesting to see the editing process play out on Github (PRs == suggested changes?). There’s just so much potential there, and so much of our audience is already on Github, it just seems like an overall win for us.

Trello:


#### Peer-review

I think peer-review possibility between authors in Hackernoon will be a good way to promote the community-based tech blog, to reduce the workload of the Hackernoon internal team and prepare a base step to use the blockchain concept in Hackernoon. At first, we can point some accredited authors and let them co-review the post. A post can be published after, for example, 3 approves. This is rather a conceptual and abstract idea and I hope I can answer some questions if you have.


DaneTeam jarvisluong: I think peer-review possibility between authors in Hackernoon will be a good way to promote the community-based tech blog I really like this idea but I’m not sure I’d want to make publishing depend on getting 3 peer reviews. One of the bigger benefits of HN is the ability to get an opinion piece out there without jumping through a ton of hoops. Do you think it would be viable to make peer reviews a post-publishing option? So say you put out a piece and other writers would have the option to do a peer review. If the piece hits some threshold of say 3-5 reviews then it gets added to a Peer Reviewed section of the homepage. This might not be a good approach but I’m trying to find a way to maintain a simple editorial process while getting the benefit from peer reviews.


I like this a lot too. Makes a lot of sense for deeper analysis pieces. I also am excited about possibility of flow where requests for edits on smaller pieces become a co-authored longer form piece.


I forgot about peer reviews! That’s one of the most interesting parts! Peer reviews, allowing 3-4 fellow writers to approve a post, is super interesting to me, particularly given my past crowdsourcing experience (and yours, @dane ). I imagine some writers will be “better” at judging which posts are “high-quality” – I’m using scare quotes because these are highly subjective, nebulous terms. Maybe we need some relative scale of quality. I’m starting to spitball here, just thinking aloud, but I’ll definitely put some more thought into this. I think it’ll be necessary in some form, at some point, to scale the editorial process (but I could be wrong).



I love the idea of having almost like a “code review” for articles by fellow writers who are approved. Maybe you can get karma like reddit or something for reviewing.


community editors will be rewarded with features and curation power. as your contributions and authority on a subject matter grows, your ability to dictate the curation on said subject matter should follow.


Trello: https://trello.com/c/MLfEWXi6/6-collective-editing
Trello: https://trello.com/c/AnhzrufI/7-collective-story-approval

#### email follow feature

The e-mail follow feature that @David mentioned sounds interesting. Would it allow integrations with things like MailChimp? That would certainly be a useful feature.

(Arthur note) I didn't find where David talks about it
https://community.hackernoon.com/t/what-are-the-killer-features-youd-like-to-see-in-hacker-noon-2-0/68/28?u=arthur.tkachenko


#### Collaborate website form that submit PR to github repo

@austin I’m procrastinating right now, and find some discussion at Github. People talking about having a form, that automatically create a PR via github bot. I was thinking that it can be next generation of our current “collaborate” website. And I think it might save some time to editors… tell me what do you think and should I dig more data for you, please



I don’t quite follow – do you mean that you’d like to see Github issues, for example, created every time a feature request is made? If so, that would be awesome :slight_smile: and if not, please, tell me where I’m getting it wrong. Thanks in advance!


User Story:

writer go to https://contribute.hackernoon.com 1
fill form
after submit, some github repo receive a PR, that contains data from that form
editor can see it as open PR, and close when new post will be published on a main site



That could be a really cool hack! It neatly steps around the need for an editorial calendar or similar constructs. However, it would take time to build this integration, time we could spend building out this functionality in 2.0 itself. We’ll have to weigh our options, but all else being equal, I’d rather give you that information on when your post will be published on the site itself, not a third-party site. In any case, you got me thinking about editorial calendars and feedback for contributors, which is great! Thanks @arthur.tkachenko!


https://github.com/facebook/Docusaurus/pull/1160
https://github.com/ymschaap/website/pull/11
https://build.amsterdam/your-company/babel
