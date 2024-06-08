# 🏥 Medical Assistance System

The Medical Assistance System is a Python-based application designed to provide medical assistance to users by predicting diseases, suggesting remedies, recommending hospitals, and estimating treatment costs and duration based on user-provided information about symptoms and patient details.

## Features

- 🩺 Predicts diseases based on symptoms and severity.
- 💊 Suggests remedies for identified symptoms.
- 🏥 Recommends hospitals for treatment based on symptoms, severity, and location.
- 💰 Estimates treatment costs and duration.

## File Structure

- `langchain/`: Contains modules for OpenAI language models and various utilities.
  - `llms.py`: Module for interfacing with OpenAI language models.
  - `prompts.py`: Module containing prompt templates.
  - `chains.py`: Module for defining chain structures for processing user requests.
  - `memory.py`: Module for managing conversation memory.
- `main.py`: Main entry point for the Medical Assistance System.

## Dependencies

- Python 3.x
- OpenAI GPT-3 API

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/medical-assistance-system.git
    cd medical-assistance-system
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Set up OpenAI API key:

    Replace `mykey` variable in `main.py` with your OpenAI API key.

## Usage

1. Run the main script:

    ```bash
    python main.py
    ```

2. Follow the prompts and provide necessary patient details and symptoms when prompted.

3. The system will provide predictions for diseases, suggest remedies, recommend hospitals, and estimate treatment costs and duration based on the provided information.

## Contributing

Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
