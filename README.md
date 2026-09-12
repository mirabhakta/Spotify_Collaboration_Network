# 🎵 Charting Connections: Spotify Artist Collaboration Network

An interactive Streamlit dashboard exploring how Spotify artists are connected through featured collaborations using network analysis and graph-based metrics.

🌐 **Live Demo:** https://spotify-collaboration-network.streamlit.app/

## Overview

Artist collaborations can help musicians reach new audiences, bridge genres, and increase visibility. This project analyzes the structure of Spotify artist collaborations to understand which artists occupy influential positions within the network and how collaboration patterns form across genres.

Rather than looking only at popularity or follower count, we use graph-based measures to examine artists' structural roles within the collaboration network.

## My Contributions

This project was developed as a team project with **Michelle Villagomez** and **Caden Maki**.

I primarily contributed to:

- Constructing and visualizing the artist collaboration network
- Performing graph-based and network analysis
- Calculating and interpreting centrality, clustering, and path-based metrics
- Identifying influential hubs and bridge artists
- Analyzing genre-based communities and collaboration patterns
- Evaluating small-world properties within the network
- Interpreting results and translating findings into dashboard visualizations

Michelle Villagomez and I were primarily responsible for the network construction, graph analysis, and interpretation of results. Caden Maki primarily contributed to the project's final conclusions.

## Research Questions

### RQ1 — Influence and Centrality
Which artists serve as the most central hubs or bridges in the Spotify collaboration network, and does an artist's centrality relate to Spotify popularity or follower count?

### RQ2 — Genre Communities
Do meaningful genre-based communities emerge from artist collaboration patterns, and do artists collaborate mostly within or across genre boundaries?

### RQ3 — Small-World Structure
Does the Spotify artist collaboration network display small-world properties, including high clustering and short path lengths that may help collaborations or music trends spread?

## Dataset

The project uses two primary datasets:

- `nodes.csv` — artist-level information including Spotify ID, artist name, followers, popularity, genres, and chart hits
- `edges.csv` — collaboration relationships between artists represented by Spotify artist IDs

## Network Model

- **Nodes:** Spotify artists
- **Edges:** Featured collaborations between artists
- **Network type:** Undirected and unweighted
- **Scope:** Static collaboration snapshot from 2013–2022

## Analysis

The project examines the collaboration network using several graph and network-analysis concepts, including:

- Degree centrality
- Betweenness centrality
- Network hubs and bridge artists
- Community structure
- Genre-based collaboration patterns
- Clustering
- Average path length
- Small-world properties

These metrics help distinguish artists who are simply popular from artists who occupy structurally important positions within the collaboration network.

## Dashboard Features

The Streamlit dashboard includes:

- Project and dataset overview
- Network summary statistics
- Interactive network visualizations
- Artist centrality analysis
- Popularity and follower comparisons
- Genre and community analysis
- Small-world network analysis
- Discussion of findings, limitations, and ethical considerations

## Tech Stack

**Python · Streamlit · Pandas · Network Analysis · Graph Theory · Data Visualization**

## Run Locally

Clone the repository:

```bash
git clone https://github.com/mirabhakta/Spotify_Collaboration_Network.git
cd Spotify_Collaboration_Network
````

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Run the Streamlit dashboard:

```bash
streamlit run dashboard.py
```

## Live Demo

Explore the deployed dashboard here:

https://spotify-collaboration-network.streamlit.app/
