# Great Movie Search Tool

## Overview
This program allows users to explore and analyze a network of movies based on shared genres, directors, and actors. Users can interact with the tool to:
1. Search for a movie to view its details.
2. Save fetched movie data to a local file.
3. Find movies related to a selected movie based on shared attributes.
4. View statistics about the movie network, such as the most common genres and countries.

The program fetches movie data using the OMDb API.
API Key: 9ba70fac
## Main Interactions
When you run the program, you will be presented with the following menu options:
1. **Search for a movie for details**: Enter the title of a movie to fetch its information.
2. **Save fetched data to a file**: Save all movie data fetched during the session to a JSON file you want.
3. **Get a recommendation list of similar movies**: Enter a movie title to discover related movies based on shared genres, directors, or actors.
4. **View the network stats for movies**: Analyze the movie network to see the most common genres and countries involved in collaborations.
or Type `exit` to quit the program.

## Python packages
To run the program, ensure you have the following Python packages installed:
- `requests`
- `networkx`
- `matplotlib`

## API Instructions
- You must have an API key for OMDb. One can get one at [OMDb API](https://www.omdbapi.com/apikey.aspx) and enter it when prompted.
- or use this as a temp key : **9ba70fac**

## Network Organization
- **Nodes**: Each node represents a movie.
- **Edges**: Edges connect movies that share common genres, directors, or actors.