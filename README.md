# Personalized-Content-Recommendation-System-With-DSA

## Overview
PersonaReel is an advanced content recommendation system developed as an academic project for the Data Structures and Algorithms (DSA) course. It leverages various data structures and algorithms to provide personalized reel and ad recommendations to users based on their interests and interactions.

## Features
- Personalized reel recommendations based on user interests and interaction history
- Targeted ad suggestions
- User interaction tracking (like, dislike, watch)
- Machine learning integration for improved predictions

## Data Structures Used
- Heaps: For efficient retrieval of reels and ads with highest relevance scores
- Graphs: Used for linking reels to users and managing interaction matrices
- Linked Lists: Doubly Linked List (DLL) for managing interaction history
- Sets: For storing and passing reels and their weights
- Dictionaries: For storing reels and their associated weights

## Algorithms
- Max Heap: For prioritizing recommendations
- Random Forest: For predicting user preferences (in machine learning improvement)

## Files
- `main.py`: Core recommendation engine and user interaction loop
- `DLL.py`: Implementation of Doubly Linked List
- `maxheap.py`: Implementation of Max Heap data structure
- `ml-improv.py`: Machine learning improvements using Random Forest

## Usage
- Follow the on-screen prompts to interact with reels and ads.
- Use commands like 'L' for like, 'D' for dislike, 'N' for next, and 'Q' to quit.

## Machine Learning Integration
The `ml-improv.py` file contains additional improvements using machine learning:
- Predicts whether a user will like a specific type of reel
- Uses Random Forest algorithm for classification
- Provides confusion matrix visualization for model evaluation

## Future Improvements
- Integration of more advanced recommendation algorithms
- Enhanced user profiling and preference learning
- Real-time data processing and recommendation updates

## Contributors
Vaibhav Shekar
Shaun Sunny
Sarath Chandra
Rohit Vishnu
Niramai Nayanar

## Acknowledgements
This project was developed as part of the Data Structures and Algorithms course.
