# Podcast Newsletter Dashboard

This is a Streamlit application that allows users to create newsletters based on podcast episodes. The application uses the Modal API to process podcast RSS feeds and extract relevant information such as the episode title, summary, guest information, and key moments. This information is then displayed in a user-friendly interface that allows users to easily create and edit newsletters.

### Prerequisites

To run this application, you will need the following:

* Python 3.6 or later
* Streamlit
* Modal
* A Modal account

### Installation

To install the required dependencies, run the following command:

```
pip install -r requirements.txt
```

### Usage

To run the application, run the following command:

```
streamlit run podcast_frontend.py
```

The application will then be available at http://localhost:8501.

### Code Walkthrough

The code for this application is divided into two files:

* `podcast_frontend.py`: This file contains the Streamlit application code.
* `requirements.txt`: This file lists the required Python packages.

The `podcast_frontend.py` file starts by importing the necessary libraries.

```
import streamlit as st
import modal
import json
import os
```

The `main()` function is then defined. This function contains the code that runs the Streamlit application.