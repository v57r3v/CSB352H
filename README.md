java c
CSB352H Bioinformatic Methods 
Winter 2025 – Lab Report 1 
CSB352: Lab Report 1 This   assignment   asks   you   to   investigate   a   gene   of   unknown   function   from Arabidopsis thaliana, by identifying orthologous sequences from   other organisms   and performing   a multiple sequence alignment of   your discovered orthologs. In   a nutshell, your lab   report will introduce your gene (see arabidopsis.org to as described   in   the   Gene Assignment section of   the Lab Reports part of   Portal; details on the gene/protein   are   also   available from this database), give explicit details of   the analysis you performed   (BLAST   and MSA), describe   the   particulars   of   what   you   found   and   comment   on   what   you   think   it means in a biological context – what could the function of   this   gene be? You will   also perform. a phylogenetic analysis on a subset of   BLAST,   generating the best-resolved   (i.e. greatest   number   of   nodes   that   are   well   supported   based   on   their   bootstrap   scores) phylogenetic tree you can. Is there evidence of   a gene duplication   event   in   a recent ancestor   of Arabidopsis thaliana and   the   other   species   whose   sequences   are   homologous?
The report should be no longer than 6 pages, double-spaced (excluding figures and references)! You   should   cite   all   primary   sources   plus   all   tools/websites/data   sources   used,   using   the   journal Nature’s   reference   format. 
Things you need to keep in mind 
• about your query:
- are you going to BLAST a nucleotide or protein sequence   (or both)?   Genomic   DNA   or   mRNA? Is your sequence long enough?
• about your search database:
- do you want an all-encompassing database or   a well-curated   one?
• about your BLAST parameters:
- which BLAST search algorithm is best for finding   orthologs   in   other   species?
- are you going to use blastn, blastp,   blastx? Why?
- which scoring matrix should you use?
• about your alignment parameters:
- which alignment program are you going to use?
- how rigorous are your gap penalty parameters?
- does your alignment “make   sense”?
• about your phylogenetic analysis:
- which method(s) are you going to use?
- include the closest A. thaliana paralog in the analysis (if   there   is   one)
- note   that   duplicated   genes   are   typically   not   identical   and   that   the “nonredundant”   database does actually have redundancies in it.
Your report should consist of the following sections: 
Introduction: (4 marks)
A   short, two-paragraph   description   of   your   gene   and   the   analyses   performed.
Be sure to include the following   information:
- organism
- sequence source (i.e GI   or AGI   ID number,   sequence type)
- physical location (if   available)
- functional product (if   known) – pI, MW, and other parameters as appropriate
Summarize the genes and taxa included in your analysis. You can   make note   of   any pertinent   alignment   patterns   you   detected   in   your   MSA   (ie: conserved   regions, range   of sequence   identity,   etc.),   and   state   what   you   are   trying   to   ascertain   with   your   phylogenetic   analyses (do not copy the above   objective!). 
Methods: (8 marks)
A concise explanation of   the parameters, data sources, web   sites used   and their citations,   and settings for each in silico experiment performed in   the   final   analysis   you’re presenting   in   this   report.   Note:   The   marker   must   be   able   to   replicate   your   results   solely   from the information in 代 写CSB352H Bioinformatic Methods Winter 2025 – Lab Report 1
代做程序编程语言this   section! 
Be sure to detail the BLAST search(es) you performed along with   any parameter adjustments you made and   justify them. Include the Blast version and databases version. Describe which alignment program you chose as well as all parameters used   in   the analysis. Explain   the   design   of   your   phylogenetic   analysis in prose form, including   the software used, the alignment and phylogenetic tree-building   algorithm(s) used (justify your choices), the parameters you chose for each algorithm.   DO NOT   INCLUDE RESULTS IN THIS   SECTION (see below.) 
Tip: The literature accepted E-value cutoff   for accepting a   sequence   as   orthologous to   the query sequence is   1e-20 as per Lecture 2. If   your   assigned   gene returns   few   or no orthologs   in   the   search, then   contact   [email   protected]   request   a   new   gene.
Results: (12 marks)
Your results will include a short discussion on what was   found   and   anything you   did that was “out of   the ordinary” and why. Also it will include   3   figures,   complete with proper captions. Each   figure   should include   a caption that   describes   the   figure.   The   caption   should   be   detailed   enough   that   the   readers   do   not   need   to   read   the   text   in   order   to   understand   the   figure: 1) a table of   your orthologous sequences (and the most   similar A. thaliana paralog   if there is one) and their associated BLAST statistical values. Be   sure to   justify   your choice       of       sequences       you       selected         for         alignment          (are       all          sequences       truly   “nonredundant”?),   and   include   only   the   sequence   retrieval   (do   not   include   pairwise alignments, please). 2) your best multiple sequence alignment of   the top   15 orthologs from your   BLAST   search – include only one other A. thaliana sequence that   is   not   the   same   as   your assigned gene, that is, include the   closest Arabidopsis thaliana paralog,   if   one   exists.   Make   sure   the   MSA   is   formatted   in   such   away   that   conserved   regions, residues,   or nucleotides are highlighted. Trim it accordingly (i.e.: don’t   include uneven   tail-ends,   as they are uninformative.) 3) A write-up in which the results of   your phylogenetic analysis are displayed and described (but not analyzed). Include within this page your preferred phylogenetic   tree with branch lengths and bootstrap values. In the text, explain any pertinent trends, divergences, or similarities seen   in your tree.
Ifyour alignment or tree viewer program doesn’t generate imagefiles to import into your report document, use screenshots with the PrintScrn button then paste followed by cropping. 
Ensure that the gene name and organism name (abbreviated if   need be) is readable   for each sequence in the alignment. Your query sequence   should be   at the top,   followed   the   closest paralog and orthologs sorted from most to least   similar.
Discussion: (6 marks)
Interpret your results in a biological context. Can you suggest   a possible   function   of   your   gene? Do its relationships with other taxa make sense to you? Is   this   gene widespread   in      the tree of   life (or at least in plants)? Can you   thus   infer whether   it   is   relatively   old   or new? Is it highly conserved across taxa? Are some regions highly   conserved   and   others not? What might this tell you about its function? Do any   species have   duplicated versions   of   this   gene? When   did   the   duplication   occur? 





         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
