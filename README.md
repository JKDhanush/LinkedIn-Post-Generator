# LinkedIn Post Generator

## Overview
The **LinkedIn Post Generator** is a powerful tool designed to help LinkedIn influencers create engaging and personalized posts. By leveraging the **Llama 3.2** open-source model, the **LangChain framework**, and **Streamlit**, this project simplifies content creation, allowing users to maintain their unique voice while saving time.

## Key Features
- **Topic Extraction**: Analyzes past posts from influencers to identify key topics.
- **Customizable Generation**: Users can select topics, post lengths (short, medium, long), and languages (including a mix of Hindi and English).
- **User-Friendly Interface**: Built with Streamlit for an intuitive experience.

## Technical Architecture
1. **Data Preprocessing**:
   - Collects and processes LinkedIn posts to extract relevant metadata (topics, engagement metrics).
   - Stores enriched data in JSON format for further use.

2. **Post Generation**:
   - Utilizes the Llama 3.2 model to generate new posts based on user-selected parameters.
   - Employs prompt engineering to ensure generated content aligns with the influencer's style.

