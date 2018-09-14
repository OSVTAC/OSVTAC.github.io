Meeting Minutes: August 27, 2018 (approved September 13, 2018)

<div id="meeting_header_right" class="headered">
Elections Commission<br>
City and County of San Francisco<br>
Don Chan, Secretary<br>
</div>

<div class="headered">
Open Source Voting System Technical Advisory Committee<br>
Christopher Jerdonek, Chair<br>
Carl Hage<br>
Roan Kattouw<br>
Tony Wasserman<br>
</div>

<div id="meeting_header_main" class="headered">
MEETING MINUTES<br>
Open Source Voting System Technical Advisory Committee (OSVTAC)<br>
of the San Francisco Elections Commission<br>
Monday, August 27, 2018<br>
6:00 p.m.<br>
City Hall, Room 421<br>
1 Dr. Carlton B. Goodlett Place<br>
San Francisco, California 94102<br>
</div>

**Order of Business**


**1\. Call to Order & Roll Call**

Chair Jerdonek called the meeting to order at 6:03 p.m. Present: Members
Hage, Jerdonek, Kattouw, Wasserman. The committee has one vacancy. Also
present: Secretary Chan.


**2\. General Public Comment**

None.


**3\. Election of Vice-Chair**

The Committee held elections for the Vice Chair position (formerly held by
Larry Bafundo). Member Wasserman was nominated but when Member Kattouw
volunteered, he graciously endorsed Member Kattouw. By voice vote of 4-0,
Member Kattouw was elected.


**4\. Approval of Minutes of Previous Meeting**

Action was tabled till next meeting.


**5\. Administration**

Chair Jerdonek said he will be putting up an announcement to fill the vacancy
left by Larry Bafundo.

The quarterly report to the Commission is due the first week of September.
Member Kattouw volunteered to draft it, with Chair Jerdonek reviewing it and
sending it to the Commission. It will include the Committee's work on the
results reporter software, the review of the Civil Grand Jury report,
comments on the Slalom report, and the tour of the Department of Elections.

The Committee will meet at its regular September 13 date.

The Chair asked the secretary about the attempt to video the meetings.
Secretary reported that the camera was recording to its internal memory,
which filled up quickly and stopped. The Department said they had fixed that
to record to the SD card. It remains to be seen whether it works tonight.

Public comment: none.


**6\. Member Reports**

Member Wasserman is going to be giving a talk on September 4 in San Jose on
open source voting. It will be to the Santa Clara County Citizens Advisory
Committee on Elections (CACE). Tomorrow, he will be going to an open source
conference in Vancouver. Member Kattouw will be presenting at a conference in
St. Louis at the end of September.

Chair Jerdonek reviewed the City’s new budget allocation of $1.25 million to
open source voting, which brings the total to about $1.7 million over two
years, including carry over from the previous year’s budget. He also reported
that the Department of Technology is doing the hiring of the project manager
for the open source project.

Along with this, he mentioned the last Commission meeting where a very
serious difference of opinion was revealed as to who should be the “owner” of
the project. Some Commissioners and the Department apparently don’t share the
same understanding of this. The vote on his amendment to the Commission’s
resolution on open source (passed at their previous meeting), asking to name
the Department as owner, failed. Similarly, replies to the Civil Grand Jury
report (drafted by Chair Jerdonek working with the Commission President) were
approved by the Commission, with the exception of those related to project
ownership.

Chair Jerdonek commented on recent media coverage of Los Angeles County's
VSAP tally system’s certification by the State, implying that it is open
source. However, he hasn’t been able to find any available code to confirm
this.

Chair Jerdonek also mentioned that the scanned ballot images that TAC asked
for have been provided. He said that the Deputy City Attorney said it would
be okay to post them on the website, as long as there are no identifying
marks linking any ballots to particular voters.

Committee members reported having participated in the new election system
demo where they could cast a ballot digitally by touchscreen and watch the
process of it being produced hardcopy and scanned. The document is not a copy
of a hand-marked ballot, but a paper cast vote record. Chair Jerdonek said
that all their equipment run Windows except the precinct scanner, which runs
Linux. It is an off-the-shelf scanner. The central scanner runs Windows.

Given that it doesn’t make a complete ballot image, there is the problem of
verifying each contest by name (not spelled out, just numbered).

At the demo Chair Jerdonek asked the vendor if they give total results for
RCV on the election results summary page, and they said they only show
first-choice totals.

The question was asked of how precinct scanners report errors. If there is an
error, the voter can see it on the screen so the pollworker is not required
to review it. But it seems to only show you the first two errors. Member
Kattouw said that the scanner is touchy, where slight bumps can disrupt the
feeding mechanism.

West Virginia will be using electronic voting technology (cell phone via
internet) for their overseas military voters.

Chair Jerdonek was asked about the status of the State matching funds that
were spoken about in previous meetings. He said it didn’t survive the
appropriations process. Assemblymember Phil Ting, who chaired the Budget
Committee, never added it to the agenda, which essentially killed it.

There was a short discussion about the DEF CON event and how they showed that
various elections websites and voting machines could be compromised. One
piece of equipement was compromised by an eleven year old within thirty
minutes.

Public comment:

Mr. Brent Turner (CAVO) said it sounded like the new Dominion voting system
is more like the "Dechert" design. He said there is a call for moving to
smart-phone voting. He made comments against Verified Voting and the Director
of Elections.


**7\. Voting System Component Development**

Due to the personal business obligations of Member Hage, he wasn’t able to do
much more on the results reporter. He will be working on converting the
electronic representation of the November election results into a format
that the results reporter can read (e.g. election definitions and results
data).

Member Hage
would like a PDF of a blank ballot or a high resolution scan of one. Chair
Jerdonek said he would ask Director Arntz, or wait until the scanned images
get publicly posted, so that Member Hage can see which ones he needs.
Chair Jerdonek asked where the scanned images
should be posted. It was decided that they could be added to the sample data
repository and then linked to from the committee's main website.

Member Hage asked if he should snapshot the county's DFM election definition
data and add it to the sample data repository.

Chair Jerdonek will email the members when the scanned images are posted.

Public comment: none.


**8\. Project Ownership and Project Management**

Chair Jerdonek reviewed this issue and question that raised disagreement at
the last Commission meeting. Briefly, the question of who “owns” the open
source voting system project, and what “ownership” means brought out
different views. Recalling the Civil Grand Jury’s statements about the
project not having a clear “owner” that interfered with the progress of the
project, the discussion at the Commission meeting centered on whether the
Department of Elections should be named the owner or whether it should be a
project of another department, e.g. the Department of Technology (DT), since
they are hiring the staff position. The Director of Elections felt that DT
was more appropriate than the Department of Elections itself being the owner.

Chair Jerdonek felt the disagreement stemmed in part from misunderstanding
what the term and nature of “owner” was. He referred to the documents that he
and Member Wasserman found for this agenda packet that presented clear
parameters for that.

Member Wasserman used the metaphor of a home repair project, using a general
contractor who manages all the sub-contractors who actually do the individual
aspects of the whole project. In this context the “home owner” does not
personally perform any of the smaller work projects, but provides the
guidance for the direction of the whole project to the general contractor.
The owner does not necessarily manage the work. The general contractor would
do that. (In the case at hand, the project manager would play the role of the
general contractor.)

Member Kattouw read a definition for project owner--

> The project owner is in charge of defining the scope of the project, the
"What?" and the "Why?” They are responsible for collecting all the
requirements for a product.

He contrasted it with project manager--

> The project manager is in charge of getting things done, the “How?” and the
“Who?”. The project manager is responsible for completing the project within
an established time and budget.

There were many new terms introduced in the documents (e.g. “scrum”), but it
was decided that it shouldn’t get too technical and removed from commonly
understood definitions.

Chair Jerdonek suggested that the Committee come up with a short piece (like
a couple of paragraphs) which clarify the terms and roles, and make a
recommendation to the Commission for its use.

Member Kattouw said the Department of Technology could be the builder of the
project, but the Department of Elections would be the customer (owner) who
would provide the guidance and specifications for what the build should do.

Member Hage read another definition from one of the documents:

> The product owner is commonly a lead user of the system or someone from
marketing, product management or anyone with a solid understanding of users,
the market place, the competition and of future trends for the domain or type
of system being developed.

Chair Jerdonek suggested using the two paragraphs Member Kattouw and Member
Hage read off, using the metaphor of home owner and general contractor, and
identifying which position within the Elections Department would be the
Project manager.

There was a discussion about using the term "product owner" versus "project
owner." Chair Jerdonek suggested leading off with project manager vs project
owner, and saying project owner shares many of the characteristics that a
product owner has in “scrum.” Chair Jerdonek further suggested using the term
"key stakeholder" for the product owner term.

Member Wasserman commented that the domain expert would be found in the
Department of Elections because you wouldn’t expect the project manager to
necessarily know the details of the voting process.

Chair Jerdonek reviewed the proposed language of the discussion by saying
that the text will include the paragraphs read by Member Kattouw and Member
Hage, with the terms domain expert and key stakeholder, using the building
metaphor but with Department of Elections, and Technology being the roles.

Member Kattouw moved to have Chair Jerdonek draft the letter, with Member
Wasserman editing it. They will send the final draft on behalf of the
Committee. Member Hage seconded the motion. Upon voice vote, the motion
carried unanimously.

Public comment: none.


**9\. Committee Recommendations**

The committee discussed adding the text created tonight regarding ownership
to the recommendations document at the next meeting.

Public comment: none.


**10\. Topics for future discussion**

Suggestions:

* Possibly attend pre-elections activities in October.

* Review the job description for the position. Can TAC review it? It was
  suggested that Chair Jerdonek make that request at the Commission meeting.


**Adjourned at 8:06 p.m.**
