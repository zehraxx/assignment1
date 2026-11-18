def print_favorite_gene():
    promoter = "AAGGCCTT"
    five_prime_UTR = "GCGGCTAA"
    start_codon = "ATG"
    exon1 = "GGCAGTAGCAT"
    intron = "AGCTACGATCAG"
    exon2 = "AGCTAGCTAGCT"
    stop_codon = "AGCTAGCATCAGT"
    three_prime_UTR = "GAGAGCGATGACT"
    polyA_tail = "A" * 25

    gene = promoter + five_primer_UTR + start_codon + exon1 + intron + exon2 + stop_codon + three_prime_UTR + polyA_tail

    print("My favorite gene is: " , gene)