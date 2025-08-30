## Prerequisites

- Python 3.8+
- OpenAI API key

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <projectname>
   ```

2. Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: .\venv\Scripts\activate
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   pip install -e . # to install setup.py
   ```

4. Set up environment variables:
   Create a `.env` file in the project root with the following content:
   ```
   OPENAI_API_KEY=your_openai_api_key
   ```