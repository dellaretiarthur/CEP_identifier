# # CEP identifier API 🏷️

This repository contains a **Python** application that identifies and validates **Brazilian** ZIP codes (CEP). It uses a database to search for valid CEPs and provides information associated with them.


# # Installation 📝

To use this application, you'll need Python installed on your system. This application has dependencies that can be easily installed using `pip`, the Python package manager.

#### 1. Clone the repository:

`git clone https://github.com/dellaretiarthur/CEP_Identifier.git
`

#### 2. Navigate to the project directory:

`cd CEP_Identifier`


#### 3. Create a virtual environment (optional but recommended):

`python -m venv env`

####  4. Activate the virtual environment:

- <small>**On Windows**</small>:
  - `env\Scripts\activate`
- <small>**On Linux or MacOS**</small>:
   - `source env/bin/activate`

    

#### 5. Install the required Python packages using pip:

- `pip install fastapi`
- `pip install uvicorn`
- `pip install -r requirements.txt`
- `pip install jinja2`


# # USAGE 💻
After installing the dependencies, you can run the application server using the following command:
- `uvicorn main:app --reload`
Note that when the server ir on, a IP adress will be displayed in the terminal. This IP is a local host IP, usually adressed as `127.0.0.1`.
Click + CTRL in the link provided in the terminal to open de URL in your browser.
#### **Note**⚡: 
**The link provided by the uvicorn servidor `http://127.0.0.1:8000/` nedds to be complemented by de following `/cep` to work.* *

- To close the `uvicorn` server, just click `CTRL + C` in the terminal. 


# # Contributing ➕

If you'd like to contribute to this project, you're welcome to fork the repository, make changes, and submit a pull request. Your contributions are highly appreciated.

# # License ©️
This project is licensed under the MIT License - see the [LICENSE](https://chat.openai.com/c/LICENSE) file for details.
