# nf-germline
sentieon dnaseq/scope nextflow for germline NGS sequencing data(WGS/WES/panel)

## blue print

1. WGS/WES/panel, DNAseq(Haplotyper) and DNAscope(ML)
2. Low-Pass WGS(低深度), DNAseq/scope call panel snp vcf, then use GLIMPSE2 to phase and impute vcf
3. additional pipelines, such as SV,CNV 

## attentions

always runs from clean fastq file, and generate single sample gvcf files


