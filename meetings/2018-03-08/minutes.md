Draft Meeting Minutes: March 8, 2018

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
Thursday, March 8, 2018<br>
6:00 p.m.<br>
City Hall, Room 421<br>
1 Dr. Carlton B. Goodlett Place<br>
San Francisco, California 94102<br>
</div>

**Order of Business**


**1\. Call to Order & Roll Call**

Chair Jerdonek called the meeting to order at 6:10 p.m. Present: Members
Hage, Jerdonek, Kattouw, Wasserman. Member Bafundo arrived late at 6:30 p.m
during item #5. Also present: Secretary Chan.


**2\. General Public Comment**

None.


**3\. Approval of Minutes of Previous Meeting**

Member Kattouw moved to approve the February 18, 2018 draft minutes, seconded
by Member Hage. The motion carried, 4-0.

Public comment: None.


**4\. Administration**

Chair Jerdonek thanked Member Wasserman for doing a good job chairing the
February meeting in his absence. He wanted to answer some of the points that
came up then. 1) The Committee’s second report is due to the Commission in
May. 2) The TAC member reporting to the Commission should mention the
Committee’s approval of the wording and spirit of the RFP for the interim
system, for its nod to accommodating requirements of open source.

It was confirmed that Member Wasserman would present at the March 21 meeting.
Member Wasserman said he welcomed any input for the report he will give.

Chair Jerdonek asked Member Kattouw if he would draft the next written report
to the Commission. Member Kattouw said he would try and welcomed any help
from the other members.

Public comment: None.


**5\. Member Reports**

Chair Jerdonek reported that the City is in the middle of its budget process,
with departments submitting budgets to the Mayor’s office. The Slalom report
is still not available, but he heard that the report might be ready by the
next Commission meeting. The Mayor’s office is aware that money for an open
source voting system has not been put in the Department’s budget. They are
awaiting the Slalom report. Member Kattouw asked to be informed when it is
available.

Member Hage has tried using Open Count but it doesn’t seem to work. The
software might have limited usefulness.

Member Wasserman is awaiting approval of a talk he wanted to give at OSCON,
the week of July 17. Member Kattouw suggested that he and Member Wasserman
could collaborate on their upcoming talks. Chair Jerdonek can provide the
slides he used in his past presentations.

Chair Jerdonek answered a couple of questions that came up in February’s
meeting. One was how the Department sorts its vote-by-mail (VBM) ballots. The
other was what happens in case of a power outage during the elections.
Regarding publishing the RCV ballot image data, he said that was voluntary.
On the question of the 1% public manual tally, in addition to selecting 1% of
precincts, the State also allows selecting VBM ballots by "batch." Regarding
the size of ballot cards, there is no standard size.

Member Bafundo summarized his report to the Commission at their February
meeting.

Public comment: None.


**6\. Project Background and Terminology**

Member Hage reported updated information about the Prime III project, which
New Hampshire modified and is calling “One for All.” He said they have
promoted it to the California Secretary of State, but he can’t find anything
on their source code. He asked if Chair Jerdonek could contact New Hampshire
to inquire. They proposed several questions to be asked.

Public comment:

Mr. David Cary spoke for the California Clean Money Campaign and encouraged
the Committee to do whatever they could to facilitate the State’s approval to
allocate funds for the development of the open source voting project in San
Francisco.

Mr. Jim Soper reported on a State hearing on cybersecurity in elections. He
commented that Dean Logan (LA County) said their project is based on an open
source "platform," but they are not making their source code available for
review. He encouraged the Committee to contact Assemblymembers David Chiu and
Phil Ting, both representing San Francisco, to support the project.

There was a short discussion about Los Angeles County's use of the word
"platform" and not "software," as compared with San Francisco's position of
making the software open source and openly developed from the start.


**7\. Project Management and Procurement**

Member Bafundo offered to get resources from the US Digital Services (USDS),
but he felt that the Committee already had enough to describe an approach and
recommend sequencing pieces of the system as it related to a procurement
strategy.

Member Wasserman mentioned a Patrick Stoddard (USDS) who works with groups to
do agile procurement. It might be worth following up with him. Chair Jerdonek
said that while the Committee has recommendations on the sequence of
components, it doesn't yet have information on the process of agile
procurement in how-to form. Member Bafundo said that Jessie Posilkin’s work
with Alaska is available in a public GitHub repository, so he can summarize
it. Chair Jerdonek asked him to possibly draft some text for the Committee’s
document.

Public comment: None.


**8\. Equipment Decisions and Implementation Plan**

Chair Jerdonek reviewed one "diff," which re-organizes how some of the
sections are in the Committee’s document. He suggested changing the term
ballot layout analyzer to ballot layout encoder.

Member Kattouw moved to approve the diff, seconded by Member Wasserman. The
motion carried 5-0.

For the second diff, Chair Jerdonek explained some of the changes in the
language around accessibility, to change the focus from use by people with
disabilities to everyone being able to use it. He discussed a new “pro” being
that if everyone used the same method to vote, their voting experience would
be the same. Another would be that the use of the machine would remove the
appearance of ambiguous or erroneous marks that demanded adjudication. This
remark would go in section 6.4.

Member Hage moved to approve this document with the revisions, seconded by
Member Kattouw. The motion carried 5-0.

Chair Jerdonek summarized the letter he drafted to the Commission that
highlights things the Committee believes the City should work on in the first
year but is specific to the budget process. He is going to ask the Commission
to approve sending the letter to appropriate individuals.

There was a discussion regarding subject and terminology in the letter, e.g.
calling someone a project lead versus a product or project owner, and how
salary levels should be competitive for the industry. There was a question
regarding the wording in the first of the five reasons, so it was changed.
Overall, the document was received positively.

Chair Jerdonek will put it on letterhead. Member Kattouw moved to approve the
letter with the discussed changes, seconded by Member Hage. The motion
carried 5-0.

Public comment: None.

There was a short discussion regarding ballot selection and printing and
specs, but it did not impact the motion. Member Wasserman will give a
statement about this letter in his report to the Commission.


**9\. Committee Recommendations**

Member Hage reviewed the PDF he submitted for section 5.3.2 that defined and
suggested ways cryptography could be used for the benefit of a voting system.
It was felt that this section was better put into an appendix that can be
referred to when looking at the recommendations.

Member Hage discussed the various things that could or should be done for
chain of custody for things like documents and log files to help make them
secure. This includes using digital signatures on several levels, files
within files (e.g. archived zip files), "jar files," and similar techniques.

He was asked if NIST was discussing the use of these methods. Member Hage
said they are only talking about using XML files for data exchange.

Member Kattouw wanted to review the document in more detail. Chair Jerdonek
suggested using the heading “Digital Security” for this appendix.

Member Hage said he thought there should be a recommended plan of how data
security and cryptography should be used. This could be part of the
requirement specification for producing all of the software. It could help
ensure data security and integrity all the way from input data.

There was a discussion related to encrypted PDF's and the extent to which
they could be viewed as an open format, as well as read and creaetd using
open source software.

Public comment:

Mr. David Cary said that when the Committee looks at recommendations for
security and cryptography, it should keep in mind what is being worked on by
VVSG 2.0 and NIST, so they are compatible. Member Hage is a part of that
working group so is familiar.

Mr. Jim Soper said several years ago there was a study on end-to-end
verifiability. He will send a summary of that to the Committee.

Member Wasserman commented that when the Committee makes recommendations they
should be more on the “why” and not the “how” so it doesn’t get too far into
prescriptive directions.

Member Kattouw mentioned the event DEF CON in Las Vegas where it was shown
how voting machines could be hacked. Member Wasserman mentioned that the RSA
conference will be in San Francisco the week of April 16.

There was some discussion of secure boot and reproducible builds, which
Member Kattouw had previously volunteered to draft language for. Chain of
security was discussed, including its relationship to certificate authorities
(CA's) and root CA's, etc.


**10\. Topics for future discussion**

Chair Jerdonek raised the question of whether it was legal to transport
people to precincts where accessible voting machines were available.

Member Kattouw said he was supposed to write a couple things, including a
recommendation related to using shims for the testing of software libraries.
He will try. He asked if the Committee could take any actions to help in
getting funds for open source. As a committee, no, but as individuals yes.

Public comment: None.


**Adjourned at 8:12 p.m.**
