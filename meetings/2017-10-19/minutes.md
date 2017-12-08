Draft Meeting Minutes: October 19, 2017

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
Thursday, October 19, 2017<br>
</div>

**Order of Business**

**1\. Call to Order & Roll Call**

The meeting was called to order at 6:03 p.m. Present: Members Jerdonek,
Kattouw, and Wasserman. Absent: Member Hage. Excused absent: Member Bafundo.
Also present: Secretary Don Chan.

**2\. General Public Comment**

None.

**3\. Approval of Minutes of Previous Meeting**

This item was postponed to the next meeting.

**4\. Member Reports**

Chair Jerdonek reported: 1) the Department finalized its contract with
Slalom. He met with their team and is very happy they are going to have a
staff person on site while doing the work. They are aware of the Elections
Commission and the TAC, and he’s encouraged that they will be responsive. 2)
He met with Carrie Bishop, San Francisco's new Chief Digital Services
Officer, and discussed open source voting with her. 3) He presented on open
source voting at an elections conference in Berkeley. 4) The Commission
passed a motion last night to encourage the Department to review the
Committee’s recommendations. 5) The Director is working on the RFP on the
interim voting system, and it should be rolled out in the next few weeks. 6)
Member Hage sent an email to the Committee regarding some other voting
projects that are occurring.

Member Kattouw mentioned that he went to a portion of the Berkeley conference.
He also reported to the Elections Commission last night.

Member Wasserman reported that he spoke at an open source conference in
Bangalore in India. Member Kattouw said that he was going to Bangalore
tomorrow.

Chair Jerdonek reported that the Travis County project has been cancelled,
and Los Angeles County submitted a part of their project (Tally System
Version 1.0) to the Secretary of State for certification.

**5\. Administration**

Chair Jerdonek is considering making a page for each section in addition to a
single-page view for the entire document. He is still considering how best to
process suggestions received. He said he will be asking members for bios
to be put on the site.

On the issue of how to get the TAC’s recommendations reviewed, a public
speaker at the Commission meeting suggested that presentations on specific
areas of higher priority could be made at Commission meetings so that the
Department and Commission can learn about them.

Dates for the next couple of committee meetings and who would be presenting
at the Commission meetings was agreed upon.

On the question of patch files and GitHub PR's, Chair Jerdonek said it is
okay to make a PR provided the patch file has already been made public
in the agenda packet.

**6\. Presentations by Committee Members**

Member Wasserman asked about whether the Committee should include public
speaking opportunities as duties for the members, so that the greater open
source community can learn about what San Francisco is doing toward that
goal. Member Kattouw mentioned some notices he had gotten inviting him to
speak, as had Member Wasserman. Both are happy to include speaking about San
Francisco in their presentations. Chair Jerdonek said the Deputy City
Attorney thought it would be fine if the Committee authorized members to
speak on behalf of the Committee, but if the venue was not approved by the
Committee, the member could still speak as an individual and not as a
representative of the committee.

Member Kattouw mentioned LibrePlanet and Member Wasserman mentioned OSCON as
upcoming conferences. Member Wasserman asked if it could be the policy of the
Committee to encourage its members to make others aware of the San Francisco
project, via conferences and other venues.

Chair Jerdonek moved to approve the two venues mentioned for members
Wasserman and Kattouw to present at, seconded by Member Wasserman. Member
Wasserman amended the motion to include a statement of principle that the
Committee encourage its members to make the wider open-source community aware
of the project via conferences and other venues.

Upon voice vote the motion carried unanimously, 3-0.

**7\. Responses to the Business Case RFP**

Member Wasserman had asked for this at the last meeting. It is included in
the packet of materials. Chair Jerdonek said Slalom suggested looking at the
two appendices, which give more specific detail on their scope of work.

Member Kattouw spoke favorably about several aspects of the contract, and
said the general overview was positive. Member Wasserman agreed. Chair
Jerdonek said there are challenges about what to build, how to divide it up
and build it, what the manufacturing costs are, and how to ensure the project
would be free of patent conflicts.

Another point brought up was doing a comparison of the costs of the two types
of systems (proprietary versus open source).

**8\. Committee Goals and Assumptions**

Chair Jerdonek commented that the remaining agenda items generally correspond
to sections of the TAC recommendations document on the website. He offered
some language edits. For one (in the non-goals sub-section), it should be
clarified that the Committee is not making recommendations on vendors, but
about systems. In the Assumptions section he recommended that it be separated
into Facts and Assumptions because certain things are facts as opposed to
assumptions. Specifically, he broke out choice of license and when the
software should be open source (namely from the beginning). He also added
that the voting system should not require the counting of votes and ballots
by hand, notwithstanding audits and recounts.

There was a short discussion about the question of security. Member
Wasserman offered a sentence that said, “independent studies have shown that
in general open source software is neither more nor less secure than
proprietary software" and suggested adding a reference to the Coverity
study.

There was a short discussion regarding the security of hardware, and there
was no answer to it. As to the measure of how open source the system is,
there were thoughts that it should be reproducible, and its software should
comply with OSI's Open Source Definition.

Public Comment:

Mr. Jim Soper described the past case of Jeffrey Dean, an embezzler, who
worked for Diebold. He commented that he’s worried about the “insiders” who
would have access to corrupting the code used for a voting system. That is
why open source is critical.

Member Wasserman read a definition of open source.

Chair Jerdonek asked for a motion. Member Kattouw moved to approve Chair
Jerdonek’s changes as discussed. Member Wasserman seconded. Upon voice vote
the motion carried unanimously 3-0.

**9\. Project Background and Terminology**

Member Kattouw reviewed his comments in the packet. Chair Jerdonek suggested
to include a response and link to the contract. He then reviewed his
documents in the packet. In regards to Other Projects, he wanted to get on
the record certain facts around the Travis County and Los Angeles County
projects and in particular if they are open source or not.

There is a further explanation of the Dominion system and its cost. Later in
the document he discusses the term EMS as it is used by the City and how it
is defined in the VVSG, so he is using the name of the product: EIMS. He
broke out the software components for precinct ballot scanners and central
ballot scanners, and stubbed out the glossary.

Chair Jerdonek said he wanted to make Resources a part of Background, add a
link in Resources to the City’s Digital Services Team, and mention that Los
Angeles' Tally System was submitted for certification.

He also said he thought it better to refer to digital ballot image as digital
ballot picture. This seemed agreeable to the members.

He also raised the question of the certification of the Tally System
component of Los Angeles's VSAP, and why the code did not seem to be
available. They do not know if this is open source or not, nor whether this
indicated that portions of a system could be certified without an entire
system being reviewed. Director Arntz did not have information about this
either. It is something the Committee should inquire into.

Member Wasserman mentioned the open source used in Brazil, versus what is
described for Los Angeles. A question was raised as to the ability to do a
FOIA for open source code.

Public Comment:

Mr. Jim Soper spoke about tabulators and that a recommendation could be that
such things must be made easily uploaded to the internet in spreadsheet
format. Other comments from committee members included making recommendations
on open data, definition of open data, and what it means to be publishable.

Member Kattouw moved to adopt the changes written in the documents, and
seconded by Chair Jerdonek. Upon voice vote the motion carried unanimously,
3-0.

Chair Jerdonek asked if anyone wanted to work on the glossary terms. Member
Kattouw suggested Member Hage.

**10\. Project Management and Procurement**

Chair Jerdonek reviewed the revisions he made, which make it easier to
follow. He added one more intermediate phase, which was suggested by Director
Arntz, where a ballot image interpreter could be used. Director Arntz was
amenable to making all the ballot pictures available for inspection.

Member Kattouw will work on the wording of having a "shim" being provided for
testing. Member Wasserman suggested language that asks for executable
deliverables after specific time periods of development. It was suggested to
get Member Bafundo’s thoughts on this. Chair Jerdonek stated that he wanted
to get away from the Department having to list extensive requirements in an
RFP. He felt that the Chief Digital Services Officer agreed.

He added a note about doing the central ballot scanner first being similar to
what Los Angeles submitted to the Secretary of State, so that San Francisco
isn’t “inventing” this concept.

A deeper discussion on project management can be held when Member Bafundo and
Member Hage are present.

Chair Jerdonek moved to adopt the language he added along with reference to
Los Angeles's submission. Member Kattouw seconded. Upon voice vote the motion
carried unanimously, 3-0.

**11\. Committee Recommendations**

Member Kattouw reviewed his patch files.

Chair Jerdonek asked if he purposely did not specify that the system had to
be built using open source tools. Maybe the language needs firming up to say
that the production version cannot be run on something that is not open
source. Member Kattouw will work on this for next meeting.

The final patch on software reuse encourages the use of open source libraries
and software under OSI licenses.

Member Kattouw discussed his feelings about licensing, which is a complex
topic. Chair Jerdonek suggested using the words, "when possible," to use dual
licensing. Member Kattouw said that he would prefer using the better
component rather than the component having copyleft licensing. Quality is
more important. Chair Jerdonek commented that when TAC makes recommendations
that affirm a position taken by the Commission, then that could be cited so
the Committee doesn't seem alone in its position.

There was a discussion about whether the system infrastructure should be
updated in-house or by professional services, in particular with respect to
security patches.

Jim Soper mentioned during public comment that the VVSG disallowed
interpreted languages due to the possibility of self-modifying code.

Member Kattouw wondered whether this restriction applied even to components
that are not in the "critical path."

Member Kattouw moved to adopt the changes for #11 with the inclusion of “if
possible” at the end of the wording around dual-licensing.

Chair Jerdonek suggested that language referencing the Commission’s
resolutions be included in the approved wording.

Member Wasserman seconded the motion and upon voice vote the motion carried
unanimously 3-0.

Chair Jerdonek brought up a question about open hardware and what it is. There
is an open hardware association. Basically, it is having blueprints and
permission to manufacture the hardware yourself. Member Kattouw commented
that the project should not have "vendor lock-in” where only a particular
vendor could produce the hardware needed.

Public Comment:

Mr. Jim Soper said that Los Angeles will have to "single-source" the
production of a thermal printer that prints a special format.

A discussion followed regarding the benefits of open hardware versus
proprietary, and if it is more important to have easy availability over being
open, and being current technology and not obsolete. No decision was reached,
but it was considered important to have some language acknowledging the topic.

**12\. Topics for future discussion**

Chair Jerdonek suggested:

* Patent infringement / avoidance
* Specifics on project management / procurement
* Standards and open data (Member Hage to elaborate)

Public comment:

Mr. Jim Soper offered to find out more about what happened in Texas.

Chair Jerdonek commented that they didn’t have a wide community support and
their primary goal didn’t seem to be attaining open source status.

**Adjourned at 8:26 p.m.**
