# App Usage Statistics Dataset Generator

This Python script generates a synthetic dataset simulating app usage statistics similar to Google Analytics. The dataset includes various attributes such as session ID, user ID, date, time, age, gender, location, retention time, device type, language, and user interactions with app features.

## Features

- Generates synthetic app usage statistics for analysis and modeling.
- Simulates user sessions, including session duration, crash events, and user interactions with app features.
- Includes randomization for realistic variations in user demographics, session characteristics, and app usage patterns.
- Supports customization of dataset size, date range, and other parameters.

## Dependencies

- pandas: Data manipulation and analysis library.
- numpy: Fundamental package for scientific computing with Python.
- Faker: Python library for generating fake data.

## Dataset Structure

The generated dataset includes the following columns:

- session_id
-user_id
- date
- time
- age
- gender
- location
- retention_time
- app_crash
- device_type
- language
- f1_transfer
- f2_bill_payment
- f3_check_balance
- f4_create_FD_acc
- user_rate

## License
This project is licensed under the [CC0-1.0](https://github.com/github/gitignore/blob/main/LICENSE)
