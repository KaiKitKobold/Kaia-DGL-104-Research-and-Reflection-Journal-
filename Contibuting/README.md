rrjKaiKitKobold
# Community Code Project 

## Table of Contents
**[Part One: External Community](#external-community)**
+ [Project Chosen](#one-project-chosen)
+ [First Issue and Process](#one-first-issue)
+ [Problem with Chosen Issue](#one-problem-issue)
+ [First Draft Read.Me File ](#one-first-draft)
+[Second Draft Read.Me File](#one-second-draft)
+ [Third Draft Read.Me File](#one-third-draft)
**[Part One: FootNotes and Refrence](#one-footnotes)**

**[Part Two Internal Community](#internal-community)**
[Code](#two-code)
[Documentation](#two-docs)
**[Part Two: FootNotes and Refrence](#two-footnotes)** 

<a id=”external-community”></a>
## Part 1: External Community
Before we begin, I’d like to give a link to my [Fork of Cloudstream](https://github.com/KaiKitKobold/KaiKitForkcloudstream), that-alongside my pull request for my [Read.me implementation](https://github.com/recloudstream/cloudstream/pull/1004) is a quick way to accesses the work that I’ve done quickly, if you Ashley are behind on grading at this stressful time. 

<a id=”one-project-chosen”></a>
### Project Chosen 
My chosen community for my external community is CloudStream. I had initially chosen it over the others because it was a small yet active community full of active contributions and had ties to a rapidly accelerating industry, that being Streaming services with user-flexibility and video players, according to Forbes [Top Streaming Statistics In 2024](https://www.forbes.com/home-improvement/internet/streaming-stats/) 
*“The video streaming industry has established itself as a colossal economic force, currently valued at an astounding $544 billion.”*
Therefore, developers who have experience in video players, streaming, or other social media platforms are a high priority on developer’s lists, and despite this open-source community being small, I thought the skills I learned from this project would help me in my future career on further projects, may it be internships, future jobs, or personal projects; this is one of the many reasons why I wished to join this community. 
#### What’s the project used for?
[CloudStream](https://github.com/recloudstream/cloudstream)
It is a video player with extension support for playing, streaming, and downloading various apps, such as Librivox[https://librivox.org/], a free, open-source audiobook extension. [YouTube](https://www.youtube.com/), a user-created video streaming platform created by Google. [Twitch](https://www.twitch.tv/directory) is a streaming platform owned by Amazon that focuses on User Created Live Content such as Art, Music, Social Chats, and Competitive Video Game Streaming such as Esports and video game Streaming: [iptv.ORG](https://github.com/iptv-org/iptv), a collection of publicly available IPTV channels worldwide. [Nginx](https://www.nginx.com/) is a web server that, among many other things, can allow you to play or stream content from your server, among many other user-created extensions for nearly anything. 

However, because of the open-source nature of the project, there are a few bad apples among the community who attempt to make user extensions that breach copyright law; Cloudstream takes copyright incredibly seriously, further details of which can be seen on their organization: [redcloudstream](https://github.com/recloudstream)
RecloudStream [Docs](https://recloudstream.github.io/csdocs/recsrc/)
 are also open-source and are not frequently maintained; this means that illegal extensions can be found in the recommended sources section. CloudStream does not affiliate with its documentation, and as I reflect on this, I see that they are working on the problem as I speak.	
#### Project’s primary issues: 
Like most open-source repositories, [CloudStream](https://github.com/recloudstream/cloudstream)
It includes an issues page to showcase contributions and discuss related issues to the project, such as bugs, feature requests, or other related issues, such as documentation. 

For further details on a detailed reflection on the issues I could have chosen, Including those across a wide variety of projects, look at week nine of my [Research & Reflection Journal.md](README.md) journal for more details on the process; however, I will take this time to reflect and showcase some issues to highlight the different labels and discuss them across the project's maintainers. 

Labels in CloudStream [Issues](https://github.com/recloudstream/cloudstream/issues) are few but descriptive. The labels are as follows, which are used by the issues and updated and reflected by the maintainers:
- Api: These issues are related to those that must be updated in the main API
- Bug: For bugs relating to the program or an extension. 
- Documentation: For issues related to Improvements and Additions to the documentation.  
- Duplicate: Assigned by maintainers. The label is used for duplicate issues.
- Enhancement: Issues Requesting New Features Or Request that help the overall flow, UI, or other aspects of the sight.
- Good First Issue: An excellent first issue for new developers or developers to acquaint themselves with the program. 
- Help Wanted: An issue that requires help or extra attention for multiple developers to work on.
- Invalid: The Issue doesn’t seem right and will likely not be worked on. 
- Not Enough Information: Not enough information is described for the issue 
- Possible Duplicate: Assigned by the Bot: Works the same as Duplicate Issue
- Possible Provider Issue: Assigned by the Bot: 
- Potential Extension: The Issue could eventually be turned into an extension 
- Question: Further Information is Requested for The Issue: 
- TODO: An Issue to prioritize issues that need to be finished 
- Won’t Fix: Issues with this label will not be worked on. 

As someone who wishes to work on the development side of the project, mainly so that I can help prioritize and work on the documentation side of our internal project, being a hobbyist writer would be something I can truly focus on rather than something that I may misinterpret or have a problem implementing promptly such as coding, but also wish to have the first-hand experience of the project. 

In the end, I tried looking through the [Good First Issue Label](https://github.com/recloudstream/cloudstream/issues?q=is%3Aopen+is%3Aissue+label%3A%22good+first+issue%22)
and found something that, with my experience with DGL 104 (HTML and CSS) and DGL 114 (Intro Mobile App Development), was something that felt reasonably easy to both implement and help the project, I decided to choose the [Better Aspect/Video Resized](https://github.com/recloudstream/cloudstream/issues/379) Issue.
The initial Implementation of the issue seemed relatively easy, but it would also help me learn more about the project, the definition of which we’ll focus on shortly.


<a id=”one-first-issue”></a>
### First Issue and Communication:
The First Issue that I decided to choose was [Better Aspect/Video Resized](https://github.com/recloudstream/cloudstream/issues/379).
As defined, of course, since it was an issue from February 17, 2023. An issue that had been requested and had active communication from around an entire year ago, I had to make sure that issue was still open for requests, and since there was no contributing document or commit rules, make sure that CloudStream was open to contributions and development, In response; I gave the following message: 

In response, The community gave me the thumbs up. Showcased documentation, and Thoughtfully responded to my questions, and gave further support to work on the project. 
Overall, They answered my questions and helped me with their documentation in order to take the next steps of the project, So, Let’s look at the next steps in more detail, shall we?

<a id=”one-problem-issue”></a>
### Researching the chosen issue:
While I would say that, at the time of research and implementation of the issue, That being around week 8 of the project, This section will describe the research I attempted while looking through this issue and some of the skills and concepts that I have learned around that time that I write this currently which is: *March 30’th 2024.*

The primary research I did was researching layouts and, more specifically, the constrained layout built into Android Studio: 
My research included looking into Using super in the [layout section](https://developer.android.com/develop/ui/views/layout/declaring-layout)
 of Android’s studio docs, more specifically [constraint layout](https://developer.android.com/develop/ui/views/layout/constraint-layout)
And [Adapter/Binding Layout View](https://developer.android.com/develop/ui/views/layout/binding)


I also tried researching the documentation provided by the maintainers and developers of the project, that is, the [For Extension developers](https://recloudstream.github.io/csdocs/devs/gettingstarted/), in cloud docs: 
 
I managed to get set up with the program fairly easily, and no problems started to arise. Initially, at the start of the project, it quickly diverts you to this tutorial on scarping. For those unfamiliar with the concept, I decided to follow along.  


However, while I attempted to follow the rules, I very quickly started to run into trouble with the development of the program, for starters. At the same time, I knew the implementation of what I needed, the layout, I didn’t know how exactly the limits of how it would react with the other program, and other issues with the program. 

### Problem with the chosen issue:

I ran into the following problems when identfying and attempting to follow-along with the project: For one, at the time I didn’t know how to identfy scraping and how to acureattly iplement it inside the program, and the steps I followed in the documentation was incrediblly confusing and didn’t awnser my questions relating to the program, no matter how much further research I did:
[CloudStream Exstension Instructions? Nope already followed that](https://gist.github.com/redtrillix/17a1d8eda270b6db831b85a860c0fcd0?permalink_comment_id=4596291)
[Stack Overflow: Something related? That dosen’t show steps? It didn’t work out for me, and was too high tech to fully appreciate and implement](https://stackoverflow.com/questions/61534733/named-destination-for-spring-cloud-stream-source-extension)

I mainly ran into problems with understanding what the source code snippets meant, and how they related to the full problem:

This made sense, to me however the others, which ranged in intensity and targeted specific variables, objects, and other aspects of the program did not. 

I had initially though that, even though I didn’t understand fully how it would be implemented, my issue was mainly related to loading links, and the content inside it; however, I was also initially turned off, looking at the implementation of the home page, and how I was supposed to work on it in such a limited time frame. 


The last example didn’t help me at all and just confused me further on how I was supposed to implement the project. 




That, alongside other problems I ran into, such as not understanding where my exstensions were supposed to go; (There were no easy-to-find sources in docs; I now know through my future research of the CloudStream that they are located in repositories, and other parts of documentation), alongside general confusion and experince with the program, I decided to drop it.

After my inital attempt to work on my project failed, I decided to look back and identfy what troubled me the most, and what needed fixing.

<a id=”one-new-issue”></a>	
### Identifying the issue and asking the community: 

After looking it over, I realized something. A lot of my initial questions:
+ Seeing if the repository accepted commits/was open 
+ Where Documentation Is/Was 
+ A description of the project and what it is.
+ Sources, Etc
This could have been easily remedied by an updated READ.ME file and the current state of the READ.ME file was not adequate, especially compared to other repositories such as LibreTube, It made the project look low-quality and lazy, which having to research many aspects of this project, is clearly, not the case; to accurately showcase what I mean, Here’s some pictures of the [READ.ME in its current state.](https://github.com/recloudstream/cloudstream)


And then, it showcases the complete list of the currently supported languages for the Contributing.md file, as you can see, while it does the bear minimum describing the project, it’s overall entirely lacking in describing important features for both a user standpoint, such as how do I download and install the app, links to Docs, FAQ etc, what this repository is even about, and the developer side, such as Developer Documentation, Reccomened Sources, If the project accepts commits, if there is any commit rules, and issue rules/guidelines. 
Helping write the READ.ME with the project was a top priority, as I wanted to communicate accurately and showcase the project as it was meant to be.

Firstly, before I began work on the project, I decided to explain both what happened to me working on the old project and how and why I was working on this project, Including the fact that I was doing this for schoolwork.


Like before, they accepted the idea for my contributions, gave me some suggestions to work on, and I got to work, but not before I did the [internal community](#internal-community) work first, which you can read more about on the chapter of the same name.


For this project, I will not showcase each iteration of the READ.ME looks and functions as, inevitably, that would add to my already limited workflow and energy and add bloat to this document. If you wish to look through each aspect of this project individually, [you can look at my pull request on CloudStream](https://github.com/recloudstream/cloudstream/pull/1004)

#### Research Process: 
While I will admit that, unlike the other aspects of the project, my research processes in the first draft were not the best, as I decided to hyper-focus on the documentation, links, and references towards specific aspects of the documentation, the issues, and the project.


I also frequently asked questions. About certain aspects of the project and what aspects they’d wish to add or want. throughout the entirety of this project, I prioritized feedback, and constructive criticism of what I could do better for the project. 
However, I constantly learned new things about the project and the community throughout this project. 

#### Issues I ran into that for the First Draft

A central issue I ran into with the first draft of the project was my lack of information about it, including whether CloudStream was a streaming service in itself or just a video player. My misconceptions about the Issues tab stemmed from my lack of experience with the project and a lack of communication between me and the project's primary maintainers. 

<a id=”one-first-draft”></a>
### First Draft Completion and Community Review: 
#### Initial Reaction: 
There was an error on the initial draft of the project, which was an expert that I took from the primary docs. It seemed like something that could sell the project to first-time viewers and engage them to read more. However, I didn’t realize the double meaning, which was shortly brought to my attention by the maintainers/developers. 


It was slightly embarrassing then, And I immediately got to work, trying to fix that error and the other aspects of the project. 
#### Fixing my mistakes:

I decided to look deeper on cloudstream on their stance on piracy, and after digging around, found their DMCA and EMUD, on their orginization’s Github page: [recloudstream](https://github.com/recloudstream) I quickly attempted to fix the header’s mistake and took some time, attempting to refine and communicate what cloudstream is; in particular and their current stance on piracy, however, due to feedback, I knew it was an video player, but I didn’t know any words to use to help spark interest in the repository. 

<a id=”#one-second-draft”></a>
### Second Draft and Maintainer Review: 
#### Asking the Community/Maintainers about the project:
I decided to ask the devs/maintainers, since they have worked on and was more in touch with the community, too describe what the project meant to them (Do not mind Candy Plug, He’s an Troll):



Also, when I proceeded further, they gave me some good examples of extension links and what legal extensions CloudStream endorses. 


#### Creating the second draft:

With the following information, references, and questions mainly answered, I returned to work to create the second draft of the READ. For the READ.ME file, I mainly attempted to refine the header and ensure it was presentable and that the tone *to an extent* was professional and neatly laid out with precise information and information on our stance on copyright, and opened communication between them I also used it to get rid of headers and links to the recommended sources and refine certain aspects to make it less wordy. 
#### Maintainer (Yapper) Review: 
After a day and class had passed, I logged back on to see that Yapper (One of the project's primary maintainers) had reviewed my second draft; the following are their GitHub comments and review of my program. I’ll review what was requested to change and why or where it could initially originate as a problem. 




That along, with many other aspects of the Read.me needed to be simple and condensed,
A general typo in the program made it seem that the steps to install would be customizable; his suggestion would help clear that issue. 
I didn’t know this information, mainly because one of the maintainers said earlier that there were no rules. I had looked at the issue template and condensed those into points in the earlier versions without knowing there was a template to base it on instead. 

This also included many syntax fixes, such as missing periods, commas, typos, etc. 

And so I got to work, Mainly focusing on updating the header to be more readable and ensuring the discord link to the server was higher up on the READ.ME file, and completely overhauling the issue section to contain the links to the current templates. 

<a id=”one-third-draft”></a>
### Third Draft (Current): 
#### The Current Commit:
After looking through, reiterating an bit and then pushing the results to my pull request, this is my updated Read.me: 


#### What Next? 
I have not gotten a reply as I write this, and I don’t think this will be brought into main. If they wish to edit it or request me to work on the content again, I’d gladly help ensure that the project is given the attention it deserves. Over winter break/spring semester, I may go back to help work on the app part of the project or work on the READ.ME if requested. 

Ultimately, I’ve learned much from this experience about development, writing for clients or communities, and the review process. It has been a very enlightening experience, and I wish to do it again soon. 

<a id=”one-footnotes”></a>
## Part 1: External Community Code Project Footnotes and References:

+ [Top Streaming Statistics In 2024](https://www.forbes.com/home-improvement/internet/streaming-stats/) 
+ [redcloudstream](https://github.com/recloudstream)
+ [My Fork of Cloudstream](https://github.com/KaiKitKobold/KaiKitForkcloudstream)
+ [My CloudStream Pull Request](https://github.com/recloudstream/cloudstream/pull/1004)
+ [CloudStream: Repository](https://github.com/recloudstream/cloudstream)
+ [Organization: redcloudstream](https://github.com/recloudstream)

<a id=”internal-community”></a>
## Part 2: Internal Community:
Again, to quickly preface, here are the links to my pull requests/issues that I’ve worked on for the internal community.
Here are the issues I attempted to resolve.
+ [Add Dart Implementation for Singleton](https://github.com/nic-dgl104-winter-2024/pattern-library/issues/6#event-12222096709)
+ [Create an appropriate folder structure in the repository](https://github.com/nic-dgl104-winter-2024/pattern-library/issues/1)
And here is my initial pull request:
+ [Pattern Library Folder Structure: Includes: Folder Structure + Dart Implementation](https://github.com/nic-dgl104-winter-2024/pattern-library/pull/42)
And my updated pull request: 
+ [Fixed HyperLinks to Rest of Repository. And updated folder structure](https://github.com/nic-dgl104-winter-2024/pattern-library/pull/60)

<a id=”two-code”></a>
### Code
While I could reiterate what I learned about Singleton and write an essay about it, it’d be much easier to go to the pattern library and look at the [READ.ME Document for Singleton](https://github.com/nic-dgl104-winter-2024/pattern-library/tree/main/patterns/Creational/singleton/Dart)

Instead, my Pull request document if the initial folder structure also showcases what the commit includes. 

<a id=”two-docs”></a>
### Documentation and Review: 
How I helped with documentation includes: 
	+ Added Documentation For Singleton Dart 
	+ Helped provide a Table of Contents for Quick Access throughout the repository/library 
	+ Helped communicate clearly with others in issues and helped give my support or ideas about projects.
	+ Helped provide a Framework for Folder File Structure. 

<a id=”two-footnotes”></a>
## Part 2: Internal Community: Footnotes & References 

+ [READ.ME Document for Singleton](https://github.com/nic-dgl104-winter-2024/pattern-library/tree/main/patterns/Creational/singleton/Dart)
+ [Fixed HyperLinks to Rest of Repository. And updated folder structure](https://github.com/nic-dgl104-winter-2024/pattern-library/pull/60)
+ [Pattern Library Folder Structure: Includes: Folder Structure + Dart Implementation](https://github.com/nic-dgl104-winter-2024/pattern-library/pull/42)
+ [Create an appropriate folder structure in the repository](https://github.com/nic-dgl104-winter-2024/pattern-library/issues/1)
+ [Add Dart Implementation for Singleton](https://github.com/nic-dgl104-winter-2024/pattern-library/issues/6#event-12222096709)
