## Background and research objective
1. The primary objective for this project is to understand the potential to study genomic medicine practices from clinical databases at Johns Hopkins Medicine (JHM) Institutions. Our broader goal is to use what we learn to design a new registry for use to study what are (in)effective clinical practices, with and without genomics.
2. The primary research question is: Can data that are passively captured from patient electronic medical records be used to derive prevalence, variety, and distribution of genomic medicine practices at JHM? 
3. The secondary research question is: Is there a difference in our capability and performance to derive the prevalence, variety, and distribution of genomic medicine practices in a primary care setting when compared to a specialty genetics care setting?

## Data source and Genomic medicine practice indicators
1. The primary source of the data for this study will be from the Adult Primary Care Center of Excellence (PC-PMCOE Registry), IRB00292427. This study will also use JHM clinical data from Epic and from RedCap for patients qualifying for the RESEQUENCE-GC study (IRB00320656) or that have an encounter with at least one JHM genetics professional.
2. Data sources to capture genomic medicine practices include electronic forms (e.g., electronic health record problem lists), clinical documents (free text), patient portals, and scanned paper forms and documents. Clinical documents we will extract include: progress notes, consults, and discharge summaries (at most 20 notes per patient).
3. Patients included in our dataset will be flagged for indicators of genetic disease, genetic testing, healthcare utilization, diagnoses, medication use, and patient communication with providers

## Data Types and sources
(table)
Data Sources
![image](https://user-images.githubusercontent.com/71967651/198303612-fa0fe447-9ab6-4d52-9cb4-9b52fa4d2bcf.png)

## Proposed Method
1. The data will be accessed on SAFE desktop in the form of flat files or from the Johns Hopkins Precision Medicine Analytics Platform (PMAP). We will analyze both structured and unstructured EHR data. This includes performing Natural Language Processing (NLP) on clinical notes. 
2. Storage locations will include SAFE virtual desktop, PMAP SQL Server database, PMAP ADLS. Analytic tools will include R, Python, PMAP (SQL Server, CrunchR, ADLS), and Excel.
3. We plan to review ~1618 (80k GT order, and 169 clinical notes, and 200k family history of genetic disorder based on Trinetx) patient records from 7/1/2016 to the present day.

