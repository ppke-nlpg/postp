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
|alól  | from under   | 1   | 1   | 1   | 1  | 1   | 1 |
|ellen | against  | 1   | 1   | 1   | 1  | 1   | 1 | 
|elől   | from in front of  | 1   | 1   | 1   | 1  | 1   | 1 |
|előtt   | in front of    | 1   | 1   | 1   | 1  | 1   | 1  |
|felé    | towards  | 1   | 1   | 1   | 1  | 1   | 1 |
|felől  | from the direction of    | 1   | 1   | 1   | 1  | 1   | 1 |
|fölé    | to above  | 1   | 1   | 1   | 1  | 1   | 1  |
|fölött | (at) above   | 1   | 1   | 1   | 1  | 1   | 1 |
|helyett    | instead of   | 1   | 1   | 1   | 1  | 1   | 1  |
|iránt  | towards  | 1   | 1   | 1   | 1  | 1   | 1 |
|köré    | to around    | 1   | 1   | 1   | 1  | 1   | 1   |
|körül   | around    | 1   | 1   | 1   | 1  | 1   | 1   |
|közé    | to between   | 1   | 1   | 1   | 1  | 1   | 1   |
|között  | between   | 1   | 1   | 1   | 1  | 1   | 1   |
|közül   | from between| 1   | 1   | 1   | 1  | 1   | 1   |
|mellé   | to next to  | 1   | 1   | 1   | 1  | 1   | 1   |
|mellett | next to, beside  | 1   | 1   | 1   | 1  | 1   | 1   |
|mellől  | from next to    | 1   | 1   | 1   | 1  | 1   | 1   |
|miatt   | because of   | 1   | 1   | 1   | 1  | 1   | 1   |
|mögé    | to behinf    | 1   | 1   | 1   | 1  | 1   | 1   |
|mögött  | behind    | 1   | 1   | 1   | 1  | 1   | 1   |
|mögül   | from behind  | 1   | 1   | 1   | 1  | 1   | 1   |
|nélkül  | without  | 1   | 1   | 1   | 1  | 1   | 1   |
|szerint | according to      | 1   | 1   | 1   | 1  | 1   | 1   |
|után    | after    | 1   | 1   | 1   | 1  | 1   | 1   |
|által   | by  | 1   | 0:sup   | 1   | 1  | 1   | 1   |
|érdekében    |on behalf of| 1      | 0:dat   | 1   | 1    | 0     | 1      |
|esetében     |in case of| 1      | 0:dat   | 1   | 1    | 0     | 1      |
|fölül   | from above   | 1   | 0:sup   | 1   | 1  | 0   | 1   |
|részére | for      | 1   | 0:dat   | 1   | 1  | 0   | 1   |
|részéről | on the part of | 1 | 0:dat | 1 | 1 | 0 | 1 |
|során   | during  | 1   | 0:dat   | 1   | 1  | 0   | 1   |
|számára | for      | 1   | 0:dat   | 1   | 1  | 0   | 1   |
|fogva   | from (time)  | 1   | 0:abl   | 1   | 1  | 0   | 0   |
|nézve   | regarding    | 1   | 0:sub   | 1   | 1  | 0   | 0  |
|alapján | based on | 1   | 0:dat   | 1   | 1  | 0/1   | -   | 
|céljából    | with the aim of   | 1   | 0:dat   | 1   | 1  | 0   | -   |
|ellenére    | despite  | 1   | 0:dat   | 1   | 1  | 0   | -   |
|értelmében   |in pursuance of| 1      | 0:dat   | 1   | 1    | 0     | -      |
|esetén  | in case of   | 1   | 0:dat   | 1   | 1  | 0   | -   |
|folyamán | in the course of | 1 | 0:dat | 1 | 1 | 0 | -|
|kívülről    | from outside      | 1   | 0:sup   | 1   | 1  | 0   | -   |
|következtében    | following    | 1   | 0:dat   | 1   | 1  | 0   | -   |
|nyomán  | based on | 1   | 0:dat   | 1   | 1  | 0   | -   |
|révén   | by means of  | 1   | 0:dat   | 1   | 1  | 0   | -   |
|útján   | by way of    | 1   | 0:dat   | 1   | 1  | 0   | -   |
|folytán | as a consequence of    | 1   | 0:dat   | 1   | ?  | 0   | -   |
|közben  | during   | 1   | 1   | 1   | 1  | 1   | -   |
|múltán  | after (time)      | 1   | 1   | 1   | 1  | 0   | -   |
|óta    | since  | 1   | 1   | 1    | 1  | 1   | -   |
|végett    | with the aim of      | 1   | 1   | 1 | 1  | -   | 1   |
|gyanánt | as  | 1   | 1   | 1    | -  | -   | -   |
|hosszat | for      | 1   | 1   | 1   | -  | -   | -   |
|ízben  | times    | 1   | 1   | 1   | -  | -   | -   |
|létére  | despite being     | 1   | 1   | 1   | -  | -   | -   |
|módjára | way of   | 1   | 1   | 1   | -  | 0?  | -   |
|módra   | mode of  | 1   | 1   | 1   | -  | -   | -   |
|múlva   | after (time)      | 1   | 1   | 1   | -  | -   | -   |
|táján | around | 1 | 1 | 1 | 1 -? | -? | - |
|tájban/tájt      | around (time)     | 1   | 1   | 1   | -? | -?  | -   |
|irányában | towards | 1 | 0:dat | 0| 1 | 0 | 1 |
|javára  | in favour of      | 1   | 0:dat   | 0   | 1  | 0   | 1   |
|kedvéért    | for the sake of   | 1   | 0:dat   | 0   | 1  | 0   | 1   |
|alul    | below    | 1   | 0:sup   | 0   | 1  | 0   | 0   |
|képest  | compared to  | 1   | 0:all   | 0   | 1  | 0   | 0   |
|kívülre | to outside   | 1   | 0:sup   | 0   | 1  | 0   | 0   |
|túlra   | to beyond    | 1   |0:sup   | 0   | 1  | 0   | 0   |
|túlról  | from beyond  | 1   | 0:sup   | 0   | 1  | 0   | 0   |
|hasonlóan   | similarly    | 0   | 0:all   | 0   | 1  | 0   | 0   |
|kivéve  | except for   | 0   | 0:acc   | 0   | 1  | 0   | 0   |
|kívül   | outside  | 0   | 0:sup   | 0   | 1  | 0   | 0   |
|szembe  | to opposite to  | 0   | 0:ins   | 0   | 1  | 0   | 0   |
|szemben | opposite to  | 0   | 0:ins   | 0   | 1  | 0   | 0   |
|szemközt    | opposite to  | 0   | 0:ins   | 0   | 1  | 0   | 0   |
|felül   | over     | 1   | 0:sup   | 0   | 0  | 0   | 0   |
|alá     | to under | 0   | 0:dat   | 1   | 1  | 1   | 1   |
|elé     | to in front of    | 0   | 0:dat   | 1   | 1  | 1   | 1   | 
|kezdve  | beginning from    | 0   | 0:abl   | 1   | 1  | 0   | 0   |
|dacára  |despite| 0      | 0:dat   | 1   | 1    | 0     | -      |
|belül   | inside of    | ?   | 0:sup   | 1   | 1  | 0   | 0   |
|át      | through  | 0   | 0:sup   | 0   | 0  | 0   | 0   |
|együtt  | together | 0   | 0:ins   | 0   | 0  | 0   | 0   |
|keresztül   | through  | 0   | 0:sup   | 0   | 0  | 0   | 0   |

