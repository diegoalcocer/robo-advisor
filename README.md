# Robo Advisor
Amazon Lex bot that will recommend an investment portfolio for a retirement plan

---

## Summary

This project is an Amazon Lex Bot that uses Amazan Lambda Functions. Machine learning and NLP are disrupting finance to improve the customer experience, users will be able to use this robo advisor to get investment portfolio recommendations for retirement. 

---
## Installation and Usage

```sh
git clone https://github.com/diegoalcocer/robo-advisor.git
cd robo-advisor/
```
To test the robo advisor and the lambda function `lambda_function.py` you need to [create an Amazon Bot](https://console.aws.amazon.com/lex/home) with four slots:
* `firstName` Amazon.us_first_name
* `age` Amazon.number
* `investmentAmount` Amazon.number
* `riskLevel` Amazon.AlphaNumeric
 
### 📚 img/

Robo advisor works by interacting with the user and providing portfolio recommendations

* In the following video, robo-advisor doesn't have use am AWS Lambda function, and this was the result:
  
    ![](img/firstRoboAdvisor.gif)

* After creating the AWS lambda function and testing it (*Test_Events/*), the following is an example of robo-advisor giving recommendations based on the user input

    ![](img/secondRoboAdvisor.gif)

---

## License

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
