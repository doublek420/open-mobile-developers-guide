# Things newcomers to open source rarely ask but often wonder 
Source: [OpenSource.com](http://opensource.com/life/14/2/newcomer-frequently-asked-questions)

*[Open Source Comes to Campus](http://campus.openhatch.org/) is an event series run by [OpenHatch](http://openhatch.org/) that introduces college students to open source tools, projects, and culture. Whenever we get a new-to-us question at an event, we write it down and answer it more fully on our blog. Here’s a collection of "Infrequently Asked Questions" that are especially relevant for newcomers to open source projects*.


**Q: I’m worried that I’ll be a burden on a project because I’m so new. What kind of effort does a project have to make to build an open source community**?

**A**: First of all, you should know that expert open source community builders like Linus Torvalds understand this tension between training new contributors and the time it takes from existing maintainers to mentor them. I’ll quote two paragraphs from [a 2004 post Linus made](https://lkml.org/lkml/2004/12/20/255) on the Linux kernel list:

> On Tue, 21 Dec 2004, Jesper Juhl wrote:

> Should I just stop attempting to make these trivial cleanups/fixes/whatever patches? are they more noise than gain? am I being a pain to more skilled people on lkml or can you all live with my, sometimes quite ignorant, patches? I do try to learn from the feedback I get, and I like to think that my patches are gradually getting a bit better, but if I’m more of a bother than a help I might as well stop.

> Linus replied:

> To me, the biggest thing with small patches is not necessarily the patch itself. I think that much more important than the patch is the fact that people get used to the notion that they can change the kernel—not just on an intellectual level (“I understand that the GPL means that I have the right to change my kernel”), but on a more practical level (“Hey, I did that small change”).

Another thing to keep in mind that is, for most projects, the project leader is the only contributor ([source](http://mako.cc/writing/hill-when_free_software_isnt_better.html)). Consider this: The act of bugging them with questions as a newcomer can make them more enthusiastic about the project as a whole!

If it were trivial to build an easily accessible open source community, virtually all projects would do it. There is some effort involved. Of course, a lot of the work that makes a project welcoming to newcomers—good documentation and setup guides, a well-maintained issue tracker, active development, standards of conduct in the community—makes the project better for everybody. But it does take time and energy, which many communities of projects aren’t willing to expend. That’s why OpenHatch exists! We know that some projects put more effort into welcoming contributors, and we want to help you find those projects.

The kinds of projects that welcome newcomers don’t see you as a burden. They see you as a huge help—even when you’re struggling to understand bugs in the issue tracker or get the development environment set up. When you ask a member of an open source project for help, that gives them important information about what part of their project is confusing or incorrect. The questions you ask and guidance you need lets them know how help others later on. And of course, once you’ve gotten familiar with the project, you’ll be able to help even more. The right kinds of project see that potential in you and want to work with you to get there.

Two rules of thumb for people who worry about being too much of a bother (which includes us, sometimes!): First, if people on the mailing list or the bug tracker haven’t told you to stop talking, then you’re probably okay, even if they haven’t replied to you yet. Second, if you want another opinion, just join the #openhatch IRC channel and ask us.

**Q: How do open source projects review changes, and how do those changes differ from a process like that of Wikipedia**?

**A**: One key cultural element of Wikipedia, at least so far in its history, is that anyone’s edits to English Wikipedia immediately become part of the live version of the encyclopedia. By contrast, to maintain quality, open source projects typically permit only a handful of people to *directly merge* changes into the main project. Therefore, submitted changes go through review.

Different communities have different standards and processes. Sometimes, there is no review at all, just automatic merging by the maintainer. In other cases, like Linux, submissions go to a mailing list [for review](https://www.kernel.org/doc/Documentation/SubmittingPatches). Others, like the OpenHatch web app, use web-based tools like GitHub pull requests. A great reference for a more complicated process is the [OpenStack Gerrit Workflow documentation page](https://wiki.openstack.org/wiki/Gerrit_Workflow).

**Q: How do you make time to contribute to open source when you’re a busy student**?

**A**: By simply using open source programs, you are uniquely positioned to help other users. Don’t forget that helping people use the software is a substantial contribution to the community! By becoming an expert in whichever programs you use, you will also gain the knowledge to help convert bugs filed by others into actionable reports for the main developers. And once you reach that point, you might find it easier to just fix the issue!

That said, it can be daunting to add another activity to schedules already stuffed full of classes, paid work, and student life. One way to approach open source is to see it not as an alternative to doing schoolwork but as part of your education. For computer science majors, open source projects are a great way to practice the concepts you’re being taught in class. In the others sciences, learning how to use and contribute to open source tools such as R or Octave (or ImageJ or PsychoPy or JMARS) can help you excel when doing laboratory work—and it looks great on your resume. Even in the arts and humanities, learning about open source tools such as Processing can help you succeed.

For students who work while they’re at school, open source projects can be potential employers. You can apply for [Google Summer of Code](http://www.google-melange.com/gsoc/homepage/google/gsoc2014) or the [GNOME Outreach Program](https://gnome.org/opw/) and do a paid internship at an open source project. Individual companies working with open source may hire students that show enough interest and ability. You can even employ yourself using open source—for instance, you could do freelance work making websites and applications by using open source tools like WordPress and Drupal.

You can make open source a part of your social life as well. Join (or start) a Students For Free Culture chapter on your campus or invite friends over for a ‘bug-fixing party’.

Finally, remember that your contributions to open source can be as big or as small as you want them to be. If you only have time to spend a few hours a month writing documentation or fixing small bugs in a project, that’s great—the skills you’re learning and connections you’re making will serve you well if you ever decide to get more involved.

**Q: What is the difference between source downloads for developers and downloads for users? What’s a stable release**?

**A**: Open source projects often release the program in a few different ways. Typically, if you are trying to contribute, you will want the latest source code cloned or 'checked out' from the project’s version control system. If you are just trying to use the program, you typically want a user-oriented download.

Many programs’ source code can’t be executed directly on a computer—it must be 'compiled', which turns it from human-readable text into machine-executable binary. The most common languages where this is true are Java, C, and C++. Therefore, the most useful download for a person who wants to run a project like OpenOffice, which is mostly written in C++, would be a compiled version specific to their operating system (for example, a Windows-specific build). By contrast, if you want to contribute to the program, you should act similarly to how the main developer acts—that is, by using a version control system on the editable program text, the source code.

Another important concept is the stable release. During development, people make contributions that break the program, conflict with other changes, or are simply unfinished. At any given point the most recent version might be completely unusable. So, maintainers periodically work towards releases (noun), which are tested to make sure they’re usable. If they are, maintainers release (verb) it.

So if you’re a user, you’ll want the stable release most appropriate to your operating system and computer. If you want to contribute, you’ll want the latest, non-compiled version.

**Q: Are all open source projects welcoming to newcomers? How can you tell when the communities around a project are filled with jerks**?

**A**: Not all open source projects are welcoming to newcomers. Not all open source projects need to be. Some projects benefit from keeping their communities small and experienced. And, some maintainers simply don’t have the energy or the inclination to mentor new people.

There’s nothing wrong with that, but it’s a shame when newcomers try to get involved with a project that isn’t interested in involving them. It’s a frustrating experience for everyone and unnecessary when there are plenty of people who’d be excited to work with them.

So how can you find a good project for you, a newcomer, to contribute to? Here are some good signs to look for:

- A large, active community is more likely to have members who can take the time to mentor. It also means that contributions will be acted on more quickly.
- Good documentation and demos mean that developers have thought about how to introduce people to their project.
- Some projects have [Codes of Conduct/Diversity Statements](https://openhatch.org/wiki/Project_codes_of_conduct), which demonstrate that the community is trying to be a safe and welcoming space.
- Projects that are part of [Google Summer of Code](https://developers.google.com/open-source/soc/) or the [GNOME Outreach Program for Women](https://wiki.gnome.org/OutreachProgramForWomen) have made a commitment to being good environments for newcomers.

At OpenHatch, we try to identify projects that are especially good for newcomers. We’re also developing a list of [OpenHatch-affiliated projects](https://openhatch.org/wiki/OpenHatch_affiliated_projects) that are working with us to make contributing to their projects as easy as possible. (If you’d like to be on that list, let us know!) Feel free to contact us and ask us for recommendations or if a particular project is known to be good for newcomers.


Of course, there’s a difference between not having the time and energy to help newcomers and being actively mean or even abusive about it. If you experience the latter and our comfortable telling us about it, we’ll do our best to support you. OpenHatch people are always willing to provide advice on projects to join, either to help you find a great experience or to make the most of a bad experience. Find us on on IRC (#openhatch on irc.freenode.net) or email us at hello@openhatch.org. You can also join groups such as [Systers](http://anitaborg.org/get-involved/systers/) or the [Empowermentors Collective](http://blog.thesilentnumber.me/2013/03/upcoming-first-meeting-of.html), which may help you navigate the free software community.

### More resources

This article has been a collection of information gathered during Open Source Comes to Campus events:

- [Infrequently Asked Questions: Wellesley College](http://openhatch.org/blog/2013/infrequently-asked-questions-wellesley-college/)
- [Infrequently Asked Questions: UMass Amherst](http://openhatch.org/blog/2013/iaq-amherst/)
- [Infrequently Asked Questions: Bloomington](http://openhatch.org/blog/2013/infrequently-asked-questions-bloomington/)

Read more posts about this [event series](http://openhatch.org/blog/tag/osctc/) on our blog.

For blog posts about getting involved with OpenHatch, read about the experiences of two of our contributors: [Britta](http://openhatch.org/blog/2013/how-i-found-an-open-source-project-for-me/) and [Mandar](http://openhatch.org/blog/2013/meet-mandar-an-openhatch-contributor/).