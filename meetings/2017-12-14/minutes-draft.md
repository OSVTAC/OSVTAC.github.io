Draft Meeting Minutes: December 14, 2017


<div id="meeting_header_right" class="headered">
Elections Commission<br>
City and County of San Francisco<br>
Don Chan, Secretary<br>
</div>

<div class="headered">
Open Source Voting System Technical Advisory Committee<br>
Christopher Jerdonek, Chair<br>
Larry Bafundo, Vice Chair<br>
Carl Hage<br>
Roan Kattouw<br>
Tony Wasserman<br>
</div>

<div id="meeting_header_main" class="headered">
MEETING MINUTES (DRAFT)<br>
Open Source Voting System Technical Advisory Committee<br>
of the San Francisco Elections Commission<br>
Thursday, December 14, 2017<br>
6:00 p.m.<br>
City Hall, Room 421<br>
1 Dr. Carlton B. Goodlett Place<br>
San Francisco, California 94102<br>
</div>

**Order of Business**


**1\. Call to Order & Roll Call**

Chair Jerdonek called the meeting to order at 6:05 p.m. Present: Members
Jerdonek, Kattouw, and Wasserman. Member Bafundo was excused absent. Member
Hage arrived late at 6:15 p.m during item #4. Also present: Secretary Chan.

**2\. General Public Comment**

Ms. Mirka Morales mentioned election integrity news in various parts of the
country. Alabama got a court order to preserve digital ballot images. Florida
was going to do a manual recount of a 2016 election, but found those ballots
to be destroyed. She mentioned these because the issue of ballot integrity
also needs to be addressed for San Francisco.


**3\. Approval of Minutes of Previous Meeting**

Member Wasserman noted that he was named as the member to report at the
Elections Commission’s January and February meetings, but it should say that
he is available for the meetings and not necessarily selected to go.

Member Kattouw said that he was responding to questions raised by Chair
Jerdonek regarding his use of the word “reproducible.” Chair Jerdonek said
there shouldn’t be an ellipsis there.

The term "LibrePlanet" has no space between the word parts.

The conference held in Southern California is called SCALE (followed by an
ordinal).

Member Wasserman moved to approve with the discussed edits. Member Kattouw
seconded. Upon voice vote, the motion carried unanimously, 4-0.


**4\. Member Reports**

Chair Jerdonek will be speaking at a conference at UC Hastings College of Law
in January and a conference in May, which is the same as last year’s Global
Election Technology Summit. He mentioned the template document from Slalom
and said that the content given should be viewed more as a placeholder rather
than true content.

There was a short discussion around some of the open source software that
Member Hage investigated (e.g OpenCount) and some of the problems he
encountered trying to run them. OpenCount is written as a monolith. Prime III
has leveraged other open source packages, but it “looks like a student
product.” An interface was mentioned that called a “low error-ability
interface.” It is supposed to reduce the amount of user error.

Members discussed how Prime III did and did not work (e.g. ballot images, QR
codes, and use in municipal elections). Member Hage said the Open Voting
Consortium (OVC) had done a demo with Santa Cruz using it.

Member Wasserman mentioned a Mozilla speech recognition project. He mentioned
Helios, an online open source election system for smaller organizations.

Member Hage said he reached out to one of the creators of OpenCount to see if
he can get the documentation for that program. Asked if these should be used,
Member Hage said maybe as models but not directly. He also mentioned briefly
a commercial vendor (Clear Ballot) that is closed source but offers a COTS
hardware approach. It is not certified by California yet.

There was a short discussion around which browsers should be used for open
source voting, and what forms of ballots or alternative format ballots can be
utilized. (Member Kattouw described a process followed in a recent European
Parliament election.)

Member Hage can further develop this section and propose recommendations.

Chair Jerdonek reported that Colorado still hasn't open sourced its
risk-limiting audit software, possibly because of unforeseen issues. He
mentioned that in his investigation of GPLv3, there are step-by-step
instruction to follow, and it is recommended that the license be issued from
the very beginning of program development.

He referred to the Slalom report (in the packet) in regards to the open
source governance model. This was discussed briefly, including not using the
term “dictator” because it could be misconstrued.

Public comment: None.


**5\. Administration**

Member Wasserman cannot attend TAC's next meeting if it is held the second
Thursday in January. Chair Jerdonek felt it preferable to have all present,
so the third Thursday would be looked at first.

Regarding licensing, Member Kattouw wasn’t able to reach his lawyer colleague
to get details. However, he said that Chair Jerdonek had included some things
in the document related to this topic. Chair Jerdonek put license text in the
document for GPLv3 and CC-BY-SA 4.0. The committee probably doesn’t need a
formal contributor license agreement (CLA).

The committee reviewed the Report #2 draft prepared by Member Bafundo.
Comments and suggested edits included:

* Minor typos in the document.
* List all four committee meetings.
* No need to attach minutes. Just provide a link.
* The link in the second paragraph should be on the “About” page.
* Remove mention of Member Wasserman speaking in Bangalore.
* Member Kattouw attended a conference in Berkeley (Take Back the Vote) that
  Chair Jerdonek spoke at.
* Member Hage is participating in a NIST working group related to elections
  data and interoperability, but not representing the Committee.
* Mention that the Committee adopted a policy to encourage members to educate
  others on open source voting.

In the Recommendations section, Member Wasserman offered, “the TAC continues
to work on a recommendation document that aims at providing guidance to the
City for developing an open source voting system.”

Chair Jerdonek: in the second sentence, “this document is being developed
iteratively and in public view on GitHub in the same way that open source
projects are developed.”

Add another paragraph mentioning that the Committee established a policy to
license their document and code. Also add a sentence providing a link to
where the latest version can be found.

Remove the quotes around "recommendation document" in subsequent mentions.
Choose a title for the document. Verify the spelling of Jessie’s name. There
is a typo in the second paragraph, third line: “specifying everything in a
request...” In page two, change, “It has learned that Colorado...” to
“Colorado...”

In the last sentence starting, “Texas has abandoned open source voting,”
change the last part to, “due to the lack of a complete combination of RFP
responses.” In the part about building awareness, name the two upcoming
conferences. The report should also have only one attachment, the
recommendations as of tonight.

Public comment: Ms. Mirka Morales asked if anyone knew when Los Angeles was
going to start using their new system. Also, is their “tally” system going to
be used for all voters or just a portion?

Chair Jerdonek said that at a previous meeting he said that the LA County
Registrar said that the stack would be open source but that the code would
merely be publicly owned.

There were no other edits to be added. Chair Jerdonek said he will add in the
date that he sends the revised document. Member Kattouw moved to approve the
document with the edits. Member Wasserman seconded . By voice vote the motion
carried unanimously, 4-0.


**6\. Committee Goals and Assumptions**

(This and the following agenda items #6 through #10 relate to the Committee’s
recommendations document on their GitHub site and the agenda packet documents
that relate to each section.)

No discussion took place for this item.

Public comment: None.


**7\. Project Background and Terminology**

Chair Jerdonek had two patches submitted, one related to the Voluntary Voting
System Guidelines (VVSG) being updated and one adding a few terms. There was
a short discussion about the term "outstack" (ballots not recognized by the
machine and separated out for manual review).

There was a question about how the VVSG could be required if they are called
"voluntary." Chair Jerdonek said it might have to do with whether the State
or Federal certification process is being used.

Member Hage will put together a subset of what he wrote for tonight, for this
section. He’ll also do a description of what Prime III is and how it works.
Chair Jerdonek moved to adopt the changes in the two documents. Seconded by
Member Hage. By voice vote, the motion carried unanimously, 4-0.

Public comment: None.


**8\. Project Management and Procurement**

The Committee has not received the materials from Jessie Posilkin yet. Chair
Jerdonek will follow up with Member Bafundo about this. For now, he wanted
TAC to adopt a statement acknowledging that parts of San Francisco City
government are interested in using agile, and that it would make sense for
the Department to work with them in implementing agile for this project.
Another statement is that if we are going to have an interim stage where we
scan ballots using third-party software, we need a way to get a layout of the
ballot in a structured format. This could be a human-assisted process.

The Committee discussed ballot format software, ballot layout creation
software, and what would be produced by it. Member Hage asked if the City
uses GEMS software. No, it is Dominion’s system. There were comments about
making auditing an early, and parallel portion of the initial phase of
development, rather than later. Member Wasserman also commented that there
shouldn’t be a hyphen between the words open source.

Public comment: Ms. Mirka Morales raised the question of whether San
Francisco would use two different ballots -- some with QR codes and some
without.

If the City uses pre-printed ballots, they would not be able to use QR codes.
However, if the ballots are on-demand, they could. This is a topic the
Committee can weigh in on.

Member Hage thought the Committee could make a list of all the major decision
points, options and issues, to be added in the Recommendations section.

Member Wasserman asked if we wanted to have a goal that the system could be
operated manually, for example in case of power failure.

Member Kattouw moved to approve the two patches with edits, seconded by
Member Hage. Upon voice vote the motion carried unanimously 4-0.


**9\. Committee Recommendations**

Chair Jerdonek reviewed Member Bafundo's suggestion at the last meeting to
take sections of the document and work on it at the meeting, so he selected
this section for review, as well as submitting two patches for it.

Suggestions: countermeasure has no hyphen. Chair Jerdonek said if the
Committee hasn’t already made the statement, it should say that all of the
system should be open source.

Member Hage suggested that the computer equipment use a secure boot and that
the secure boot recognize a digital signature (e.g. from the California
Secretary of State).

The Committee discussed the issue of having trusted hardware versus software
and how jurisdictions could verify that the software is the same (e.g. as
binaries). One issue is securing the hardware (e.g. storing the machines so
they are not tampered with). Member Wasserman mentioned the cloud and posited
that there are implications to the development process. For example, how
would one specify the build environment in that case?

Chair Jerdonek referred to the second patch regarding having test data
separate from the underlying code. Two points were expressed: having digital
ballot pictures from elections, and keeping the test data separate from the
actual code (e.g. which would more easily permit multiple implementations of
the same software component). The Committee discussed various elements of the
testing process and quality assurance in general.

San Francisco's current system does not have a built-in capability to produce
digital ballot pictures, so an extra scanner would need to be used. Also,
since election ballots are sealed, the scanning could not be done later.

Member Kattouw moved to adopt the patches with edits, seconded by Member
Hage. Upon voice vote the motion carried unanimously, 4-0.

Reviewing the Recommendations section of the document: Chair Jerdonek said
the section is currently divided into eighteen topic areas, with eight yet to
be filled in at all.

Member Hage suggested separating what he is preparing (decision points, pros
and cons, etc) from this large section, and having a more detailed
description of the incremental approach, modules, and the like in a separate
section.

Member Wasserman referred to sections 4.3 and 4.4 and suggested identifying
the different "actors" in the system -- e.g. all types of voters and the
kinds of things the system has to provide for them, as well as those who are
providing the service. This way the Committee could better cover all the
requirements the system needs to fulfill.

Possibly create a new section in the document that speaks to what needs to be
built: what title would that section have, or would it be part of background?

Member Wasserman discussed the value of identifying the user stories and the
personas who would be active in the context of the election system. If doing
agile he would recommend “sprints”: user stories and what will be implemented
in each sprint, starting with who’s involved and ending up describing the
work to be done in each step of the process.

Points brought up: sub-divide the background section and put this in there.
The incremental section is also getting unwieldy. Possibly title it: "Initial
Phase, First Components." Take section 4.2 and make it section 5.0. Add
audits as a category.

Regarding the central ballot scanner, mention having ballot batch management.
Separate the component descriptions out. Explain the functionality of each,
including a high-level description of what it does, the inputs, the outputs,
and the sub-components.

Chair Jerdonek suggested highlighting sections regarding the first phase
vis-a-vis the budget and timeline. Move the components section out and list
all of them regardless of the order in which they are needed. Should there be
a section for proposed components and proposed phases? Chair Jerdonek will
work on this for the next meeting.

The document needs an executive summary. The committee would need to discuss
what needs to be included. Members could bring patches to the meeting for
discussion and action and include them in the agenda packet. Member Wasserman
will work on user stories and context. Chair Jerdonek will break out the
phase descriptions. Member Kattouw will work on the “to-do” about elections
and find a place in the recommendations section for something regarding
reproducible builds and secure boots.

Member Hage, regarding section 4.6, suggested separating out sensitive code
from unsensitive code. One goal should be to minimize the amount of code.

Member Hage also raised the subject of revision control, saying that all
“intermediate files” should be in a format compatible with revision
inspection. Member Kattouw will review this with his other tasks.

Public comment: None.


**10\. Voting Process and Equipment Decisions**

Member Hage suggested a new section for the Committee’s document: one listing
decisions that have to be made, along with pros and cons and background
information. There is already some language on requirements gathering and key
decisions, but that could be combined with what Member Hage is working on.

Member Wasserman mentioned that the term "voting types" does relate to
personas. Member Hage agreed there should be a section like this.

The question was raised as to where to draw the line between questions the
Committee should answer and those the Department should.

Chair Jerdonek suggested that Member Hage take section 4.3.1 and merge it
with his draft, in a consistent format.

Member Kattouw mentioned the question of the type of printing devices
(requiring power, potential for jamming, etc) as one that needs answering or
recommending.

Public comment: Ms. Mirka Morales asked about AB 450: does the county have
the option to go directly to vote-by-mail, or does it have to use the vote
center process? She said that Los Angeles is moving toward vote centers, and
providing mail ballots only to those who are registered as permanent
vote-by-mail.


**11\. Topics for future discussion**

No topics were suggested.

Public comment: None.


**Adjourned at 9:25 p.m.**
