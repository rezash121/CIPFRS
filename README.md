# **CIPFRS: The Many Facets of Fairness in Recommender Systems: Consumers, Providers and Items**

## **Table of Contents**
- [Overview](#overview)
- [Features](#features)
- [Usage](#usage)
- [Contributions](#contributions)
- [License](#license)
- [Contact](#contact)

- ## **Overview**
Autonomous decision-making systems, particularly recommender systems, have received increasing attention concerning fairness, i.e., if all stakeholders affected by such a system are treated equally as a result of the recommendations. While extensive research literature exists and solutions to ensure fairness for consumers and providers have been proposed, a key hidden stakeholder remains underlooked: the items themselves, which many either disregard or consider combined with providers. To this end, we propose a fairness-aware recommender system, CIPFRS, designed to optimize fairness across all three key stakeholders: consumers, providers, and items. We examine 
consumer fairness regarding their level of interaction with the system; high and low-activity users should be treated equally. Further, all providers should have an equal opportunity for their products to be recommended. Finally, we propose an approach to implement item fairness in each provider's inventory. 


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
