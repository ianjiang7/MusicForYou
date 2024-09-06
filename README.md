# Music For You

This Google Colab file uses two APIs to recommend users artists. If these artists have upcoming concerts or events, Music For You will provide the user Ticketmaster information for the concert.

## Features
- Finds artists similar to the inputted artist using the Taste Dive API
- Finds upcoming concerts of the similar artists on Ticketmaster using the Ticketmaster API
- Displays 5 similar artists and up to one concert for each artist

## Prerequisites
To use Music For You, you must set up API keys for both Taste Dive API and Ticketmaster API.
- For Taste Dive, create an account on their website and visit https://tastedive.com/account/api_access.
- For Ticketmaster, visit https://developer.ticketmaster.com/products-and-docs/apis/getting-started/ and follow instructions for registering for the Discovery API.
Once obtained, add these keys to the SECRETS tab in Google Colab

## Usage
1. Run the cells.
2. When prompted, enter an artist you like.
3. The notebook will display 5 similar artist and up to 1 concert for each artist
