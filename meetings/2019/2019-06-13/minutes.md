Meeting Minutes: June 13, 2019 (approved November 14, 2019)

<div id="meeting_header_right" class="headered">
Elections Commission<br>
City and County of San Francisco<br>
William Walker, Secretary<br>
</div>

<div class="headered">
Open Source Voting System Technical Advisory Committee<br>
Christopher Jerdonek, Chair<br>
Roan Kattouw, Vice Chair<br>
Carl Hage<br>
Brandon Philips<br>
Tony Wasserman<br>
</div>

<div id="meeting_header_main" class="headered">
MEETING MINUTES<br>
Open Source Voting System Technical Advisory Committee (OSVTAC)<br>
of the San Francisco Elections Commission<br>
Thursday, June 13, 2019<br>
6:00 p.m.<br>
City Hall, Room 421<br>
1 Dr. Carlton B. Goodlett Place<br>
San Francisco, California 94102<br>
</div>


**Order of Business**

**1\. Call to Order & Roll Call**

Chair Jerdonek called the meeting to order at 6:06 p.m. Present: Members
Hage, Jerdonek, Kattouw, Wasserman. Excused absence: Member Philips. Also
present: Secretary Walker.


**2\. General Public Comment** (6:07pm)

None.


**3\. Open Source Voting Project Plan** (6:07pm)

Chair Jerdonek reported that Director Gerull had told him over email that the
community meeting has been rescheduled for July 19th at 2:30pm-5pm. He also
gave her the list of email addresses to contact that the TAC had
brainstormed, which came out to 55 addresses.

Member Kattouw asked how much money is allocated in next year's budget. Chair
Jerdonek answered that the latest he had heard was that the city will not
allocate additional funds, but will carry over the $1.5 million allocation
from this year, which was intended for two years. Chair Jerdonek opined that
this would not be enough for the Department of Technology to put out an RFP,
but enough to keep on the people that were hired, and a bit more. He also
pointed out that if the state matching funds proposal passes, this
already-allocated money would be eligible to be matched.

Member Wasserman asked if this would come up at the Elections Commission
meeting. Chair Jerdonek responded that the Mayor and the Board of Supervisors
are responsible for the budget.

Member Kattouw asked if the Department of Technology had requested additional
budget. Chair Jerdonek answered that they had made a budget request to COIT,
but he wasn't sure for how much, and he had heard that COIT wanted to wait
another year. (Later in the meeting, Member Kattouw discovered the request
was for $3 million.)

Public comment: None.


**4\. Approval of Minutes of Previous Meetings** (6:14pm)

This item was continued to the next meeting.


**5\. Administration** (6:14pm)

The members agreed to schedule the next OSVTAC meeting for July 11th.

Member Kattouw agreed to report on behalf of OSVTAC at the next Elections
Commission meeting on Wednesday, June 19th.

The members discussed the draft report prepared by Member Kattouw. Member
Wasserman pointed out that Director Gerull's name was misspelled; that he
attended SCaLE but did not speak there; and that he was the one to attend the
Clean Money Campaign event, not Chair Jerdonek. Member Wasserman suggested
the report should say that he attended a panel presentation by people
responsible for the Los Angeles County voting system.

Member Hage moved to adopt the report with these corrections; Member Kattouw
seconded.

Public comment: None

The motion passed. Ayes: 4 (Jerdonek, Kattouw, Hage, Wasserman); Noes: 0
(none); Absent: Philips

Member Kattouw agreed to prepare the corrected report in time for it to be
part of the agenda packet for the next Elections Commission meeting.

Chair Jerdonek corrected a statement he had made at the last meeting. He had
said that SCaLE was going to set up a committee to work on open source, but
he meant to say that Los Angeles County is starting a new advisory committee
to advise them on open source.

Chair Jerdonek reported that he had merged Member Kattouw's changes to the
recommendations document and the CLA. He said links should be added to the
CLA on the web site and from every project. Member Kattouw offered to propose
something at the next meeting.

Chair Jerdonek reported that there would be an agenda item to reappoint the
OSVTAC's members at the next Elections Commission meeting.


**6\. Member Reports** (6:26pm)

The members discussed a Politico article submitted by Member Wasserman,
describing a remote access feature that was revealed in voting machines made
by VR Systems and ES&S. Member Kattouw pointed out that ES&S wouldn't have
been able to lie about this feature for years if the code had been open
source. Member Hage pointed out that digital signatures enable tracking all
changes, and that the recommendations document doesn't talk about access
authentication yet. He suggested the TAC consider establishing policies for
machine access that are based on physical hardware keys as well as passwords.

Chair Jerdonek reported that AB1784 has passed the Assembly, and is now in
the Senate Elections Committee, but hasn't been scheduled for a hearing yet.
He reported that the California Clean Money Campaign is open to feedback on
the language. He had asked Director Gerull if the City had sent a letter of
support, and she responded that they had, about a week before it passed the
Assembly. Member Kattouw reported that he attended the Assembly Elections
Committee hearing for AB1784 on April 26th. New co-author Asm. Lorena
Gonzalez came to speak in support. The Clean Money Campaign brought about 30
supporters to the hearing, who spoke in support in public comment, as did
Member Kattouw. Nobody spoke in opposition.

Member Hage reported that he saw a notice on the Secretary of State's email
list for county elections officials on June 7th about the meeting minutes
from the Office of Voting System Technology Assessment (OVSTA). The meetings
mentioned a grant to Los Angeles County for VSAP. Chair Jerdonek pointed out
that this is likely coming out of funding that all counties get, for
proprietary voting systems. Chair Jerdonek also pointed out that Los Angeles
no longer says its system is open source, and instead says it's "built using
open source software."

Member Hage reported that he had seen an announcement that AB2125 from last
year authorizes risk-limiting audits in lieu of the 1% manual audit for the
March 2020 election. Member Kattouw pointed out that AB2125 is structured as
a pilot program that only applies to the March 2020 and November 2020
elections.

Member Wasserman reported that he was going to attend OSCON in Portland, OR,
and would be speaking on July 17th. The Linux Foundation's Open Source Summit
North America accepted a similar presentation proposal of his; no exact date
is set yet for his presentation, but it will be around August 22nd in San
Diego. Member Wasserman said he was planning to build on Chair Jerdonek's and
Member Kattouw's presentation materials, but that for this audience he wanted
to focus on the political, economic and social issues around doing open
source in a government setting.

Committee members offered to vote to authorize Member Wasserman to speak on
behalf of OSVTAC, but Member Wasserman declined.

Public comment: None.


**7\. Voting System Component Development** (6:51pm)

Chair Jerdonek reported that the TAC had a productive working meeting on June
8th, which lasted a little over two hours. Chair Jerdonek, Member Hage and
Member Kattouw attended.

Member Hage reported that Member Kattouw had sent him a link to his branch
with changes to add turnout information and had asked for help. He found that
the software doesn't load the summary data for turnout correctly, and said he
would work on fixing that, so that Member Kattouw can add turnout information
to the results reporter output.

Member Hage reported that he updated all the data loaders to all of the
missing data that is in the converted source data, so that all of this
information is now getting loaded, except for contest status, which he still
needs to review. He also filed some issues in the issue tracker for the data
converter.

Member Hage suggested that sample data could be generated by running the data
converter in a special mode that pulls out one normal contest, one RCV
contest and one measure. That way, small test cases could be generated
automatically, and would no longer have to be written manually. Chair
Jerdonek suggested it might make more sense to have a standalone script for
crafting test cases, more automated than hand editing but not full-blown data
conversion. He expressed concern that the vote totals wouldn't add up, and it
wouldn't be clear whether that was because of a bug or because it's sample
data. Member Hage responded that the data converter doesn't do any
computation currently, but that a special script could be written to correct
the totals. Chair Jerdonek agreed, but emphasized this script should only be
run on test data, not on real data. Member Kattouw said that he liked the
idea of using the data converter to generate the minimal test data, because
then the structure of the test data would always match that of the real data;
it's hard to keep the two synchronized with hand editing.

Chair Jerdonek said he would like to try to meet with Director Arntz again,
to ask for feedback. He suggested that, since the Department of Technology
staff assigned to the project aren't working with vendors to write code,
maybe they could be given the work of coordinating with the Department of
Elections to get them to use the TAC's results reporter software.

Member Hage asked if the new Dominion system is ImageCast Central. Some other
counties used this system in 2016, so they might be able to provide sample
data. Member Hage emphasized that, in order to be able to import data from
the November 2019 election as results are being reported, he would need to
know the data format in advance so that he can write a data converter. Chair
Jerdonek said the Director understands this.

Member Hage and Member Kattouw discussed what the best way would be for
Member Hage to suggest CSS changes.

Chair Jerdonek suggested adding a separate item to the next meeting's agenda
for going through the process for working with members of the public.

Public comment: None.


**8\. Digital Signatures** (7:07pm)

Member Hage clarified that the document attached to this item was the same
version as the one discussed at the last meeting, because he hadn't had time
to submit changes. He said he still needs to fill in the missing sections,
and he wants to write a Python script that implements the procedure described
in the document.

Public comment: None

Member Kattouw pointed out a Markdown syntax error in section X.6, and said
the section about log files was confusingly written. He suggested language
that he thought would be clearer.

Chair Jerdonek suggested clarifying that git is a version control system
(VCS) the first time it's referenced.

Member Hage said the document doesn't address authentication, but that's a
separate topic and should not be added to this document.

Member Hage said he would make the changes Member Kattouw suggested, and fill
in the missing sections, then bring this document back to the TAC for a vote.


**9\. Topics for future discussion**

Chair Jerdonek suggested discussing the public collaboration aspect that he
mentioned during item 7, and discussing digital signatures again. He also
suggested discussing long-term project governance.

Member Wasserman suggested discussing public feedback that would come out of
upcoming presentations about the project.

Member Hage suggested revisiting the FAQ. Member Wasserman suggested adding a
"basics" section to the FAQ.

Chair Jerdonek suggested having another optional meeting at the library.

Public comment: none.

**Adjourned at 7:41 p.m.**
