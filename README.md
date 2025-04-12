# 🌐 Wikipedia Semantic Explorer

[![Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://your-app-url.streamlit.app)
[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://python.org)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

An AI-powered Wikipedia explorer that uses BERT embeddings to find semantically related articles and visualize their connections.

![Demo Screenshot](demo.png) *(Replace with your actual screenshot)*

## 🚀 Features

- **Semantic Search**: Find related articles using BERT embeddings
- **Relevance Scoring**: See how closely related articles are (0-1 scale)
- **Interactive Visualizations**: Plotly-powered similarity graphs
- **Quick Facts**: Get key information at a glance
- **Image Previews**: See article thumbnails when available

## 🛠️ Tech Stack

- **Natural Language Processing**: BERT embeddings, cosine similarity
- **Backend**: Python, Wikipedia API, Streamlit
- **Visualization**: Plotly, Matplotlib
- **Deployment**: Streamlit Cloud (or your preferred platform)

## 🎯 How It Works
Enter any Wikipedia article title

The system:

- Fetches the article content

- Generates BERT embeddings for the article and its links

- Calculates semantic similarity scores

- Displays results with interactive visualizations
