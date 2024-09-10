# World History Since 1500: Q&A Dataset

This repository contains a set of question and answer pairs derived from the book "World History Since 1500: An Open and Free Textbook" by John Rankin and Constanze Weise of East Tennessee State University.

## Dataset Description

This dataset consists of high-quality question and answer pairs generated from the content of "World History Since 1500: An Open and Free Textbook". The Q&A pairs are designed to cover key historical events, figures, and concepts from 1500 to the present day, providing a comprehensive resource for students, educators, and history enthusiasts.

## Attribution and License

### Original Work

- **Title**: [World History Since 1500: An Open and Free Textbook](https://open.umn.edu/opentextbooks/textbooks/world-history-since-1500-an-open-and-free-textbook)
- **Authors**: John Rankin and Constanze Weise
- **Institution**: East Tennessee State University
- **Copyright Year**: 2023
- **License**: CC BY-SA (Creative Commons Attribution-ShareAlike)
- **Language**: English

### Derivative Work (This Dataset)

This Q&A dataset is a derivative work based on the original textbook. It was created using the PlanAI task orchestration framework to generate question and answer pairs.

- **License**: CC BY-SA 4.0 (Creative Commons Attribution-ShareAlike 4.0 International)
- **License URL**: https://creativecommons.org/licenses/by-sa/4.0/

### Attribution Statement

This work is derived from "World History Since 1500: An Open and Free Textbook" by John Rankin and Constanze Weise of East Tennessee State University, published in 2023. The original work is licensed under CC BY-SA. This derivative work, consisting of generated question and answer pairs, is also licensed under CC BY-SA 4.0.

## PlanAI Framework

The question and answer pairs in this dataset were generated using PlanAI, an open-source task orchestration framework. PlanAI is licensed under the Apache License 2.0.

- **PlanAI GitHub**: https://github.com/provos/planai
- **PlanAI Documentation**: https://docs.getplanai.com/

## Usage

This dataset is provided in JSON format. Each entry contains a question and its corresponding answer, along with metadata about the source material.

### Sample Structure

```json
{
    "metadata": {
        "dataset_name": "World History Since 1500 Q&A Dataset",
        "dataset_description": "A collection of question and answer pairs derived from 'World History Since 1500: An Open and Free Textbook'",
        "original_work": {
            "title": "World History Since 1500: An Open and Free Textbook",
            "authors": [
                "John Rankin",
                "Constanze Weise"
            ],
            "institution": "East Tennessee State University",
            "publication_year": 2023,
            "language": "English",
            "license": "CC BY-SA",
            "license_url": "https://creativecommons.org/licenses/by-sa/4.0/"
        },
        "derivative_work": {
            "title": "World History Since 1500 Q&A Dataset",
            "creator": "Your Name or Organization",
            "creation_date": "2024-09-10",
            "description": "Question and answer pairs generated using PlanAI task orchestration framework",
            "license": "CC BY-SA 4.0",
            "license_url": "https://creativecommons.org/licenses/by-sa/4.0/"
        },
        "generation_tool": {
            "name": "PlanAI",
            "version": "0.1.3",
            "repository": "https://github.com/provos/planai",
            "documentation": "https://docs.getplanai.com/"
        },
        "attribution": "This work is derived from 'World History Since 1500: An Open and Free Textbook' by John Rankin and Constanze Weise of East Tennessee State University, published in 2023. The original work is licensed under CC BY-SA. This derivative work, consisting of generated question and answer pairs, is also licensed under CC BY-SA 4.0.",
        "usage_notes": "This dataset is intended for educational and research purposes. Users should refer to the original textbook and other authoritative sources for definitive information.",
        "contact": "For questions or concerns, please open an issue in the GitHub repository: https://github.com/yourusername/world-history-1500-qa"
    },
    "qa_pairs": [
        {
            "question": "What was the impact of Winston Churchill’s 1946 speech on U.S. public opinion towards the Soviet Union?",
            "answer": "The immediate impact of Churchill's 1946 speech was profound, reshaping U.S. public perception of the Soviet Union as a formidable adversary. By recognizing and naming Soviet influence in Central and Eastern Europe, Churchill not only illustrated the urgency of the situation but also positioned the United States as a key player in countering Soviet ambitions. Following the speech, events such as the Soviet attempt to pressure Turkey underscored the call to action that Churchill proposed. The United States' response, including military deployments and the establishment of the National Security Council, reflected a newfound seriousness in American foreign policy. This attitude paved the way for substantial policy changes aimed at preventing any further encroachment of communism, signifying the beginning of a prolonged ideological confrontation with the USSR."
        },
    // More Q&A pairs...
  ]
}
```

## Contributing

While this dataset is primarily generated from the original textbook, we welcome contributions that improve the quality, accuracy, or coverage of the Q&A pairs. Please submit a pull request with your proposed changes.

## Disclaimer

This dataset is intended for educational and research purposes. While efforts have been made to ensure accuracy, users should refer to the original textbook and other authoritative sources for definitive information.

## Contact

For questions or concerns regarding this dataset, please open an issue in this GitHub repository.