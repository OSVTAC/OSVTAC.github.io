Draft Meeting Minutes: March 14, 2019

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
MEETING MINUTES (DRAFT)<br>
Open Source Voting System Technical Advisory Committee (OSVTAC)<br>
of the San Francisco Elections Commission<br>
Thursday, March 14, 2019<br>
6:00 p.m.<br>
City Hall, Room 421<br>
1 Dr. Carlton B. Goodlett Place<br>
San Francisco, California 94102<br>
</div>

**Order of Business**

**1\. Call to Order & Roll Call**

Chair Jerdonek called the meeting to order at 6:12 p.m. Present: Members
Hage, Jerdonek, Kattouw. Excused absences: Members Philips and Wasserman.
Also present: Secretary Walker.


**2\. General Public Comment**

**Jim Soper, Voting Rights Task Force,** discussed how smudges on ballots
counted for a KPFA Local Station Board election were misinterpreted as votes
by their voting machine, causing the KPFA election to be recounted, and
suggested that OSVTAC consider this when developing an open source system for
San Francisco.

**John Brakey, Audit USA,** stated a need for elections with ballots that are
transparent, trackable and verified. He added that when votes are counted,
people should demand that machines are counting ballots and not pictures
of paper ballots.

**Dylan Saloner** urged the Committee to consider developing a web
application to create ballots, with references on how to use the application
published to GitHub. He added that cryptographic voting would not be a
direction the Committee should be pursuing, especially with voting
applications.

**Richard Tamm, Voting Rights Task Force,** said he wanted the OSVTAC to
succeed in creating an Open Source Voting System that can be shared with
other counties.

**Carl Carter** said the repairing of voting systems can be done remotely,
that this practice tends to be standard industrywide, that often voting polls
post-election are out of sync with election results consistently by up to
seven percent, and that people are covertly manipulating election results.

**Lori Grace,** involved with election integrity issues, appreciates the
democratic approach that San Francisco has with its Open Source Voting
process.


**3\. Open Source Voting Project Plan** (6:22 p.m.)

Chair Jerdonek reported that no representatives were present from the
Department of Technology (DT). He mentioned that the Dominion Voting System
Contract and Request for Proposals were included in the Board Packet, and
that he was pleased to hear that Chief Information Officer Linda Gerull would
solicit input from the OSVTAC on the Open Source Voting System project. He
said that DT's evaluation of other planned or existing Open Source Voting
System projects was continuing; and that a $3 million budget request for the
current and subsequent budget cycles (Fiscal Years 2019-2020 and 2020-2021)
was submitted by DT for approval by the Mayor’s Office.

Public comment:

* **Jim Soper** suggested that Secretary of State Alex Padilla is highly
  unlikely to support open source voting and suggested enlisting Governor
  Gavin Newsom into supporting open source voting.

* **Dylan Saloner** stated that without being able to verify one’s vote,
  it will be difficult to know whether or not a person’s vote is being sold.
  He suggested law enforcement and social norms over the fear that people
  will not actually verify their vote. He concluded by saying money may not
  be the correct way to go or proceed.

* **Carl Carter** stated that he is hopeful that Los Angeles will build a
  fully open source voting system, with the ability to read, verify and audit
  a voter’s vote, without a QR (Quick Response) code, which requires an
  optical scanner to be read.


**4\. Approval of Minutes of Previous Meeting** (6:42 p.m.)

Chair Jerdonek continued approval of the Meeting Minutes from February 14,
2019 to the next scheduled Open Source Voting Technical Advisory Committee
meeting.


**5\. Administration** (6:44 p.m.)

* Chair Jerdonek announced a Special Meeting of the Open Source Voting
  Technical Advisory Committee to be held on Sunday, February 17, 2019 from
  3:00 p.m. to 5:30 p.m. at the San Francisco Public Library, Main Branch,
  Third Floor, inside the Martin Paley Conference Room. Attendance for
  committee members is optional, the Committee will reserve this time for
  working on open source code, and recommended that attendees bring a laptop.

* Chair Jerdonek announced that the next regular meeting of OSVTAC would be
  held April 11, 2019 at 6pm.

* Member Kattouw agreed to attend the March 20, 2019 Elections Commission
  meeting and report activities on behalf of OSVTAC.

* Chair Jerdonek reported that TAC members are continuing work on proofs of
  concept for the project and on a results reporter that will help the public
  visualize election results as they are released to the public on Election
  Night.

Public comment:

**Jim Soper, Voting Rights Task Force,** offered to invite people to the
Special Meeting.

**Dylan Saloner,** requested a timeline outlining the implementation
deadlines for the Open Source Voting System project.


**6\. Member Reports** (6:48 p.m.)

Member Kattouw mentioned a potential flaw in new voting machines that
Westchester County (New York) plans to buy that are also manufactured by
Dominion Voting Systems, the provider of voting machines to the San Francisco
Department of Elections. The flaw, identified by a New York State Board of
Elections Commissioner, involves a ballot marking device that could mark
undervoted ballots if the machine were compromised by a hacker. Member Hage
added to Member Kattouw’s report that machines that combine scanning and
printing of a ballot could be dangerous, and suggested that all-in-one ballot
scanner and marking devices limit writing to prevent hacking.

Member Hage reported that--

* He attended a conference on election security held March 6, 2019 in
Mountain View (Santa Clara County). He said he met several election
advocates, including Stephanie Singer from Free and Fair, Kim Alexander of
the California Voter Foundation, and voting security expert Ben Adida.

* Voting expert Ben Adida is in the process of developing an open source
voting system, but that it is in its early stages of development. Member Hage
reported that only twenty-five states conduct post-election audits, which
could be a cause for concern that fraud may be happening in states without
the audits.

* Conference presenters agreed that there are still problems with paper
ballots. Although they are not the panacea, they are verifiable, unlike
states like Georgia with paperless, unverifiable ballots. Some suggestions
included adding a “skip this choice” voting option to determine whether a
person meant to skip a particular ballot question; ensuring that ballots are
machine-marked and not hand-marked; and creating a ballot printout that is
verifiable by the voter and that does not require a code reader.

* The Secretary of State may want to consider creating its own digital
signature certification software in order to bypass certification vendors
such as Verisign;

* That some voters in San Benito and Kings counties experienced up to four
hour waits for conditional registration to vote (CRV);

* Hardware keys might be more useful for open source voting. He recommended a
number of vendors presenting to the OSVTAC about how to use this technology
for the pilot project.

Chair Jerdonek reported that--

* Member Wasserman sent a video to the OSVTAC of a talk at which he
participated in Pasadena called the SCaLE conference (Southern California
Linux Expo). The conference is geared toward the open source community, and
is interested in Open Source Voting applications. SCaLE has convened a
working group on Open Source Voting that has not yet begun to meet, but will
meet soon and information from their first scheduled meeting will be shared.

* Member Philips shared an article with the OSVTAC regarding a $10 million
grant from the US Department of Defense’s DARPA to develop a prototype Open
Source Voting machine. This prototype, when completed, would still need to
meet requirements as defined by the Department of Technology in order for San
Francisco to use it for a future election.

* California Clean Money Campaign is working on a new state matching funds
bill to present at the state legislature for their approval.

* VotingWorks has started an open source repository for a ballot-marking
device (BMD) that might be usable for the open source voting project.

Public comment:

**John Brakey, Audit USA,** said that there needed to be a human element in
voting, and that hand-marked paper ballots is the only way to go; he made
suggestions about how to incorporate hand markings into the new voting system
and added that voting may be a secret process, but counting votes is a public
process that should be open source, with ballot images, and with good audits.

**Carl Carter** said he met with the California State Office of Cybersecurity
in Sacramento. He only encountered what he called a marketing spokesperson;
Carter is in the process of meeting with a second contact, Joe White of the
California Secretary of State’s office. He agreed to connect both of these
contacts with the OSVTAC and the Elections Commission and encouraged the
Commission and OSVTAC to encourage California state officials to support any
efforts to implement Open Source Voting.


**7\. Equipment Decisions and Implementation Plan** (7:26 p.m.)

Member Kattouw presented changes to the Equipment Decisions and
Implementation Plan section. Member Kattouw reported that he recommended
approval of his presented changes, which was created by referencing a paper
presented by Member Hage at the February 2019 OSVTAC meeting; a reference was
also added to fully record voter data. Jerdonek and Hage approved of the
report and of the plan as presented.

Member Hage moved to approve the Equipment Decisions and Implementation Plan
as amended; Chair Jerdonek seconded the motion.

Chair Jerdonek requested a roll call vote be taken by Secretary Walker on the
proposed changes.

Ayes: 3 (Hage, Jerdonek, Kattouw). Noes: 0 (None). Absent: Philips,
Wasserman. The Equipment Decisions and Implementation Plan was approved with
a unanimous vote (3-0).


**8\. San Francisco's Next Voting System** (7:28 p.m.)

Chair Jerdonek reported that the Dominion Voting System Contract between
Dominion and the City and County of San Francisco was approved on Tuesday,
March 12; he added that the Legislative Analyst report and a memorandum from
the Director of Elections summarizing the aspects of the contract were also
included in the Committee Meeting packet. He, then, received comments from
Committee Members.

Member Kattouw commented that a lot of new features are exciting, that many
of the features will save time, and that the upgrade brings the Department
out of the early aughts (2000s) to the current era. He said the system will
have more flexibility and mentioned that in order for the system to be
certified by the California Secretary of State that the machine could not use
the internet. He asked if California jurisdictions were actually using
risk-limiting audits. Chair Jerdonek responded that a pilot was done a few
years ago.

Chair Jerdonek suggested that the OSVTAC ask for sample ballot exports for
the new voting machines in order to learn how to integrate the pilot project
into the new system. Member Hage agreed with this suggestion and suggested
using physical principles, excluding these, noting if error that incorrect,
then auditing 200 ranked choice voting ballots with 99 percent probability
that this is the right outcome. Member Kattouw added that this may be more
difficult with ranked choice voting to figure out the proper cutoff
considering the high number of ballots in a ranked choice contest.


**9\. Contributor License Agreements (CLA's) for OSVTAC Projects** (7:44 p.m.)

Chair Jerdonek reported that he did hear back from the City Attorney
regarding the proposed Contributor Licensing Agreement. He stated that the
City Attorney recommended to the Chair of the OSVTAC that the OSVTAC enter
into the contributor licensing agreement with contributors, and that the City
and County could determine later whether it wants to use the OSVTAC software.

Member Kattouw reported that the agreement would be that anyone who
contributes to the software repository would enter into a signed contributor
licensing agreement with the OSVTAC. The agreement would allow that the
software author retain the copyright of their own contribution, but they
would allow the OSVTAC and the City and County of San Francisco, should the
City and County enter into the agreement, to license under the GPLv3, agree
that the OSVTAC can relicense it under a separate agreement for any media
created.

Member Kattouw moved to approve the CLA document that he proposed; that the
OSVTAC authorized Member Kattouw to modify it slightly after being approved
so it can be generalized to all OSVTAC projects, not specific to the results
reporter project; and, authorize Member Kattouw to write the text that will
appear at https://osvtac.github.io/cla. Member Hage seconded the motion.

Chair Jerdonek requested a roll call vote be taken by Secretary Walker to
adopt Member Kattouw's proposal as discussed.

Ayes: 3 (Hage, Jerdonek, Kattouw). Noes: 0 (None). Absent: Philips,
Wasserman. The Contributor Licensing Agreement was approved with a unanimous
vote (3-0).


**10\. Voting System Component Development** (8:03 p.m.)

Members discussed the status of each Member’s progress on their development
of their particular component of the voting system. Member Hage discussed
complications of whether source data for elections be boolean or some other
type of selection; Options include winning, election, and leading. He then
elaborated on whether the choices be coded as word phrases or as single
letter codes.

Public comment:

**Dylan Saloner** asked whether OSVTAC had a broader framework or if the
focus for the Open Source Voting project was solely on building a vote
tabulator. Chair Jerdonek responded that the OSVTAC has a recommendations
document with a number of different components, one of which is the results
reporter, which is not responsible for vote tabulation.


**11\. Topics for future discussion** (8:16 p.m.)

The following topics were suggested for discussion or action at a future
meeting:

* Data Licensing

* Voting Security

* Use of Hardware Security Modules in Pilot Project

Public comment:

**Dylan Saloner** asked where verification keys come into the process of Open
Source Voting System Implementation.

No further topics were suggested.


**Adjourned at 8:21 p.m.**
