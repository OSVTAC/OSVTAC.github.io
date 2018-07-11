Meeting Minutes: June 14, 2018 (approved July 10, 2018)

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
MEETING MINUTES<br>
Open Source Voting System Technical Advisory Committee (OSVTAC)<br>
of the San Francisco Elections Commission<br>
Thursday, June 14, 2018<br>
6:00 p.m.<br>
City Hall, Room 479<br>
1 Dr. Carlton B. Goodlett Place<br>
San Francisco, California 94102<br>
</div>

**Order of Business**


**1\. Call to Order & Roll Call**

Chair Jerdonek called the meeting to order at 6:04 p.m. Present: Members
Hage, Jerdonek, Kattouw, Wasserman. Member Bafundo had an excused absence.
Also present: Secretary Chan.


**2\. General Public Comment**

None.


**3\. Approval of Minutes of Previous Meeting**

This item was postponed to the next meeting.


**4\. Administration**

Chair Jerdonek reported that at its June meeting the Elections Commission
reappointed all TAC members to a second term except for Member Bafundo, who
chose not to reapply because his work travel has conflicted with meetings.
The application period to replace his seat will open sometime after the
election.

It was decided that Member Wasserman would represent TAC at the Elections
Commission's July meeting. The next TAC meeting will be held on Tuesday, July
10\. Secretary Chan will confirm the availability of the room. Member Kattouw
said that the next couple months will be very busy for him because of work
and personal responsibilities, so he will not be able to take on much work
for TAC during this time.

Chair Jerdonek mentioned the idea of video recording the TAC meetings for
YouTube posting. Member Kattouw moved for TAC to try this at the next meeting
if equipment can be obtained. Member Hage seconded. The motion carried 4-0.

Chair Jerdonek brought up the topic of using a custom domain for TAC for its
site hosted on GitHub Pages. There was a short discussion of the pros and
cons of this. No action was taken.


**5\. Member Reports**

Member Kattouw reported that he was a poll worker for the election. He will
be working on a personal project to write code to analyze the RCV ballot data
after the election. He was also accepted to be a speaker at a conference on
September 27, 2018 in St. Louis called Strange Loop. He will do a
presentation similar to the one he did at LibrePlanet. Chair Jerdonek moved
and Member Wasserman seconded to approve Member Kattouw speaking as a member
of the committee.

Member Hage discussed election results he reviewed and some problems he
encountered in gathering counties’ data.

Chair Jerdonek reported that he was also a poll worker and had a high turnout
of voters at his precinct. He went to City Hall afterwards on election night.
He said there was a technical problem that delayed the reporting of results
by a couple of hours. He also said there was a good chance the Department
could obtain a collection of digital ballot pictures for the committee as
the committee has discussed at previous meetings.

Chair Jerdonek also reported that Maine just used RCV in their state election
and voted to keep using it in future elections. The coverage of RCV by the
San Francisco Chronicle has been negative.

On the funding front the City has only committed $300K to the open source
voting project so far this budget cycle. The California Clean Money Campaign
has on record commitments of support for future funding from Mayor-elect
London Breed, Supervisor Malia Cohen, and others. Clean Money will be working
in the coming weeks on getting $4 million in additional funding for the next
fiscal year.

There was a discussion around how different types of ballots were dealt with
in the voting process, how the vote records are relayed to the central office
for tallying, and what percent of ballots had to be handled manually to
resolve whatever could not be handled manually by the machines.

Member Kattouw said that he could add some pros and cons to the text that
Member Hage presented at the last meeting regarding machine-marked ballots.

Public comment:

Mr. David Cary discussed Alameda County's RCV reporting. He mentioned that
the vote center in City Hall had long lines with wait times upwards of
forty-five minutes for voters.


**6\. Voting System Component Development**

Member Hage presented a demo of a results reporter that he and Chair Jerdonek
started writing and pushed to GitHub. It has a number of features including
the ability to output results multi-lingually, but it is not finished yet.
The Department might be able to use it as soon as the November election. It
is meant as a proof of concept. Part of the intent is to show that Slalom's
cost estimate for the results reporting component was too high and that, if
done in an agile and open-source manner, the rest of the system could
potentially be developed for a cost much lower than Slalom's estimates.

It will be an ongoing task to refine and expand the functionality to be able
to produce all the reports that the Department currently produces, including
reports that the Department doesn’t currently do automatically. It was
proposed that each month one person could be designated a lead in choosing
who should work on the code, and then rotate the task to different committee
members each month. The proposal was to put it as a repository in GitHub
under TAC's account with name “osv-results-reporter.” Member Hage responded
to questions about how the input file is formatted and organized.

Public comment:

Mr. Jim Soper said that people in the election integrity community would like
to see the precinct reports in spreadsheet format. He said there was a state
law requiring that the data be available in such a format within 30 days
after the election.

Mr. David Cary suggested they also demonstrate other aspects of the agile
process and how it can apply to this project. He mentioned the continued work
by NIST on setting up standards so that data gathering might be easier.

There was a short discussion regarding how to proceed with the project,
including using a “gatekeeper” to oversee who was working on the project
between meetings, allowing independent submissions, or giving separate pieces
to individuals to develop, that can then be compiled and reviewed by the
other members during meetings.

Chair Jerdonek moved that the Committee create a GitHub repository for an
open source results reporter called “osv-results-reporter,” starting with the code
presented tonight, and adopt this as an official TAC project, with the added
condition that this action only be valid if the copyright for individual
contributions by committee members can be retained by the individual
committee members. Member Wasserman seconded.

Public comment:

Mr. David Cary suggested that the code be ultimately subsumed in the code
used for the open source voting project and that the City be the copyright
holder.

The question of how to do copyrights was discussed, including such issues as
GPL, contributor license agreements (CLA's), and only allowing contributions
from members of the public if the copyright is willingly transferred to the
City. Does the Committee’s intellectual property work qualify as owned by the
City, or is it the copyrighted property of the individuals in the Committee?
This question will be investigated further. Member Kattouw and Member
Wasserman will bring language that could possibly be used.

Member Hage volunteered to be the gatekeeper for the next month. Member
Kattouw moved that he be appointed, and Member Wasserman seconded. The motion
carried 4-0.


**7\. Project Background and Terminology**

Member Kattouw summarized the two diffs he prepared for the agenda packet.
Chair Jerdonek moved to accept the patches. Member Hage seconded. The motion
carried 4-0.


**8\. Equipment Decisions and Implementation Plan**

Member Kattouw reviewed his "diff" for this item, which included pros and
cons. Suggestions were made to revise some of the language around verifying
machine-marked ballots. Member Hage moved to accept, and Member Kattouw
seconded. The motion carried 4-0.

Public comment:

Mr. Jim Soper discussed Los Angeles County’s process of scanning QR codes on
their ballots, which he said aren’t voter verifiable.


**9\. Committee Recommendations**

There was no discussion on this item.


**10\. Slalom Report**

Member Kattouw’s comments on the Slalom Report, which were included in the
agenda packet, were reviewed and discussed. It included some more prominent
points of contention about the report, but didn't include a complete or
in-depth analysis of each point.

Member Wasserman wanted “OSI-approved license” to be used instead of “a
proven license.”

The Committee discussed various issues around licensing, software ownership,
and if there are examples of governments having licenses for voting systems.

Slalom’s cost estimates were discussed. It was noted that the costs of open
source weren't consistently compared to the cost of the current system for
all components. Moreover, the costs weren't constructed based on any
analysis. Rather, they were generic, boiler-plate presentations. They also
didn’t compare the costs of current open source voting related projects in
government use, including Colorado and New Hampshire, for example. Further
evidence of the unreliability of the estimates is that the cloud-based
hosting estimates were outrageously high compared to current, actual costs.

Member Wasserman asked if TAC should write a succinct response of these
points to the Elections Commission. Chair Jerdonek said he will be
introducing a resolution next week to the Commission recommending a rejection
of certain aspects of the Slalom report. The TAC could make a preliminary
statement at that meeting. Member Wasserman can highlight the points and
emphasize that the TAC seriously questions Slalom’s conclusions.

There was a short discussion with Mr. David Cary about the cost of hardware
scanners, either from Dominion or off-the-shelf.

Public comment:

Mr. David Cary commented that his last statement to the Commission to reject
the Slalom report did not come with much specific justification, but his
document included in the agenda packet attempts to provide some of that. He
encouraged the Committee to give some high-level feedback to the Commission
on the report.

Member Wasserman raised the question of the impact it would have if the
Committee recommended rejecting the Slalom report. Would it take the open
source voting project back to square one? Chair Jerdonek felt it wasn’t
necessary to come up with a total estimated cost for the project because that
didn’t coincide with the agile development method being advanced, where the
modular development of components provides a better means to estimate and
control costs at each stage.

Mr. Jim Soper said that the OSET Foundation could probably provide decent
cost estimates for an open source voting system. He commented that New Hampshire used a
derivative of Prime III, which is not open source. It passed certain
tests in Ohio, but it is not totally certified. He believed that the Slalom
report did damage to the possibility of the State legislature funding the
project, due to the report's high cost estimates.

Mr. David Cary reminded the Committee that at the March Commission meeting,
there was a motion to move forward with getting funding and doing the next
steps for developing the system. The budget request put forth by Director
Arntz was not the $4 million requested by the Commission. There seems to be a
disconnect between the Commission’s policy and what is actually happening.
There needs to be a stronger statement about the Slalom report. He didn’t
think there was anything new in the report beyond what was already contained
in the Commission’s 2015 resolution.

Member Wasserman commented that the only cost numbers that people can
consider are what Slalom presented. Mr. David Cary said that in 2015 certain
groups presented various cost estimates to the Commission.

Chair Jerdonek mentioned that DHR has a technology project to improve the
City’s hiring process. It will use an agile approach, has a project manager,
and is a multi-million dollar project very similar in scale to the open
source voting project, yet COIT gave them $1 million to begin their work.

The Committee crafted the following written statement to send to the
Commission (at 4:33:00 of the meeting audio):

> “Certain inaccuracies and basic omissions in Slalom’s Report lead us to
seriously question the report as a whole. We recommend not relying on it for
determining the future direction of the project. A few of the more glaring
examples include: (1) None of the costs are realistically substantiated. They
are based on generic cloud-based applications and not specific to a voting
system application. (2) $1 million for cloud hosting is an absurdly high
figure, orders of magnitude greater than what it would actually cost. The
estimate shows a fundamental lack of understanding of what a voting system
entails. (3) No consideration was given to open source election software
recently developed or used by other states, including Prime III used in New
Hampshire and Colorado RLA used in Colorado. The development process that
they described is not in line with open source development processes. We are
happy to substantiate these points further if needed. We encourage the
Commission to assert its previous resolution to follow our recommendations.”

Member Kattouw moved to adopt the statement, with Member Wasserman seconding.
The motion carried 4-0 vote.


**11\. Topics for future discussion**

Public comment:

Mr. Jim Soper suggested looking at AB 2125 regarding risk limiting audits.


**Adjourned at 10:45 p.m.**
