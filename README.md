# Natural language understanding dataets in 2018

This page collects NLU datasets proposed in 2018.

| Dataset    | task | style                | size | source             | where     | web                                                | misc                              | similar datasets     |
|------------|------|----------------------|------|--------------------|-----------|----------------------------------------------------|-----------------------------------|----------------------|
| CoQA       | RC   | free form (+no ans)  | 127k | various articles   | TACL?     | [url](https://stanfordnlp.github.io/coqa/)         | conversational questions          | QuAC                 |
| QuAC       | RC   | extraction (+no ans) | 100k | Wikipedia          | EMNLP2018 | [url](http://quac.ai/)                             | conversational questions          | CoQA                 |
| HotpotQA   | RC   | extraction           | 113k | Wikipedia          | EMNLP2018 | [url](http://hotpotqa.github.io/)                  | multi-hop reasoning               | QAngaroo             |
| SWAG       | QA   | multiple choice      | 113k | video caption      | EMNLP2018 | [url](http://rowanzellers.com/swag/)               | situational commonsense reasoning |                      |
| DNC        | NLI  | textual entailment   | 570k | NLP tasks          | EMNLP2018 | [url](http://decomp.io/)                           | diverse NLI                       | SNLI, MultiNLI       |
| OpenBookQA | QA   | multiple choice      | 6k   | science facts      | EMNLP2018 | [url](http://data.allenai.org/OpenBookQA)          | external knowledge                | ARC                  |
| RecipeQA   | RC+  | various              | 36k  | recipe             | EMNLP2018 | [url](https://hucvl.github.io/recipeqa/)           | multimodal comprehension          | TextbookQA, FigureQA |
| CLOTH      | RC   | cloze                | 99k  | English exams      | EMNLP2018 | [url](http://www.cs.cmu.edu/~glai1/data/cloth/)    |                                   | RACE                 |
| DuoRC      | RC   | extraction           | 186k | movie plot         | ACL2018   | [url](https://duorc.github.io/)                    |                                   | NarrativeQA          |
| SQuAD2.0   | RC   | extraction (+no ans) | 150k | Wikipedia          | ACL2018   | [url](https://rajpurkar.github.io/SQuAD-explorer/) | no answer: 50k                    | NewsQA               |
| CliCR      | RC   | cloze                | 100k | clinical case text | NAACL2018 | [url](https://github.com/clips/clicr)              |                                   |                      |
| FEVER      | NLI? | fact verification    | 185k | Wikipedia          | NAACL2018 | [url](http://fever.ai/)                            |                                   |                      |
| MultiRC    | RC   | multiple choice      | 6k+  | various articles   | NAACL2018 | [url](http://cogcomp.org/multirc/)                 | multiple sentence reasoning       | MCTest               |
| ProPara    | RC   | various              | 2k   | procedural text    | NAACL2018 | [url](https://github.com/allenai/propara)          |                                   | bAbI, SCoNE          |
| ARC        | RC   | multiple choice      | 8k   | science exam       | ?         | [url](http://data.allenai.org/arc/)                | easy 5197, challenge 2590         |                      |

Note:
* QA = question answering, RC = reading comprehension = question answering with the context, NLI = natural language inference aka recognizing textual entailment
