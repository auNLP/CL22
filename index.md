Computational Linguistics
============

Overview 
---------------------

|Format | Time         | Place | Instructor                     |
|------|---------------|--------|---------------------------|
| Lecture | Tues 10-16 | 1453-116  | Yuri Bizzoni + Emil Rønn  |
| Groupwork | Thurs 10-16 | 5008-127   | Yuri Bizzoni + Emil Rønn | 

Note: The [Gather.Town](http://bit.ly/CLGather) space is always available for you! Feel free to have your study group meetings here. 

This course is a theoretical and applied introduction to *Computational Linguistics*. You will gain hands-on experience with computational and corpus-based methods to gain insight into natural language data, including both structured and unstructured data. By the end of the course, you will be familiar with the basic algorithms and statistical models that underlie much computational linguistic research, and understand the role of these methods in language technology as applied in commercial contexts. You will leave the course with an understanding of the state of the art of this subfield, and its advantages and limitations relative to other linguistic research methods.  

The second half of the course will walk students through the process of writing a multi-author research paper: from making the initial project pitch, to designing and outlining the work, to developing a literature review, to implementation and first draft, followed by peer review and revision.

[Please read the full description of course/exam in the course catalog!](https://kursuskatalog.au.dk/en/course/101936/Computational-Linguistics)

   
Expectations / Workload
---------------------

This is essentially a two-part course. 
+ *Part 1* (weeks 6-16) teach you about computational linguistics in theory and practice
+ *Part 2* (weeks 16-18) guide you through the writing of an original research paper for the [exam](https://kursuskatalog.au.dk/en/course/101936/Computational-Linguistics) for more information. 

Note: The nature of this course is that you have to be diligent about putting aside a little time to work (almost) every day. Do your best to make programming a regular habit! 

Most computational liguistics courses have an army of instructors plus labs and office hours. Because I'm on my own, I've worked very hard to design an effective class for you, despite our lack of resources.  **My commitment to you** is to give you carefully-designed, level-appropriate exercises that aren't a waste of your time, and will give you valuable skills for your future study and career. But to benefit from this, **you must make the weekly work plan a habit and do your best to keep up!**


### Weekly work plan ### 

In each row of the schedule, you see four categories of work you need to have done before coming to class that day. 

1. **Read/Watch** - *Before Weds lecture*: Readings and sometimes videos. Slides are added here after the lecture. 
2. **Prepare** - *Due at noon before Weds lecture* Group exercises based on the content to deepen your understanding
3. **Programming ** - *Activities for Thurs class* In Part 1, you will have programming assignment based on the prior week's class, which you are welcome to work on with your study group.  Later, you will submit portions of your research project. 
4. **Skills/methods/tools** - Relevant for this week's coding projects. See the list of **Resources** below (e.g. LearnPython.org) - I'll be adding more as the semester progresses. 

Note: You're expected to prepare the **Prepare** exercises with your group, but if you can't meet with your group just do them on your own. 



Schedule and materials
---------------------
| Week | Read/Watch                                                     | Prepare                                                                                                                                                           | Programming                                                                                                                                                                                                                                  | Skills/methods/tools                                                                             |   |
|------|----------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------|---|
| 5    | [Python Workshop](class0.md)                     |   | [Python Workshop doc](https://docs.google.com/document/d/1iYwk-Xd6duJjIpWtvTZtdFslLZKScCg3WIVVAr_JNjA/edit?usp=sharing)   | Variables and Types, Lists, Basic Operators  |   |
| 6    | [Introduction](class1.md)                                      |                                                                                                                                                                   |                                                                                                                                    HW1_basics[(py)](HW1_basics.ipynb) HW1_solutions[(py)](HW1_solutions.ipynb)        |   Strings, Conditions, **For** loops, Basic functions                         |   |
| 7    | [Encoding language](class2.md)                                 | [Exercises](exercises2.md)                                                                                                                                        |                                                                                                     [Internship Workshop](workshop.md) (with Simon Kristensen)      | |   |
| 8    | [Language modeling](class3.md)                                 | [Ngrams exercise](exercises3.md)                                                                                                                                  | HW2_counting[(zip)](HW2_counting.zip) HW2_solutions[(py)](HW2_Solutions.ipynb) Optional ngrams notebook[(py)](Optional_ngrams_notebook.ipynb)                                                                                                              | Dicts, tuples, File handling, Control statements (if else), more functions, iterators            |   |
| 9    | [Text processing and regex](class4.md)                                            | 1. [Regex Tutorial (do by yourself](https://regexone.com/) 2. [Reading and regex exercises (group)](exercises4.md)                                                                                | HW3_regex[(zip)](HW3_regex.zip) HW_3_Solutions[(py)](HW3_solutions.ipynb)                                                                                                                       |  Regex and grep                                                  |   |
| 10   | [Classification 1](class5.md) | [Manual classification](IMDB_texts.pdf)     |     HW4_classify[(ipynb)](HW4_classify1.ipynb)                                                                                                                                                   | NLTK                                                                             |   |
| 11   | [Classification 2/Sentiment](class5-2.md)    | [Classification exercises](NB_sentiment_problems.docx) [Solutions](NB_sentiment_solutions.docx)     |    HW4_classify_continued[(ipynb)](HW4_classify1.ipynb) HW_Sentiment[(colab)](https://colab.research.google.com/drive/1lUaJQ-BDgl5cBMBOuzNVeBDuPp5ZH6Tb?usp=sharing)                                                                                                                                                      |    Pandas, Tweepy, Matplotlib                                                                           |   |
| 12   | [Searching and TF-IDF](class6.md)                        | [Searching exercises](exercises7.md) |        HW5_search[(zip)](HW5_Search.zip)                                                                                                                                     |                                                                 |   |
| 13   | NO CLASS                                        |    Relax! / Slap af!                                                                                                                                                               |                                                                                                                                             |                                                                    |   |
| 14   | [Vector models](class7.md)                                            |                                                                                                                         |  [HW6_Word Embeddings](https://colab.research.google.com/drive/1s3CejYsZGdzFGNnQMSUV-I8ibvcp4kWa?usp=sharing)                                                                                                                                              |                                                                     |   |
| 15   | Pitches (2 min presentations)                                            |    [Pitch exercise](https://docs.google.com/document/d/17v8Uqwoho3P2nzVdCdSY47uG978kOd0lKVOHd6dnTfw/edit?usp=sharing)                                                                                                                                                              |  Project meetings |                                                                                                  |   |
| 16   | [Dialog systems and AI](class10.md)                      |                                                                                                                [**Outline due**](outline_assignment.md)           |    [Sign-up for supervision](https://docs.google.com/spreadsheets/d/13TlKPBF8hkvDjHDZhh6BWcvumcOH8Be8o8LasuzXSrY/edit?usp=sharing)                                                                                                                                                                                                  |                                                                                                  |   |
| 17   | Research report supervision                                    |                                                                                                                                         **Bibliography due**         |    [Sign-up for supervision](https://docs.google.com/spreadsheets/d/1fKkRx2iXOKyahM2Sm2OM2Jax-622un_upob0PdYAaEE/edit?usp=sharing)                                                                                                                                                                                                                |                                                                                                  |   |
| 18   | [Couse recap/draft assignment](Final_week_CL21.pdf)    |   Course eval (BB)                                                                                                                                           **[Gantt chart due (Weds 5/5)](gantt.md)**                                                                                                   |                                                                                                                |                                                                                                  |   |
| 19   | NO CLASS                      |                                                                                                                                            **Draft due (Tue 11/5 noon) - [instructions](https://docs.google.com/document/d/1Pze1Qd0mTmz2w-ZAqLYcMswgG82yNqyfScAxnbRiEQ4/edit) **   **Peer reviews due Fri 14/5 8am - [instructions](https://docs.google.com/document/d/1isu6WE4UEJCNaOzgvwwNSMZuU_HIQs60iyHYp0Czq2k/edit) **            |                                                                                                                                                                              |                                                                                                  |   |
| 22   |                                                                |                                                                                                                                                                   | **[Final exam deadline 1/6](https://eksamen.au.dk/)**                                                                                                                                                                                                                   |                                                                                                  |   |



Learning to program 
---------------

### Python 3 resources

You will receive an invitation to [Datacamp](https://learn.datacamp.com/), where you can do self-paced study on Datacamp courses! You can study whatever you want, but I recommend the following (in order): 

+ Python Fundamentals 
+ Natural Language Processing with Python 
+ NLP with Deep Learning 

Note: You must register with your post.au.dk email address, and login with the same email address every time. 

Final papers
---------------
[Paper titles from 2019 Research Workshop](2019_Papers.md)

[Paper titles from 2019 NLP](NLP_posters_flier.pdf)

Getting support in your studies
------------------
AU has a support centre, focused more on disability support:

[Rådgivnings- og støttecentret (au.dk)](https://www.au.dk/raadgivnings-og-stoettecentret/)

National student counselling service: 

[Hjemmeside | Studenterrågivningen (srg.dk)](https://srg.dk/en/) 

Questions about the class? 
---------------

<div class="padlet-embed" style="border:1px solid rgba(0,0,0,0.1);border-radius:2px;box-sizing:border-box;overflow:hidden;position:relative;width:100%;background:#F4F4F4"><p style="padding:0;margin:0"><iframe src="https://padlet.com/embed/rrs91oe4ws2uwluk" frameborder="0" allow="camera;microphone;geolocation" style="width:100%;height:608px;display:block;padding:0;margin:0"></iframe></p><div style="padding:8px;text-align:right;margin:0;"><a href="https://padlet.com?ref=embed" style="padding:0;margin:0;border:none;display:block;line-height:1;height:16px" target="_blank"><img src="https://padlet.net/embeds/made_with_padlet.png" width="86" height="16" style="padding:0;margin:0;background:none;border:none;display:inline;box-shadow:none" alt="Made with Padlet"></a></div></div>
