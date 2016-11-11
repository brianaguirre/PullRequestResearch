**Is Openness a good feature? Why?**

I took "openness" in two different ways. Openness from the side of GitHub, as a business and coding model and openness of code within the tech world in general. In terms of the former, it appears that GitHub’s goal is to enable developers to contribute to projects in a way that does not disrupt workflow and enhances contribution by allowing project owners/creators to submit changes and add on features openly. In order to do so, projects are open in a way that it can be shared and co-owned by many individuals. The idea of openness though extends beyond those who are directly “owners” of the projects. GitHub also allows contributors to implement code from non-project owners. According to their site and people who work at GitHub, the idea stems from ideals of code and technology itself; that making development and software advancements is a social contribution as well as a technical one and as such benefits society not just the individuals. So in that sense, GitHub also agrees that projects (Repos) should open to people who wish to make contributions, despite not being owners of the code directly.

As far as latter goes, the concept of free sharing of technological information existed way before computers were around, but communities of open source software became popularized in 1950’s and 60’s as the production computer operating software and compilers grew. As code became more mainstream, several universities worked together to share research and knowledge. In recent years, due to technological advancements, it’s common to see communities that share code such as GitHub itself, the largest open source community (according to their site), and StackOverflow, among others. And so, due to the availability of code, and the openness that currently exists, there are several pros and cons in terms of how open PR’s and fork stats are within a GitHub repo:

Pros:
**Reach** - people can distribute code and findings to people with very little resistance (No costs to download the code, pre-made license agreements that GitHub compiles, free hosting, etc.), so that same attitude and outlook is carried through with PR statistics. So when you make a PR available and open to other contributors, it helps them see workflow and train of thought.

**Effect on REPO Types/Tools** - Notice that when there are plenty of forks and PR’s submitted, it’s usually because the owner(s) have done some sort of work towards making it easy for people to contribute. So the openness makes repo owners more likely to consider to include guides or code to allow people to work on bugs or new features.

**Momentum**
If you show stats for PR’s, it perhaps encourages people that their contributions will not be ignored, because you can see activity under the repo. The openness perhaps has the same effect that seeing a tip jar with some money in it already does for future tippers; knowing others care enough or paved the way, encourages you to care yourself. (NOTE: Personally I see whether there have been recent commits.)

**Community** - Openness creates a sense of transparency, which is inviting to people. So when GitHub allows strangers to work and contribute on projects, these people are connected and form a relationships, which drives the project forward and the software world forward. It also makes it so that you can learn from other users in terms of how to suggest changes and how to deal with PR’s yourself, perhaps in your own repos. 

Cons:
**Lose of Focus** - Openness invites critiques and other interpretations of ideas. So something that affects some of the repos and PR’s from being accepted is maybe how the contributor doesn’t solve or do what the creator originally originally intended. This maybe is one of the reasons some PR’s don’t get accepted, despite solving what the contributor wanted to solve, just disagrees creatively. (NOTE: Solving bugs with technologies that clash with previous work, is not backwards compatible, or contributions that require too much time or energy to maintain)

**Negative Attitude** - Openness in PR’s can sometimes lead to pressure on the owner to just automatically accept people’s contributions. The idea of someone working for free or volunteering to solve something for you is great, but when are you, as an owner, allowed to say thanks but no thanks. (NOTE: Again, contributor solved something using wrong technology, or his/her contributions take too much time or energy to maintain or implement, etc.) 

**Open PRS = Bad Project Owners** - Seeing open PR’s for a while, and seeing so much information about other people’s PR’s such as comments, time lapses, attempts, etc., imply a lot about the project and the owners. If it took a while for a PR to be accepted, it’s much easier to assume that the owner was picky, or didn’t spend time on it, so blame goes to owner not contributor. (NOTE: personally, I think that as someone maintaining an open source project, it’s somewhat your duty to look at and respond to PR’s in a timely manner) 


Sources:
GitHubs business model and OpenSource model:
https://github.com/business
https://github.com/open-source

Workers at GitHub:
https://twitter.com/patricktoomey
https://twitter.com/nothingstrivial


**Do you think the percentage of merged PRs is a good feature? Why**?

No. Part of me thinks seeing a percentage, unless it’s a good one, would discourage people to contribute more. For example, 50%, I personally would consider to be great for a small repo. But, “what is a good %” in terms of project owners and contributors? The ratio and factors, can be sometimes arbitrary. It’s tough to say. And what if people are just busy, and what if some PRs are just bad and so they are never merged, all of those factors would count against them and so the percentage would decrease.

GitHub already offers so many other statistics in terms of commits and solved bugs that show the user the presence of an active repo and project community, so no need to see a percentage of merged PRs.

NOTE: This might be different for a project owner vs. contributor. When a % is great, maybe you want to brag about it to encourage more people to submit PRs. As a contributor, seeing a percentage might be something you consider in order to decide whether it’s worth submitting a PR for.

**My understanding is that they are useless for us. Right?**
What is useless? Seeing which % of PRs have been accepted without discussion, or the discussion within the PRs themselves?

I think discussion might be important. I think seeing which ones have been accepted without discussions is important because I think sometimes, if they are small and fix something minor/a tiny bug, then they would of course be accepted quickly. Consider a PR that only has one file, or one small comment, then it’s easy to process (look at, analyst it, then merge it). In some PRs with discussion, other users comment “Nice, I hope this gets pulled soon.” So there is urgency or approval from other people, and then the owner merges it.


**So they are not PRs that were rejected first. That means they are useless for us. Right?**

I think you’re right. As far as I understand it, the ones that submit all the commits at once and are merged are the ones we don’t care about since they were accepted on their first try. Ones that then submit commits on their branch and then those are reviewed and accepted are the ones we want to look at.

**This is good. Are the comments about the coding style of the commit? Or the changed code themselves? Or the commit message is not clear enough? I think these are our concern**.

Mandana wrote “commits” not comments, but there are comments too that the owner writes for the contributor.

Owner comments on PR but does not accept it:
Comments on functionality of the code. “Compatibility” is something that comes up often. So contributor fixes bug or problem but using a technology that he/she is familiar with, but does not take into account which Java version the project is under and making sure it works with prior versions. - It appears the other contributors tell the contributor who submitted the PR what the issue is. EX: Pull 73.

In the case above (Pull 73): contributor makes two commits, 5 days later told they don’t work, then finds out they don’t work because of backwards compatibility, same day, fixes them and then the PR is accepted.

I couldn’t find other PRs that were originally rejected and then finally accepted and merged. All other ones were accepted at once.

I also agree that these are the ones we want to be paying attention to because I have noticed that all of the closed out PRs that were not accepted (merged), the owner at least comments on them. Technically we are not looking at the non-accepted PRs but we at least know that comments seem to be important because I doubt someone will just reject a PR without at least a sentence at to why.


**Great. What are the reasons that make them un-merged? What is the content of communication between authors and maintainers**?

I found comments to be on a few number of things:
1. Logic: Most commented PR that was un-merged was about user that had a corrupt DB. But he/she submitted a PR to remove capital in order for the game to stop submitting an error. So the comment from the owner told the user that the PR would result in breaking the logic of the game because contributor suggested removing capital of a city, when in fact all cities must have capitals. 

2. Functionality: contributors who suggested making changes that then break other parts of the code. The owner comments on the fact that “nice code but…” it breaks code/DB’s, doesn’t do exactly what it says it’s supposed to so no point in adding it.
Some other contributors also comment on things not working or PR breaking other parts of the project.

Comments from owner then just mmostly address lack of testing, functionality (contributor maybe solves problem directly, but in doing so negatively affects other code parts or features). 

3. +1: Other users says it’s a good idea.

4. “Manually fixing things” - Owner closes things un-merged because things have been done manually through his branch. Note that either owner includes it within the latest update, or codes solution himself since contributor suggested something that owner didn’t think worked well.

**Most merged PRs are small:**

1. Many of the 1-5 commit PRs with a good original comment get merged.
2. PRs that either consisted of “This would be a good feature” didn’t get merged right away or at all. I think it’s because owner might need to take more time to consider whether it’s a good idea or not. (More time consuming = harder to finally accept)
3. PR that have few edited files get merged as well. 



**If a PR is not merged, and the maintainer is asking something, what are they asking? This could be a concern from maintainers**.

NOTE: A lot of PR’s closed were not merged.

Most commented open PR is of a contributor suggesting something he/she likes to be merged. But has a lot of comments because other users are telling the PR submitter that the code doesn’t work and there are bugs. (No repo owner comments)

None of the open PR’s have had maintainer comments, only other contributors. 

**Could you confirm that what kind of policy? Coding style? Or the core value of a project**?

Coding style and functionality are the only ones I was able to find. Backwards comparability and using the right version are the two comments from the repo owner that I was able to find.



**ADDITIONAL NOTES:**

1. Other users often make more comments on PR’s than the repo owner himself/herself.
2. Accepted PR’s have few commits and few files edited. 
3. A lot of closed un-merged PR’s were about adding additional functionality or features, not necessarily about fixing bugs.
4. More than 60% of closed PR’s titled “Fixed” or something along the lines were not merged.
5. PR’s with most comments were usually not merged.
6. Common word seeing in merged PR’s were “add” or “added”
7. A lot of closed PR’s that were not merged were closed by the user who submitted the PR. (Could be due to lack of activity? Correction? Maybe update had the suggested commits?)




