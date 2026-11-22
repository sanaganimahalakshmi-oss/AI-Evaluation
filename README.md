# AI Skill Tag Evaluation

## Objective

Evaluate the accuracy of AI-generated skill tags for 50 job descriptions.

## Dataset

- job-descriptions-tagged.csv
- skill-list.csv

## Files

- labels.xlsx
- report.pdf (or report.docx)
- README.md

## Evaluation Method

Each job description was manually compared with the AI-generated skill tags.

The following were identified:

- Correct Tags
- Wrong Tags
- Missing Tags

## Results

- Correct Tags: 165
- Wrong Tags: 30
- Missing Tags: 63
- Precision: 84.62%
- Miss Rate: 27.63%

## Suggested Improvement

Implement synonym mapping (Node ↔ Node.js, JS ↔ JavaScript, Excel ↔ Microsoft Excel) to improve tag accuracy.
