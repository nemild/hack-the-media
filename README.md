# Hacking Engineers and Engineering Media
### Background
There are many ways to “hack” software engineers by influencing media sources and fellow community members.

This document collects examples of intentional and unintentional hacks of software engineering information sources like Hacker News, Reddit, and tech blogs. The hope is to unbias these sources and provide antibodies to engineers so that they can make better personal and team decisions. (For more background, see this [introductory essay](https://www.nemil.com/musings/hack-an-engineer.html))

While this is targeted at engineers, many of the examples and lessons here apply to anyone who uses media to make decisions or understand what's going on around them.

Contributions are welcome (see our [guidelines](contributing.md)). Follow me on Twitter ([@nemild](https://twitter.com/nemild)) to see more examples of media manipulation.

### General Notes
- Key questions to ask with any media:
  - Why are they writing about this topic and how do they and/or their sources personally benefit? Always need to understand the personal motivation of writer and their sources
  - What is the technical background of the writer? A surprising number of people with little subject matter expertise have strong opinions on highly technical topics
  - Why is the media distributor (social network, news organization) putting this piece of content in front of me? How do they benefit from having me see this content?
  - Do I "need to know" this topic that this content is covering? Would investigating this topic be a productive use of my time, or could I use this time investigating other topics? Not knowing could cause you to have a parochial view of the world, but knowing could lead to you being hacked
- **Reader Interest is King**: When something is heavily covered, it is often due to large reader interest — not due to the importance of the event for you
	- Editors and especially social media algorithms focus on engagement as it maximizes interest and revenue; also, a key reason for confirmation bias, filter bubbles, and technical hype (read about [Cecil the Lion's coverage](https://www.nytimes.com/2015/08/17/business/where-clicks-reign-audience-is-king.html), or [the US coverage of the war in Yemen](https://www.nytimes.com/2016/10/02/world/why-some-wars-like-syrias-get-more-attention-than-others-like-yemens.html) to see what stories sell to an American audience)
	- Rather than thinking of news as mirror of what’s going on in the world, think of it as mirror of what people want to read/hear
	- This is a key reason for so much content about hyped topics like blockchains, AI, or the latest frontend framework (journalists/editors share similarities with entrepreneurs/VCs in that they're - in aggregate - providing coverage of and investing in the stories [the market wants](http://www.paulgraham.com/good.html))
- **Issues with Online Democracy**: Social networks algorithms and voting mechanisms generally treat each of us equally, which diminishes how much voice is given to experts; often an issue on deeply technical topics
- **Empathy Gap**: Media and social media forums often have little empathy for the “other” side, as a given audience prefers to see themselves in the best light — and it is more engaging to see the most easily caricatured/dismissed voices on the other side (see many cryptocurrency communities). Leads you to a deeply flawed view, which you need to consciously correct for by favoring moderate voices on the "other" side. Also suggests that algorithms need to chase more than outrage and engagement (this is a key reason for filter bubbles, see the WSJ's [Red Feed vs Blue Feed](http://graphics.wsj.com/blue-feed-red-feed/))
- **The Power of Narrative**: Humans generally value stories with a certain narrative arc (e.g., good vs evil); Hollywood writers and journalists face similar incentives to cater to this demand
  - For deciding what war to cover in America, value to "[an emotionally engaging frame of clearly identifiable good guys and bad guys](https://www.nytimes.com/2016/10/02/world/why-some-wars-like-syrias-get-more-attention-than-others-like-yemens.html)" that can be pitched to an audience
  - Other example: The rise and fall of blood testing startup Theranos in media coverage
  - This approach is substantially at odds with what a dispassionate observer would choose to cover when making the best personal and societal decisions
- **Attention Economy**: All media sources are in constant competition against each other for the 'attention' of their audience, in the hopes that they can later exploit that attention (examples: branding, propaganda, donation solicitation, ad monetization). Attention is a very scarce commodity (only 24 hours in a day), so the competition for your eyeballs can reach a fever pitch.
- **Fact Distortion Field**: Motivated parties often create a "fact distortion field" in media that justifies their parochial views; they do this by encouraging content that supports their views and paying scientists/engineers to support these views
- **Building antibodies**: Scientists and engineers deeply benefit from getting things “right” in their job; to do the best job, critical for us to identify ways our data sources are influenced — and how to partially unbias them

### Content Playbook
These are common content strategies that technical organizations can use to influence engineers:

- Play into an engineer’s fear of being left behind technologically
  - Argue something is the future and what’s used now is old and anachronistic; especially powerful on junior developers (example: [“modern web development”, MongoDB coining the term “post-transactional future”](https://www.nemil.com/mongo/3.html))
- Write derivative content on hyped topics, as you know there’s a huge market that already wants to read this (examples: blockchains, NoSQL, microservices)
  - Hype is a function of reader interest, but often says little about engineering appropriateness
- Support others who write seemingly tangential content that supports the need for your product (example: containerization companies and microservices)
- Write something controversial that you don’t fully believe
  - Controversial posts engage partisans and evoke vitriol (“engagement”) on the other side in social media, which is the fuel to get something widely discussed

### Sources and Hacks
## Social Media


#### Common Issues Across Social Media Platforms

*Example Hacks*

- **Selective facts (intentional)**: Share partial facts with your followers (i.e., factual coverage that only shows part of the picture - and conveniently ignores facts that don't support a pre-existing view) (Example: Partisan news organizations, competing cryptocurrency projects; for more background, see [my article on selective facts](https://qz.com/1130094/todays-biggest-threat-to-democracy-isnt-fake-news-its-selective-facts/))
- **Fake News**: False content that comport to reader’s views (example: fake news)
- **Glurge**:  False content that aims to "inspire" readers; as they don't advocate for a political position, they tend to avoid as much scrunity as "fake news" (example: [Snopes' page on "glurge"](https://www.snopes.com/fact-check/category/glurge-gallery/))
- **Astroturfing**: Troll armies upvote and positively comment on their posts (Example: [Russia's Internet Research Agency](https://www.nytimes.com/2018/02/18/world/europe/russia-troll-factory.html))

*Other Issues*

- **Selective facts (unintentional)**: Algorithms favor factual coverage that only shows part of the picture, as this maximizes engagement; key issue with relying on likeminded friends and algorithms that focuses primarily on engagement to dictate content
- **Extreme “other”**: Lack of empathy for other side, as more relevant to see the most extreme actions of the other side and ignore the poor actions of the most extreme people on your side (example: [CIA deaths versus limited coverage in US of CIA actions elsewhere](https://www.nytimes.com/2017/05/20/world/asia/china-cia-spies-espionage.html), [one cryptocurrency subreddit’s view on another](https://twitter.com/FEhrsam/status/892429946550837248))
- **Clickbait**: Decision of clickworthiness made on title alone, leading to incentives for clickworthy titles and easily explained content

#### *Reddit and Hacker News*

**How it works**

- Anyone can join and vote in community, with everyone’s vote counted equally
- For new posts, the number of upvotes soon after posting determine placement in the front page ranking
- Comments are similarly upvoted, with early comments generally advantaged over later comments
- Goal is to favor content that is likely to be heavily upvoted *for the community of upvoters*
- (Popular input source in startup communities and for junior engineers)
- For more on Hacker News, see [A List of Hacker News's Undocumented Features and Behaviors](https://github.com/minimaxir/hacker-news-undocumented)


**Example hacks**

- **Upvoting Ring**: Asking your friends and supporters to upvote (common in dev tool companies, training programs, incubators); this can work despite social network countermeasures
- **Allied Commenters**: Get your allies to be the first commenters (which your friends will then upvote and bubbe to the top), subtly shaping the views of everyone who reads the content
- **Confirmatory Content**: Creating content that justifies pre-existing views or financial incentives of subreddit holders; see what popular views are before, and ape them (example: [cryptocurrency subreddits](https://twitter.com/fehrsam/status/892429946550837248) that promote their own currency, and discredit competing currencies)

**Other issues**

- **Tribalism**: Tribal behavior by key influencers can determine how certain topics are received (example: Though HN was quite negative to MongoDB, what would the reaction have been if MongoDB was a Y Combinator company?, [How does one cryptocurrency subreddit approach another](https://twitter.com/FEhrsam/status/892430348285427713)?)
- **No more experts**: No distinction for experts versus others; one layman has the same voting power as the world’s most thoughtful expert (Example: a non-engineer vs. the world’s most thoughtful database expert on MongoDB posts); readers may also not take the time to understand background/expertise of writer
- **Militant Minority**: Upvoting and posting community is likely small compared to readers, providing lots of power to a small group of motivated users; motivated users are often people who personally benefit from post
- **Different Needs**: Ideal tools for one group/use case don’t map to another group/use case, even though both share the same social network (Example: frontend engineer’s database preferences for a hackathon vs. backend engineer’s database preferences for production, [TDD and the needs of consultants](https://news.ycombinator.com/item?id=14664311))

#### *Facebook and Twitter Feeds*

**How it works**

- Algorithms take newly posted content from often likeminded friends/followers and decide what to feature so that user engagement is maximized (click, like, share/retweet)
- Unlike Reddit model, algorithm is focused on maximizing engagement for each individual user, not for a broader, more diverse community


**Other issues**

- **Confirmation Bias**: Extreme degree of confirmation bias
	- We click on content that justifies our individual views without interacting with the full body of research on a topic; newsfeed algorithms see these choices and give us more of the same
	- Gives us an irrational confidence that we know what is “reality”, because all evidence we see justifies a certain view - and the only opposing side that breaks through is the most extreme, outrageous voices that can be easily dismissed

**Potential Antibodies**

- **Wants vs Needs**: Social feed algorithms focus on user "wants", but in engineering, huge value to determining your "needs"

- Realize huge degree of confirmation bias on Twitter/Facebook — and echo chambers in every social network
	- Ari Paul, CIO Blocktower, on social media around cryptocurrency:

> “Easiest way to be popular is to tell people what they want to hear.  Easiest way to get rich is to tell rich people lies that they want to hear.” ([link](https://twitter.com/aridavidpaul/status/938154852567396352))

- Ari Paul, CIO Blocktower:

> “When I tweet anything positive about cryptocurrency it gets 10x the likes/shares as anything negative…” ([link](https://twitter.com/aridavidpaul/status/938153893636247552))

This example shares a lot of similarities with [publication bias](https://en.wikipedia.org/wiki/Publication_bias) in the sciences. Reader interest influences what content is produced ("the invisible hand of the reader") and distributed on social networks.

- Realize it is newsworthy/relevant to see the excesses of the opposite side, but not very newsworthy/relevant to see excesses of your side (leads to empathy gap); applies in engineering communities, but also across religions and countries
	- Noah Smith: “There are always a handful of people out there doing any stupid, crazy, or annoying thing you can imagine. And the media has an incentive to find those people and shove their excesses in your face.” ([link](https://twitter.com/noahpinion/status/934837949404811264)); social media algorithms especially value these extreme events, as they help them maximize engagement
	- My research on Islamic terrorism coverage in the NY Times vs non-Islamic terrorism and homicides ([link](https://www.nemil.com/s/part2-terrorism.html))

## Conferences and Meetups
**How it works**

- Conferences make money primarily through ticket sales, sponsorships, and booths; they aim to fill the conference seats
- Companies and media organizations organize groups of speakers and market the conference
- Sponsors and corporate organizers want to show their technology in the best light
- Motivations to speak at a conference ([according to MongoDB’s marketing team](http://web.archive.org/web/20120724115659/http://meghangill.com/2012/06/25/how-to-run-a-tech-conference-part-4-finding-speakers/))
	- increasing the speaker’s network
	- raising the speaker’s profile (personal branding)
	- recruiting for the speaker’s company
	- marketing for the speaker’s company (and for conference sponsors)

**Example hacks**

- **Sponsor speaker**: For companies, support a speaker unaffiliated with your company who you think will be likely to represent your view
- **Organize your own conference**: Run your own conference to ensure your own viewpoint is widely shared — and then shared widely online afterward by participants (Example: [MongoDB funding for conferences and user groups](https://www.nemil.com/mongo/3.html))

**Other issues**

- **Invisible hand of the sponsor/organizer**: Hard to speak badly about any sponsor/conference organizer, as it may impact if you’ll get free follow-up marketing or a future speaker invitation (Example: [Server Density highlights marketing benefit from speaking at MongoDB conference](https://blog.serverdensity.com/does-everyone-hate-mongodb/))
- **Surfing on hype**: Conferences need to fill seats, and so often feature tested ideas that will encourage this (e.g., NoSQL)

**Potential Antibodies**

- Conferences should be just one additional data point that augment learnings from being around talented engineers — and shouldn’t be used as a primary view of what’s going on
- Weigh the background and personal motivations of every speaker
- Weigh the motivations and editorial power of who’s running the conference

## Content Marketing
**How it works**

- Create “valuable” content that doesn’t look like an ad; is apt to get engagement and influence engineer behavior (examples: uptake a dev tool platform, enroll in a training program, join a company, use an open source package)
- Popular reasons for content marketing: increase domain SEO (example: [Yummly](http://firstround.com/review/the-seo-tips-that-helped-tally-20-million-visits-a-month/), [Nerdwallet](https://outrunseo.com/how-nerdwallet-built-a-520-million-company-using-a-content-based-seo-strategy/)), collect sales leads, sell product/service, recruit engineers, improve brand
- Content can be created in house, or relatively small amounts of funding can encourage others to create the content needed (example: [Pusher’s technical tutorial solicitation](https://pusher.com/guest-writer-program))
- Content marketing applies far beyond online posts, including categories like whitepapers to handouts in college/grad school classes

**Example Hacks**

- Create content that encourages audience to mistakenly believe that your product should be bought (Example: [REST is dead piece in Free Code Camp written by author trying to sell PluralSight GraphQL course](https://news.ycombinator.com/item?id=14839576); post was submitted by owner of Free Code Camp who was looking to get distribution; see [my response](https://news.ycombinator.com/item?id=14840321))

**Other Issues**

- Lots of content marketing passes for journalism
- University/grad school reading can be content marketing (At one top business school, a professor confided to me that the smartest move for many CEOs was to push for business school case studies that biased students to want to join their companies; these case studies would often read like a fawning profile)
- Need to write content on widely read topics to maximize readership; leads to an echo chamber of hype around new technologies since these have been validated to be of interest
- Content is expensive to produce (and the costs of creating more effective content is only increasing), so only those with the resources and exposure are the ones most likely to present the content to you. For more information, please read ["Content Shock: Why content marketing is not a sustainable strategy"](https://www.businessesgrow.com/2014/01/06/content-shock/)

**Potential Antibodies**

- Have to be able to identify when something is content marketing in everything from online posts to school curriculums
- Ask what is motivation of writer and how this influences their view; also need to understand their technical background
- Use content marketing to learn, but use it with proper skepticism
	- Fred Wilson, Partner Union Square Ventures:

> “So how should entrepreneurs use this knowledge that is being imparted by VCs …? Well first and foremost, you should see it as content marketing… That doesn’t mean it isn’t useful or insightful. It may well be. But you should understand the business model supporting all of this free content. *It is being generated to get you to come visit that VC and offer them to participate in your Seed or Series A round.* That blog post that Joe claimed is not scripture in his tweet is actually an _advertisement_. Kind of the opposite of scripture, right?” ([link](http://avc.com/2016/08/understanding-vcs/))

## Tech blogs and top media publications

**How it works**

- Trained (and untrained) journalists research various topics and work with editors to publish on blogs and print news
- Media organizations most often make money from ads; in some cases, they make money from subscription fees
- At its best, [goal of journalism](https://www.reuters.com/article/rpb-adlertrump-idUSKBN15F276) is to give the "facts [we] need to make good decisions"
	- Baser goal is to optimize eyeballs and number of paying subscribers by providing content that audiences want to read
	- News site can have some similarities to a convenience store that determines product placement based on maximizing sales (maximizing viewership is a key reason for the journalistic saying "If it bleeds, it leads")

**Example Hacks**

- **Rewarding Supporters/Attacking Opponents**: Media organizations/journalists can try to reward supporters such as negotiating with politicians for favorable coverage or painting their enemies in an unfavorable light; can do this to gain exclusive future access from a source or reduce competition
    - In tabloid industry, buying story to bury it is called "[catch and kill](https://www.newyorker.com/news/news-desk/donald-trump-a-playboy-model-and-a-system-for-concealing-infidelity-national-enquirer-karen-mcdougal)"; allows you to exercise leverage and/or gain a future source
    - Examples: [speculation about National Enquirer and Donald Trump](https://www.newyorker.com/magazine/2017/07/03/the-national-enquirers-fervor-for-trump), [Donna Brazile and Hilary Clinton](https://www.snopes.com/donna-brazile-leaves-cnn/), [Benjamin Netanyahu negotiating for more positive coverage](https://www.nytimes.com/2017/01/08/world/middleeast/israel-benjamin-netanyahu-yediot-aharonot-deal.html), [speculation that Rupert Murdoch implicitly threatened Mark Zuckerburg for better economics from Facebook](https://www.wired.com/story/inside-facebook-mark-zuckerberg-2-years-of-hell/), debates about the relationship between media barons and politicians around the world
- **Selective Leaking**: Leak something to a journalist that reflects unfavorably on your competitor, allowing it to receive more credibility than if sourced back to your company (example: [Speculation of New England Patriots leak](https://www.nytimes.com/2018/01/14/sports/football/patriots-tom-brady-belichick.html), politics on any given day)
- **Pay to place**: Pay journalist/writer directly to place a piece (example: [HuffPo/Forbes/etc](https://news.ycombinator.com/item?id=16182576))
- **Pay others to place**: Pay for PR firm to place (example: [Syria’s Asma al-Assad’s team pays $5k for help getting a favorable Vogue article](https://www.theatlantic.com/international/archive/2012/01/the-only-remaining-online-copy-of-vogues-asma-al-assad-profile/250753/))
- **Pre-written Articles**: Write a press release that is easy for a journalist to publish without modification  (example: [my experience in East Timor](https://www.nemil.com/musings/hack-an-engineer.html#timor-leste))

**Other Issues**

- **Engagement is king**: Reader interest and social media algorithms prize engaging content, rather than information that leads to good engineering decisions (example: [feverish coverage of Cecil the Lion](https://www.nytimes.com/2015/08/17/business/where-clicks-reign-audience-is-king.html), [example why atrocities in Yemen are not well covered in the US press](https://www.nytimes.com/2016/10/02/world/why-some-wars-like-syrias-get-more-attention-than-others-like-yemens.html))
	- Coverage is a function of reader interest; fundamental problem with using media to make decisions
		- What’s covered is not the same as what’s important for the decisions we make each day
		- Focus on newsworthiness and relevance leads to substantial “sampling bias”
	- Opportunity to create fake content that meets reader interest (example: [Jim Cramer talking about how easy it is to create fake news that Apple’s original iPhone isn’t selling well](http://www.cc.com/video-clips/rfag2r/the-daily-show-with-jon-stewart-exclusive---jim-cramer-extended-interview-pt--2), allowing him to profit off a fall in the stock price, 2016 US Election)
- **Technical Competence**: Many journalists don’t have a technical or business background, but write on these topics authoritatively
- **Getting past PR**: PR steers journalists in favored directions and sometimes implicitly threatens things journalists value like access to a CEO (example: [public relations, marketing and advertising at Theranos](https://californiahealthline.org/news/reporters-notebook-the-tale-of-theranos-and-the-mysterious-fire-alarm/) )
- **Talent**: Salary in journalism is a fraction of tech industry, meaning that many experienced, smart journalists increasingly leave or work in house
- **Access**: Journalists trade favorable coverage for access/tips; businesses favor journalists that "toe the line"
  - Companies/investors can control access to their companies, dictating the rules that journalists must follow to get exclusives and scoops; can cut off access to influence future coverage (examples: [EA  and Steve Hogarty](https://twitter.com/misterbrilliant/status/483224360418041856), [Coverage of the British Monarchy](https://www.nytimes.com/2018/01/14/arts/television/queen-coronation-bbc-smithsonian.html), [Disney and the LA Times](https://boingboing.net/2017/11/05/bob-iger-vs-the-press.html), [Liz Smith and Celebrity journalism](https://mobile.nytimes.com/2017/07/28/nyregion/liz-smith-lions-of-new-york.html), [Michael Arrington trying to interview Tron cryptocurrency founder](https://twitter.com/arrington/status/969414440062877696?s=12))
  - Hard to get access in first place with many "A-listers", unless they have something to sell; these "A-listers" often also actively shop for journalists who will be an ally
- Journalists try to:
	- maintain good source relationships (e.g., investors) and access for future information
	- manage substantial story deadlines with limited time (example: [Paul Graham’s post on maximizing PR and importance of making stories easy for journalists](http://www.paulgraham.com/submarine.html))
	- show strong engagement metrics to ensure job security (Example: [Greta Van Susteren at MSNBC](https://www.nytimes.com/2017/06/29/business/media/greta-van-susteren-leaving-msnbc-after-only-six-months.html))
	- can be fired or influenced to prevent unfavorable coverage even in seemingly innocuous beats like business or technical reporting (example: [Newsweek firing for critical coverage of Newsweek’s parent company](https://www.nytimes.com/2018/02/05/business/media/newsweek-firings.html)) (there are obviously much worse things that happen to journalists, and my focus is in tech reporting)
	- use “three’s a trend” as common heuristic, despite the fact that this would be laughable to most statisticians (example: [Great Clown Scare of 2016](https://www.nytimes.com/2016/09/13/insider/on-the-creepy-clown-beat-you-really-cant-make-this-stuff-up.html), [anecdotes vs data](https://twitter.com/trengriffin/status/948366029058535424))
	- (sometimes) keep a future career path open to the technology sector

**Potential antibodies**

- When something is heavily covered, it is substantially due to large reader interest — not due to the importance of the event for you; risk of confirmation bias and sampling bias if you don’t adjust signal
	- Paul Graham: “The number of news stories about a problem is not a sign of how serious it is, but of how much demand there is for stories claiming so” ([link](https://twitter.com/paulg/status/888496117159276545))
	- Tren Griffin: "The journalistic formula of 2018 so far seems to be: *I found a few bat shit crazy people in region X doing Y. Therefore the practice of doing Y is widespread in that region X.* A few anecdotes are not data establishing something is a widespread practice." ([link](https://twitter.com/trengriffin/status/948366029058535424))
	- My research on death coverage in the NY Times and risk assessment ([link](https://www.nemil.com/s/part3-horror-films.html))
- Realize vivid stories are powerful for user engagement, while lots of drier data and stories that inform good decisions are less monetizable (example: [Shooting of Australian in US - and needs/pre-existing beliefs of Australian readers](https://www.nytimes.com/2017/07/22/us/minneapolis-police-shooting.html))
- Dig into technical background of writer
- When you see something covered, ask yourself who is motivated to have it covered this way
	- Especially valuable in laudatory personal profiles
	- In leaks, who could have leaked it and what was their motive? What important information might be unleaked?
- When a PR-like piece is shared ([A24 in GQ](https://www.gq.com/story/a24-studio-oral-history), IBM Watson, a laudatory profile) , ask what the covered party’s motivation is to get the word out now (recruiting, sales, corporate branding)
- Distinguish between guest written or sponsored pieces, and something written by the staff
- Read *[All the News That’s Fit to Sell](https://www.amazon.com/All-News-Thats-Fit-Sell/dp/0691123675/ref=sr_1_1)* (Stanford Professor James Hamilton) and *[Public Opinion](https://en.wikipedia.org/wiki/Public_Opinion_(book))* (Walter Lippmann) for more on how events are turned into news

## Fellow engineers

**How it works**

- Fellow engineers/scientists may be vocal in social media, conferences, and on mailing lists


**Example Hacks**

- Give them a monetizable business model, so that they’ll represent your views (example: [MongoDB consultants who then speak favorably about MongoDB](http://web.archive.org/web/20120724115659/http://meghangill.com/2012/06/25/how-to-run-a-tech-conference-part-4-finding-speakers/))
- Give them equity in the success of your business — increasing the likelihood they’ll speak positively of you and, at minimum, reducing the likelihood they can publicly say negative things about you (example: [cryptocurrency ownership](https://twitter.com/fehrsam/status/892429946550837248), open source developer equity grant)
- **Give a college talk or become an ongoing college lecturer**: For entrepreneurs this lets you scout talent, increase your company's brand on campus, and improve your own personal brand; for VCs, this lets you scout deals earlier and have greater consideration to be the chosen funder when the company raises outside funding

**Other Issues**

- Establish your expertise in one topic so that you have people's attention. Once you have their attention, express your views on another topic that you have no expertise in
- Fund researchers who pursue avenues that will be potentially accretive to your interests; not explicit bias, but means that opposite hypothesis may be weakly pursued

**Potential antibodies**

- Question funding and incentives of anyone speaking favorably about a chosen technology
- Just because someone has a well regarded reputation (e.g., through open source contributions, through previous well regarded projects) doesn’t mean they can’t be representing parochial incentives that are at odds with what is right for you
- Like with all written media, you have to question the incentives of someone speaking
