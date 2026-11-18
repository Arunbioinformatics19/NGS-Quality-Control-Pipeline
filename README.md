# NGS-Quality-Control-Pipeline

 An End-to-end Next-Generation sequencing (NGS) quality control and filtering workflow built on  Linux using real **Illumina Novaseq 6000** sequencing data ('ERR5743893').

 ## Tools & Technologies Used
 * **Command Line & Data Inspection:** Linux (Ubuntu), 'zcat', 'wc'
 * **Quality Assessment:** 'FastQC'
 * **Adapter Trimming & Filtering:** 'Fastp'
 * **Unified Quality Reporting:** 'MultiQC'

 ## Key Scientific Findings
 1.**Raw Data Integrity:** Verified 198,314 raw sequencing reads (793,256 lines) without file corruption.
 2.**Quality Filtering('fastp'):** Filtered out 87 low-quality and ambiguous ('N') reads, retaining **99.95% clean reads** (198,227 reads) with **93.26% Q30 bases**.
 3. **Master Dashboard ('MultiQC'):** Aggregated 'FastQC' and 'fastp' metrics into a unified interactive quality report ('multiqc_report.html').
 
