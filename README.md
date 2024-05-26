# Gmail AutoLabel App

## Overview

Managing an overflowing email inbox is a common challenge, with numerous irrelevant emails making it difficult to focus on what's important. While many email clients, such as Gmail, offer basic categorization into Primary, Social, and Promotions, they often fall short of providing personalized and customizable email organization based on individual priorities.

The Auto Email Labeller project aims to address this issue by enabling users to create customized email labels based on their specific needs and interests. By allowing users to define their persona and areas of focus, this tool helps to cut through the noise and keep their inbox clutter-free.
  

## Implementation Specifics
Higher Level Back End Architecture  

- We tried to rely less on frameworks such as langchain and other AI frameworks since they were overkill, sticking to minimalism was a deliberate decision  
- Providing an alternative AI Model that runs locally for privacy concerns

This Repo focuses on the backend functionality of the Auto Labeller , the front end is in the works and at a very early stage  
  
- We decided to build this as a windows native application using flutter and using a unconventional file read-write system with sub process calls to the python process
- This is to avoid the additional overhead of having an API Server on both ends , which again seemed like an overkill for such a project
- Our focus is on having this run locally as an application and not a cloud first app

## Getting Started
   Download the "Auto Label build.zip" raw file and extract it

### Installation

1. To get access to the app, you have to be added as a tester.So email me your mail id on:
   ```
   pranaam541@gmail.com
   ```
2. Open the "Hackathon" file in the extracted folder to access the app.

3.  The script will process your emails and automatically apply the appropriate labels based on 
     the configuration.
   

### Congragulations!!! You have successfully Labeled you emails.To check the labeled emails open your Gmail.



