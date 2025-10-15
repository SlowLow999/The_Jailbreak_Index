# The Jailbreak Index

### A Curated Database for AI Security Researchers

---

#### [View the Live Index ⬅️](https://slowlow999.github.io/The_Jailbreak_Index/)



## About This Project

The Jailbreak Index is a centralized, open-source project designed to track and analyze prompt injection vulnerabilities in prominent AI models. The goal is to consolidate scattered research into a single, accessible database for security researchers, red teamers, and developers.

This index aggregates and standardizes data from over 18 peer-reviewed studies and security reports published between 2024 and 2025. It is presented in a self-contained, single-page application with a user interface designed for clarity and rapid assessment.

## Key Features

* **Comprehensive Database:** In-depth security analysis of 38+ models from leading AI labs, including OpenAI, Google, Anthropic, and Mistral.
* **Standardized Difficulty Ratings:** A consistent 1-to-5 scale is used to rate the difficulty of bypassing a model's safety protocols, allowing for direct comparison.
* **Detailed Vulnerability Data:** Each entry includes insights into primary attack vectors (e.g., Adaptive Attacks, Timed-Release), documented success rates, and relevant notes from the source material.
* **Data Visualization:** The summary section includes an interactive chart that provides a high-level overview of the security landscape across all cataloged models.
* **Single-File Architecture:** The entire project is contained within a single `index.html` file, making it highly portable and easy to host or run locally.

## Tech Stack

The project is built with a focus on simplicity and performance, using fundamental web technologies:

* **HTML5**
* **Tailwind CSS**
* **Vanilla JavaScript**
* **Chart.js**

## How to Contribute

Contributions are welcome and essential for keeping the index current. If you have new data or would like to suggest an improvement, please follow this process:

1.  Fork the repository.
2.  Make your changes or additions directly within the `index.html` file.
3.  Submit a pull request with a clear title and a description of the changes.

Alternatively, you can open a GitHub Issue to submit new findings or discuss potential changes.

## Disclaimer

The information provided in The Jailbreak Index is for educational and research purposes only. It is intended to contribute to the responsible disclosure of vulnerabilities and aid in the development of more secure and robust AI systems.

## License

This project is distributed under the MIT License.
