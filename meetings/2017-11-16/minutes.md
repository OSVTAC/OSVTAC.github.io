Meeting Minutes: November 16, 2017


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
Open Source Voting System Technical Advisory Committee<br>
of the San Francisco Elections Commission<br>
Thursday, November 16, 2017<br>
6:00 p.m.<br>
City Hall, Room 421<br>
1 Dr. Carlton B. Goodlett Place<br>
San Francisco, California 94102<br>
</div>

**Order of Business**


**1\. Call to Order & Roll Call**

Chair Jerdonek called the meeting to order at 6:05 p.m. Present: Members
Bafundo, Jerdonek, Kattouw, and Wasserman. Excused absence: Member Hage.
Also present: Secretary Don Chan.


**2\. Project Management and Procurement**

Vice Chair Bafundo introduced Ms. Jessie Posilkin, who was invited to speak
on modular procurement and agile practices in government. Ms. Posilkin is an
Innovation Specialist at GSA / 18F and a colleague of his. She spoke to
the committee via video conferencing. A video recording can be viewed at:
<https://www.youtube.com/watch?v=aI1glu6O5ic>.

Ms. Posilkin began by saying that the principles behind modular procurement
are not far from the basics of software development, that is, when you are
developing software it is better to use a modular approach. Points made
included:

* The larger the RFP and contract amount, the greater and more complex the
  monitoring and review requirements of the funding source are likely to be.
* Historically, such large contracts are burdensome, often unrealistic, and
  often result in cost overruns.
* Using agile practices is about getting “to market more quickly, and
  building things more cheaply and better.”
* It is critical for the Committee to define what are reasonable sizes of
  “chunks” for the project. Member Wasserman asked if, when portioning out
  “chunks,” does she organize it in terms of a collection of user stories
  or some number of “sprints.”  Ms. Posilkin said she discouraged employing
  just user stories, because if there are many, the contract may get too
  specific and not have the flexibility to allow making needed changes.
* Define the constraints of the environment rather than detail what the
  system needs to do.
* List the number of sprints to have definite time-limited development goals.

Member Wasserman asked whether you should have the same contractor do several
“chunks.” Ms. Posilkin replied that you might not want to have the same
contractor. She mentioned that the State of California has a couple of good
vendor pools that we might want to try accessing:

* Develop a pre-qualified vendor pool, with vendors who have passed
  inspection or approval for their services.
* These pre-approved pools are not necessarily based in the area or
  discipline of the product being sought.
* For any custom software development, she would not recommend requiring a
  respondent to have experience with voting systems.

The question was raised as to how you get government funders to fully fund
something that will be built a “block at a time,” when the ultimate product
details and costs are not known up front. She responded that you have to find
a “champion” who gets it and has the power to allocate the funds.

If an RFP doesn't detail outcomes enough, how do you require vendors
to do “additional” tasks? She replied that you shouldn’t think of a contract
as unamendable. Her experience has shown contracts to all the time have
multiple change orders (with costs adjustments) as a common occurrence. She
said the most important element is strict monitoring of the contract.

There was a feeling that in order to assure that a definite product was
obtained at the end of each modular project, there needs to be a “buy-in” by
the City beyond hiring an external intermediary (e.g. a technical lead to
oversee the project). Contracts can be written in terms of target
capabilities, key constraints, and key outcomes so that trade-offs could be
made actively during the development of those increments.

When asked for examples of how specific modular contracts are written, she
said it is not how it is written that determines modularity, but rather how
you are making a format that allows for agile software development.

She mentioned a report from the National Association of State CIOs that lays
out why governments should adopt agile.

There was a discussion about the “granularity” of a contract and how explicit
one should be while giving the contractor the flexibility to work without
restrictive conditions. The wording of the contract is key, but oversight by
the City is critical, and not just contracted out to an outside body for the
responsibility.

Chair Jerdonek said that he had a conversation with Robert Henning, an
Assistant Director of the San Francisco Office of Contracts Administration
(OCA), regarding the project in relation to agile procurement. He was given
information on the City codes that guide the procurement process. He
suggested the idea of the Committee holding a panel discussions where this
topic can be explored with him, the City's Chief Innovation Officer, and the
City's Chief Digital Services Officer.

Key “take-aways” from the presentation: the committee needs to define the key
building blocks or modules, as well as the order of development. The project
needs to be approached incrementally and not as a single deployment. There
can be an accumulation of user stories that cover all potential scenarios of
users (voters), which can then be sequenced to address each particular
problem.

It was suggested that at the next committee meeting, examples of modular
contracts can be examined and discussed. Ms. Posilkin offered to send
examples for review. Member Wasserman said that he would check with Code for
America to see if they have examples. The question of putting award limits on
each contract was raised. Depending on the amount, the process can be more or
less streamlined. For example, if chunks are under $50K or $100K, it might
not need an RFP process.

The product of the contract should be a functional deliverable, and not just
“progress reported”. How to price such a contract was discussed, in terms of
the number of person-years, but no specific figures were agreed on.

Public comment: Mr. Jim Soper stated that the group he is working with is
seeking funds from the California Secretary of State. Any funds from
elsewhere would be helpful in advancing this project.

The idea of enlisting the help of 18F was discussed. No decision was reached.


**3\. General Public Comment**

Mr. Jim Soper mentioned an article he read that said all Intel computer chips
contain a hidden operating system (Minix) on them.

Member Wasserman gave a short explanation of what Minix was (i.e. what it is
turned into on that chip).

**4\. Approval of Minutes of Previous Meetings**

The corrections were as follows. For the September minutes: section 3 should
read “pull request.” In #4 of the numbered list, the word “ballot” is
misspelled. In #11, replace ”reviewed” with “talked through.”

With these corrections, Vice Chair Bafundo moved to approve the draft minutes
for the September 21, 2017 and October 19, 2017 meetings. It was seconded by
Member Kattouw. Upon voice vote, the motion carried unanimously.


**5\. Member Reports**

Vice Chair Bafundo reported that when he worked on the LA project his team
delivered a design document that detailed the philosophy of the project, how
it should be built and why. He had reached out to LA to try and get a copy of
that document but has not heard back. He mentioned a previous colleague,
David McGivney, also involved with that project, who might be called on to
give some insight to its inner workings, either through prepared questions,
or being part of that panel discussion brought up by Chair Jerdonek.

Member Kattouw mentioned his report at the Elections Commission meeting and
some of the discussion items that were dealt with, including a report from
both BOPEC and Slalom, and a memo from Travis County explaining why they are
not going forward with open source. He also mentioned that he submitted a
proposal to speak at LibrePlanet’s March conference. Lastly, he said he heard
that Concord, New Hampshire had used the Prime III system for a local
election.

Member Wasserman raised the idea of Member Kattouw doing his presentation at
a smaller conference as a “practice run” and mentioned SCALE (which will be
held in Pasadena before the LibrePlanet conference).


**6\. Administration**

Chair Jerdonek reviewed the meeting schedule for the rest of the year and
going into next year. The December meeting will be on the 14th. Member
Wasserman will attend the December 20 Elections Commission meeting, Vice
Chair Bafundo will attend the January 17 Commission meeting, and Member
Wasserman is available for the February 21 and March 21 meetings. For next
year the committee will try a second Thursday meeting schedule, but remain
flexible if changes are needed.

Chair Jerdonek reported on changes he made to the website. He said there was
a suggestion that when changes are made to the recommendations document, the
dates of those revisions be indicated as notes within the text.

Vice Chair Bafundo asked if it would be possible to take the document and
work on them at the committee meetings. Chair Jerdonek said maybe it could be
done a section at a time and do updates at the meeting.

Chair Jerdonek raised the topic of licensing the Committee’s work on the
Committee’s website (code and/or content). There needs to be clarification of
who owns the work being developed, and how those copyrights are held. Member
Kattouw has someone he can ask. As a first step, Chair Jerdonek suggested
that the code be issued under the GPLv3 license. He moved that the committee
adopt as a policy that the code in the repository be licensed under GPLv3 or
if a new version comes out, be upgraded to that version, and that the
documentation be clear that contributions are accepted under those terms.
Member Kattouw seconded.

Member Kattouw reviewed some of the aspects of licensing, what kind of
license and updating or commercializing implications there are.

Upon voice vote the motion carried unanimously. Member Kattouw moved that the
recommendations document in the repository be licensed under CC BY-SA 4.0
(the Creative Commons Attribution-ShareAlike 4.0 International License).
Member Wasserman seconded. Upon voice vote, the motion carried unanimously.

It was suggested that the Committee’s policy should be to encourage members
to license their conference presentations under CC BY-SA.

Member Kattouw moved to make it the policy of the Committee to encourage its
members to license presentations they produce about this topic under the
CC BY-SA 4.0 license. Member Wasserman seconded.

Member Kattouw said it was conventional to have a CONTRIBUTING.md document.
Member Wasserman mentioned the possibility of public contributions wanting
recognition. It was noted that the history of such changes is listed in the
document so recognition is technically public. He said to satisfy the legal
attributions of CC BY-SA, it is only necessary to list all of the authors or
provide a link to such a list. If done right, we could reflect the authors of
every change using Git.

Chair Jerdonek said that Member Hage would need to agree before the
recommendations document can be licensed since Member Hage has contributed
some text to the document and he is not present today.

He also mentioned that the next Committee report to the Commission is due in
January. Vice Chair Bafundo volunteered to draft it.


**7\. Committee Goals and Assumptions**

Vice Chair Bafundo asked if the Committee has had any discussion of open
source and what needs to be open source, and whether the Committee adopted a
policy on this. For example, can some components like the tally system not
be? The main points brought up were: components should be prioritized for
which are "critical path" components or part of the core of the system (e.g.
the tally system), and those should be recommended as open source. Other
components may or may not demand this (e.g. if an existing, private-vendor
component is cheaper and can be interweaved with the other open source
components). It was noted that sometimes using a private vendor’s product may
limit what open source components can be developed. He said that the
Committee should seek for as much of the system as possible to be open
source, but if compromises have to be made, do it on the back end.

**8\. Project Background and Terminology**

Chair Jerdonek noted the copy of the application from LA County to the
Secretary of State for certification of their Tally System and found it very
lacking in information. Member Kattouw said such applications are many times
used as “place holders” where they come back and fill in the dearth of
details. This might be an attempt to get a partial system certified and not a
complete system.

Chair Jerdonek mentioned an article sent to him by Dr. Juan Gilbert about the
Prime III system in New Hampshire. He also said he learned that it has been
modified from its original form without those changes being public, so that
it is technically no longer open source.

Member Kattouw mentioned seeing a task opened on the Colorado project that
said “Discussion: precise choice for open source license.” It names AGPLv3
with classpath exception.

Chair Jerdonek commented that STAR-Vote (Travis County) did not take an agile
approach and tried to do everything all at once.

Member Hage sent an email to Chair Jerdonek compiling research he had done on
other open source voting system projects. There should be a section in the
recommendations document that summarizes these projects. Member Hage’s
document can be discussed at the next meeting.

Chair Jerdonek asked to put a link in the recommendations document to the LA
submission. Member Kattouw so moved, seconded by Chair Jerdonek. Upon voice
vote, the motion carried unanimously.


**9\. Committee Recommendations**

At a previous meeting the subject of interpreted programming languages was
brought up. Chair Jerdonek said he researched this and found out that the
VVSG (voluntary voting systems guidelines) has gone through three iterations,
and that the latest version adopted in March 2015 removed the prohibition on
interpreted languages.

Member Kattouw brought up a question from Chair Jerdonek around his use of
the word reproducible (vis-à-vis building open source systems), and he
clarified that to mean something that could be taken and independently built
by other government bodies.

Chair Jerdonek mentioned some other items to be discussed: 1) concern for
patent infringement, 2) should the City own the copyright or dual copyright
between vendor and City. There was a short discussion about types of
copyrights and the benefits and implications of each (e.g. single, dual, or
multiple). 3) He had another test recommendation where test cases are
separate from the code. There was a short discussion regarding the use of
digital ballot images for independent testing of results.

The term “digital ballot picture” was previously chosen over using the term
“digital ballot image.”


**10\. Topics for future discussion**

* Detail modularity in terms of procurement (breaking into manageable
  “clumps”) to be agile-friendly. Chair Jerdonek listed three things to be
  considered: 1) the principles behind this, 2) the sequencing of the
  components, and 3) the process by which to procure those modules. Member
  Wasserman cautioned that we shouldn’t over constrain the RFP writers or
  responders. Vice Chair Bafundo offered to draft this up. Member Wasserman
  said he would be happy to review that draft.
* Take the procurement section to review and detail out (e.g. sequence of
  modules, principles and approaches for issuing RFPs for modules, and the
  procurement process).
* Incremental approaches, or just the recommendations section in general.

**Adjourned at 9:34 p.m.**
