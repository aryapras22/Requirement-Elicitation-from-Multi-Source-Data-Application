# Requirement-Elicitation-from-Multi-Source-Data

old repository : https://github.com/aryapras22/Requirement-Ellicitation-from-Multi-Source-Data

This project facilitates requirement elicitation from multi-source data by leveraging NLP techniques and multi-source data analysis. It integrates a backend powered by Django and a frontend developed with modern JavaScript frameworks.

## Installation Guide

Follow these steps to set up and run the project:

### 1. Prerequisites
- Ensure **MongoDB** is installed and running on your system.
- Install **Conda** for managing the virtual environment.

### 2. Setting Up the Environment
1. Clone the repository.
2. Rename `.env.example` to `.env` and add your API key from [Newscatcher](https://www.newscatcherapi.com/).

### 3. Backend Setup
1. Create a virtual environment:
   ```bash
   conda env create -f requirements.yml --name env_name
   ```
2. Activate the virtual environment:
   ```bash
   conda activate env_name
   ```
3. Install the SpaCy English pipeline:
   ```bash
   python -m spacy download en_core_web_lg
   ```
4. Navigate to the backend directory and start the Django server:
   ```bash
   python manage.py runserver
   ```

### 4. Frontend Setup
1. Navigate to the frontend directory.
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the frontend server:
   ```bash
   npm run dev
   ```

## Notes
- This project uses the [Newscatcher API](https://www.newscatcherapi.com/) to retrieve news data for analysis.
- Ensure your API key is valid and properly configured in the `.env` file.

## Troubleshooting
- **Database Issues**: Ensure MongoDB is running and properly configured.
- **Environment Issues**: Double-check the virtual environment setup and required dependencies.

## Contributing
Feel free to fork the repository and submit pull requests for any improvements or bug fixes.

---

Happy Coding! 🎉

