# Religious Chatbot
The goal of this project was to train a machine learning chatbot off of religious texts using transfer learning in order to investigate the significance of the religious texts on the LLM as well as any apparent emergent traits that could be determined from the chatbot.

# Contents

### Team/Contributers
---

This project was originally proposed by Drew Dickens, and was taken up by myself and Dr. Tue Vu on behalf of the Data Center at Southern Methodist University. 

### Purpose
---

As is touched on above, the purpose of the project was to give Drew Dickens a functional machine learning chatbot so that he could use it in a dissertation regarding the use of religion within artificial intellingence. The model was to be used as a proof of concept that AI could be influenced by the implementation of religion into its training material, as well as to investigate how the inclusion of this material alters the chatbot.

### Data Cleaning
---

The data cleaning was a massive part of the process in creating this project. We went through multiple different datasets and many different iterations of each one in order before landing on the dataset that was used to train the posted model. Most of the time data cleaning went into configureing the data to be presented in a converstational format, so that it may effectivley contribute to the conversational aspect of the chatbot.

### Model Training
---

The model was trained using the pre-trained dialog-response model, DialoGPT, which was implemented using transformers and transfer learning. This was all trained on the university M2 supercomputer.

### Current State
---

The chatbot was successfully trained to be conversational and would accurately answer questions based on the religioud text it was given. Drew was able to use this chatbot for his dissertation and within the data center, we were able to observe some interesting occurences, such as spontaneous nihlism that we wished to investigate further. Unfortunatley, not long after our model was trained and operational RAGs (Retreival Augmented Generation) became popularized. They became extremely popular through their use in OpenAI's `OpenAI Playground`, and they made it much easier to train a conversational machine learning chatbot based off of a given text. As a result of this, and the success of his dissertation, Drew stopped working with the data center my team was moved to different project. The models we created through this research are still available on HuggingFace to be downloaded, and the relevant links are posted below.

### Resources
---

Model on Hugging Face: https://huggingface.co/rlatt/DialoGPT-large-King-James-Bible-test-accurate
Proof of Concept Model on Hugging Face: https://huggingface.co/rlatt/DialoGPT-large-RickSanchez






