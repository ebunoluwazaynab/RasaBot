# Rasa Chatbot Project

This project contains a Rasa chatbot with additional functionalities.

## Setup Instructions

### Prerequisites
- Python 3.7+
- pip (Python package installer)

### Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/ebunoluwazaynab/RasaBot.git
    cd RasaBot
    ```

2. **Create a Virtual Environment**:
    ```bash
    python -m venv ./venv 
    .\venv\Scripts\activate
    ```

3. **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

### Running the Project

1. **Train the Model**:
    ```bash
    rasa train
    ```

2. **Run the Chatbot**:
    ```bash
    rasa shell
    ```

3. **Run Rasa Server with API and CORS**:
    ```bash
    rasa run --enable-api --cors "*"
    ```

### Chatbot Widget

To integrate a chatbot widget, you can use the following repository:
- **Chatbot Widget Repository**: [git clone https://github.com/JiteshGaikwad/Chatbot-Widget.git](https://github.com/JiteshGaikwad/Chatbot-Widget.git)

### Additional Resources

- [Rasa Documentation](https://rasa.com/docs/)
- [Rasa SDK Documentation](https://rasa.com/docs/rasa/sdk/)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
