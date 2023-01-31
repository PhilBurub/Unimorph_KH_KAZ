A repository to store data we used during the annotation of Kazym Khanty corpora<br><br>
Tasks:
1. Collect raw data:
    * Kazym FW
    * Western FW
    * [website](http://www.babel.gwi.uni-muenchen.de/index.php?abfrage=KK_corpus&subnavi=corpus_pub)
2. Initial preprocessing, making UniMorph-like tsv files with all the information from the data (stem - wordform - tags):
   * Kazym and Western FWs - TSV to Triplets.ipynb
   * website - Website to Triplets.ipynb
3. Developing [a universal UniMorph tagset](https://docs.google.com/spreadsheets/d/16ISV_Tj9VOCSoos6XBLfljAnNMa1vxNfhyvU3EpkVyU/edit?usp=sharing)
4. Combining all the data - Unifying.ipynb -> Unified.tsv
5. Finding verb lemmas - Verb lemma redo.ipynb -> Prep.tsv
6. Manual check in [google sheets](https://docs.google.com/spreadsheets/d/1UL6KxLe6wz9uzrZl_zKgVVO24hoatezjtemCGVKqDU8/edit?usp=sharing)
7. Last automatic adequacy check:
   * Current manually checked data - manual check.tsv
   * Notebook - LastRevision.ipynb
   * Result - final.tsv
