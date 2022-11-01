## Background 
Need to monitor if Genomic Medicine Practice are effective.

## Objective
To enable secondary research studies to understand the potential and effectiveness of Genomic Medicine Practice.

## Population Description
1. The primary source of the data for this study will be from the Adult Primary Care Center of Excellence (PC-PMCOE Registry), IRB00292427. This registry will also include patients that had an encounter with at least one JHM genetics professional.
2. Patients included in our dataset will be flagged for indicators of genetic disease, genetic testing, healthcare utilization, diagnoses, medication use, and patient communication with providers

## Data Types and Sources
Data sources to capture genomic medicine practices include electronic forms (e.g., electronic health record problem lists), clinical documents (free text), patient portals, and scanned paper forms and documents. Clinical documents we will extract include: progress notes, consults, and discharge summaries (at most 20 notes per patient).

<img width="323" alt="image" src="https://user-images.githubusercontent.com/71967651/199326661-b2daf585-ae83-41aa-b946-7c8961096ffa.png">


## Proposed Method (under revision) 
1. The data will be accessed on SAFE desktop in the form of flat files or from the Johns Hopkins Precision Medicine Analytics Platform (PMAP). We will analyze both structured and unstructured EHR data. This includes performing Natural Language Processing (NLP) on clinical notes. 
2. Storage locations will include SAFE virtual desktop, PMAP SQL Server database, PMAP ADLS. Analytic tools will include R, Python, PMAP (SQL Server, CrunchR, ADLS), and Excel.
3. We plan to review ~1618 (80k GT order, and 169 clinical notes, and 200k family history of genetic disorder based on Trinetx) patient records from 7/1/2016 to the present day.

