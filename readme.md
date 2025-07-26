# HiEnWrite: A Hindi-English Bilingual Dataset for Big Five Personality Detection

HiEnWrite is a bilingual (Hindi-English) dataset designed to support research in **personality detection** based on the **Big Five traits**: Extroversion, Agreeableness, Conscientiousness, Neuroticism, and Openness. The dataset includes free-form handwritten text samples along with self-reported personality scores and demographic metadata.

## 📦 Dataset Contents

The dataset is structured as a CSV file with the following key columns:

- `image`: ID of the input sample (associated with text or images)
- `Extroversion`, `Agreeableness`, `Conscientiousness`, `Neuroticism`, `Openness`: Personality trait scores (integer scale)
- `Age`, `Gender`: Demographic attributes


## 🧠 Purpose

HiEnWrite was curated to:
- Enable development of **bilingual and code-mixed systems** for personality profiling.
- Facilitate research on **cross-lingual and culture-aware personality detection**.
- Provide a diverse set of handwriting samples tagged with Big Five scores for both supervised and zero-shot models.

## License

The dataset in this repository is licensed under the [Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/).

You are free to share and adapt the material for non-commercial purposes, as long as proper credit is given.

## 📚 Citation

If you use this dataset in your work, please cite:

```bibtex
@article{checker2025hienwrite,
  title={HiEnWrite: A Hindi-English Bilingual Dataset for Big Five Personality Detection},
  author={Checker, Saksham and Yadav, Madhuri and Katarya, Rahul},
  journal={ACM Transactions on Asian and Low-Resource Language Information Processing},
  year={2025},
  doi={10.1145/3756010}
}
