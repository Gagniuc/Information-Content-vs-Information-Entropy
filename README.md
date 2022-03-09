# Information content vs Information entropy
Information content (red) vs Information entropy (black) on sequences

<i>Entropy vs self sequence alignment</i> is a Javascript implementation of a scanner that makes a comparison between two methods, namely between Shanon entropy (Information entropy) and self-sequence alignment (Information content). Information entropy (IE) and Information content (IC) are two methods that quantitatively measure information. Here, these parallel results are shown in the form of signals above a given sequence (<i>z</i>). To obtain these signals, the contents of sliding windows are analyzed with the two methods and the values are stored as discrete signals inside a vector. Specifically, here both measure the information in the sequence of characters stored in a variable called <i>z</i>:

```js
var z = "AAAAAACAGGTGAGTAAAAAAAA";
```

Thus, this comparison is made to highlight the qualitative differences between information entropy and the new method of information content described as a primary source in the book entitled <i>[Algorithms in Bioinformatics: Theory and Implementation](https://books.google.ro/books?id=y1I5EAAAQBAJ&printsec=frontcover&source=gbs_ge_summary_r&cad=0#v=onepage&q&f=false)</i>. Below, the black line represents the Shannon Entropy and the red line represents the information content over the <i>z</i> sequence.

Live demo: https://gagniuc.github.io/Information-Content-vs-Information-Entropy/

<kbd><img src="https://github.com/Gagniuc/Information-content-red-vs-Information-entropy-black-/blob/main/%5BG%5D%20Information%20content%20vs%20Information%20entropy.png" /></kbd>


# References

- <i>Paul A. Gagniuc. Algorithms in Bioinformatics: Theory and Implementation. John Wiley & Sons, Hoboken, NJ, USA, 2021, ISBN: 9781119697961.</i>

- <i>Gagniuc and Ionescu-Tirgoviste: Gene promoters show chromosome-specificity and reveal chromosome territories in humans. BMC Genomics 2013 14:278.</i>

- <i>Gagniuc and Ionescu-Tirgoviste: Eukaryotic genomes may exhibit up to 10 generic classes of gene promoters. BMC Genomics 2012 13:512.</i>

- <i>Ionescu-Tîrgovişte C, Gagniuc PA, Guja C (2015) Structural Properties of Gene Promoters Highlight More than Two Phenotypes of Diabetes. PLoS ONE 10(9): e0137950.</i>
