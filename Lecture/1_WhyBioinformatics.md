# Welcome to class!

## We will start with an introduction to the importance of bioinformatics in genetics, genomics, and organismal biology

Let's say we want to do something easy. 

**Question 1:** How many total nucleotides are in this string of DNA from a mouse?

```
AGTCCTTGAGCCCCTGCAGCCTCAGAAGAGGGAGTCATCAGCTGAAACCTCCAGGAACCACCGGGGGTCC
CAGAAGGTATGTGCTAAACTCCATCCAGATGTTGTGTTTCGTTTTGTTCTTTTTCTTCTTTTTTCCTCTC
TAATCATAATCAAAGAGTGAACAAGTGGTTTTCACATTATCAAGCAACGCAGGGAAGAAATACAGTTTCC
TTCTTTCCTGGCCAGGTCTGTACCAAATAAAGGAGCAAGAAAGAGACTTAGGGTTTTTGGGTAATACAGA
CAAGCACCTGAATTCACATTTGGTGCTTTATACACACAGCGGAAATACCAGGTATACAAGGTAGACCATG
TCGCAGACCCTTCAGTAAGACCCAATCAGCACTGACTTTTCAGCTTCCAGGGTTGTTACCTGTGCTCGAG
GGAGCCCATCAGTCTTAAAATCCCTCTTAAAAACGACTGTGGTGCAAATAGGTCAGACAGTAAAATAGAG
GCGTTGCTGTCTTAGAAAGGGAGAGACTGTGAATGAAACTTTCTGGGAGCACCTGCGCATCCGCTGTGCC
CATCAACTTCGTCATCCCCGTGGGTCACAAGTGGTCACCAGACAGCTCGCAAAACTGTTCTCTGGCCGCC
CAGCTCTCCTGGGGTTAACTTGCTGAGGGGCTAGGATGAGGAAAACCAGATCTTCCTAGGCTGCAGCTCA
```

Now, how many instances of Adenine (A) are there in this same segment of DNA?

**Question 2:** What about if we are interested in transcribing this into RNA? Please do this.

Finally, lets identify this section of the genome! We know this is a mouse, so as an exercise I will just give you a few mouse genes that this could be.

**Question 3:** Which gene is our DNA sequence?

Gene 1, agouti signalling protein:
```
>Agouti signalling protein
CTGCCTCCCCAGTGGTGGCATCCATCCCAGTAGAGTGCACCACGAGGCTGACTTCCTCTTCCCAGCCAGG
TCCTCCGTCCTACACTGGGCTCCCCTGGTTCAGAAGCTGTCCCTGTGACTCAGAGCCCACCAGCTCCCCC
CAGCTCCCACCAGCTCCACTCACTCAGCGGCATCTCTGCTGACAGTATCATTTGCTCATCTTACTGATGG
AGCACTGGGGATCCGGGAGGGCAGATAACTCAGCTTAAAATCAGATTCTAGAGTGACAGATAGATCCAAA
ACCAGCCCTTTGATCCTCTGGTCCTCTTTCTACTCTGCCATGGGCTCCCAGAAACTTGAACTAGAACACA
TACAAACCAACACAGATCTCCCAAAGACGTGAACAAGTTCATGGACTTTACCAGCATGAGACAAAGCCAC
CACACAACACAGAGGAGCACTTCCAGGTCTGGAGACACAAGTGGCAAAGAGCCTCCTTGCTAGGTGCCCA
CCCAGACACAAGTGAGCATGCTTGCTTGACATTTGCTCCCCTCCCCCTTAGCAGGGTTTGGCCATGGTTA
CAGCATCCTGACAACCTATTTAAACCAACATGCAGGAACTGGCATCAAAGTACCATTTCCCACCAGTCTG
AGTCCTTGAGCCCCTGCAGCCTCAGAAGAGGGAGTCATCAGCTGAAACCTCCAGGAACCACCGGGGGTCC
CAGAAGGTATGTGCTAAACTCCATCCAGATGTTGTGTTTCGTTTTGTTCTTTTTCTTCTTTTTTCCTCTC
TAATCATAATCAAAGAGTGAACAAGTGGTTTTCACATTATCAAGCAACGCAGGGAAGAAATACAGTTTCC
TTCTTTCCTGGCCAGGTCTGTACCAAATAAAGGAGCAAGAAAGAGACTTAGGGTTTTTGGGTAATACAGA
CAAGCACCTGAATTCACATTTGGTGCTTTATACACACAGCGGAAATACCAGGTATACAAGGTAGACCATG
TCGCAGACCCTTCAGTAAGACCCAATCAGCACTGACTTTTCAGCTTCCAGGGTTGTTACCTGTGCTCGAG
GGAGCCCATCAGTCTTAAAATCCCTCTTAAAAACGACTGTGGTGCAAATAGGTCAGACAGTAAAATAGAG
GCGTTGCTGTCTTAGAAAGGGAGAGACTGTGAATGAAACTTTCTGGGAGCACCTGCGCATCCGCTGTGCC
CATCAACTTCGTCATCCCCGTGGGTCACAAGTGGTCACCAGACAGCTCGCAAAACTGTTCTCTGGCCGCC
CAGCTCTCCTGGGGTTAACTTGCTGAGGGGCTAGGATGAGGAAAACCAGATCTTCCTAGGCTGCAGCTCA
CTTGACTGCCCTTCACCCCACACCTGAACTCGGGCTCCTGGGAGAGAACCTGAGGAAAGGCAGCTTAGCC
AAGGCTGCACTGCCAGGGGCTTCTCTGCCAGGGGCCACTTCTGGCTGCAAGCTGTAGGCAGGACCAGGAA
TGGATGTCACTGGAGATGGGAAGCTCAGTGACGAAGGGACCTTACTTCCAGTCCCCAAAAGATGCCATTT
TCAATGTTCTCCTCTGAATTGGTGAGTTTCAAAATTTTTAGACCTTAGACTGTGTGAGCAAAGTCAGAGT
CTAGACTGTTTACTGGTTAAACATACAAGGAAACAATGTGGGTTTTTTTGTTGTTGTTGTTGTTGTTTCT
TTGTTTTTTTGTTTTGTTTTCTTTTTTGATATTTTTGAATTTGATTGAACTCTTTAGTGGAAAACGTGTT
TTAAAGGAAAACCAAACCAAACCACCCAGTGCACTTGGTGCGCCTTGCATTTTGACCCAGCCCACGGAAT
AATTTAGAAGTCTCTCCGCAGACCACCAGAGATCCTTGCATTTTATCTGAAGAACCATAAATCTTAAAAA
CGTCGTGTTAATTTCAGTACCTTTCTTTTCATCTGGATTTCTCCTCGTTGGCCACAGAGAGCGATTTCTG
ATGAATCCTGGAACATGTCCTGTACTGTAAGAGGTGAGCGGGTCCGGAGGAGGAGATTTGTTCTCAGCGA
GTGTTTTCATTAATATTGTATCTATGCTGTAGTTATATATATCTTGTTGGATGCATCCTTACTTCCGTTT
TCTTGTCAAGTCCCCTCAGTGGTCTTCAGTATTTAGTTTACTTTTGCTTCTTTGTTTCTCCTCTAGAAAA
CTGTCGTCTAGTTTTGATATTTAGATAGTTGTGCTCTGGAGCATGCTGCTTGCTGGAATTTCAGAATCAC
```

Gene 2: melanocortin receptor 1
```
>Melanocortin receptor 1
GAGAAAAGCTCCCTTCTTCTCCAGAGTCCCGTCTACCCTGGCTTGGCGAGGGAAAGGAACCAGACATATA
TCAGAGGCAAGTAACCAAGAAGTCTGGAGGTGTTGAGTTTAGGCATGTCTCTACCTGAGCCACTTGGGAA
GAGACAGGGAGAACAGCAGAAGGCTAAGCTACTTCACACTGGCAGTGAGAGTCCATGAGCAGAGCTCAGG
GTCCTCAGCAGGAAGTGTCTATGCCATGCCGAGGCTGGCCTGTCCAGCCAGAAAGAACACAAGTGTAAAG
GAAAATCGGAGCGTGCCTGTATGGAAAGAGGCCGGTCTGAGGGATGTCAGAGACCCCCGACAACAACATG
AAGTGAATCAGAAGCTGGGGGCTGATACCACCTGGAGCTGCAGCCTCCACAGACCGCTTCCTACTTCCTG
ACAAGACTATGTCCACTCAGGAGCCCCAGAAGAGTCTTCTGGGTTCTCTCAACTCCAATGCCACCTCTCA
CCTTGGACTGGCCACCAACCAGTCAGAGCCTTGGTGCCTGTATGTGTCCATCCCAGATGGCCTCTTCCTC
AGCCTAGGGCTGGTGAGTCTGGTGGAGAATGTGCTGGTTGTGATAGCCATCACCAAAAACCGCAACCTGC
ACTCGCCCATGTATTACTTCATCTGCTGCCTGGCCCTGTCTGACCTGATGGTAAGTGTCAGCATCGTGCT
GGAGACTACTATCATCCTGCTGCTGGAGGCGGGCATCCTGGTGGCCAGAGTGGCTTTGGTGCAGCAGCTG
GACAACCTCATTGACGTGCTCATCTGTGGCTCCATGGTGTCCAGTCTCTGCTTCCTGGGCATCATTGCTA
TAGACCGCTACATCTCCATCTTCTATGCGCTGCGTTATCACAGCATCGTGACGCTGCCCAGAGCACGACG
GGCTGTCGTGGGCATCTGGATGGTCAGCATCGTCTCCAGCACCCTCTTTATCACCTACTACAAGCACACA
GCCGTTCTGCTCTGCCTCGTCACTTTCTTTCTAGCCATGCTGGCACTCATGGCGATTCTGTATGCCCACA
TGTTCACGAGAGCGTGCCAGCACGCTCAGGGCATTGCCCAGCTCCACAAAAGGCGGCGGTCCATCCGCCA
AGGCTTCTGCCTCAAGGGTGCTGCCACCCTTACTATCCTTCTGGGGATTTTCTTCCTGTGCTGGGGCCCC
TTCTTCCTGCATCTCTTGCTCATCGTCCTCTGCCCTCAGCACCCCACCTGCAGCTGCATCTTCAAGAACT
TCAACCTCTTCCTCCTCCTCATCGTCCTCAGCTCCACTGTTGACCCCCTCATCTATGCTTTCCGCAGCCA
GGAGCTCCGCATGACACTCAAGGAGGTGCTGCTGTGCTCCTGGTGATCAGAGGGCGCTGGGCAGAGGGTG
ACAGTGATATCCAGTGGCCTGCATCCTGTGAGACCACAGGTACTCATCCCTTCCTGATCTCCATTTGTCT
AAGGGTCGACAGGATGAGCTTTAAAATAGAAACCCAGAGTGCCTGGGGCCAGGAGAAAGGGTAACTGTGA
CTGCAGGGCTCACCCAGGGCAGCTACGGGAAGTGGAGGAGACAGGGATGGGAACTCTAGCCCTGAGCAAG
GGTCAGACCACAGGCTCCTGAAGAGCTTCACCTCTCCCCACCTACAAGGCAACTCCTGCTCAGCCCTTCA
GCTCATTCAGCCTGGGCTCTCCTGCTGGGACAGACATGAAGTCTCTAAGTTAAAAGAATGACAGACAAGC
CGGGCGGTGGTGGCGCATGCCTTTAATTCCAGCACTTGGGAGGCAGAGGCAGGTGGATTTCTGAGTTCGA
GGCCAGCCTGGTCTTCAGAGTGAGTTCCAGTGACGGCCAGGGCTATACAGAGAAACCCTGTCTCAAAAAA
AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAATGACAAACAAGAGCTAAGGGGGAGCAACTACTCTTGGTG
GAAGCTTCTGATAAGAGGATTTGTGGCCATGAAAACCCAGCCATAGCCATGCAGTAGGCAGCTTAAGGAA
GTGAGACCCTTCCTCAGCACATGGAGCAGAATTGTAGAATGTGCATCTTGCAGGAGGGGCCTACCCATTT
GCACAAGCGGTGTGGGACTGACCTAAAAATGGCTCCTGGGAATCCCAAGAGGTGGGCACCCAACTGCTCA
CACCAGCAGGCTACTCTGTCAAGTGCCTCCTCCACCAGCTGCAGGGGAGGCTGTTGGCTTATCACTGACC
ACAGCCTGTGTGGCTCTGAGCCAGGAAGCAGTTGAAATGCTAAGGTCAGAGGGAGGGAGCCTCCTTGCCA
TCTTCCCTAGCTCTCTCCAGAAGCTGAGTGAAGTTTGGGTGAGAGGACAGGGAGAGTGGTCACATTAGGG
AGATGGGAGTCTCAGAAGCCACAGCTAGCTGCCTGCCTGATTTAGGAAACCACGGTCCCGTCTTGGCTTC
CTCTATGACTACAAACTTCAGATCAGAGCAAGCAGCGGCAGAAAAAGTTTCCTCGTGCCTCTATGGTGAC
```

Gene 3: Tyrosinase
```
>Tyrosinase
AAGCTTAGTGTAAAACAGGCTGAGAGTATTTGATGTAAGAAGGGGAGTGGTTATATAGGTCTTAGCCAAA
ACATGTGATAGTCACTCCAGGGGTTGCTGGAAAAGAAGTCTGTGACACTCATTAACCTATTGGTGCAGAT
TTTGTATGATCTAAAGGAGAAAATGTTCTTGGCTGTTTTGTATTGCCTTCTGTGGAGTTTCCAGATCTCT
GATGGCCATTTTCCTCGAGCCTGTGCCTCCTCTAAGAACTTGTTGGCAAAAGAATGCTGCCCACCATGGA
TGGGTGATGGGAGTCCCTGCGGCCAGCTTTCAGGCAGAGGTTCCTGCCAGGATATCCTTCTGTCCAGTGC
ACCATCTGGACCTCAGTTCCCCTTCAAAGGGGTGGATGACCGTGAGTCCTGGCCCTCTGTGTTTTATAAT
AGGACCTGCCAGTGCTCAGGCAACTTCATGGGTTTCAACTGCGGAAACTGTAAGTTTGGATTTGGGGGCC
CAAATTGTACAGAGAAGCGAGTCTTGATTAGAAGAAACATTTTTGATTTGAGTGTCTCCGAAAAGAATAA
GTTCTTTTCTTACCTCACTTTAGCAAAACATACTATCAGCTCAGTCTATGTCATCCCCACAGGCACCTAT
GGCCAAATGAACAATGGGTCAACACCCATGTTTAATGATATCAACATCTACGACCTCTTTGTATGGATGC
ATTACTATGTGTCAAGGGACACACTGCTTGGGGGCTCTGAAATATGGAGGGACATTGATTTTGCCCATGA
AGCACCAGGGTTTCTGCCTTGGCACAGACTTTTCTTGTTATTGTGGGAACAAGAAATTCGAGAACTAACT
GGGGATGAGAACTTCACTGTTCCATACTGGGATTGGAGAGATGCAGAAAACTGTGACATTTGCACAGATG
AGTACTTGGGAGGTCGTCACCCTGAAAATCCTAACTTACTCAGCCCAGCATCCTTCTTCTCCTCCTGGCA
GGTAAGATGCACTATATAGAGAGAGTTGCAAAGACTGGTACTTCAGCAGCCACATTTTCATGCTCTGTGA
GCATCTCTGATAATATCTCAGGGCAGAAAATGTGCCTTACTAACAGATGTTAATGCTTCTTGATTTCTTT
TTCTCTTTTGAGAACTCTTCAAAGTTGTTATTAAACAAATATCTATGTGCTTATTTGTCTTAATATCTAA
CAGCTTAGTTAGATTTCTAAGCTGCTATAAACAAGGACTGATTGGTTCACCACTGTATTGTTAGCACCTC
CTATGGTATCTGGAATAAACAGTAACTCAGTTATTTAAGAATGGATGAGAAACCAGATTATCTTAGTTCA
TGTTTCTGAGTAATATTAAAATTAATATTAACAGTAAAATCCATAAGTATGCTACTTTAAAATATAAATC
TCTGGCCAAAACCAAGACTTATTATTCAGGATCTTCAAGAGAAAGTGCTGAGATAATTCACTAAGTATCA
GAGATGACCTTTATTACATGATTGCCTGATAGAAAAAATGATTACACACACACAAAAAAATCTTCAGTTG
CTTAAATTTTAAACGTTGCTGACTCTCAAACAGTTAAGTAATAAAAGAGTTAAAGCCTGCTGTGTATTTA
GAATATGTGAATACCTATTGAAAGAATTTATTGTACAATTAATATAAACAGACTTCTATTTTACAGTCAT
AAGATACTACTTAATTTGTTAAAAATTATTTTTTGATAGCATTGTTGGTAAATAGCAAAGGTGATATTTG
CTAATGATTACAAGGGCTGTCTGGCTAACTTACGTTATGTTCAGGGAGAAGACAGTCCTTTTTAAGGAAT
GGGCACTTTCTAACTTTTTTTCTCTAGGATGGAGAAAAATTAGCCTTCTTCCTACTTTAAAAATGTTAGA
CATAGAATTAAGGGATTGTTATTTTGAGATTAAATTTTCTTTTCTCCTATTATTTTTCCTCATTCTGGAA
TGGAAGCAAAAGATGAAGAAAGAAATATATGTTAAATTGTTTTCCTTTAAATGAACACAAATGTGAAATA
TGTTTTTCTGCCTATCTTGTAAAATTTTCTATTGCAACTATTCTGATTACCAGTTCAAATGGGGAAAAAA
GAACATAGGCTACCCCACACTTGAAATTTTGAAATATGAATGTCCTCTGTCTCTGCTGGTCTAACACTTC
CAAAATGGAAACCTTTAAAGGGCCACTGTAAATTACAGCTGCTAATTCCTGGTGCCAATGGTGATAAGTG
TTTACTAAACCTAGTGAGTACTTTATAGCATGGGGCTCTGCTGCGAAGTAACATTGCTGTATATTTTCAG
TCATTCTACCTTAATTCATGAACTGCAAAACTCTCATCTAGCTTTTTACTTCTCTAGCTATTGCTTTAAG
TTCTATCAGGCTCAGGTGTGGAATTCTCTCAGTTACAATATTCGATTTGTTATATAGCATTACTTGATGC
```

## How much did that suck? And how poorly did we all do?!

## Now we will do this bioinformatically!

Our initial DNA sequence is in a file called `DNAseq.fa`. We can use this to answer the above questions.

How many total nucleotides are there?

```bash
grep -v "^>" DNAseq.fa | wc -c
```

How many "A"s are there in this DNA sequence?

```bash
cat DNAseq.fa | tr -cd "A" | wc -c
```

What is the RNA sequence (ie, transcribe the DNA)?

```bash
cat DNAseq.fa | sed "s/T/U/g"
```

Finally lets identify this gene. The potential genes I gave you are in the file `Possiblegenes.fa`.

```bash
# first make the blast database (what you will search through)
makeblastdb -in Possiblegenes.fa -dbtype nucl

# now search for our gene within that database
blastn -query DNAseq.fa -db Possiblegenes.fa -out blastsearch.txt

# view results 
cat blastsearch.txt
```

## WOW, so much easier right???

Imagine trying to do a lot of genomic work by hand. Remember the human genome contains approximately 3 *BILLION* base pairs...
