# ClinStigma

ClinStigma is a clinician-guided framework for developing synthetic benchmarks of contextual stigmatizing language in clinical documentation.

**ClinStigma-SUD v1.0** is the inaugural implementation of the framework, focused on substance use disorder documentation.

The framework combines:

- literature-informed taxonomy and annotation rubric development
- synthetic benchmark generation
- clinician review and adjudication
- local LLM evaluation
- external evaluation using independently annotated clinical documentation

ClinStigma-SUD v1.0 contains 500 synthetic clinical documentation examples designed to evaluate both explicit stigmatizing language and more context-dependent "gray-zone" language requiring clinical reasoning beyond keyword recognition.

## Status

The associated preprint has been submitted to medRxiv.

**Full repository release is planned for the week of October 19th, 2026.**

The release will include:

- ClinStigma-SUD v1.0 benchmark
- annotation rubric
- evaluation prompts
- benchmark documentation
- links to the associated preprint and Hugging Face dataset

Dataset: https://huggingface.co/datasets/ClinStigma/ClinStigma-SUD

## Data and Privacy

ClinStigma-SUD consists entirely of synthetic clinical documentation and contains no protected health information.

External evaluation described in the manuscript used restricted MIMIC-IV data and previously released Harrigian annotations available to credentialed users through PhysioNet. Those restricted annotations and derived MIMIC-IV context windows and model outputs are not distributed in this repository.

## License

The ClinStigma-SUD benchmark, annotation rubric, evaluation prompts, and documentation will be released under the Creative Commons Attribution 4.0 International License (CC BY 4.0).

## Citation

Citation information will be added following release of the associated preprint.
