Draft Meeting Minutes: September 21, 2017

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
Thursday, September 21, 2017<br>
</div>

**Order of Business**

**1\. Call to Order & Roll Call**

Chair Jerdonek called the meeting to order at 6:02 p.m. All members were
present at the gavel.

**2\. General Public Comment**

None.

**3\. Approval of Minutes of Previous Meeting**

Member Kattouw pointed out a couple of mistakes. In regards to Colorado
seeking a license for their risk-limiting audit (RLA) system, it should not
be identified as a GPL v3 license. Member Wasserman pointed out a grammatical
error in #9 “When about international….” Should be corrected. With these
corrections, Member Kattouw moved to approve the minutes, Member Wasserman
seconding. Upon voice vote, the motion carried unanimously.


**4\. Member Reports**

Chair Jerdonek mentioned the SF Chronicle article on open source voting (the
reporter attended the last Committee meeting), which was positive. He then
referred to the document (in the packet) which addressed Member Hage’s
question about the cost to run an election in SF. There was a short
discussion about specific items in the table: contract amounts vs general
costs, numbers of elections and precincts.

There was a question raised about a Tecla switch (in the presentation on
accessible voting) and Member Hage mentioned standards being drafted by the
EAC (Elections Assistance Commission) that might include this element).
Member Wasserman asked if we might set a requirement that the contractor (for
SF) have thorough knowledge on disability access so that their project
incorporates that from the onset.

Chair Jerdonek said that the Committee members wouldn’t be using the GitHub
site (for working with content) until the “Sunshine” implications are cleared
up, but they can work on their own profiles if they want.

Member Kattouw reported he would be going to New Hampshire on personal
business in the next couple of months, so if the Committee wanted him to
touch base with the people working on their open source voting system, he’d
be happy to. He asked if Committee members could issue “poll requests”. He
asked what the term “re-making ballots” means (heard at the Elections
Commission meeting. Member Bafundo explained what he’s seen in the LA process.

Member Hage mentioned what the working group of the NIST was developing in
terms of definitions. He said he searched and found that the voting machines
San Francisco uses are from ESS, which was bought by Dominion. He described
the steps the machine takes in the voting process. He went on to describe
what different locales are doing vis a vis open source voting;

1. Colorado is doing a risk limiting audit where they are using uses a
contractor (Free and Fair) who uses Open Count software (a general-purpose
scanning tool) to rescan a statistical sample of ballots.

2. the LA system has a custom designed voting booth, which is still to be
made.

3. New Hampshire uses a paper ballot printer and counts choices
electronically, but it was only used for accessible voting.

4. The Travis Co. system is similar to Prime III, voting in precincts, but
can use a QR code to print the allot. It is just being proposed now.

Member Wasserman gave a short review of his report to the Elections
Commission last night.

Chair Jerdonek mentioned that he was speaking on open source, in Berkeley at
an October 7/8 weekend conference, and that Director Arntz expects the
contract with Slalom would get signed off in about 2 weeks. He noted LA
county had issued a document for verified or confirmed vendors; documents are
online.

Member Bafundo reported that the former Secretary of State of Missouri, who
consults with 18F, might be a good resource to have come speak to the
Committee or he could speak with her first and bring the points regarding
agile contracting and procurement strategies to the Committee.

It was stated that presenters before the Committee could present via video
feed, while Committee members could not participate via video. He also spoke
with Dean Logan of LA county and asked if he would share their software
solution design document created as part of their project, but has not heard
back yet. If they would it could help San Francisco get started as it’s very
detailed about various parts of its project.

Public Comment: Mr. David Cary said that Colorado’s earlier Risk Limiting
Audit process did involve re scanning ballots but that they had problems
tracking those images back to physical ballots.

Ms. Mirka Morales spoke of her observations from the March 2016 primary where
ballots were ‘re-made’. She also questioned the LA County procedure where
they will not do precinct level tallies, but just central. (It was clarified
that the LA system does not produce or record an electronic cast vote for
tallying, but prints out a paper ballot that is transported for central
tallying.

**5\. Administration**

Chair Jerdonek said that for now, he would do updates to the repository on
GitHub until later when it could be rotated to another Committee member to
do, to avoid multiple members working on the documents, which could look like
a violation of Sunshine. Individual members could do as Member Hage did, work
on something (a document), submit it to Chair Jerdonek to be included in an
upcoming meeting for discussion.

Member Kattouw suggested that more items be ‘farmed’ out to Committee members
so that it doesn’t all fall on the Chair to compose.

Committee representation at the Elections Commission meeting: Member Kattouw
will attend the October meeting, and Member Bafundo will attend the November
meeting.

The following dates for Committee meetings were proposed for the remainder of
the year: October 19, November 16, December 14.


**6\. Project Terminology and Resources**

(Discussions of items #6-9 are based on the documents in the agenda packet
that refer to each item)

Chair Jerdonek said that from the last meeting it was suggested that further
definitions/descriptions of terms were desirable. The Committee reviewed the
glossary of terms that Member Hage submitted for the item. There was a
mention of a white paper by LAFCO (Local Agency Formation Commission), but
LAFCO is not a body related to open source so should not be included.

Member Kattouw asked about 3b and said there is no reference to open source
in the LA County official documents, but they have made oral claims that they
want to be open source. Member Wasserman commented that many times projects
start off as open source but have added proprietary layers that can generate
revenues in the future. He mentioned the use of the Open Core model.

Member Kattouw moved to accept the document with the deletion of LAFCO as a
link, seconded by Member Bafundo. Upon voice vote, the motion carried
unanimously.

Member Bafundo commented that the text from HAVA (Help America Vote Act)
seems to infer preference for a particular hardware/software configuration (a
distributive tally model).

Member Kattouw felt that the description was of a more exhaustive model and
that anything less would just mean reducing the number of elements (hardware)
needed, so this could be written into the assumptions. Member Wasserman
questioned whether this could conflict with the object of using off the shelf
commercial hardware.

There was a discussion about whether the description of hardware was
prescriptive or limiting, and language was suggested to say that the
description is just a representation of the components found in existing
voting systems, but is not intended to constrain the choices that a future
implementation might make.”

Member Kattouw offered: to section 2.2.2 second paragraph…for simplicity, “we
assume for the purposes of this example,” add at the end of that section “we
further assume tallying occurs at the precincts.”

Member Bafundo suggested adding the ballot as a component. Member Kattouw
suggested this be written up for the next meeting.

Member Hage said the document does not mention the poll book. It was
mentioned that this is in conflict with the HAVA definitions.

Member Wasserman said that the software support for the accessible ballot
marking device isn’t mentioned in 2.2.2.

Chair Jerdonek offered to add: Accessible ballot marking device software (in
bold).

Asking for a motion to accept the terminology with edits, without the
glossary, Member Wasserman so moved, seconded by Member Kattouw.

The vote was called and the motion carried unanimously.

Public Comment: Mr. David Cary handed out a document that had select
terminology from the VVSG1.1 (Voluntary Voting System Guidelines) Glossary.
He said that the term Election Management System is something contained
entirely within the definition of a voting system. That is in contradiction
to how the Committee’s document uses it.

He further talked about incorporating ballot adjudication as a component of
the system. And a separate software component of an “event logger.”

It was clarified that adjudication of ballots was only for those needing
human intervention to resolve any questions of its markings.

Chair Jerdonek stated that the EMS that San Francisco uses is sold by DFM
(vendor).

It was suggested that the glossary Member Hage put together be used as an
appendix and include terms beyond the need of the document the Committee
creates (sort of a global glossary for open source elections), and one be
specifically made up of terms used in the text of the document.

Member Kattouw was surprised that there isn’t a definition of “outstacked
ballots” and suggested adding that.

Mr. David Cary suggested making this a proposed glossary “pool” where the
public could make comments and suggestions to.

Member Kattouw reminded Committee members that if they had items they wanted
added to this, they need to prepare them and submit them for that.

Mr. Jim Soper suggested having a definition of ballot image. There is one in
the Voluntary Voting System Guidelines.


**7\. Project Management and Procurement**

Member Bafundo asked if project management was going to focus specifically on
risk mitigation? He felt that this was related to #9 where that could be seen
as a product of project management. Chair Jerdonek explained that the overall
project management would be issues of how to do the various processes, eg,
how to let RFPs, in one large packet or in multiple smaller ones. Outsource
the management? How to course correct?

The Committee discussed what the boundaries of this were and what questions
had to be raised in order to address the different barriers to possibly
enlisting best practices, eg. the laborious RFP process of the City; how
could an effective contract be let to account for the many components that
need to be developed. How do the different bodies within the election process
(the Department, the Commission, the TAC, the vendors) relate to one another
to expedite best practices? There needs to be research done on the question
of what is possible within the constraints of the City’s processes.

Public Comment: Mr. David Cary felt that things needed to be developed for
the Department that they can handle (ie. in pieces), and that it is important
to look at procurement vis a vis the City’s processes to see how Agile
management can be employed.

The Committee discussed the need for a library to be used in project
development, and if the Committee needs to prescribe particular types of
hardware.

Member Kattouw moved to adopt the language of this section as is for the
present, seconded by Member Bafundo. Upon voice vote, the motion carried
unanimously.

Public Comment: Mr. Jim Soper commented that there are many people involved
in this concept and should be called in to hear about their experiences.

Ms. Mirka Morales said that looking at the scanning devices for ballots would
be important as in the future there may be relatively little precinct based
voting.

**8\. Committee Recommendations**

Chair Jerdonek explained that these items were assembled from various past
discussions, and in no prioritized order. These are the decision points and
not necessarily the decisions themselves. There is a distinction between
accessible voting and not-necessarily-accessible voting.

There was a discussion about preserving the privacy of the voter. The
question of license compatibility for different components was raised. In
relation to this was the re-use of previously existing software components.
Member Kattouw will work on language to include this topic. He suggested
further clarification to the term open source software language -- preferring
the phrase "programming language." He will also work on language for this.

The question was raised as to who would oversee and maintain the repositories
after they are developed, and when the code would be made available for review
during the process of development. Chair Jerdonek said that the section on
maintenance could be used to record ideas on this.

On the point of using actual voting data sets to test the program, Member
Kattouw mentioned the example of the Merced election. Such a data set could
be used.

On the question of open source’s security, it was felt that a discussion on
this issue should be included in the document.

Public Comment:

Mr. David Cary referred to “Assumptions” and suggested adding a section that
says “this is the foundation we are building on and here are the facts to do
it.” He further suggested taking out “end-to-end verifiability.”

Mr. Jim Soper said that end-to-end verifiability is far from realizable.

It was asked if elections ballots are kept for any length of time. The
answer is yes, but they cannot be opened without a court order.

Chair Jerdonek agreed with Mr. David Cary’s point about not making some
decisions very early on. He will change the language on that point and the
language regarding end-to-end verifiability.

With agreed-upon edits, Member Kattouw moved to accept this section. Member
Wasserman seconded. Upon voice vote the motion carried unanimously.


**9\. Incremental Approaches**

The meeting was re-convened at 9:16 pm.

Chair Jerdonek commented that these items are part of the system that could
be developed and implemented in “piecemeal” fashion rather than waiting to
activate as a total system, and that the Committee feels development and
implementation in increments is preferable. There was a discussion of SB 360
and what it allows. There was a discussion around defining data formats
required of the contractor, or allowing the contractor to do so.

Public Comment: Mr. David Cary encouraged the Committee to take a stand to
use incremental approach to the development of the system.

Member Kattouw moved to accept the language in this section. Member Hage
seconded. Upon voice vote the motion carried unanimously


**10\. Topics for future discussion**

Member Wasserman said to re-visit agenda items #6, 7, 8, 9 and proposed
changes to them. Member Hage said he’ll work on some items and post them
before the meeting. Member Wasserman suggested a report on the Berkeley
conference. He asked whether the Committee members should take a ‘low
profile’ or begin to develop a ‘talking points’ presentation. Member Hage
recommended reading the LAFCO report. Member Wasserman said he’d like to
review the winning proposal for the RFP, if available.

Public Comment: Mr. Jim Soper described a little more of what will be
happening at the Berkeley conference.

Mr. David Cary mentioned that according to Director Arntz, only the wining
proposal to the RFP would be publicly viewable.

**Adjourned at 9:56 p.m.**
