Question 2: Please assign variables to the individual components of your favorite gene! (e.g. promoter, 5' UTR, start codon, exon1, intron, exon2, stop codon, 3' UTR). Print the entire gene by using the string concatenation operator, on the standard output! Note: Feel free to create a fictional gene sequence by randomly filling in the gene components by the characters corresponding to individual nucleotide bases.

Answer of student 3

promoter = "TTAAATATATATA"
five_prime_UTR = "UUCGCGTATAGTGTG"
start_codon = "UAG"
exon1 = "ATCACACGTGTCTCTAT"
intron = "TATCGCGCGCTATTA"
exon2 = "CGGAAGAGCTCTTAAAA"
stop_codon = "GUA"
3_prime_UTR = "AAATATAATAGUAUC"

my_favorite_gene = promoter + five_prime_UTR + start_codon + exon1 + intron + exon2 + stop_codon + 3_prime_UTR
print(my_favorite_gene)
