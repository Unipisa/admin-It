# Admin-It

Admin-It is a parallel corpus of **sentences in Italian administrative language** for Automatic Readability Assessment (ARA) and Automatic Text Simplification (ATS). The corpus comprises **736 original-simplified sentence pairs**. We organized the corpus in **three subsets** according to the different simplification type applied: 

* [Operations (OP)](OP): 588 pairs of sentences from the subset of the Simpitiki corpus (Tonelli et al., 2016) related to the administrative domain. The sentences are simplified by means of a **single simplification operation** (e.g., split, reorder, merge, lexical substitutions).

* [Rewritten Sents (RS)](RS): 100 pairs of original-simplified sentences. The original sentences were selected from websites of Italian municipalities and the Pawac Corpus (Passaro and Lenci, 2015). Sentences were **manually simplified both at lexical and syntactic levels**.

* [Rewritten Docs (RD)](RD): 48 pairs of sentences selected and manually aligned from administrative documents collected and simplified by Cortelazzo (1998; Cortelazzo et al., 1999). This resource contains pairs of original-simplified **documents rewritten according to linguistic simplification and communicative effectiveness criteria**.

#### References

* Cortelazzo, M. A. (1998). Semplificazione del linguaggio amministrativo. Quaderni del Comune di Trento. Progetti, 3. 
*	Cortelazzo, M. A., Pellegrino F., & Viale, M. (1999). Semplificazione del linguaggio amministrativo. Esempi di scrittura per le comunicazioni ai cittadini. Comune di Padova.
*	Tonelli, S., Aprosio Palmeri, A., & Saltori, F. (2016). [SIMPITIKI: a Simplification corpus for Italian](https://ceur-ws.org/Vol-1749/paper52.pdf). In *CLiC-it/EVALITA*.
*	Passaro, L. C., & Lenci, A. 2015. [Extracting terms with EXTra](https://arpi.unipi.it/retrieve/handle/11568/843205/190664/Europhras2015-EXTra.pdf), in Corpas Pastor, G. (edited by), «Computerised and corpus-based approaches to phraseology: Monolingual and multilingual perspectives», Tradulex:188-196.


## Citation

If you use Admin-It in your research, please cite our AACL 2022 paper:

> Martina Miliani, Serena Auriemma, Fernando Alva-Manchego and Alessandro Lenci. 2022. [Neural Readability Pairwise Ranking for Sentences in Italian Administrative Language](https://aclanthology.org/2022.aacl-main.63). In *Proceedings of the 2nd Conference of the Asia-Pacific Chapter of the Association for Computational Linguistics and the 12th International Joint Conference on Natural Language Processing*, pages 849–866, Online. Association for Computational Linguistics.


```BibTeX
@inproceedings{miliani-etal-2022-neural,
    title = "Neural Readability Pairwise Ranking for Sentences in Italian Administrative Language",
    author = "Miliani, Martina and
      Auriemma, Serena and
      Alva-Manchego, Fernando and
      Lenci, Alessandro",
    booktitle = "Proceedings of the 2nd Conference of the Asia-Pacific Chapter of the Association for Computational Linguistics and the 12th International Joint Conference on Natural Language Processing",
    month = nov,
    year = "2022",
    address = "Online",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2022.aacl-main.63",
    pages = "849–-866",
    abstract = "Automatic Readability Assessment aims at assigning a complexity level to a given text, which could help improve the accessibility to information in specific domains, such as the administrative one. In this paper, we investigate the behavior of a Neural Pairwise Ranking Model (NPRM) for sentence-level readability assessment of Italian administrative texts. To deal with data scarcity, we experiment with cross-lingual, cross- and in-domain approaches, and test our models on Admin-It, a new parallel corpus in the Italian administrative language, containing sentences simplified using three different rewriting strategies. We show that NPRMs are effective in zero-shot scenarios ($\sim$0.78 ranking accuracy), especially with ranking pairs containing simplifications produced by overall rewriting at the sentence-level, and that the best results are obtained by adding in-domain data (achieving perfect performance for such sentence pairs). Finally, we investigate where NPRMs failed, showing that the characteristics of the data used for fine-tuning, rather than its size, have a bigger effect on a model's performance.",
}
```
