# Gmail AutoLabel App

## Overview

Managing an overflowing email inbox is a common challenge, with numerous irrelevant emails making it difficult to focus on what's important. While many email clients, such as Gmail, offer basic categorization into Primary, Social, and Promotions, they often fall short of providing personalized and customizable email organization based on individual priorities.

The Auto Email Labeller project aims to address this issue by enabling users to create customized email labels based on their specific needs and interests. By allowing users to define their persona and areas of focus, this tool helps to cut through the noise and keep their inbox clutter-free.

## Implementation Specifics

### Higher Level Back End Architecture  

- **Minimalist Approach**: We deliberately minimized reliance on heavy frameworks like langchain and other AI frameworks to keep the system lightweight and efficient.
- **Local AI Model**: To address privacy concerns, we provide an alternative AI model that runs locally on the user's device.

### Backend Functionality

This repository focuses on the backend functionality of the Auto Labeller. The frontend is currently under development and is at a very early stage.

- **Windows Native Application**: We chose to build this as a Windows native application using Flutter to ensure smooth performance.
- **Unconventional File Read-Write System**: We implemented a unique file read-write system with subprocess calls to the Python process to avoid the overhead of having an API server on both ends.
- **Local Application**: Our focus is on having this application run locally rather than being cloud-first.

## Getting Started

### Installation

1. **Tester Access**: To access the app, you need to be added as a tester. Please email your mail ID to:  
   ```
   pranaam541@gmail.com
   ```

2. **Accessing the App**: Open the "Hackathon" file in the extracted folder to access the app.

3. **Labeling Process**: The script will process your emails and automatically apply the appropriate labels based on the configuration.

### Congratulations!

You have successfully labeled your emails. To check the labeled emails, open your Gmail.

Let me know if you need further assistance or have any questions!
