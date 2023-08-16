# Medical Insurance Cost Estimation Project

This project is a Python script that estimates medical insurance costs based on different factors such as age, sex, BMI, number of children, and smoking status.

## Table of Contents
- [Description](#description)
- [Usage](#usage)
  - [Factors Explored](#factors-explored)
  - [Getting Started](#getting-started)
- [Contributing](#contributing)
- [License](#license)

## Description
This project demonstrates how different factors influence medical insurance cost estimations. The Python script uses a formula to calculate insurance costs based on age, sex, BMI, number of children, and smoking status.

## Usage
### Factors Explored
The project explores the impact of the following factors on insurance costs:
- Age
- BMI (Body Mass Index)
- Sex (Male or Female)
- Smoking Status
- Number of Children

### Getting Started
1. Clone the repository:
https://github.com/Katis254/Medical-Insurance-Cost-Estimation.git

3. Run this Python script:
# Create the initial variables
age = 28
sex = 0  # 0 for female, 1 for male
bmi = 26.2
num_of_children = 3
smoker = 0  # 0 for non-smoker, 1 for smoker

# Insurance estimate formula
insurance_cost = 250 * age - 128 * sex + 370 * bmi + 425 * num_of_children + 24000 * smoker - 12500

# Display the insurance cost
print("This person's insurance cost is {} dollars.".format(insurance_cost))

# Age Factor
age += 4  # Adding 4 years to age
new_insurance_cost = 250 * age - 128 * sex + 370 * bmi + 425 * num_of_children + 24000 * smoker - 12500
change_in_insurance_cost = new_insurance_cost - insurance_cost
print("The change in cost of insurance after increasing the age by 4 years is {} dollars.".format(change_in_insurance_cost))

# BMI Factor
age = 28  # Resetting age to its original value
bmi += 3.1  # Adding 3.1 to bmi
new_insurance_cost = 250 * age - 128 * sex + 370 * bmi + 425 * num_of_children + 24000 * smoker - 12500
change_in_insurance_cost = new_insurance_cost - insurance_cost
print("The change in estimated insurance cost after increasing BMI by 3.1 is {} dollars.".format(change_in_insurance_cost))

# Male vs. Female Factor
bmi = 26.2  # Resetting bmi to its original value
sex = 1  # Changing sex to male
new_insurance_cost = 250 * age - 128 * sex + 370 * bmi + 425 * num_of_children + 24000 * smoker - 12500
change_in_insurance_cost = new_insurance_cost - insurance_cost
print("The change in estimated cost for being male instead of female is {} dollars.".format(change_in_insurance_cost))


4. Observe the estimated insurance costs and changes based on different factors.

## Exploring Factors
### Age Factor
The script evaluates the impact of age on insurance costs. It calculates the difference in insurance costs when the age is increased by 4 years.

### BMI Factor
The project also investigates the role of BMI in insurance cost estimations. It calculates the difference in insurance costs when the BMI is increased by 3.1.

### Male vs. Female Factor
The script explores how sex affects insurance costs. It calculates the difference in insurance costs when changing the sex from female to male.

## Contributing
Contributions are welcome! If you'd like to contribute to the project, follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or improvement.
3. Make your changes and test them.
4. Commit your changes with a descriptive message.
5. Push your branch to your forked repository.
6. Create a pull request to the main repository's `main` branch.

## License
This project is licensed under the [MIT License](LICENSE).

## Contact
For questions or feedback, feel free to contact [Dennis Kithandi](mailto:kithandikatisya@gmail.com).
