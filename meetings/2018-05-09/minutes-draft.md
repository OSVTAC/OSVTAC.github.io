Draft Meeting Minutes: May 9, 2018

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
Open Source Voting System Technical Advisory Committee (OSVTAC)<br>
of the San Francisco Elections Commission<br>
Wednesday, May 9, 2018<br>
6:00 p.m.<br>
City Hall, Room 421<br>
1 Dr. Carlton B. Goodlett Place<br>
San Francisco, California 94102<br>
</div>

**Order of Business**


**1\. Call to Order & Roll Call**

Chair Jerdonek called the meeting to order at 6:01 p.m.  Present: Members Hage, Jerdonek, Kattouw. Excused absences: Members Bafundo and Wasserman.
Also present: Secretary Chan.


**2\. General Public Comment**

No members of the public were present.


**3\. Approval of Minutes of Previous Meetings**

Member Kattouw pointed out a typographical error in the April minutes. With
that correction, the minutes were approved by a vote of 3-0.


**4\. Administration**

Chair Jerdonek will see if either Member Bafundo or Member Wasserman can do
the TAC report at the next Commission meeting. If no member can attend, then
Chair Jerdonek will do the report. The next Committee meeting will have to be
in another room. Secretary Chan will confirm which room that will be. Chair
Jerdonek thanked Member Kattouw for doing TAC's written report to the
Commission. It is posted on the website and has gone to the Commission. The
updates on the website will be done soon.

There were no public comments.


**5\. Member Reports**

Chair Jerdonek reported on an event organized by the California Clean Money
Campaign on Sunday. It kicked off their campaign to support open source
voting. It was attended by about 125 people with many political officials
speaking in support. Member Kattouw also attended the meeting. Chair Jerdonek
also mentioned a budget committee meeting of the Board of Supervisors
tomorrow morning, with an agenda item on open source voting. He will be
presenting during it.

Member Kattouw heard at Sunday's event mention of open source voting in Ohio
using Prime III. He found a citation from the Open Source Initiative which
said Prime III was certified for state usage in Ohio.

Member Kattouw mentioned a tech conference in St. Louis in December. Chair
Jerdonek moved to permit Member Kattouw to speak there on behalf of the
Committee. Member Hage seconded. There was no public comment. The motion
carried 3-0.

Member Hage has been working on getting sample data for the upcoming election
from the Department. He found sample ballots online. However, they have
watermarks that obstruct what is on the ballot.

Several questions need answers, including how precincts are identified and
whether there is a database that translates multilingual ballots. He feels it
would be good to have a data package for people who might want to experiment
with open source components. Chair Jerdonek said that much of this would fit
under item #6 for discussion.

Member Hage reported that he found a sample remote accessible vote by mail
ballot online on the San Francisco Department of Elections website (via
“Democracy Live”), but that it includes some Google-tracking JavaScript.
There was a discussion about how they were doing this and whether State law
permitted this for remote vote-by-mail ballots conducted by a third-party.

The committee reviewed the URL that Member Hage found to see what
functionality was present.

Member Kattouw said he will be a poll worker and wants to write some software
to interpret the RCV data.

Chair Jerdonek reported that COIT had a committee meeting where they
recommended allocating only $300K for the open source voting project for the
next year, and that this was approved by the full COIT body.

Public comment:

Mr. Sergey Armishev said it would be beneficial if there were links to some
site that listed the ballot requirements or formats that need to be met by
the open source system (e.g. paper size).


**6\. Voting System Component Development**

Chair Jerdonek reviewed that at the last meeting he brought up the idea of
TAC developing one of the easier voting system components, namely the
reporting component, as a proof of concept. Member Hage started work on it
since the last meeting. Member Hage said that instead of doing a design
document he went ahead and put together a rudimentary prototype. His approach
was to make a template-based report generator, using HTML5 as a rendering
engine. The Committee inspected the samples Member Hage created. He plans to
share the repository by the next meeting.

Chair Jerdonek said that he asked Director Arntz how the Department did its
summary page and was given their source code. It was a collection of PHP
pages -- one for each language. It was probably done with in-house staff.

There was a discussion around how Member Hage’s prototype works and what it
should be able to do. The two parts to it are code and data manipulation, and
building templates and CSS. Member Kattouw offered to work on the latter
part. Chair Jerdonek offered to help on the former, and on the Python,
testing, and getting Docker working.

Member Hage said that he’d like scanned copies of marked ballots from the
election as test data. Member Hage moved to ask the Commission to request the
Department to create a set of scanned ballots after the upcoming June
election, preferably from one precinct, but if not feasible, then scans of a
representative set of at least 100 ballots. Member Kattouw seconded.

Public comment:

Mr. Adam Wojcieh asked if sample ballots were available to view. Member Hage
said he could give him a link to a site where he can view one.

The motion carried 3-0.

Chair Jerdonek asked Member Hage if there were any other items for the sample
data he wanted to mention. Member Hage replied-- getting a scanned blank
ballot; getting un-occluded PDF files; learning how they deal with precincts
(e.g. doing ballots in batches or using some identifying mark on the ballot);
what cast vote record files are created and whether we can get copies of
them; are raw count files created or just totals; and whether there is ballot
text support for alternative language translations.


**7\. Project Background and Terminology**

Member Hage raised the subject of how using the term “agile” can be
insufficiently clear due to its longtime use and interpretation by
individuals. It means different things to different people. He suggested that
when the term is used, it should be stated specifically what is meant. Member
Kattouw reviewed the recommendations document and said it appeared fairly
well-defined and clear wherever it was currently being used.

Chair Jerdonek said he’ll try to come up with a short, clear definition for
review.

Public comment:

Mr. Adam Wojcieh commented that the committee could simply provide links to
existing definitions, and that it wasn’t necessary to come up with their own
definitino. Also, it means different things depending on the subject (e.g.
software or hardware).


**8\. Equipment Decisions and Implementation Plan**

Member Hage referred to the document he revised based on the committee's
previous discussion of it. He pulled out two issues, including whether voting
machines should store cast vote records (CVR's). Member Bafundo informed him
that Los Angeles County's new VSAP system doesn’t store them. There was a
short discussion about whether to store or not, and what the pros and cons
were. Chair Jerdonek suggested using the term “mark” rather than “print” in
the title for section 8.4. On another point, use the term “device” rather
than “machine.” It was decided to leave it for now.

The Committee continued looking at Member Hage’s document, discussed the
usage of terms and their meanings, and suggested changes to the language. At
the conclusion of the discussion, Member Kattouw moved to accept the edits,
seconded by Chair Jerdonek. There was no public comment. The motion carried
3-0. The revisions will appear in the Recommendations document on the
Committee’s website.


**9\. Committee Recommendations**

There was no discussion on this item.


**10\. Slalom Report**

Committee members shared their initial reflections on the Slalom report, with
the intention of more comprehensive discussions taking place during
subsequent meetings. Some of the comments included the following.

Member Hage:

In Section 1.1, there is no mention of a detailed design or recommendations
for such a design, so their costs estimates are unrealistic. They didn't
consider the requirements and recommendations of how the system should work.

Section 1.5 contradicts the agile approach to design and development.

On page 6, it is only suggested to bring in the open source community after
the project is developed, not simultaneous to the development process. It
might be better to choose a term different from “benevolent dictator” because
of the connotations.

In Section 2.1.2, the report references STAR-Vote as a comparison, but it
shouldn't be a comparison.

Regarding Section 2.1.4, the committee discussed how to involve the open
source community in development.

Member Kattouw had comments on two items:

In Section 2.1.5 regarding certification, the report doesn't acknowledge the
possibility of certifying individual components rather than the whole system.

In Section 2.1.6, the issue of licensing is settled, which isn't implied by
the report.

In Section 4, the table doesn't show any consideration of assets that are
open source -- only proprietary resources.


**11\. Topics for future discussion**

Two items were raised: the budget for the open source project, and the
demonstration results reporter.


**Adjourned at 8:35 p.m.**
