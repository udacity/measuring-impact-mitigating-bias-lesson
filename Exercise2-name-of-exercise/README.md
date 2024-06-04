
[![LinkedIn][linkedin-shield]][linkedin-url]
[![Youtube][youtube-shield]][youtube-url]
[![Udacity][udacity-shield]][udacity-url]

# Fairness Evaluation Exercise

This exercise is designed to help learners evaluate and report on the fairness of an AI chatbot for a fictional AI based product named Mango Oasis, specifically focusing on identifying and mitigating geographical biases. 
The goal is to analyze chatbot responses, calculate relevant metrics, and provide actionable recommendations based on the findings


# Requirements

- Python
- Pandas
- Matplotlib
- RAGAS
- DeepEval
- Seaborn

# Instructions
- Ensure the data file is in the correct format.
- Follow the steps outlined to load data, calculate metrics, detect bias, visualize results, and generate the report.
- Use the provided code snippets to complete each step.
- This notebook is optimized for Google Colab.

### NOTE

I prefer if you upload it to colab and run it.

However, to run this locally, be sure you:
-  have python running locally, update the library install format from `!` to `%` so for example `!pip install foo` becomes `%pip install foo`
- store secrets as env variables in your local system using `os.environ.get("SECRET_NAME")` vs what I've currently implemtented



## License

Distributed under the MIT License. See `LICENSE` for more information.


[linkedin-url]: https://linkedin.com/in/noblea
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[youtube-url]: https://youtube.com/c/nobleackerson
[udacity-url]: https://www.udacity.com/course/ai-product-manager-nanodegree--nd088
[youtube-shield]: https://img.shields.io/badge/-Youtube-black.svg?style=for-the-badge&logo=youtube&colorB=555
[udacity-shield]: https://img.shields.io/badge/-Udacity-black.svg?style=for-the-badge&logo=udcaity&colorB=555
