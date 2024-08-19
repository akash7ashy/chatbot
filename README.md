# Custom Chatbot for PSNA College of Engineering and Technology

## Overview

This README provides an overview of the custom chatbot designed for PSNA College of Engineering and Technology. The chatbot aims to assist users with inquiries related to course schedules, administrative staff details, and other relevant information about the college.

## Features

- **Course Schedules**: Provides detailed information about the courses offered, their schedules, and academic calendar.
- **Administrative Staff Details**: Provides information about the administrative staff, including contact details and roles.
- **Knowledge Base**: The chatbot uses a knowledge base that can be updated with new information as needed.

## Prerequisites

### Software Requirements

- **Python**: Ensure Python 3.x is installed on your system.
- **Streamlit**: Install Streamlit for creating the interactive web application.

### Knowledge Base File

- **File Structure**: Ensure you have a `knowledge_base.json` file with the correct structure.

## Installation

### Clone the Repository

```bash
git clone <repository-url>
cd <repository-directory>

## streamlit installation:

pip install streamlit

## Set Up the Knowledge Base:
Ensure you have a 'knowledge_base.json file' in the project directory with the following structure:

{
  "courses": [
    {
      "course_name": "Course Title",
      "schedule": "Course Schedule",
      "details": "Additional Information"
    }
  ],
  "staff": [
    {
      "name": "Staff Member",
      "position": "Position",
      "contact": "Contact Details"
    }
  ]
}

## Usage
## Run the Chatbot
Use Streamlit to run the chatbot application:
streamlit run app.py

## Interact with the Chatbot
Open the web browser and navigate to the local URL provided by Streamlit (usually http://localhost:8501).

Contact
For further assistance, please contact:

Support Team: 13r.akash@gmail.com
Technical Contact: 13r.akash@gmail.com









