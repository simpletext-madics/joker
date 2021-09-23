# JokeR
  <p align="center">
  <img src="Joker.png" width="120" height="142">
  </p>

[Home](index) | Project | [Partners](partners) | [Contact Us](contact) | [Tools](tools) | [<img src="drapeau FR.png" width="20">](https://motsmachines.github.io/joker/FR/projet)
<br>
  <h1 align="center"><a href="https://motsmachines.github.io/joker/EN">CLEF Workshop JOKER</a>:</h1>
  <h2 align="center">Automatic Pun and Humour Translation</h2>
  <h3>Topics & Goals</h3>
  <p>
The goal is to unify the scientific community interested in automatic localization of humor and puns.  The JokeR project addresses the issue of European identity through the study of humor in a cross-cultural perspective. The main objective of the JokeR project is to study the strategies of localization of humor and puns and to create a multilingual parallel corpus, annotated according to these strategies, open and freely available, as well as evaluation metrics.
  </p>
<h3>Motivation & Relevance to CLEF & Significance for the field</h3>
  <p>
Intercultural communication relies heavily on translation. Humor remains by far one of its most difficult aspects; to understand humor, one often has to grasp implicit cultural references and/or capture double meanings, which of course raises the question of the (in)translatability of humor. Puns are a common source of humor and are used by novelists, poets, and playwrights, as well as in titles, headlines, toponyms, anthroponyms, organizations, and advertising for their attention-getting or mnemonic, playful, subversive, etc. values. The translation of humor and puns is therefore in high demand. Modern translation is heavily aided by technological tools, yet few works have studied the automation of humor and puns translation and the creation of humor corpora. To the best of our knowledge, there does not exist any parallel corpus.
  </p>
  <p>
The <b>multilingual parallel corpus</b> issued as the results of the JokeR workshop will be a step forward in the automatization of humour localization so as to train and evaluate machine translation models. Few <b>monolingual</b> humour corpora exist; for example, datasets created for the tasks of the International Workshop on Semantic Evaluation SemEval <a href="#note1">[1]–[3]</a>: #HashtagWars: Learning a Sense of Humor (2017), Detection and Interpretation of English Puns (2017), Assessing Humor in Edited News Headlines (2020), HaHackathon: Detecting and Rating Humor and Offense (2021). Mihalcea and Strapparava <a href="#note1">[4]</a> collected 16,000 humorous sentences and an equal number of negative samples from news titles, proverbs, British National Corpus, and the Open Mind Common Sense dataset, while another dataset contains 2,400 puns and not-puns from the news, Yahoo!Answers, and proverbs <a href="#note1">[5]</a>, <a href="#note2">[6]</a>. Most datasets are in English; few exceptions in Italian <a href="#note2">[7]</a>, Russian <a href="#note2">[8]</a>, <a href="#note2">[9]</a>, and Spanish <a href="#note2">[10]</a>.
  </p>
<h3>Application domain</h3>
  <p>
The multilingual data and metrics resulting from the JokeR workshop will be a step forward in the automation of humor localization in order to train and evaluate machine translation models. This corpus might also be useful for translation students. 
  </p>
<h3>Evaluation setup, metrics and pilot tasks</h3>
  <p>
The goal of the JOKER workshop is to bring together translators and computer scientists to work on an evaluation framework for creative langage. All types of contributions will be welcomed:
  <ul>
  <li>Research & survey papers</li>
  <li>Position, discussion & demo papers</li>
  <li>Extended abstracts of published papers</li>
  </ul>
However, we will also propose three pilot tasks.
  </p>
  <p>
Data: We have already collected more than 1000 translated puns in English and French from various sources: video games (Enter the Gungeon, Undertale, South Park, League of Legends, Phoenix Wright, Pokemon etc.), advertising slogans, litterature (Shakespeare, Alice, Astérix, Dragons, Harry Potter etc.). Some slogans and punning tweets were translated by our experts. The collected data mainly contains punning named entities, in many cases neologisms. Each pun in each language was classified in several classes (multi-label classification) and explained (how the punning construction is made), e.g. Why is music so painful? Because it HERTZ was annotated as Paronymy (there are slight differences in both spelling and sound) and explained in the following way: Hertz/hurts
  </p>
  <p>
<b>Pilot task 1</b>: Classify and explain a given punning construction in a proper noun or a neologism. The classification will be evaluated by the accuracy, while the explanation will be compared against the gold-standard (exact match).
  </p>
  <p>
<b>Pilot task 2</b>: Translate a given pun from a proper noun or a neologism from English into French.
  </p>
  <p>
<b>Pilot task 3</b>: Translate a given punning phrase from English into French. 
  </p>
  <p>
For the tasks 2& 3, it is necessary to establish metrics for evaluating translation quality. Traditionally, machine translation quality is measured by the BLEU (Bilingual Evaluation Understudy) metric, which calculates vocabulary overlap between the candidate translation and the reference translation <a href="#note11">[11]</a>. However, no metric based on vocabulary overlap is applicable to evaluate creative language translation. First, we will opt for a questionnaire to be filled in by the annotators ("is the wordplay present in the translation?", "is the semantic field preserved in the translation?” etc.). At the end of the workshop, we will study the automation of the selected metrics. 
  </p>
<h3>Organizers</h3>
  <p>
The JOKER workshop involves researchers from computer science and humanities/translation.
  </p>
  <p>
Computer scientists:
  </p>
  <p>
<b>Liana Ermakova (pilot task chair)</b> has been an associate professor at the University of Western Brittany - UBO (Brest, France) since 2017. She participated in the INEX/CLEF Tweet Contextualization task in 2011-2014. She was also one of the organizers of CLEF 2017 Microblog Cultural Contextualization Content Analysis Task, CLEF 2016 Cultural micro-blog Contextualization Workshop, workshop Mots-Machines 2019-2020. She was the leader of the SimpleText@CLEF workshop in 2021. She leads the JOKER project financed by the <a href="https://www.univ-brest.fr/sea-eu/menu/appel-a-projets">SEA-EU search grant</a> and supervises interns https://www.univ-brest.fr/hcti/menu/Membres/Enseignants-chercheurs/Ermakova--Liana
  </p>
  <p>
<b>Tristan Miller</b> (Austrian Research Institute for Artificial Intelligence, Austria) is working on computational detection and interpretation of humour and leads the Computational Pun-derstanding: Computer-Assisted Translation (CAT) of Humorous Wordplay project. Within this project he developed the system PunCAT to assist in pun translation. He co-organized SEMEVAL-2017 shared task on the computational detection and interpretation of puns, SEMEVAL-2021 shared task on learning from disagreements as well as numerous panels at the International Society for Humor Studies Conference.  https://logological.org/ 
  </p>
  <p>
<b>Anne-Gwenn Bosser</b> has been an associate professor at the ENIB (France) since 2013, and a member of Lab-STICC (CNRS UMR 6285) where she leads the COMMEDIA team. Before that, she was a senior lecturer at Teesside University in the UK. She is interested in computational narratives and narrative generation. She co-chaired the International Conference in Interactive Digital Storytelling in 2020. She is a member of the French Association for Artificial Intelligence AFIA and organises a jam on generation of funny and poetic texts.  https://labsticc.fr/en/directory/bosser-anne-gwenn 
  </p>
  <p>Humanities/translation</p>
  <p>
<b>Élise Mathurin</b> has been an associate professor at the University of Western Brittany (Brest, France) since september 2019. Her research focuses on English linguistics. She is a member of the laboratory HCTI EA-4249. She is also the current head of the Master’s degree in translation and interpretation of the University of Western Brittany: Master Rédacteur / Traducteur. E. Mathurin is also involved in the SEA-EU project JokeR and in the organization of the workshops Mots/Machines: Do machines have a sense of humor? She participates in the supervision of JOKER’s interns. 
  </p>
  <p>
<b>Radia Hannachi</b> is an Assistant Professor at the University of South Brittany. Her research interests focus on the use of ICT in language learning and teaching; corpus linguistics and data-driven learning; distance learning, learning-to-learn and autonomisation in language learning. R. Hannachi and S. Araújo will integrate pun translation and analysis in their language/translation classes to enrich the dataset.
  </p>
  <p>
<b>Sílvia Araújo</b> is an Assistant Professor at the Department of Romance Studies of the University of Minho. Her main research interests are corpus linguistics, technologies applied to languages and digital humanities. Related to these areas, she has coordinated projects funded by FCT (<a href="http://per-fide.ilch.uminho.pt/site.pl/index.en">Perfide, PortLinguE</a>). She is director of the Master's Degree in Digital Humanities and a member of the Steering Committee of the Master's Degree in Translation and Multilingual Communication.  Furthermore, she coordinates the techLING annual international conference, devoted to the application of technology to languages and linguistics, which will reach its sixth edition in 2021. http://cehum.ilch.uminho.pt/researchers/25 
  </p>
  <p>
<b>Fabio Regattin</b> is an Assistant Professor at the Department of Language and Literature, Communication, Education and Society of Università degli Studi di Udine (Italy), where he teaches French-Italian translation. He is also a translator, mainly working for publishers and as a drama translator. He recently authored Traduction et évolution culturelle (L'Harmattan, 2018) and Tradurre un classico della scienza (with Ana Pano Alamán, Bononia University Press, 2015); he also edited two volumes on self-translation: Autotraduction - Pratiques, théories, histoires (Emil, 2020) and Gli scrittori si traducono (with Alessandra Ferraro, Emil, 2019). 
  </p>
  <p>
Other colleagues involved in the JOKER project:
  <ul>
    <li>Benoît Jeanjean (HCTI EA-4249, UBO), Latin Professor, translator, chief of the <a href="https://www.univ-brest.fr/libros/">LIBROS+</a> project</li>
    <li>Gaëlle Le Corre (EA 4451 CRBC, UBO), English Linguistics Lecturer</li>
    <li>Mohamed Saki (HCTI EA-4249, UBO), English Linguistics Lecturer</li>
    <li>Sergio Portelli (Associate Professor, Head of Department of Translation, University of Malta)</li>
    <li>Ġorġ Mallia (Media & Communications department, Faculty of Media & Knowledge Sciences, University of Malta), Associate Professor, specialist in humour</li>
    <li>Monika Bokiniec (Department of Aesthetics and Philosophy of Culture, Faculty of Social Sciences, University of Gdansk), Associate Professor, specialist in humour</li>
    <li>Gordan Matas (University of Split, Croatia)</li>
  </ul>
  </p>
  <p>
Interns - Technical Translation/Redaction Master’s Degree’s Students (UBO): Adrien Couaillet, Ludivine Grégoire, Orlane Puchalski
  </p>
<h3>Details of the expected target audience and how to reach them</h3>
  <p>
The  target audience are students and researchers in IR (task 1), NLP (task 2&3), and translation (task 2&3). Students in translation can train neural network models. We will also encourage manual runs (students in translation, foreing language teaching - especially tasks 2 & 3) to enhance data for the next editions. 
  </p>
  <p>
We plan to spread the information via the following channels:
  <ul>
    <li>Mailing lists: SIGIR, info-ic, madics, clef, ntcir, bulle-i3, ln, nlp-seminar, romip, <a href=mailto:"TRANSLATIO@jiscmail.ac.uk">TRANSLATIO@jiscmail.ac.uk</a>, organizers’ university mailing lists</li>
    <li>Social network promotion</li>
    <li>Information on organizers’ personal pages, the JOKER project network</li>
    <li>Advertising Labs at CLEF 2021 and ECIR 2022 and other conferences, workshops and local events, e.g. the Mots-Machines seminar in Brest 2022,  <a href="https://frenchtech-brestplus.bzh/vous-avez-aime-brest-is-ai-en-2020-vous-adorerez-les-ai-days-bzh-en-2021/">AI (artificial intelligence) DAYS.BZH</a>, AESLA <a href="https://aesla2020.udc.es/">(Spanish Society for Applied Linguistics)</a> , AFIA <a href="http://afia-competitions.fr/2020-introduction/">(French Association for Artificial Intelligence)</a> jams on generating poetic and funny texts</li>
  </ul>
<h3>Expected length of the workshop at the conference is half-day:</h3>
  <ul>
    <li>Opening speech 15 min</li>
    <li>Guest speaker 1 h</li>
    <li>Presentations of the participants 15 mins + 5 min for questions</li>
    <li>Closing speech 15 mins</li>
  </ul>
  <p>
<b>Acknowledgement</b>. This project has received a government grant managed by the National Research Agency under the program "Investissements d'avenir" with the Reference ANR-19-GURE-0001.
  </p>
<h3 id="note1">References:</h3>
  <p>
<p>[1]	‘SemEval-2021 Tasks’, SemEval-2021. https://semeval.github.io/SemEval2021/tasks.html (accessed Mar. 02, 2021).</p>
<p>[2]	‘Tasks < SemEval-2017’. https://alt.qcri.org/semeval2017/index.php?id=tasks (accessed Mar. 02, 2021).</p>
<p>[3]	‘Tasks < SemEval-2020’. https://alt.qcri.org/semeval2020/index.php?id=tasks (accessed Mar. 02, 2021).</p>
<p>[4]	R. Mihalcea and C. Strapparava, ‘Making Computers Laugh: Investigations in Automatic Humor Recognition’, in Proceedings of Human Language Technology Conference and Conference on Empirical Methods in Natural Language Processing, Vancouver, British Columbia, Canada, Oct. 2005, pp. 531–538. Accessed: Mar. 02, 2021. [Online]. Available: https://www.aclweb.org/anthology/H05-1067</p>
<p>[5]	A. Cattle and X. Ma, ‘Recognizing Humour using Word Associations and Humour Anchor Extraction’, in Proceedings of the 27th International Conference on Computational Linguistics, Santa Fe, New Mexico, USA, Aug. 2018, pp. 1849–1858. Accessed: Mar. 02, 2021. [Online]. Available: https://www.aclweb.org/anthology/C18-1157</p>
<p id="note2">[6]	D. Yang, A. Lavie, C. Dyer, and E. Hovy, ‘Humor Recognition and Humor Anchor Extraction’, in Proceedings of the 2015 Conference on Empirical Methods in Natural Language Processing, Lisbon, Portugal, Sep. 2015, pp. 2367–2376. doi: 10.18653/v1/D15-1284.</p>
<p>[7]	A. Reyes, D. Buscaldi, and P. Rosso, ‘An Analysis of the Impact of Ambiguity on Automatic Humour Recognition’, in Text, Speech and Dialogue, Berlin, Heidelberg, 2009, pp. 162–169. doi: 10.1007/978-3-642-04208-9_25.</p>
<p>[8]	V. Blinov, V. Bolotova-Baranova, and P. Braslavski, ‘Large Dataset and Language Model Fun-Tuning for Humor Recognition’, in Proceedings of the 57th Annual Meeting of the Association for Computational Linguistics, Florence, Italy, 2019, pp. 4027–4032. doi: 10.18653/v1/P19-1394.</p>
<p>[9]	A. Ermilov, N. Murashkina, V. Goryacheva, and P. Braslavski, ‘Stierlitz Meets SVM: Humor Detection in Russian’, in Artificial Intelligence and Natural Language, Cham, 2018, pp. 178–184. doi: 10.1007/978-3-030-01204-5_17.</p>
<p>[10]	S. Castro, L. Chiruzzo, A. Rosá, D. Garat, and G. Moncecchi, ‘A Crowd-Annotated Spanish Corpus for Humor Analysis’, in Proceedings of the Sixth International Workshop on Natural Language Processing for Social Media, Melbourne, Australia, Jul. 2018, pp. 7–11. doi: 10.18653/v1/W18-3502.</p>
<p>[11]	K. Papineni, S. Roukos, T. Ward, and W.-J. Zhu, ‘BLEU: a method for automatic evaluation of machine translation’, in Proceedings of the 40th annual meeting on association for computational linguistics, 2002, pp. 311–318.<p/>
  </p>
