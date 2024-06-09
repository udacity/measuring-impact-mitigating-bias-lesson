# RAG System Performance Evaluation

[![Libraries Used](https://img.shields.io/badge/libraries-RAGAS%20%7C%20DeepEval-blue)](https://github.com/explodinggradients/ragas,https://github.com/deep-eval/deepeval)

This project evaluates the performance of a Retrieval-Augmented Generation (RAG) system by calculating various metrics such as Faithfulness, Answer Relevance, and Geographical Bias. The evaluations use the RAGAS and DeepEval libraries, with results visualized and summarized for easy reporting.

This script evaluates Large Language Model (LLM) responses for:

- **Faithfulness:** How accurately the LLM adheres to the source data.
- **Answer Relevance:** How relevant LLM responses are to user queries.
- **Geographical Bias:** The extent to which LLM responses exhibit geographical bias.

## Usage

1. **Prerequisites:**
   - Python environment
   - Required libraries (install via `pip install ragas deepeval datasets pandas matplotlib seaborn nest_asyncio`)
   - Your LLM response data in the `data_samples` dictionary (replace the placeholder)

2. **Run the Script:**
   - Execute `python your_script_name.py`

## Output

- **Console:** Average scores for each metric.
- **DataFrames:** Detailed results for further analysis (`faithfulness_score_df`, `answer_relevance_df`, `geographical_bias_df`).
- **Plot:** Distribution of answer relevance scores.

## Key Functions

- `create_test_cases(data)`: Converts your dataset into DeepEval's LLMTestCase format for bias analysis.
- `visualize_answer_relevancy(relevancy_df)`: Generates a histogram plot to visualize answer relevance score distribution.

## Customization

- Easily adapt the `data_samples` dictionary to match your data structure.
- Modify the `threshold` in `BiasMetric` to adjust sensitivity for bias detection.
- Explore other metrics available in RAGAS and DeepEval libraries.

## Notes

- Assumes your dataset has columns: `user_query` and `chatbot_response`.
- The example plot is for answer relevance; similar visualizations can be created for other metrics.
- For deeper analysis, refer to the individual dataframes.


## License

Distributed under the Apache License. See [LICENSE](https://github.com/ByteanAtomResearch/ai-product-course-fer/blob/main/LICENSE)  for more information.
Copyright (c) 2024 Noble Ackerson
