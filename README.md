# WQM
Willamette Quarterly Meeting prototype work: Web-based Direct Directory

Languages:  Python, JavaScript, SQL / noSQL
First public announcement:  
https://groups.yahoo.com/neo/groups/mensgroup_wqm/conversations/messages/100

I'm working on a white paper / proposal to Willamette Quarterly proposing 
that I be allowed to recruit a team of interested parties keen on developing 
a Web-based Direct Directory (WDD) for our WQM region, meaning directory-
relevant data entered by a Friend would immediately propagate through the 
on-line web listing for world-readable sharing, assuming successful 
authentication.

The idea is say 6% - 60% of Friends are willing to have identity information 
made public, though with listee control over exactly what info that is.
Street address?  Mobile?  Twitter?  Facebook?  It's up to you what you want 
shown and to maintain the record in question, though perhaps at least a 
real name (no anonymous nor pseudonymous listers) and at least one meeting 
affiliation would be mandatory.

Motivations:

i)  in part we're just eager to give Friends a direct way to list themselves 
publicly without going through the cumbersome NPYM process, which as of 2016
results in a semi-secret document, nothing on the web.

ii) In addition, having a well of pre-cleared public data, used with permission, 
will enable any number of developers to hack on Direct Directory renderings 
with some real data to chew on, not just phony test data.  Developers won't 
have to worry about keeping the data confidential, though keeping it up to 
date is another matter and should be the job of a specific Github repo.

iii) implementing this directory at the quarterly level allows us to model 
a multi-Monthly Meeting (MM) data structure and perhaps even direct data 
transmits between our site and the WQM meetings. Engaging in these experiments 
does not preclude individual Monthly Meetings from implementing a WebDD (Web-
based Direct Directory) as well.

iv) allowing many developers to prototype with the same data will give 
Monthly Meetings more ideas about how they might modernize, as well as 
NPYM (North Pacific Yearly Meeting) should the latter ever wish to escape 
from the Dark Ages (the age of secretive "black box meetings" which cater 
to the paranoid, at the cost of making our practices less open, less 
transparent, less viable in the longer term).

v) we can become more Unicode friendly, allowing primary names to be spelled 
using characters from outside the Latin alphabet -- i18n (internationalization)
is an important way to advertise our global awareness as Liberal (in this 
case "Beanite") Friends.[1]

vi) mobile phone apps might be developed.

We're still in the beginning stages of fleshing out the proposal.  In the 
course of co-organizing publicity for the WQM Mens Group next March (2017),
I'm already in a role necessitating interaction with WQM principals, so 
the conversations will be evolving organically.  I'll update this listserv
(npym-it-discuss, a Google group [2]) from time to time about our progress.

The details involve JSON as a storage format [3] and gradually adding "roles" 
(phase 2) i.e. if a person is currently or even a past clerk of some committee, 
we could show this both in the directory entry, and on our regional timeline.  
However in phase one, we're less focused on roles, given Western Friend is 
already tackling that one.

========

[1] http://www.quaker.org/liberal-history/bean.html

[2] https://groups.google.com/forum/#!forum/npym-it-discuss

[3] Example json:

{'name': 'Kirby Urner',
'alphabetized_on:': 'urner kirby',
'twitter_handle': 'thekirbster',
'facebook_handle': 'thekirbster',
'meetings': ['Multnomah', 'Bridge City Friends']}
