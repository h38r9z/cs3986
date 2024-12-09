java c
Coursework   for   COMP4132   24-25
OverviewThe   coursework   aims to   make   use of the   machine   learning techniques   learned from this   module   to   solve   a   practical   problem. The   coursework   consists   of three   key   parts:   1)   main   submission:   coursework   report   and code, 2)   Individual   report, 3)   presentation.
Please   read   this   document   carefully   to   see   the   requirement   of   the   coursework   and   the   explanations   and   further   details.
Important   dates
•          Team formation:   26th   Nov   2024
•            Final submission deadline: 23th   Dec   2024
•            Presentations:   24th   Dec   2024
Copying   Code   and   PlagiarismYou may freely copy and adapt any of the code samples   provided   in the   lab   exercises   or   lectures. You   may   freely   copy   code   samples   from   the   PyTorch   documentation,   which   have   many   examples   explaining   how   to do specific tasks. This coursework assumes that you will do so and   doing   so   is   apart   of the   coursework.   You   are   therefore   not   passing   someone   else’s   code   off   as   your   own,   thus   doing   so   does   not   count   as   plagiarism.You can, and you should look at other code/papers online, but you   need to   reference any   source/material   that   you   have   used   as   inspiration,   and   highlight   what’s   your   contribution.   Turnitin/JPlag   will   detect   any   use   of   external   sources   automatically.   Successful   completion   means   that   you   are   able   to   explain   your   solution   during the   presentations. The   university takes   plagiarism   extremely   seriously   and this   can   result   in getting 0 for the group coursework, the   entire   module,   or   potentially   much worse.
Getting   HelpYou   MAY ask the   module convenor for help in   understanding the group   coursework   requirements   if they      are   not   clear   (i.e.   what   you   need   to   achieve).   Talk   to   me   during   the   labs,   after   the   lecture,   or   post   your   questions   on   Moodle.   Any   necessary   clarifications   will   then   be   added   to   the   Moodle   page   or   posted   on   the   discussion   forum   so   that   everyone   can   see   them.   You   may   NOT   get   help   from   anybody   else   (other      than   your   group   mates)   to   actually   do   the   coursework   (i.e.   how   to   do   it), including the module convenor.
Task   SpecificationThe   aim   of this   coursework   is to   offer you   an   opportunity to   put your   hands   on   designing/developing   an   advanced machine   learning   based solution.   Language   Models (LM) are very   popular   nowadays in the   area   of   Natural   Language   Processing.   In this coursework you are asked to   use   LM together with other   machine   learning techniques   learned   in this   module to solve the   problem of joke generation.   In   particular, you are   expected to   provide a   machine   learning   based solution that   is able to generate   a joke given an   input   such   as a few starting words, similar to one of your   lab exercises   but   much more   compherensive. Your   solution   should   beat   least satisfying the following   requirement:
•          Be able   to   generate   a   full joke which   may   consists   of several   sentences.
•          The    generated   joke   should   at   least   make   some   sense   compared   with   say   random   generation,   based on the   data you   used.
•          Additional functionalities that   make the solution   better.Note that you may not have enough resources (i.e.   GPUs) to   perform   a thorough training. You can useless   data for the training   in your   laptop or you can   use online   resources such as Google Colab. You   can   use the   lab   as   a   starting   point   but   your   solution   should   not   be   the   same   as the   labsolution.   You   should   usethis   datasetas   the   training   data.
Team   Formation   InstructionsYou   should   form   groups   of   at   most   three   students.   The   group   contributions   on   the   coursework   will   be   assessed,   but   also   each   individual   effort.   Each   group   should   select   one   person   as   the   Team   leader.   The   team      leader    will      be    in      charge      of      organising       meetings,    team      coordination,    group      submissions      and   communications.    During   the    lab    session    on    26th       Nov,    you    will    form.    your   group.   You   can   talk   to   the   convenor for   better   understanding of the coursework.
Coursework   Report   (main   submission)The   report   must   be   clearly   presented   in   English   with   no   more than 4000   words,   excluding   all the figures   and tables,   summarizing   how the task   is   done, justification   on your   decisions   involved,   and the   results   of your analysis. This   report should   be submitted   (with code) via   Moodle   by the   due   date. The   folder   should   be   named   by the group   id   (to   be assigned).
The   submission   should   cover   the   following:
1.         Team   ID   (assigned   by the   module convenor), student   names and   Ids.
2.          Introduction   presents the aims, the   problem you   solved,   and   outlines the   solution.
3.          Methodology   focuses   on   the   reasoning   for   the   certain   techniques   and   designs   that   you   used   in   this coursework. This describes and explains your chosen methods and design. It is very   important   to elaborate why you design your solution   in your   way.
4.          Result and discussion contains   a   description   and   analysis   of   the   results.
5.          Conclusion   allows   you   to   have   the   final   say   on   the   issues   you   have    raised   in   this   coursework,   synthesize your thoughts, demonstrate the   rationale of your solution.
6.          Reference   if there are   links,   papers, codes   are   used.
CodeAll the code, and documentation files   should   be   submitted with   the   main   submission   via   Moodle.   You   do   not   need to   upload   the   model   if   it   is   too   big.   Instead   you   can   put   in   on   online   storage   such   as   one   drive   and   baidu disk and   put the   link together with the   documentation.The 代 写Coursework for COMP4132 24-25R
代做程序编程语言  code   should   contain   a   README   file   explaining   all   the   included   materials,   and   references   to   other   codes/papers you   have   used for   inspiration.   Moreover,   some   brief documentation(s)   should   be   provided   for each code file to explain   the   code   structure   and   describe   how to   use   the   code   and   data.
Individual   Report
Each   member of a team   is expected to submit   a two-page   report   including   the   following:
1.         The student   information   including full   name, email, and   ID.
2.          A      table      of      participation      marks:    this       should      provide      marks    to       show       how      group      members   contributed/collaborated to the coursework. This table should have three columns, 1) student full   name, 2) a   mark out of   10 and   3)   one   (or   maximum   two)   sentence(s)   for   making justification.
Student   name
Mark   (out of   10)
Marking justification
   
   
   
3.         A   brief   explanation   of   the   individual   role   in   the   coursework   outlining   the   offered   contributions   (Maximum one   page).
4.         A   discussion of   individual   understandings, findings,   and   reflections on the   coursework and team-   working (Maximum one   page).
This   report   should   be   submitted   by   each   student via   Moodle,   a   separate   submission. The   format   should   be:
“Student   Number.   Pdf”   (e.g.,   20029784.pdf)
This will   be   used to assess the   role of each   individual   in the coursework. This   report   also   might   be   used to   ask   relevant questions during the   presentation.
Presentation
All   the   teams   will   present   orally   24th   Dec.   For   this,   all   group   members   will   be   required   to   be   present   to
deliver a   presentation and answer questions from   attendees   and   module   convenor.   The   presentations are open for   all the   students.
All oral sessions will follow a similar structure to how they are held in atypical physical conference format.
•          The   module convenor will   introduce   each group.
•          The   authors   will   deliver   the    presentation   (8   minutes   maximum)   for   the   audience.   Please   make   sure you   practice this   before the session.
•          Once   the    presentation    has   concluded,   the   module   convenor   will   facilitate   a   live   QA   period   (3   minutes approx.) with the audience and the   module convenor.
•          Process   repeats for   each   subsequent   group   in the   session.
Presentation tips
•          Please   use a   template   to   make   your   presentation   slides,   it   will   be   available   on   Moodle.
•          Suggest   having   maximum 8   slides,   1   slide   a   minute.
•          You   need to   upload your   presentation file on   Moodle,   (one   day)   before the   presentation.
•          Start off with a   brief   introduction   of   yourselves   and   the   key   focus   of your   coursework.
o   This should outline the contributions of each   student   in   the   coursework.
•          The outline of the presentation should be similar to the structure of the coursework      (e.g.   introduction and   motivation,   methodology, experimental set-up,   results, and conclusions).


•          It   is   a   8-min   presentation,   do   not   aim   to   show   every   single   aspect   of your   coursework,   focus   on   the   most   important things/findings.   Key   points:   Make sure you state   clearly your   motivation   and   how good your solution   is.
•          Be   ready   for   any   question   and   discuss   your   contribution.   You   can   prepare   additional   slides/files   for any potential questions you expect. You maybe asked to explain your solution, and even show   your   code,   so   please   make   sure   that   one   appointed   member   of the   group   can   share   the   screen   and show the coursework   and the   code.
•          All   members should contribute during   the   presentation.
Coursework   Marking   Criteria
•          Individual   Report   (10   marks): Each member of   the team is expected to submit an individual report.
o   Active   role
               Does the student actively   participate   in the coursework?
               What   are the   student’s   contributions to the   coursework?   How they   are   relevant   and valuable?
o   Understanding
               Does    the      report    show      a    fair      student’s       reflection    and       understanding    of      the   coursework?
               Does the report clearly highlight the key findings of   the student in the coursework?
•          Main   Submission   (70   marks):   Each group   should   submit   report   of their   machine   learning solution      together with the code   produced.
o   Introduction
               Do   the   team   understand   the   overall   aims   and   the   problem   to   be   solved   in   this   coursework?
               Do they   provide a clear description of the   solution   provided?
o   Design/Methodology
               Explanation of the   methodology.
               Justification of the   proposed   methodology..
o   Experiments   and   results
               Are the experiments well designed to test the   proposed   solutions?
               Do the   results support the original   idea?
               Is the analysis   coherent?
o   Writing
               Clear description,   reproducibility
               Quality of visual elements, illustrations, tables.
               Quality of   References
o   Code   and   data   -   software   quality
               Efficiency, clarity of the code   to   solve the   problem
               Documentation
•          Group   Presentation   (20   marks):   Each   group   is   asked to   deliver   a   8-min   presentation   summarising      their contribution +   3   mins for   QA.
o   Quality and clarity of the   presentation
o   Response to   questions from the   module convenor   and   public
o   Understanding of their solution
o   Individual    participation    in    the    presentation.    All    members    are    expected    to    participate   equally.



   

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
