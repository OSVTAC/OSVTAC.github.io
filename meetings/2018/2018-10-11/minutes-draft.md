Draft Meeting Minutes: October 11, 2018

<div id="meeting_header_right" class="headered">
Elections Commission<br>
City and County of San Francisco<br>
Don Chan, Secretary<br>
</div>

<div class="headered">
Open Source Voting System Technical Advisory Committee<br>
Christopher Jerdonek, Chair<br>
Roan Kattouw, Vice Chair<br>
Carl Hage<br>
Tony Wasserman<br>
</div>

<div id="meeting_header_main" class="headered">
MEETING MINUTES (DRAFT)<br>
Open Source Voting System Technical Advisory Committee (OSVTAC)<br>
of the San Francisco Elections Commission<br>
Thursday, October 11, 2018<br>
6:00 p.m.<br>
City Hall, Room 421<br>
1 Dr. Carlton B. Goodlett Place<br>
San Francisco, California 94102<br>
</div>

**Order of Business**


**1\. Call to Order & Roll Call**

Chair Jerdonek called the meeting to order at 6:01 p.m. All present: Members
Hage, Jerdonek, Kattouw, Wasserman. The committee has one vacancy. Also
present: Secretary Chan. Member Wasserman had to depart at 8:28 p.m.


**2\. General Public Comment**

None.


**3\. Approval of Minutes of Previous Meeting**

Chair Jerdonek asked about the comment about SHA files and in what context it
was brought up. Member Wasserman moved to approve with corrections, seconded
by Member Kattouw. The motion carried 4-0.


**4\. Administration**

The normally scheduled TAC meeting can go forth. Chair Jerdonek mentioned
that the project page on the website has been fleshed out with descriptions.
Missing still are budget documents.

Public comment: None.


**5\. Member Reports**

Member Hage has looked into security issues and showed a couple of hardware
security tokens. He discussed briefly how they can be used to hold encryption
keys inside the hardware. These are being suggested for use in conjunction
with GitHub repositories. He suggested signing the TAC GitHub repositories
with them to demonstrate the concept. NIST-certified versions of the keys
exist. NIST also has specifications on container security. If TAC is going
to use containers, they should probably be in compliance with those. The
concept of using digital signatures could be demonstrated by TAC.

He mentioned DEF CON this year, which showed how easily voting machines could
be hacked. He said it would be important to note that security should be
based on paper records and auditing rather than attempting to make hardware
impenetrable.

Member Hage reviewed the ballot scans received from the Department (6
precincts, about 20 pages each), mostly English/Chinese. He wanted clean
PDF's. Chair Jerdonek will ask for those. Member Hage said there is data on
the November election on the Department’s website, but some of it isn’t
updated (e.g. precinct maps from 2016).

He mentioned that he is on a Secretary of State (SoS) email list. He
discovered that there is a statewide database of election information that
counties are required to submit information to the SoS for, but it is not
open for public review.

Member Wasserman reported that Estonia’s election turnout is low (similar to
the United States), despite the ease with which they can vote there.

Member Kattouw reported on his presentation in St. Louis. About 100 people
attended. One participant indicated interest in contributing to the
Committee’s work.

Member Wasserman will be speaking at a conference in Shenzhen next week.

Chair Jerdonek referred to the packet document regarding the Los Angeles
County project. It shows that LA County does not have a license for their
system, and in particular confirms again that it is not open source.

Public comment:

A member of the public commented on the use of YubiKeys, and how they are
used.


**6\. Open Source Voting System Project Manager**

At the last Elections Commission meeting, Chair Jerdonek asked the Department
of Technology if a TAC member could participate in the interview process for
the Project Manager position. He was told there was a possibility. However,
yesterday he learned they had decided this wouldn't be possible. Secretary
Chan mentioned that they left open the possibility of including up to five
questions that the Commission or TAC could submit for posing to the
candidates.

The Committee discussed different qualities they felt a successful candidate
should have, including involvement and contributions to open source projects,
familiarity with agile processes, how they have managed staff and work within
an agile framework, and experience with security issues. The Committee
discussed and developed five questions for the interview panel to use.

Public comment:

Mr. JP Posma commented that candidates could be asked to list some open
source projects they’ve been in involved in. That way one could go directly
to the projects and see what their contributions were. He also suggested
asking if they have ever contracted out for software development, and how
familiar they are with voting systems. He said he believed there are people
with security experience that also have the other qualities being sought.

Mr. Jim Soper suggested using the term "contributors" rather than "vendors."
He said security isn’t just a module but a single primary concern for the
project. He also felt that an important quality in candidates would be how
they adjust to changes.

Member Kattouw moved to approve the five questions, seconded by Member Hage.
By voice vote the motion carried unanimously, 4-0. Chair Jerdonek will take
them before the Commission.


**7\. Civil Grand Jury Report**

Chair Jerdonek mentioned that the Board of Supervisors would be holding a
committee hearing next Thursday on the Civil Grand Jury (CGJ) Report and the
responses to the report. He pointed out the cover letter attached to the
consolidated response to the report from the Mayor, Department of Technology (DT),
and Department of Elections. It stated that a discovery phase à la the Slalom
Report was planned. He was concerned that the administration's plans are not
aligned with the Commission's and Committee’s position.

The Committee looked over the proposed timeline and activities and wondered
whether the plan was to develop a roadmap or to actually produce concrete
components of the project. There was a feeling that DT should go back to
TAC’s recommendations to prioritize project activities and follow a more
agile process. It appeared from the format of the plan that DT might not be
familiar agile processes.

There was also a feeling that the Committee needed a more direct line of
communication with DT so there could be more alignment with recommendations.
The Committee discussed what it felt should be the next steps in development.
Some thoughts were: defining what the modules are, the input and output
formats, doing things in an agile way, and not outsourcing the work of
designing the planning phase. There should be community involvement from the
beginning. Discussions with jurisdictions that have made similar attempts
should take place (e.g. Colorado). There doesn’t have to be a fully developed
plan before any single component is completed. If DT could return to the
Committee’s recommendations, they could begin more quickly on many components
without as much up-front planning.

When Chair Jerdonek gets a chance to talk with Director Gerull, he will ask
for clarification on the role of the OSV steering committee listed in the
draft plan and whether the plan is to produce components of the system, or
just to formulate a whole plan.

There was a question of whether funds were clearly allocated for specific
products/outcomes in this budget. Chair Jerdonek will try to track down some
budget documents for the project.

Public comment:

Ms. Mary Ryan, CCMC, commented that DT's plan does not identify an open
source system architect, which she felt was essential to bring the right
perspective to the initial development.

Mr. Steven Buss agreed with Ms. Ryan about having an open source system
architect, and with Member Wasserman in saying the plan looked like a generic
Gantt chart that was adjusted to apply to the open source project. He also
thought that developing data formats in advance would be premature.

Mr. Jim Soper said he thought it would be very important for TAC to sit down
with DT to get clarification on some of the questions and concerns the
Committee has with the plan.


**8\. Voting System Component Development**

Member Hage said he is getting election data and will put it into TAC's
sample data repository. He said he would like to see an actual accessible
remote vote-by-mail ballot to see if it has the same security issues as the
sample, but there are limitations on who can get one. There was no answer to
if they could get a copy of the ballot. Chair Jerdonek said he hoped there
could be progress on this by the next meeting.

Member Hage has seen the precinct boundaries files. He wants to get a nice
CSS design for the results reporter. Member Kattouw will help him on this.

Chair Jerdonek asked Member Kattouw if he could get a CLA template for the
Committee to discuss. He also suggested a code of conduct for the repository,
in the interest of modeling good practices. Member Wasserman noted that the
Association for Computing Machinery (ACM) has one on their website.

Public comment:

Mr. Jim Soper didn’t think there was a big security issue with accessible
vote-by-mail balloting

Mr. Steven Buss mentioned using GeoPandas for mapping visualizations and has a
friend who has done this who might be open to helping.

Member Hage commented that getting some graphic visualizations of election
results might be a good candidate for soliciting public contributions.


**9\. November 6, 2018 Election**

Chair Jerdonek and Member Kattouw were sable to observe the Logic and
Accuracy (L&A) testing (separately), and they reported on what they saw.
Member Kattouw was surprised to see the process being done by a Dominion
employee.

Member Wasserman departed at 8:28 p.m.

Member Hage asked if there was documentation on the machines available. Chair
Jerdonek will check on that.

The Committee reviewed the answers from the Department to TAC's questions
after the June election observation (see agenda packet).

Public comment:

Mr. Jim Soper gave a short description of how WinEDS handles balloting.


**10\. Committee Recommendations**

Member Hage said it would be good to review the issue of security. He thought
it would be good to have that in TAC's recommendations document as background
material before DT begins making a roadmap. He also suggested that TAC could
possibly digitally sign all of its documents. Chair Jerdonek recommended that
Member Hage propose something for the Committee to consider, including
workflows and assumptions.


**11\. Topics for future discussion**

None at this time.


**Adjourned at 8:52 p.m.**
