# **CIPFRS: The Many Facets of Fairness in Recommender Systems: Consumers, Providers and Items**

## **Table of Contents**
- [Overview](#overview)
- [Features](#features)
- [Usage](#usage)
- [Baseline Reference](#baseline-reference)
- [Contributions](#contributions)
- [License](#license)
- [Contact](#contact)

- ## **Overview**
This project introduces CIPFRS, a fairness-aware recommender system that optimizes fairness for three key stakeholders: providers, items, and consumers. Our approach ensures balanced opportunities for providers to showcase their items, reduces popularity bias across items, and promotes equitable treatment for all consumers based on their interactions.

This code aims to replicate and extend the baseline methodology from the original work, with modifications and additional features to enhance evaluation and optimize fairness aspects.

## **Features**

- **Multi-Stakeholder Fairness**: Ensures fairness for consumers, providers, and items in the recommendation process.
- **Customizable Fairness Modes**: Supports multiple fairness modes to address different stakeholder needs.
- **Gini Index Evaluation**: Includes measures for assessing fairness across providers and item inventories.
- **Extensive Evaluation**: Evaluates system performance and fairness using various metrics.
  
## **Usage**

We provide a Jupyter Notebook that contains all the code and required packages for installation and running the project. Follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/rezash121/CIPFRS.git
   cd CIPFRS
   ```

2. Open the notebook:
   ```bash
   jupyter notebook CIPFRS Notebook.ipynb
   ```

3. Follow the instructions in the notebook to set up the environment, install necessary packages, and run the code. The notebook includes explanations and cells for executing each part of the process.

## **Baseline Reference**

This project builds upon the baseline implementation available at:  
[rahmanidashti/CPFairRecSys](https://github.com/rahmanidashti/CPFairRecSys).

Some parts of this code (functions, parameters, algorithms) are taken directly from the original work by Hossein A. Rahmani, while additional modifications, new functions, and evaluations have been added by author of CIPFRS as part of this project.

## **Contributions**

Contributions are welcome! If you'd like to contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.

Please ensure your code adheres to the project's coding style and passes all tests before submitting a pull request.

## **License**

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## **Contact**

For any questions or suggestions, please contact:  
**Reza Shafiloo**  
Email: [rezashafiloo121@gmail.com](mailto:rezashafiloo121@gmail.com)  
GitHub: [rezash121](https://github.com/rezash121)
