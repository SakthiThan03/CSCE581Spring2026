# Quiz 3 Feedback - Sakthi Thanigai

**Q1: 42 / 70**
**Q2: 25 / 30**
**Total: 67 / 100**

---

## Q1 - 42 / 70

- **-12**: The submitted `us-allstates-voter-faqs.csv` is not an all-states combined dataset. It has 103 rows and only two states (`NM` and `TX`).
- **-16**: The LIME sample-explanation requirement is not met at the required scale. The notebook generates a per-state/per-class sample set, but the submitted artifact `us-allstates-voter-faqs-classifier-svm_calibrated-sampleoutput.csv` contains only 3 examples, and the PDF dump corresponds to that small set rather than around 100 explanations spanning states/classes.

## Q2 - 25 / 30

- **-5**: The five selected presidents are not spaced about 50 years apart. The chosen years are 1789, 1829, 1897, 1961, and 2025, which produce gaps of 40, 68, 64, and 64 years.
