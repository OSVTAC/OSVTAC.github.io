Draft Meeting Minutes: December 6, 2018

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
MEETING MINUTES (DRAFT)<br>
Open Source Voting System Technical Advisory Committee (OSVTAC)<br>
of the San Francisco Elections Commission<br>
Thursday, December 6, 2018<br>
6:00 p.m.<br>
City Hall, Room 479<br>
1 Dr. Carlton B. Goodlett Place<br>
San Francisco, California 94102<br>
</div>

**Order of Business**

**1\. Call to Order & Roll Call**

Chair Jerdonek called the meeting to order at 6:03 p.m. Present: Members
Hage, Jerdonek, and Wasserman. Member Kattouw arrived late during item #3 at
6:05 p.m. Member Philips was absent (excused). Also present: Secretary Chan.


**2\. General Public Comment**

No members of the public were present during the meeting, so there was no
public comment on any of the agenda items.


**3\. Approval of Minutes of Previous Meeting**

The Committee discussed the draft minutes. Member Kattouw said item #7 should
reflect that he did like the JS Foundation CLA, but that it did not include
mention of patent grants.

Member Wasserman commented that the two sentences for item #9 attributed to
him do not follow. The first sentence was to indicate that he felt that the
Department of Technology (DT) should keep the Committee’s recommendations in
mind as they work on the open source voting project to ensure that the
project uses good practices. The second sentence referred to the issue of
security in an unclear fashion, so it can be stricken.

With those corrections, Member Kattouw moved to approve, seconded by Member
Wasserman. Upon voice vote, the motion carried unanimously 4-0.


**4\. Administration**

Chair Jerdonek said he would check to see whether Member Philips can attend
the next Commission meeting to report for TAC. If not, then Chair Jerdonek
will do it. The next TAC meeting will be January 10. All present said they
can make it.

Chair Jerdonek mentioned that his term on the Commission ends January 1 (with
a maximum 60-day holdover), and he will apply to the Board of Supervisors for
reappointment for a second term.

Secretary Chan announced that he has informed the Commission he intends to
resign, but the specific date has not been set.

The Committee discussed its "tri-annual" report due to the Commission in
January, but without a specific date. Member Wasserman said it should include
significant things that have happened (e.g. DT’s plan, Member Philips
joining, the open source results reporter being worked on) and have some
“take-aways.” It was agreed to have a draft to review at the next committee
meeting. Member Kattouw said he might be able to do one by the end of
December, but if others have the time also, they should do it instead.

Chair Jerdonek said that he would review Member Kattouw's pull requests to
bring the recommendations document on TAC's website up to speed with what TAC
has voted on.


**5\. Member Reports**

Member Wasserman went to a conference on open source compliance organized by
KPMG. They looked at existing compliance efforts and tools. He mentioned a
group called the OpenChain Project
([https://www.openchainproject.org](https://www.openchainproject.org)), which
is one of the Linux Foundation's projects. It seeks to put together
compliance standards for open source projects. He also mentioned the TODO
group ([https://todogroup.org](https://todogroup.org)). The standards or
guidelines are intended to help people and organizations using or building
open source software to keep it in compliance with all the licenses attached
to it in its development.

There was a discussion about how the Department carried out the random
selection of precincts for the 1% public manual tally. Members Kattouw and
Wasserman attended the Department’s selection for the count. They were the
only members of the public in attendance. The process carried out did not
follow exactly what was documented. Namely, the precincts selected are to be
audited completely. The "extra" precincts are only to audit the races that
were not covered in those first selected. They actually audited more than
what was required by regulations.

Chair Jerdonek reported that to his knowledge DT has not yet hired the
project manager.


**6\. Voting System Security**

Member Hage spoke about the sample data he downloaded from the City. The City
uses the SHA-512 hash rather than SHA-256, which TAC's open results reporter
(ORR) currently uses. Member Hage wanted to know if TAC had a preference. It
affects the final presentation format.

Member Hage commented that if they had the file that contained all the hashes
of the data, he could create a detached signature for the file and then sign
everything. If multiple signatures were desired they could add a suffix into
the signature file. He said they could try this on their sample data and
track the data that’s created from that.

The Committee discussed different scenarios using digital keys. On the
question of having a digital key for sign-on to their records, should there
be a single key or multiple keys, single verification or multiple
simultaneous verifications, etc? Chair Jerdonek wanted to have a description
of the workflow and caveats (e.g. possible problem scenarios and the effect,
like if one key is lost).

There was mention about the ways some certificates of authority and
verification work, with different layers of access for key holders.

There was a question of whether the City needs to have a digital signature
for protecting its software and hardware, and what the Committee should
recommend for that. If the Committee begins to use one itself, this can go on
to show how it can be used by the City. Chair Jerdonek said it would be good
to develop a statement that would lay out what DT should do in regards to
this question and what the costs would be.

Chair Jerdonek asked if any member could produce a paper that summarizes the
issues and possible solutions. Member Hage will set up a process for the
Committee’s sample data that will include a digital signature (key) and an
explanation of how it will work.


**7\. Contributor License Agreements (CLA's) for OSVTAC Projects**

Member Kattouw reviewed the CLA, which he revised following TAC's discussion
at the last meeting. He said that it now includes the statement that they can
re-license any contribution to any license approved by the open source
initiative, including both permissive and copyleft licenses.

Chair Jerdonek said he has sent the draft to the Deputy City Attorney for
discussion. He said that he personally had not decided whether he thinks
re-licensing to a permissive license should be allowed or not. Member Hage
remembered that Member Philips said more people are moving toward less
restrictive licensing. Member Wasserman said that many are going with static
linking versus dynamic linking, which presents problems with LGPL (the Lesser
General Public License). Member Kattouw brought up that some licenses are
one-way compatible, where you might be able to incorporate another’s
software, but not vice versa. There was a discussion around containers and
means of distribution of software.


**8\. Voting System Component Development**

Member Hage said he completed the data converter, but he still needs to write
a correlator. He’s working with the JSON files with some changes. He created
a config file to work with them. He will continue to work on adjustments as
he runs tests and makes changes to refine the capabilities.

Member Kattouw did some basic CSS templates (about 20 lines of CSS) and
showed what it could do. He’ll store this in the ORR repo.

There was a discussion regarding the different codes necessary to identify
ballot items and results (e.g. candidate contests for win/loss/leading/tie)
and other terms. Member Kattouw couldn’t construct the templates that would
display such status.

Chair Jerdonek felt the CSS and other demo display code should not be in the
ORR repo. He suggested rendering what was already from the sample data and
then run the template with the actual data Member Hage has gotten. He asked
Member Hage to add the sample data repository as a sub-module of the demo
repo, and then add a script to the demo repo that basically hard-codes the
relative paths.

Chair Jerdonek said it will be getting more difficult to work independently.
He thought maybe the Committee could list issues they needed/wanted to get
done, and bring those back to be voted on at a meeting.

Member Kattouw will request the following issues: winners and leading
candidates in each round, distinction between real candidates or choices and
metadata like number of voters and number who cast ballots, distinction
between precincts and other areas, and put June and November results into the
demo repo. Chair Jerdonek asked for ORR to have the ability to display a
countywide turnout relative to the number of eligible voters for a more
accurate picture of voter participation. There also needs to be a general
translation table to support multiple languages.

There was a discussion about the semantics of the term ‘over/under vote,’

Member Kattouw mentioned as an aside that the Department had sortable tables.
Clicking any header would sort the table based on that field.

Chair Jerdonek moved for the Committee to agree that the issues Member
Kattouw enumerated are things the Committee wants to work on. Member Hage
seconded. Upon voice vote, the motion carried unanimously 4-0.

Chair Jerdonek further said it would be good for members to think of issues
outside of the meetings.

Chair Jerdonek asked about what Member Philips was working on. Member Hage
summarized the Member Philips was looking into the use of machine learning to
identify target markings on a ballot.


**9\. Topics for future discussion**

One topic was forming a subcommittee if needed to work on ORR and other
components.


**Adjourned at 8:38 p.m.**
