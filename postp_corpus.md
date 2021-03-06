Listing all the postpositions from the literature and their attribute values. 
A value of 1 indicates that the given postposition always produces the typical behaviour of postpositions in the syntactic structure under examination. 
Columns:
- *pos*: the preferred ordering of the postposition and its complement regardless of their adjacency. 
- *zero*: the ***case-marking*** of the complement. The exact case required by the postposition is listed in the table.
- *adj*: delineates the strict adjacency of the two words. 
- *wh* represents the word's behaviour in wh-questions. Does the postposition always follow the wh-word, or can it stay behind? 
- *dem*: details the structure with a demonstrative pronoun. Is the postposition copied onto the demonstrative as well,
or is only the case marker copied? 
- *pers pron*: specifies the structure with a personal pronoun. When postpositions take a pronominal complement, where does the agreement marker appear? 
On the postposition itself, or on another element?

A question mark indicates that I am not entirely certain in the acceptability of my examples for testing the given property. 
A '-' marks that the given postposition does not appear in the given construction (with a personal pronoun, for example)


Here I sum up the teatures and their binary values used when evaluating the behaviour of postpositions in the corpus. 
P stands for postposition.
|**Column**| **the feature**| **if 1** |**if 0** |
|---|---|---|---|
|pos | position of P relative to the noun | P always follows the noun | P may appear before and after the noun|
|zero  | the case of the noun |always caseless noun |P takes a noun with a lexical case | 
|adj  | the adjacency of the two words  | noun and P always next to each other  | other words may appear between P and the noun |
|wh  | the behaviour of P in wh-questions  | P follows the wh-word  | P stays behind |
|dem|P's behaviour with demonstrative pronouns|P is copied onto the demonstrative |P is not copied onto the demonstrative|
|pers pron |person-number agreement with a personal pronoun|person-number agreement appears on P |person-number agreement not on P |


|postposition    | **meaning** | **pos** | **zero** | **adj** | **wh** | **dem** | **pers pron** |
| ---- | ----- |---|---|---|---|---|---|
|alatt | under | 1   | 1   | 1   | 1  | 1   | 1 | 
|al??l  | from under   | 1   | 1   | 1   | 1  | 1   | 1 |
|ellen | against  | 1   | 1   | 1   | 1  | 1   | 1 | 
|el??l   | from in front of  | 1   | 1   | 1   | 1  | 1   | 1 |
|el??tt   | in front of    | 1   | 1   | 1   | 1  | 1   | 1  |
|fel??    | towards  | 1   | 1   | 1   | 1  | 1   | 1 |
|fel??l  | from the direction of    | 1   | 1   | 1   | 1  | 1   | 1 |
|f??l??    | to above  | 1   | 1   | 1   | 1  | 1   | 1  |
|f??l??tt | (at) above   | 1   | 1   | 1   | 1  | 1   | 1 |
|helyett    | instead of   | 1   | 1   | 1   | 1  | 1   | 1  |
|ir??nt  | towards  | 1   | 1   | 1   | 1  | 1   | 1 |
|k??r??    | to around    | 1   | 1   | 1   | 1  | 1   | 1   |
|k??r??l   | around    | 1   | 1   | 1   | 1  | 1   | 1   |
|k??z??    | to between   | 1   | 1   | 1   | 1  | 1   | 1   |
|k??z??tt  | between   | 1   | 1   | 1   | 1  | 1   | 1   |
|k??z??l   | from between| 1   | 1   | 1   | 1  | 1   | 1   |
|mell??   | to next to  | 1   | 1   | 1   | 1  | 1   | 1   |
|mellett | next to, beside  | 1   | 1   | 1   | 1  | 1   | 1   |
|mell??l  | from next to    | 1   | 1   | 1   | 1  | 1   | 1   |
|miatt   | because of   | 1   | 1   | 1   | 1  | 1   | 1   |
|m??g??    | to behinf    | 1   | 1   | 1   | 1  | 1   | 1   |
|m??g??tt  | behind    | 1   | 1   | 1   | 1  | 1   | 1   |
|m??g??l   | from behind  | 1   | 1   | 1   | 1  | 1   | 1   |
|n??lk??l  | without  | 1   | 1   | 1   | 1  | 1   | 1   |
|szerint | according to      | 1   | 1   | 1   | 1  | 1   | 1   |
|ut??n    | after    | 1   | 1   | 1   | 1  | 1   | 1   |
|??ltal   | by  | 1   | 0:sup   | 1   | 1  | 1   | 1   |
|??rdek??ben    |on behalf of| 1      | 0:dat   | 1   | 1    | 0     | 1      |
|eset??ben     |in case of| 1      | 0:dat   | 1   | 1    | 0     | 1      |
|f??l??l   | from above   | 1   | 0:sup   | 1   | 1  | 0   | 1   |
|r??sz??re | for      | 1   | 0:dat   | 1   | 1  | 0   | 1   |
|r??sz??r??l | on the part of | 1 | 0:dat | 1 | 1 | 0 | 1 |
|sor??n   | during  | 1   | 0:dat   | 1   | 1  | 0   | 1   |
|sz??m??ra | for      | 1   | 0:dat   | 1   | 1  | 0   | 1   |
|fogva   | from (time)  | 1   | 0:abl   | 1   | 1  | 0   | 0   |
|n??zve   | regarding    | 1   | 0:sub   | 1   | 1  | 0   | 0  |
|alapj??n | based on | 1   | 0:dat   | 1   | 1  | 0/1   | -   | 
|c??lj??b??l    | with the aim of   | 1   | 0:dat   | 1   | 1  | 0   | -   |
|ellen??re    | despite  | 1   | 0:dat   | 1   | 1  | 0   | -   |
|??rtelm??ben   |in pursuance of| 1      | 0:dat   | 1   | 1    | 0     | -      |
|eset??n  | in case of   | 1   | 0:dat   | 1   | 1  | 0   | -   |
|folyam??n | in the course of | 1 | 0:dat | 1 | 1 | 0 | -|
|k??v??lr??l    | from outside      | 1   | 0:sup   | 1   | 1  | 0   | -   |
|k??vetkezt??ben    | following    | 1   | 0:dat   | 1   | 1  | 0   | -   |
|nyom??n  | based on | 1   | 0:dat   | 1   | 1  | 0   | -   |
|r??v??n   | by means of  | 1   | 0:dat   | 1   | 1  | 0   | -   |
|??tj??n   | by way of    | 1   | 0:dat   | 1   | 1  | 0   | -   |
|folyt??n | as a consequence of    | 1   | 0:dat   | 1   | ?  | 0   | -   |
|k??zben  | during   | 1   | 1   | 1   | 1  | 1   | -   |
|m??lt??n  | after (time)      | 1   | 1   | 1   | 1  | 0   | -   |
|??ta    | since  | 1   | 1   | 1    | 1  | 1   | -   |
|v??gett    | with the aim of      | 1   | 1   | 1 | 1  | -   | 1   |
|gyan??nt | as  | 1   | 1   | 1    | -  | -   | -   |
|hosszat | for      | 1   | 1   | 1   | -  | -   | -   |
|??zben  | times    | 1   | 1   | 1   | -  | -   | -   |
|l??t??re  | despite being     | 1   | 1   | 1   | -  | -   | -   |
|m??dj??ra | way of   | 1   | 1   | 1   | -  | 0?  | -   |
|m??dra   | mode of  | 1   | 1   | 1   | -  | -   | -   |
|m??lva   | after (time)      | 1   | 1   | 1   | -  | -   | -   |
|t??j??n | around | 1 | 1 | 1 | 1 -? | -? | - |
|t??jban/t??jt      | around (time)     | 1   | 1   | 1   | -? | -?  | -   |
|ir??ny??ban | towards | 1 | 0:dat | 0| 1 | 0 | 1 |
|jav??ra  | in favour of      | 1   | 0:dat   | 0   | 1  | 0   | 1   |
|kedv????rt    | for the sake of   | 1   | 0:dat   | 0   | 1  | 0   | 1   |
|alul    | below    | 1   | 0:sup   | 0   | 1  | 0   | 0   |
|k??pest  | compared to  | 1   | 0:all   | 0   | 1  | 0   | 0   |
|k??v??lre | to outside   | 1   | 0:sup   | 0   | 1  | 0   | 0   |
|t??lra   | to beyond    | 1   |0:sup   | 0   | 1  | 0   | 0   |
|t??lr??l  | from beyond  | 1   | 0:sup   | 0   | 1  | 0   | 0   |
|hasonl??an   | similarly    | 0   | 0:all   | 0   | 1  | 0   | 0   |
|kiv??ve  | except for   | 0   | 0:acc   | 0   | 1  | 0   | 0   |
|k??v??l   | outside  | 0   | 0:sup   | 0   | 1  | 0   | 0   |
|szembe  | to opposite to  | 0   | 0:ins   | 0   | 1  | 0   | 0   |
|szemben | opposite to  | 0   | 0:ins   | 0   | 1  | 0   | 0   |
|szemk??zt    | opposite to  | 0   | 0:ins   | 0   | 1  | 0   | 0   |
|fel??l   | over     | 1   | 0:sup   | 0   | 0  | 0   | 0   |
|al??     | to under | 0   | 0:dat   | 1   | 1  | 1   | 1   |
|el??     | to in front of    | 0   | 0:dat   | 1   | 1  | 1   | 1   | 
|kezdve  | beginning from    | 0   | 0:abl   | 1   | 1  | 0   | 0   |
|dac??ra  |despite| 0      | 0:dat   | 1   | 1    | 0     | -      |
|bel??l   | inside of    | ?   | 0:sup   | 1   | 1  | 0   | 0   |
|??t      | through  | 0   | 0:sup   | 0   | 0  | 0   | 0   |
|egy??tt  | together | 0   | 0:ins   | 0   | 0  | 0   | 0   |
|kereszt??l   | through  | 0   | 0:sup   | 0   | 0  | 0   | 0   |

