A repository to store data we used during the annotation of Kazym Khanty corpora<br><br>
Tasks:
1. Collect raw data:
    * Kazym FW
    * Western FW
    * website
2. Initial preprocessing, making UniMorph-like tsv files with all the information from the data (stem - wordform - tags):
   * Kazym and Western FWs - TSV to Triplets.py
   * website - 
3. Developing (a universal UniMorph tagset)[https://docs.google.com/spreadsheets/d/16ISV_Tj9VOCSoos6XBLfljAnNMa1vxNfhyvU3EpkVyU/edit?usp=sharing]
4. Combining all the data
5. Automatic detection of errrors:
    * finding same wordforms with different tagsets
    * finding lemmas not listed in Solovar's dictionary
6. Manual check
