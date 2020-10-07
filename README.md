# IUA-Channel: "If unsure ask ..." An alternative to explicit Responsibilities.

I like [Intranet Wikis](https://github.com/guettli/intranets). It helps to find a common terminology.

Here comes a story. 

I have seen this several times: A co-worker (Bob) created a cool tool. Then I would like to create a new wiki page explaining this
cool thing. The Bob likes this idea. He is busy doing things, so he is happy that I want to document it. And I am happy since I like to improve our knowledge base.

Me: Hi Bob, I would like to create a little wiki page about your cool tool. 

Bob: Yes, great. Thank you.

Me: Bob, are you okay with me writing on the wiki page that you are responsible for this?

Bob: hmmm, I don't know. 

In other words, he is not comfortable with it.

Background: I am not the manager of Bob. We work on eye-level (peer-to-peer). Nobody told me to care for the wiki. I do it to make life easier for new comers and people from other departments.

My first step was okay for Bob: Create a page where every employee can read about the cool new tool. But he does not like the second step. Why?

Inspired by the book [Brave New Work](https://www.bravenewwork.com/) by Aaron Dignan I realized: Org-Charts and official "Responsibilities" are less important today. 

"You are responsible for xyz" is roughly the same as "You are to blame if something goes wrong."

There are different kinds of people. Some are brave super-heroes. And most are not. That's ok. I am not a brave super-hero, too. I don't want to be the one to blame, although I like to build stuff which makes customers or colleagues happy.

Bob created something new because it was useful. He wanted to solve something which helps now and today. He does not want to be the one to blame if this does not work two years later. That's understandable.

Nevertheless, I still have the new wiki page before me which explains the basics of the new tool.

How to proceed? Just close it, document the tool and don't mention a name on the page?

What is my goal? I have this scene on my mind: A new team member heard about this tool. He finds the wiki page and he learns the basic facts about the cool tool. But he wants to know more about a particular detail. Or he wants to improve it, or he just wants to says "thank you for this tool".

I want to help the new team member to learn the basics fast. There is no need to explain every detail on the wiki page. Just an overview. If the new team member has a question, he should know where to ask.

Bob, the creator of the tool, is in the "getting things done" mode. He does not see that it makes sense to document and advertise his tool. And that's all right.

If "responsible" does not fit. Which alternatives exist?

In an Org-Chart there is a line between two boxes. Imagine there are two boxes A and B. How to call the line between A and B?

* A is responsible for B
* A is accountable for B
* A manages B
* A owns B
* B reports to A

The attentive reader might notice that I don't make a distinction between what A or B is. It could be a person, a role,
a department, a team, a tool, a service ...

There was a time when I was new and completely clueless. I remember this very well.

For example when I tried to compile the Linux kernel for the first time. In 1997 this was common practice and done
by most Linux users. I was completely lost. A lot of unknown tech terms faced me and great search engines like were
not invented yet. Before compiling the kernel a lot of questions got asked interactively. 

I am very thankful for the kernel hacker who had the idea to put a [sane default](https://en.wikipedia.org/wiki/Default_(computer_science)) option called "if unsure choose ..." to every question.

Since I had no clue, this hint helped me do manage this complicated process.

23 years later (some days ago) I read about [Direct Responsible Individual (Apple)](https://fortune.com/2011/08/25/how-apple-works-inside-the-worlds-biggest-startup/).
I think this is a good solution for temporary projects. For a time-frame of two weeks to maybe eight months, it is easy to say "Yes, I want to be a directly responsible individual."

But back to me sitting in front of the screen creating a new wiki page. This is not a temporary project.
This is a tool/service/process/feature/product that will last longer. No end in sight so far. Going to our manager to solve this would make
it too complicated. This should be doable on the peer-to-peer level.

Thank you for your patience in reading my story.

... short dramaturgical pause ... 

The solution: **IUA-Channel: If unsure ask ...**

It does not matter how big your Wiki or knowledge-base is. Not everything will
be covered. You should always provide a channel so that people can ask questions.

More is not needed. Newcomers should know whom to talk to.

The IUA-Channel can be a person, a role, a chat-channel or a mail-address.

In above example the IUA-Channel take the pressure of Bob. Imagine he created an internal tool in the context of Kubernetes (Cloud
orchestration software). And there is already a general chat channel called #kuberentes, then you could add
to the page of the new tool: "If unsure ask in #kubernetes". This way the responsibility is was handed over from
one individual to a group. Bob feels better and if Bob is on vacation it is likely that someone else can answer
the question of the new team member.

You could call it "Contact-Channel" or "Support-Channel". But this wouldn't be new, cool, agile, lean or innovative :-)


## Different perspectives

### I don't get the problem you want to solve with IUA

I want to raise obviousness to make the work environment more efficient. This is hard to grasp. Raising
obviousness means to change thousand small things, and at the end nobody will notice a difference. It will
just work.

A comparison: traffic jams created by road construction works are a common smalltalk topic. People need to wait,
and this annoys them. Since they are annoyed they start to speak. If the road is fine, then they complain about the weather.
They don't even realize that the roads are in a very good state. Infrastructure is taken for granted, although it shouldn't.

If you look at this comparison, then you realize: You can raise obviousness and make work easier, and finally nobody 
will say "thank you". That's live. Don't expect a "thank you". Do it since you see that it makes sense.

## Alternatives to IUA-Channels

### Alternative: RACI Matrix

[Responsibility assignment matrix](https://en.wikipedia.org/wiki/Responsibility_assignment_matrix)

Responsible, Accountable, Consulted, and Informed.

IUA is about "consulted". Who can I consult, if I need advice. This can get solved at peer-to-peer level and is very helpful.

### Alternative:  DRI

[Direct Responsible Individual (Apple)](https://fortune.com/2011/08/25/how-apple-works-inside-the-worlds-biggest-startup/).


### Alternative:  ARPA

[ARPA: A Framework Alternative to the RACI Model](https://www.helpscout.com/blog/arpa-raci-model/)

* Accountable: 
The person who is accountable to the business (in some cases the board) for success. Strategic decisions related to the project or initiative are made by this person.
* Responsible: One or two people who are responsible for day-to-day execution, making sure the work gets done within project constraints and meets our standards of excellence. Tactical decisions related to the project or initiative are made by these folks.
* Participant: People who allocate time and resources to support the project’s delivery, but for whom the project is not a primary role or responsibility. They make decisions related to the quality of the work, but they otherwise look to the Responsible or Accountable party for direction.
* Advisor: People who are consulted on one or more aspects, but they have no decision-making authority.

I think ARPA is like DRI about temporary projects. The use case for IAU-Channel is for permantent tools/services/processes/features/products.

### Alternative:  Asset Management / iso9001

[Asset Management](https://en.wikipedia.org/wiki/Asset_management): 

> Asset management refers to systematic approach to the governance and realization of value from the things that a 
> group or entity is responsible for, over their whole life cycles. It may apply both to tangible assets 
> (physical objects such as buildings or equipment) and to intangible assets (such as human capital, 
> intellectual property, goodwill or financial assets). Asset management is a systematic process of developing, 
> operating, maintaining, upgrading, and disposing of assets in the most cost-effective manner (including 
> all costs, risks and performance attributes).

"Perfect is the enemy of good". Even if your company has a ISO-9001 certificate, it is likely that a lot of
things are unclear. IUA-Channel can help you to solve all this small things in a quick and agile way.

### Alternative:  Ownership.

This term gets used often. For example: [10 Ways to Encourage Employees to Take Ownership in Their Work](https://ericchester.com/10-ways-encourage-employees-to-take-ownership-at-work/)

Companies want it, but does the term "Ownership" really fit here?

Just have a look at the Wikpedia page: [Ownership](https://en.wikipedia.org/wiki/Ownership).

You can own a car, a house, land or real estate ...

You can take ownership of things you created, then "take ownership" means "build new things". This fits
to a fast growing startup.

But in an established company "take ownership" would mean to take it away from somebody. This is like stealing.

## What is better than having two contact channels?

> What is better than having two contact channels?

Answer: To have **one** contact channel.

Why: Because "don't make me think". If you have two contact channels, then the user/customer needs to think. he needs
to decide which contact channel to choose. Thinking hurts. Don't let you users/customers feel pain.

Keep it simple.

## Conclusion

I think there are three levels of "Responsibility":

* Org Chart: This is the official Responsibility. You can't take ownership here on your own.
* DRI (Direct responsible individual): For temporary project, an individual who has the final word fits well. This way decisions get done fast and without long discussions.
* [IAU-Channel](https://github.com/guettli/IUA-Channel): "If unsure ask ...": A long-lasting support channel for internal processes or tools.

### About

I like Working-out-loud and you can read about other topics at [Thomas WOL at Github](https://github.com/guettli/wol)

What do you think about this? Please write me a mail guettli.iua@thomas-guettler.de or create an issue at GitHub.

Please tell me typos or strange wordings, I am not a native speaker.
