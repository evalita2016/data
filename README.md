EVALITA
==========

EVALITA is a periodic evaluation campaign of Natural Language Processing (NLP) and speech tools for the Italian language.

The general objective of EVALITA is to promote the development of language and speech technologies for the Italian language, providing a shared framework where different systems and approaches can be evaluated in a consistent manner.

The diffusion of shared tasks and shared evaluation practices is a crucial step towards the development of resources and tools for NLP and speech sciences. The good response obtained by EVALITA, both in the number of participants and in the quality of results, showed that it is worth pursuing such goals for the Italian language.

As a side effect of the evaluation campaign, both training and test data are available to the scientific community as benchmarks for future improvements.

EVALITA is an initiative of the Italian Association for [Computational Linguistics (AILC)](http://www.ai-lc.it/) and it is endorsed by the [Italian Association for Artificial Intelligence (AI*IA)](http://www.aixia.it/) and the [Italian Association for Speech Sciences (AISV)](http://www.aisv.it/index.php).

http://www.evalita.it/

EVALITA 2016
===============

The 5th evaluation campaign EVALITA 2016 was organized along the following selected tasks:
* [ArtiPhon](http://www.evalita.it/2016/tasks/artiphon) - Articulatory Phone Recognition
* [FactA](http://www.evalita.it/2016/tasks/facta) - Event Factuality Annotation
* [NEEL-IT](http://www.evalita.it/2016/tasks/neel-it) - Named Entity rEcognition and Linking in Italian Tweets
* [PoSTWITA](http://www.evalita.it/2016/tasks/postwita) - POS tagging for Italian Social Media Texts
* [QA­4FAQ](http://www.evalita.it/2016/tasks/qa%C2%ADfaq) - Question Answering for Frequently Asked Questions
* [SENTIPOLC](http://www.evalita.it/2016/tasks/sentipolc) - SENTIment POLarity Classification

EVALITA 2016 is an initiative of [AILC](http://www.ai-lc.it/) (Associazione Italiana di Linguistica Computazionale).

Proceedings are available on the [CEUR open access platform](http://ceur-ws.org/Vol-1749/) and on the [aAccademia University Press website](http://www.aaccademia.it/scheda-libro?aaref=870).

Read the [Storify story](https://storify.com/EVALITAcampaign/evalita-2016-workshop) on the final workshop.

Follow EVALITA 2016 on [Twitter](https://twitter.com/EVALITAcampaign) and [Facebook](https://www.facebook.com/evalita2016/) and use the hashtag #EVALITA2016 to disseminate the initiative!!

DATA
=======

Data repository structure:

|-*artiphone: ArtiPhon data*<br>
|----cnz_1.0.0<br>
|----test\_artiphone\_lables.zip<br>
|-*facta: FactA data*<br>
|----evalita2016\_facta\_gold\_pilot.tsv<br>
|----evalita2016\_facta\_tweet\_id\_pilot<br>
|-*neelit: NEEL-IT data*<br>
|----neel-it16\_dev-set\_v4: training set folder<br>
|----neel-it\_evalita2016-nil.gold.idfix: goldstandard annotations<br>
|----neel-it\_evalita2016\_v3.data.gold.test: Test set<br>
|-*postwita: PoSTWITA data*<br>
|-----goldDEVset-2016\_09\_05.txt: training set data<br>
|-----goldTESTset-2016_09_12.txt: test set data<br>
|-*qa4faq: QA4FAQ data*<br>
|-----qa4faq\_dev\_v3: training data folder<br>
|-----qa4faq\_qrel: relevance judgments<br>
|-----qa4faq\_qrel.trec: relevance judgments (TREC format)<br>
|-----qa4faq_question: questions for testing<br>
|-*sentipolc: SENTIPOLC data*<br>
|-----sentipolc16\_gold2000.csv: test set<br>
|-----sentipolc16\_officialdistrib\_train.csv: training set<br>
|-shared: Files in this directory contain tweet ids shared between tasks<br>
|-EVALITA 2016 overview: Overview of the 5th Evaluation Campaign
of Natural Language Processing and Speech Tools for Italian

Each task folder contains a PDF document that describes the task and data format. You can find further information on the website of each task.

If you use these data in writing scientific papers, or you use this data in any other medium serving scientists or students (e.g. web-sites, CD-ROMs) please include the following citation:

@CONFERENCE{Evalita2016,<br>
author={Basile, P. and Cutugno, F. and Nissim, M. and Patti, V. and Sprugnoli, R.},<br>
title={EVALITA 2016: Overview of the 5th evaluation campaign of natural language processing and speech tools for Italian},<br>
journal={CEUR Workshop Proceedings},<br>
year={2016},<br>
volume={1749},<br>
}

LICENSE
==========

*Attribution-NonCommercial-ShareAlike 3.0 Italy (CC BY-NC-SA 3.0 IT)*

You are free to:
* Share — copy and redistribute the material in any medium or format
* Adapt — remix, transform, and build upon the material

The licensor cannot revoke these freedoms as long as you follow the license terms.

Under the following terms:
* Attribution — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
* NonCommercial — You may not use the material for commercial purposes.
* ShareAlike — If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.
* No additional restrictions — You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.

Notices:
* You do not have to comply with the license for elements of the material in the public domain or where your use is permitted by an applicable exception or limitation.
* No warranties are given. The license may not give you all of the permissions necessary for your intended use. For example, other rights such as publicity, privacy, or moral rights may limit how you use the material.

https://creativecommons.org/licenses/by-nc-sa/3.0/it/deed.en
