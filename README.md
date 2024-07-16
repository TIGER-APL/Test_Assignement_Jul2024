# TIGeR Bioinformatician Interview Assignment

## Part 1: Make an automated workflow written in a scripting language e.g. BASH, python, R, that does the following:
  - Accepts multiple vcf files as inputs. In this assignment we provided 3 vcf files that we want you to use to demonstrate your workflow. For example:
    `python myworkflow.py HG005_MRG_x35.hard-filtered.vcf.gz HG006_MRG_x35.hard-filtered.vcf.gz HG007_MRG_x35.hard-filtered.vcf.gz`
  - Performs vcf file integrity check. This step should flag at least one of the provided inputs. The file check should manage and recover from the problem input.
  - Filters variants to keep only SNP calls, discarding all INDELs
  - Removes any SNP calls with a Phred QUAL score that is below 20 or a depth (DP) of less than 5 reads.
  - Outputs the SNPs that pass the criteria to a new vcf file
\* In your submission, please include your workflow script, the outputs, and also include instructions on how to run your workflow and how to install any dependencies or external software used by the workflow. Note: we will be running your script
\*\* This workflow should use only publicly available software tools

## Part 2: Make an analysis script that finds unique SNP calls in each valid VCF file from Part 1.
  - Present unique SNP calls in each sample in a report that is outputted by the script (nothing fancy is required. It can be a basic text or markdown report)
  - Summarize characteristics of the unique SNP calls and add the summary to report. Select 2-3 characteristics or metrics that you think would be interesting or helpful. Features or metrics related to the alignments, variants, genes, or genome locations are all suitable areas to consider. In your report, please describe why you selected the characteristic or metric.
 - Generate 1 plot to that helps describe one of the characteristics of the unique SNP calls (This can be output in any image format, png, svg etc)
\*  In your submission, please include your analysis script, the outputs, and also include instructions on how to run your script and how to install any dependencies or external software used by the workflow. Note: we will be running your script
\*\* This analysis should use only publicly available software tools

Please upload your submission to a new public github.com repository that you create and send us the repository address before the deadline.

