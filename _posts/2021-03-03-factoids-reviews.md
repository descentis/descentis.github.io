---
layout: post
title: Tracing the Factoids
subtitle: Reviews from WWW-21 and CHIIR-21
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [Wikipedia,Riviews]
comments: true
---

# Prohect Details
Name: Tracing the Factoids: the Anatomy of Information Re-organization in Wikipedia Articles
Authors: Amit Arjun Verma, Neeru Dubey, S. R. S. Iyengar, Simran Setia
Portal(s) where submitted: CHIIR-21 and WWW-21



# Review History

## CHIIR - 21

-------------------------  METAREVIEW  ------------------------
This is the meta-review by the Senior PC member responsible for the paper.

Synthesis:

The connection that you draw between the theories of Information Seeking
and the creation, addition, and editing activities associated with the lifecycle of Wikipedia articles,
is not yet fully developed. We do encourage more revision of this paper to tease out precisely which
Information Seeking behavior theory you believe to be expressed by the Wikipedia article organization process,
and to provide more details on that theory with respect to the editing process to make it clear for readers.
Alternatively, there are other theories regarding knowledge creation, and information editing that could be
just as relevant, especially given the focus on the authoring/editing aspects of collaborative article
development. The CHIIR PC discussed whether indeed you needed to try to tie the work to one or more
Information Seeking theories - on balance we did not feel this to be essential to gain acceptance. The PC
also observed that the CHIIR community have deep expertise in Information Seeking theories and thus it is
imperative to be quite clear and comprehensive when discussing their application to your scenarios.


The reviewers also commented on the embeddings and characterization of similarity. Although overall there
was acceptance of your approach, various aspects could do with additional clarification or analysis. These include
confirming that high scores truly correlate with human assessments of similarity, that similarity corresponds to
positional relevance within an article, and to provide examples of paired
sentences such that the score differences are shown - perhaps with a variant of Fig 1.

In addition, the reviewers provide a number of additional suggestions for things to fix.


Additional Comments:

I've added a few more comments of my own below:

A minor point is one of consistent terminology - you refer variously to "Wikipedians", "editors", "contributors",
and "crowd". I think you intend to use these synonymously - if so, please choose one and then use it throughout.

In the Introduction, you assert that the Wiki technology used by Wikipedia is "a user-friendly interface" - I think
this is a slightly bold claim to make, given the somewhat arcane markup-heavy text interface for the MediaWiki system
that is little changed in ~20 years!
There's certainly low barriers to entry and wikitext-based systems were usable through circa 1995 browser technology,
but they're not the same thing.

Section 2 - Related work.
"knowledge gets build" -> ... built

Section 3 - Understanding ...
"Hence, the crowd in Wikipedia is often responsible for such rearrangements, which eventually creates a proper ordering of
all the information present in the article." - I'm not sure that we can go from one example to "proper ordering" for information.
By proper ordering, do you mean causally related, or time-sequenced? Many Wikipedia articles have information in
different subsections that is not linear in time with respect to the whole article. At the least, I think it would be good
to define what you believe is meant by "proper ordering" - beyond simply higher average inter-sentence similarity scores.
This might be a useful angle to explore the relationship to Information Seeking theories, perhaps that of sense-making.

Another aspect to develop more clarity on is the different roles carried out by editors and how these
main roles you have identified (contributing and rearranging) behave with respect to the Information Seeking theory of choice.
Are information creators different from information rearrangers? Do the roles overlap? Does the proportion of
creating/deleting (Fig 2) vs rearranging activities change over time?



Final Disposition:

I wish to emphasize that this paper stirred the reviewing group to discuss various aspects
of what makes a good CHIIR paper. All the reviewers, the PC and I felt that the subject matter is of clear interest to a CHIIR audience and that combining theoretical and empirical analysis is appealing.

Nevertheless, the connection to the general idea of Information Seeking Theory is not developed fully in terms of the specific theory (of several) that you believe applies, and more clarity regarding the roles of different Wikipedia users (browsers vs authors, and within authors, those are mostly creators vs mostly rearrangers) is desirable. Going beyond statistical analysis via sentence similarity to more details on the qualitative support for that measure and why it might reflect improving quality would also be valued.

So let me thank you again for submitting your paper to CHIIR 2021 for review. Although we are not recommending
acceptance at this time, the work you've carried out is interesting and we look forward to seeing it further developed
and published in the future. As part of the PC discussion of your work, we wished to emphasize to you that we believe
there is a rich set of opportunities for exploring your investigation more deeply. For example, if you are able
to also compare information creation/curation with information access (by casual readers rather than writers). To
what extent does the article's length determine how similar successive sentences become under your measures? Are
there common structures that evolve over time in articles of certain types, which again may contribute to sentence
similarity within the sub-structures? While we know that it is always disappointing not to be accepted, we wish to
assure you that we think your work is of distinct research interest and will have even more broad appeal after
a round of revision. We hope that the comments and suggestions in these reviews will help you carry this out and we
welcome future submissions from you on this topic to CHIIR.



----------------------- REVIEW 1 ---------------------
SUBMISSION: 82
TITLE: Tracing the Facts Sequencing: the Anatomy of Information Re-organization in Wikipedia Articles
AUTHORS: Amit Arjun Verma, Neeru Dubey, S. R. S Iyengar and Simran Setia

----------- Relevance -----------
SCORE: 0 (fair)
----------- Originality -----------
SCORE: 2 (excellent)
----------- Technical/methodological soundness -----------
SCORE: 1 (good)
----------- Quality of presentation -----------
SCORE: 2 (excellent)
----------- Impact of contributions -----------
SCORE: 1 (good)
----------- Adequacy of citations -----------
SCORE: 1 (good)
----------- Reproducibility -----------
SCORE: 1 (good)
----------- Overall evaluation -----------
SCORE: 2 (accept)
----- TEXT:
The submission shows an elaborate analysis of Wikipedia articles and their structure. The structure is analyzed by measuring the similarity of subsequent sentences and taking the average.
The work represents an interesting application of deep learning technology, in this case sentence embeddings.

The idea to consider sentences as factoids could be challenged and a mapping to entities and arguments could be an alternative. However, this approach is probably very robust. It would have been helpful for give some examples for similar sentences (within and between articles) to support the assumption that sentences with a high cosine values between their USE mappings are indeed similar for humans.

The relation to Information Seeking needs to be strengthened and explained. The sentence in the first paragraph of section 5 is not enough to make this relation clear. (“The IS theory” -> there are many theories in IS)  The submission also not on HCI (CCS concepts selected)

The article also compares the similarity (we could call it semantic coherence) to the quality labels of Wikipedia and find a correlation. That means, the coherence metric using USE is a useful quality measurement for texts.
Future work, could identify e.g. the positions in articles which receive most changes.

The analysis in section 6 uses a ranking correlation coefficient. Here the authors should add a sentence explaining the behavior of Pearson when a new sentence is added. Also for this analysis, examples should be used to show whether this really leads to the identification of similar sentences.
It would have been interesting to relate the analysis to the edit history. (in case a sentence is deleted and added somewhere else, does the metric capture that?)

Is there any bias due to the length of the articles?
There might also be a lower similarity between sentences of different paragraphs.

Related work should not give a long list of 6 references without clearly stating their individual contribution. A paper is not a reading list.



Details:

that majority -> that the majority



----------------------- REVIEW 2 ---------------------
SUBMISSION: 82
TITLE: Tracing the Facts Sequencing: the Anatomy of Information Re-organization in Wikipedia Articles
AUTHORS: Amit Arjun Verma, Neeru Dubey, S. R. S Iyengar and Simran Setia

----------- Relevance -----------
SCORE: -1 (poor)
----------- Originality -----------
SCORE: 0 (fair)
----------- Technical/methodological soundness -----------
SCORE: 1 (good)
----------- Quality of presentation -----------
SCORE: 1 (good)
----------- Impact of contributions -----------
SCORE: -1 (poor)
----------- Adequacy of citations -----------
SCORE: -2 (very poor)
----------- Reproducibility -----------
SCORE: 1 (good)
----------- Overall evaluation -----------
SCORE: -1 (weak reject)
----- TEXT:
In this article, the authors study the reorganization of information in Wikipedia articles through following the edit history of articles. They operationalize their idea by using a sentence-level analysis. Each sentence is considered a factoid.
They calculate the cosine similarity between two consecutive factoids (sentences) in each revision to assess how well information is organized in a Wikipedia article.

The average semantic similarity of an article is taken as a proxy for the correct arrangement of information in an article. The higher the avg similarity is, the more correctly information is ordered.

They show that over an articles lifecycle (a lifecycle has four steps or quadrants) most articles evolve in a way that in the end, the spread of similarity is smaller i.e. a more cohesive article is the result. They also show that similarity correlates with quality class. Better articles have a higher sentence similarity.


The article is well written and easy to follow. The strongest parts are sections 4-8 i.e. the analysis part and presentation of results. This is interesting to read and a nice contribution. Maybe some parts could be a bit more condensed i.e. a longer explanation of Pearson correlation.


The most crucial drawback that the article suffers from is the lack of relevance to CHIIR and CHIIR topics. The authors try to link their study to CHIIR by using information seeking theory as the basis/ a guiding theory for their study. However, this is done on a very superficial level. The authors speak of 'the information-seeking theory' but don't really explain which one they refer to and what parts they use for their study. This gets especially evident in the introduction, wherein a sentence that refers to information seeking theory Niklas Luhman and Jean Piaget get cited. The immediate relevance of these two books to information seeking theory and their work is not given and the authors also don't explain the link. Their aim to study HOW information is gathered/how individual people contribute to an article is not given. The authors are aware of that and mention that they don't analyse different types of editors and their role in the limitations of their study, but this!
  also breaks the link to CHIIR topics. As mentioned above, I think the overall analysis is interesting, but the authors oversell the results a bit as they don't really do any analysis on the differences in editors, their role and how this contributes to the arrangement of information in an article.

The lack of details on which theory they use is unfortunately mirrored in the related work section. As mentioned above the authors don't discuss literature on information seeking theory. Only one article relating to collaborative information seeking is mentioned. Moreover, I would recommend giving the RW part a bit more structure, separating it into wiki-related work and IB work. Here I would also want to add that more editors not necessarily make an article less biased. The editor gender gap (most editors are male) is well known and more editors don't make an article/the Wikipedia automatically more diverse.

With a better link to information seeking theory and more editor related analysis, this could be a future CHIIR paper. However, at its current state, I feel its not there yet.

Some further comments:

I think the colon in the title is set on the wrong spot (should be after facts?)

Related to Figure 1: The authors start explaining the timeline in the middle. Maybe guiding the reader through every step would be good.

Table 1 is, for my liking, a bit meaningless. I think it would be much better if summary statistics on the data-set would be presented instead of listing four random articles.



----------------------- REVIEW 3 ---------------------
SUBMISSION: 82
TITLE: Tracing the Facts Sequencing: the Anatomy of Information Re-organization in Wikipedia Articles
AUTHORS: Amit Arjun Verma, Neeru Dubey, S. R. S Iyengar and Simran Setia

----------- Relevance -----------
SCORE: 1 (good)
----------- Originality -----------
SCORE: 1 (good)
----------- Technical/methodological soundness -----------
SCORE: 0 (fair)
----------- Quality of presentation -----------
SCORE: 1 (good)
----------- Impact of contributions -----------
SCORE: 0 (fair)
----------- Adequacy of citations -----------
SCORE: 1 (good)
----------- Reproducibility -----------
SCORE: 1 (good)
----------- Overall evaluation -----------
SCORE: 0 (borderline paper)
----- TEXT:
This paper presents an empirical analysis of the impact of edits on the re-organization of factual information in Wikipedia articles. The authors measure the relevance of factoid (sentence) positions in the article by calculating the similarity between consecutive sentences using represented by pre-trained embeddings. They also measure the correlation of sentence similarity with revisions to analyze the stability of factoid evolution over time. Besides, a correlational analysis is also conducted between the average semantic similarity of sentences in an article and the article quality.

The paper targets a relevant problem in crowd knowledge creation. Dataset and analysis are interesting. The paper is well structured and overall easy to follow (with some minor writing issues, see below).

My main concerns are the following.

First, the method for the analysis needs to be better justified. The authors use pre-trained embeddings of sentences and use them for calculating semantic similarity between sentences. While that in general makes sense, in this specific context where the authors want to quantify the relevance of sentences positions in an article according to their semantic similarity between consecutive sentences, several gaps need to be addressed, including
- how reliable are those pre-trained embeddings for measuring sentence semantic similarity?
- how well does semantic similarity between consecutive sentences approximate the relevance of sentence positions in an article?

Second, the implication of the results is not very clear. The authors show that crowd edits help to re-organize factual information in an article (not considering the aforementioned problem), from which they believe that it will help the site designers in developing more robust user interfaces. I found it a bit difficult to connect the finding to the implication. It appears to me that the finding is already recognized by the site designer and that the actual challenges for improving article quality are crowd engagement, effective content moderation, etc.

Writing can be improved. There are places where the messages are vague, e.g.,
- in the introduction "objective and organization", "which allows us to quantify the content organization", it's unclear which property of the content organization is quantified.
- similar problem in section 6, "the impact of factoids re-arrangement in an article’s development", which impact is unclear.


## The Web Conference - 21 Reviews (Wiki Workshop)

-------------------------  METAREVIEW  ------------------------
There is no metareview for this paper


----------------------- REVIEW 1 ---------------------
SUBMISSION: 8
TITLE: Tracing the Factoids: the Anatomy of Information Re-organization in Wikipedia Articles
AUTHORS: Amit Arjun Verma, Neeru Dubey, S. R. S Iyengar and Simran Setia

----------- Overall evaluation -----------
SCORE: 2 (accept)
----- TEXT:
This paper investigates the rearrangement of information in Wikipedia articles due to gradual edits. The authors quantify how information organization, especially the positioning of factoids i.e. sentences taken as factual information tokens,  impacts the quality of such articles. The authors find higher rearrangement in the early stages of the article revision and convergence towards a stable version.  Moreover, they find a positive correlation between average sentence similarity and the articles’ quality class.

Overall, the article is well written and well-grounded in the literature, although the task at study was not particularly explored previously. The methodology implied is appropriate for the task. I believe that even if the measure of similarity between consecutive factoids (averaged on the article!) is not immediately or solely related to the order of the factoids (but rather to the order and the content jointly or the style), the correlation analyses performed are thorough, the results find interesting patterns and they are well discussed.

For these reasons, I believe that the article should be accepted with minor modifications.

Minor comments:
- The authors thoroughly explain how word2vec and Fasttext work in Section 4.2, but they give no explanations on why they chose to use Tensorflow’s Universal Sentence Encoder. I believe they could elaborate more on that, by adding the motivations and the differences that led to that choice.
- In Sections 4.3, the “quality classes” are mentioned but not described (they are briefly described in a paragraph in Section 6, that could be moved to the correct Section).
- In Figure 6 the labels on the x-axis could be replaced with the labels of the quality classes.



----------------------- REVIEW 2 ---------------------
SUBMISSION: 8
TITLE: Tracing the Factoids: the Anatomy of Information Re-organization in Wikipedia Articles
AUTHORS: Amit Arjun Verma, Neeru Dubey, S. R. S Iyengar and Simran Setia

----------- Overall evaluation -----------
SCORE: 1 (weak accept)
----- TEXT:
This paper describes an analysis of information reorganisation in 500 Wikipedia articles. The authors measure the semantic similarity of consecutive sentences (as calculated through cosine similarity of sentence embeddings) and investigate how this changes through the article's life cycle. Their findings indicate that this similarity metric increases and converges as articles mature. The results are interesting and convincing, with some limitations.

The central premise here is that information is being inserted and then, in later revisions, displaced to different locations in the article, causing an increase in the semantic similarity of consecutive sentences. However, no evidence is presented that the same factoids are indeed present and are being reorganised in consecutive edits; consecutive sentence similarity may be increasing because of the addition of new information. Some qualitative analysis might make your argument stronger.

Some statements need to be backed up by experiments or reworded. Eg.:
- "More specifically, we observe a positive correlation between the revisions and average semantic similarity between the consecutive sentences in the majority of the Wikipedia articles. The result implies the crowd involvement in organizing the factual information in the articles." --> This does not directly imply crowd involvement. In the extreme case, one editor could be performing all of the edits.
- "We believe editors of an article continually revise its content, maintaining the overall quality and flow. The gradual edits performed over time reduce the knowledge gap in an
article, making it complete and exhaustive." --> Again, the role of information added versus reorganised seems blurry. From what I can see, your research does not investigate the knowledge gap evolution in an article at all, so it may be best to remove such claims.
- A minor point: You state that the information organisation process is an indirect result of edits by contributors, but then also say that there are some editors which focus on this: "We believe a set of watchful eyes regularly edit and revise the ordering of information, pushing the article to a complete stage". These seem like contradictory statements; if you focus on reordering statements, it is not an indirect result.

Editorial points:
- The introduction contains a great deal of unnecessary background but does not explain your own contributions very well. I'd recommend adding here that you are working with sentence embeddings of consecutive sentences, as this would answer the questions I had.
- Information seeking theory is mentioned often, but only defined in the penultimate section. I'd recommend defining it in the introduction.
- Your method bears on coherence studies (eg. https://arxiv.org/abs/1907.02427), which might be nice to mention in related work.
