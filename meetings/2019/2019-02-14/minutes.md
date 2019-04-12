Meeting Minutes: February 14, 2019 (approved April 11, 2019)

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
Thursday, February 14, 2019<br>
6:00 p.m.<br>
City Hall, Room 421<br>
1 Dr. Carlton B. Goodlett Place<br>
San Francisco, California 94102<br>
</div>

**Order of Business**

**1\. Call to Order & Roll Call**

Chair Jerdonek called the meeting to order at 6:04 p.m. Present (all):
Members Hage, Jerdonek, Kattouw, Philips, and Wasserman. Also present:
Secretary Walker.


**2\. General Public Comment** - 6:05 p.m.

Brent Turner of the California Association of Voting Officials (CAVO) spoke
about a letter his organization sent to the California Little Hoover
Commission, an independent California state oversight agency, on the subject
of open source voting and election system security.


**3\. Open Source Voting Project Plan** - 6:07 p.m.

Chair Jerdonek reported—

* San Francisco CIO and Director of the Department of Technology Linda
  Geruall was invited to the meeting, but she was unable to attend.

* Director Gerull reported earlier that her Department hired someone named
  Sean Roberts into a full-time position as the technical project manager /
  lead for the Open Source Voting Project. He started in December. A second
  person was offered a part-time position in a project management /
  communications role, but the job offer was declined. Director Gerull is
  exploring other ways to fill the latter role.

* Director Gerull submitted a $3 million budget request for the project to
  the Committee on Information Technology (COIT).

* Nina Sparling, a student at the UC Berkeley Graduate School of Journalism,
  is doing a story on open source voting and will be attending some OSVTAC
  meetings to observe.

Public comment:

Brent Turner (CAVO) spoke regarding the uniqueness of the Open Source Voting
project and suggested that it not be treated like a regular departmental
project. He suggested that the Committee pursue project benchmarks and
timelines to be implemented, and he supported the idea of Technical Lead Sean
Roberts presenting at a future OSVTAC meeting.

Nina Sparling, a student at the UC Berkeley Graduate School of Journalism,
introduced herself as a journalist and said she will be recording the OSVTAC
meeting to gather audio for a podcast on open source voting.


**4\. Approval of Minutes of Previous Meeting** - 7:53 p.m.

At 6:11 p.m. it was announced that this item would be considered later in
the meeting. The committee returned to the item after agenda item 8.

The minutes were approved after a motion to approve and a second.

AYES: Hage, Jerdonek, Kattouw, Philips, Wasserman. NOES: None.


**5\. Administration** - 6:18 p.m.

All members but one (Member Wasserman) said they could attend the OSVTAC
meeting at its regularly scheduled date on March 14, 2019, so it was agreed
to schedule the meeting for that time.

Member Wasserman volunteered to give the Open Source Voting Technical
Advisory Committee report at the February 20, 2019 regular Elections
Commission meeting. He said that he would discuss the software engineering
work OSVTAC has been doing and say that OSVTAC would like to meet with newly
hired Technical Lead Sean Roberts.

Chair Jerdonek asked Member Philips to provide his bio and to decide whether
he would like an sfgov.org email address.


**6\. Member Reports** - 6:20 p.m.

Member Hage reported that the California Secretary of State's office reported
that former Governor Jerry Brown recently signed AB 2125 into law. This bill
permits the use of risk-limiting audits in lieu of the one percent manual
tally. Paper ballots are included in the ballot definition, but scans are not
allowed. It defines the risk limit for the audit and states that the
Secretary of State, in consultation with statistical experts and
stakeholders, will adopt regulations to implement and administer the audits.

Member Hage said that the office also mentioned AB 1013, which requires
counties to provide a remote accessible vote-by-mail system. This is already
implemented in San Francisco. There was also mention of an August 29 notice
that there is $134 million in funds allocated to modernize voting systems.
This also includes $1.5 million for cyber security and $1.5 million for
voting place accessibility.

Chair Jerdonek mentioned that San Francisco's contract with Dominion for its
next voting system has not yet been submitted to the San Francisco Board of
Supervisors for approval. He will let the Committee know when the contract is
made public. He said that Trent Lange of the California Clean Money Campaign
is working on another state matching funds request. He mentioned that
Elections Commissioner Lucy Bernholz provided information on the possibility
of partnering with the federal agency 18F on the Open Source Voting Project.
He included that information in the agenda packet. Chair Jerdonek also
reported that the San Francisco Board of Supervisors reappointed him to the
Elections Commission for a second five year term.

Member Kattouw reported that an organization called the Coalition for Free
Governance published a paper on voters in a Tennessee 2018 primary. They
found that it is difficult for voters to validate paper ballots that are
marked by a ballot-marking device (BMD). He was hoping this information could
be included in TAC's recommendations in the section on pros and cons of
BMD's. He mentioned that the state of South Carolina publishes the digital
cast vote record (CVR) of every ballot, something that is not possible in San
Francisco with its current voting system. In South Carolina, this data can be
converted into JSON files and published. He also added that an academic
poster was created that correlated voting behavior between different offices
and ballot measures, which is indicative of the types of analysis that can be
done when this data is made public.

Public comment:

Brent Turner (CAVO) suggested that OSVTAC should stipulate that the
voter-verified paper audit trail (VVPAT) is a botched design for open source
voting and does not provide a paper ballot after a voter casts a ballot.
Efforts should be made to eliminate voter intent issues that are caused by
voters marking ballots by hand. He suggested that people familiarize
themselves with the Open Voting Consortium.


**7\. Voting System Security** - 6:44 p.m.

Member Hage reported on his progress with this item and asked committee
members for suggestions on drafting a technical document on voting system
security. He suggested a methodology and format for cryptographically signing
and securing data generated by the open source voting system and said that it
could be notarized by the California Secretary of State. He said that an
inexpensive hardware-based key could be used, using standard open source
software methods. He committed to creating instructions on how to use the key.

Member Hage discussed further legal issues related to public and private keys
and suggested having simulated signatures. He added that the committee could
recommend how to process and validate digital signatures.

Chair Jerdonek gave suggestions on how to organize the document. He suggested
adding assumptions to each section and also explaining what one gets from
each recommendation. One can start from a higher level when explaining system
specifications in the technical document.

Member Hage stated that security should be part of the architectural design.
Member Wasserman agreed, stating that security is a key component of any
systems architectural design. He said that principles and preferences can be
identified without stating preferences for a particular vendor or software.

Public comment:

Brent Turner (CAVO) suggested sticking with the initial concept of the
General Public License (GPL) when developing the open source voting software.
He expressed his nervousness about business interests coming in to nuance the
system and licensing for the system.


**8\. Voting System Component Development** - 7:11 p.m.

Member Hage reported that he was able to correlate all the ID's and found
missing data in some of the Department of Election's EMS system. This could
be resolved by using fake ID's.

Member Philips reported that he was researching and prototyping how
machine-learning techniques could be incorporated into the open source voting
system.

Chair Jerdonek reminded OSVTAC about the Sunshine Ordinance and open meeting
laws governing how committee members perform their duties. He discussed
logistics and planning for an upcoming OSVTAC special "working" meeting.
Member Kattouw suggested using a conference room at a San Francisco Public
Library location. Chair Jerdonek asked Secretary Walker to look into
scheduling a space for the special meeting.


**9\. Topics for future discussion** - 7:53 p.m.

No topics were suggested.


**Adjourned at 7:54 p.m.**
