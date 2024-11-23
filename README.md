# Real Estate Developer Tower Design Optimization Project

### 📋 Overview

This project, completed as part of a university assignment, addresses the "Real Estate Developer Tower Design Case," where the goal is to design an optimal residential tower that maximizes profitability. The task involved allocating apartments of different sizes and categories across a tower of varying heights (23, 40, and 56 floors). Each apartment was categorized based on its sector (social, middle, free) and ownership type (corporation, investor, private). The design also needed to adhere to several restrictions, such as minimum percentages for social and middle-sector apartments, average size requirements, and ownership distribution, making it a complex optimization problem.

### 🛠️ Solution

To solve this problem, we developed a linear optimization model using the Pyomo library in Python. The model determines the optimal allocation of apartment types to maximize profit while respecting all given design constraints. The problem can be modelled in many different ways, but these approaches differ significantly in efficiency. The model we coded is fully linear and minimizes the number of variables used, leading to a more efficient solution. However, this efficient model also requires some post-processing of the outcomes. Additionally, sensitivity analyses were conducted to explore how modifications to certain restrictions could influence overall profitability, providing valuable insights for potential negotiations with regulators.
