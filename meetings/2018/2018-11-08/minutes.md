Meeting Minutes: November 8, 2018 (approved December 6, 2018)

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
Brandon Philips<br>
Tony Wasserman<br>
</div>

<div id="meeting_header_main" class="headered">
MEETING MINUTES<br>
Open Source Voting System Technical Advisory Committee (OSVTAC)<br>
of the San Francisco Elections Commission<br>
Thursday, November 8, 2018<br>
6:00 p.m.<br>
City Hall, Room 421<br>
1 Dr. Carlton B. Goodlett Place<br>
San Francisco, California 94102<br>
</div>

**Order of Business**


**1\. Call to Order & Roll Call**

Chair Jerdonek called the meeting to order at 6:03 p.m. Present: Members
Jerdonek, Kattouw, and Wasserman. Members Hage and Philips arrived late
(excused) during item #3 at 6:17 p.m. and 6:18 p.m., respectively. Also
present: Secretary Chan.


**2\. General Public Comment**

None.


**3\. Open Source Voting Project Plan**

Chair Jerdonek welcomed City CIO and Executive Director of the San Francisco
Department of Technology, Linda Gerull. Committee members had questions
regarding the draft plan she presented (included in the agenda packet).


**4\. Approval of Minutes of Previous Meeting**

Member Kattouw noted a typo and with that correction, moved to approve the
minutes of the September 13, 2018 meeting. Member Hage seconded. Upon voice
vote, the motion carried unanimously 5-0.


**5\. Administration**

Chair Jerdonek introduced new TAC member Brandon Philips, who gave a short
self-introduction.

The decision was to have the next committee meeting on December 6 rather than
December 13.

Member Kattouw said he can speak on behalf of the committee at the next
Commission meeting on November 21.

Public comment:

Mr. David Cary complimented the committee and asked if they had addressed the
Civil Grand Jury’s proposal to create a portal or site for the open source
project. Chair Jerdonek referred him to the project page link on the
committee’s website whose purpose was to fulfill that recommendation.


**6\. Member Reports**

Member Kattouw reviewed some of the comments made at the Commission meeting
regarding the Department of Technology’s (DT) draft Project Initiation Plan.
He was pleased by the responsiveness to the comments he raised at the last
OSVTAC meeting. He also spoke about his experiences observing the Logic and
Accuracy testing held by the Department. He said he observed the elections
results reporting and was generally pleased with how it was done. He heard
that Vancouver has a process similar to New Hampshire where QR codes are
created before the ballot is scanned. He said he is looking forward to when
we will have CVR data.

Member Hage reported on his elections work, which includes writing programs
to convert election results for thirty-five counties. He spoke about the fact
that the State collects all county voting information but only uses some of
it and throws the rest away. None of it is available to the public. There was
a short discussion about Member Hage‘s request for documentation or manuals
for San Francisco's current Dominion voting system and whether this could
distract from or harm the committee’s work.

Member Wasserman reported on his keynote talk on open source in Shenzhen,
China.

Chair Jerdonek reported that he sent to Director Gerull the questions that
TAC developed and voted on at the previous meeting. He was a polling place
inspector on Election Day. At his polling place there was a larger ballot
discrepancy during the reconciliation than he had seen in the past. This was
due in part to unused vote-by-mail ballots being counted as voided precinct
ballots. He said he will tell the committee when the Department does the
random selection of precincts if they want to observe.

He also mentioned a panel discussion he participated in, along with Ben
Adida, the creator of the online voting system Helios.

Public comment:

Mr. David Cary commented that it is specifically in the area of verifiable
vote counting that open source exceeds proprietary closed source systems’
credibility. It is more important to get a core system up and running and add
extra capabilities only later.


**7\. Contributor License Agreements (CLA's) for OSVTAC Projects**

Member Kattouw researched this topic, taking into account previous committee
discussions on issues related to licensing, intellectual property, etc. He
summarized that the Apache CLA is simple and allows the entity you are
agreeing with to re-license your contribution. For GPLv3 projects this is a
concern. He liked the JS Foundation CLA, but it does not include patent
grants. He favored one used by the Harmony Project (harmonyagreements.org).
All of this was covered in his email (see agenda packet).

The issue was also raised regarding the City being the owner of the project
and protecting itself from possible complications from outside contributors
to it or future revisions. Any such action might require action on the part
of the Board of Supervisors. If ownership does not reside with the City, then
the CLA might not be necessary. The City Attorney's office would need to
confirm, but in initial discussions the Deputy City Attorney felt the City is
a copyright owner.

Member Philips felt that GPLv3 is the most aggressive copyleft license,
whereas more and more organizations are leaning towards licenses like Apache
2.0. Member Philips also mentioned using a DCO (Developer Certificate of
Origin) as an alternative to a CLA, which shows up as a "Signed-off-by" line
in a commit.

Member Wasserman mentioned that the evolution of GPL came out of a problem
Richard Stallman had with "tivoization." Member Kattouw will revise his
proposed CLA with a re-licensing clause, and Chair Jerdonek will review it
with the Deputy City Attorney.

Public comment:

Mr. David Cary said his understanding was that for federal regulatory
certification, they would have to show origin of software. He wasn’t sure how
that applied to the state certification process. He also felt that the Affero
GPL is preferable to the GPL.


**8\. Voting System Component Development**

Member Hage reviewed what he has done since the last meeting on the Open
Results Reporter (ORR), which uses Python and Jinja templates. He asked
Member Kattouw to write some CSS templates. Member Kattouw said he would have
this done by the January meeting. Member Hage said the code in ORR could also
be used to generate accessible sample ballots. This could replace the service
the City uses now (OmniBallot Online).

Chair Jerdonek reviewed some of ORR's online documentation and the sample
demo output, which is available online. It already has certain reporting
features that the City currently doesn't have. He thought the next step could
be to have the data from the November election, a script to generate from
that data the input files for ORR, and an attractive template to present
ORR's output.

He wanted to explore how the committee could expand and better organize its
development of the Open Results Reporter -- given “sunshine” restrictions --
and see if the committee could work on more than just the results reporting
component.

Member Wasserman wanted to explore how the committee could actually get this
module integrated into the final project rather than just having it as an
academic exercise. Member Wasserman felt that it would be good to take the
“prettified” ORR, give it to DT, and see how they respond.

The discussion of how to proceed considered individual members working on
their own but left open how to keep everyone on the same track. There was
also the question of how public contributions could fit in. Member Hage
thought it would help to explain how working in a container environment and
using digital signatures could help address security.

Chair Jerdonek explained to Member Philips how the ORR accepts tabulated vote
totals in JSON and TSV forms, and uses template files to format them for
public viewing.

Chair Jerdonek said he will continue to flesh out features of the results
reporter. He asked Member Hage if he could create a script to generate from
the real election data the input files for ORR, and to store those input
files in the sample data repo. He also asked if there could be a regression
test to check that the conversion code is generating the input files
correctly, as the conversion code changes.

Public comment:

Mr. David Cary suggested the route of taking some of the concerns DT may have
about the current voting system and constructing the TAC project in a way
that addresses those questions. This could also provide proof of how it can
fit into the larger project goals without having to wait for planning out the
entire system at the beginning.


**9\. Committee Recommendations**

Member Hage suggested going back to the section on security and expanding the
background appendix, before DT gets too far along.

Member Wasserman again recommended that we keep open lines of communication
with DT to ensure that the committee's recommendations are followed.

Member Hage said he will work more on the glossary to amplify terms
for cryptography and security. Member Wasserman suggested a way to present
this via identifying the vulnerabilities and then offering the solution to
each. Chair Jerdonek said that definitions didn’t need to be expansive or
very technical.

Member Kattouw thought if Member Hage separated the topic of security into
two parts: (1) to verify the security of the data flow (what is inputted is
outputted correctly), and (2) to ensure that the software you think is
running the machine IS running it, it would read more easily.


**10\. Topics for future discussion**

The topics were the topics that were mentioned earlier in the meeting:
security, and continued discussion of CLA's.


**Adjourned at 9:10 p.m.**
