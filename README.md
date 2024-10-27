# AI & Machine Learning Research Papers Dataset

This dataset contains a curated collection of 1296 research papers focused on advancements in Artificial Intelligence and Machine Learning. It is intended as a resource for researchers, educators, and developers to explore and analyze diverse topics within AI and ML.

---

## Dataset Summary

- **Total Papers**: 1296
- **Domains Covered**: 
  - Artificial Intelligence (AI)
  - Machine Learning (ML)
  - Deep Learning
  - Natural Language Processing (NLP)
  - Computer Vision
  - Reinforcement Learning
  - And more!
- **Sources**: Aggregated from reputable journals, conferences, and open-access archives.
- **Data Format**: JSON or CSV (check files for specific formats)

---

## Dataset Details

### Columns

| Column             | Description                                                                                           |
|--------------------|-------------------------------------------------------------------------------------------------------|
| `paper_id`         | Unique identifier for each paper.                                                                     |
| `title`            | Title of the research paper.                                                                          |
| `abstract`         | Summary or abstract of the paper’s content.                                                           |
| `authors`          | List of authors, separated by commas.                                                                 |
| `publication_date` | Date of publication (in `YYYY-MM-DD` format).                                                         |
| `journal`          | Journal or conference where the paper was published.                                                  |
| `keywords`         | Relevant keywords associated with the paper.                                                          |
| `pdf_url`          | Direct link to the full-text PDF (where available).                                                   |
| `doi`              | Digital Object Identifier (DOI) for easy citation and referencing.                                    |
| `citations`        | Number of citations, where available.                                                                 |
| `topics`           | Primary topics or categories the paper belongs to, e.g., NLP, Computer Vision, Reinforcement Learning.|

---

## Usage Examples

This dataset can be used for various research and development purposes:

1. **Trend Analysis**: Identify emerging trends and key topics in AI and ML over time.
2. **Text Mining & NLP**: Perform topic modeling, keyword extraction, or sentiment analysis on abstracts and keywords.
3. **Citation Analysis**: Study citation patterns to identify influential works or frequently cited topics.
4. **Recommender Systems**: Develop models to recommend related papers based on topics, keywords, or citation counts.

---

## Getting Started

To use this dataset:

    ```bash
    import subprocess

    # Use subprocess.run for better practice
    subprocess.run(['curl', '-L', 'https://huggingface.co/datasets/khushwant04/Research-Papers/resolve/main/research-papers.tar?download=true', '-o', 'research-papers.tar'], check=True)
    subprocess.run(['tar', '-xf', 'research-papers.tar'], check=True)
    ```

## License

This dataset is provided for academic and research purposes. Please adhere to the licensing terms of individual papers as specified by their publishers.

---

## Citation

If you use this dataset in your research, please cite it as follows:

```bibtex
@dataset{your_name_aiml_papers_2024,
  title = {AI & Machine Learning Research Papers Dataset},
  author = {Khushwant Sanwalot},
  year = {2024},
  publisher = {Hugging Face},
  url = {https://huggingface.co/datasets/khushwant04/Research-Papers}
}
