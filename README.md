# Creditworthiness Evaluation Fuzzy Logic System

This repository contains a simple Matlab program designed to evaluate the creditworthiness of individuals based on fuzzy logic principles. Using inputs such as income, credit history, and existing debts, the system outputs an evaluation of the individual's creditworthiness, categorizing it into three groups: low, medium, and high.

## Overview

The system implements a fuzzy logic approach to categorize creditworthiness. It uses predefined membership functions and rules to process the inputs (income, credit history, existing debts) and generate an output (creditworthiness). The categorization of creditworthiness into low, medium, and high is intended to aid in decision-making processes related to credit and loans.

### Input Variables

- **Income**: Reflects the client's income level. Fuzzy sets: Low, Medium, High.
- **Credit History**: Represents the client's past credit behavior. Fuzzy sets: Poor, Medium, Good.
- **Existing Debts**: Indicates the client's current debt level. Fuzzy sets: None, Few, Many.

### Output Variable

- **Creditworthiness**: The evaluation of the client's ability to repay. Fuzzy sets: Low, Medium, High.

### Rules

The system comprises nine rules that define the relationship between the input variables and the creditworthiness output. These rules enable the system to provide a nuanced evaluation based on the inputs provided.

### Example

Given an income of 500,000, a credit history score of 5, and existing debts amounting to 50, the system evaluates the creditworthiness as "Medium".

## Getting Started

To use this fuzzy logic system, you will need MATLAB installed on your computer. The core of the system is contained within the `Creditworthiness_Calculator.txt` file, which includes the fuzzy logic system's setup, rules, and membership function definitions.

### Installation

1. Clone this repository or download the `Creditworthiness_Calculator.txt` file.
2. Open MATLAB and navigate to the directory where the file is located.
3. Load the fuzzy logic system by opening the `Creditworthiness_Calculator.txt` file in MATLAB.

## Usage

After loading the system in MATLAB, you can input values for income, credit history, and existing debts to evaluate an individual's creditworthiness. The system will output a categorization of the creditworthiness as low, medium, or high based on the predefined rules and membership functions.


## Note

- This system is a simple demonstration of applying fuzzy logic to real-world problems. It serves as a foundational example for more complex systems that could incorporate additional variables and more detailed rules for a comprehensive evaluation.
