---
title: 'Brainstorming '

---

# Unit 8 Group Project - Milestone 1

**Team Name:** [Mike & Isaac]  
**Course:** [Mobile Computing]  
**Demo Day:** Unit 10  

**Team Members:**
- [Michael Danquah-Tabbi]
- [Isaac Robinson]

**GitHub Repo Link:** 

- [AND101 Project 8](https://github.com/IRO05/AND101_Project8.git)


## Project Overview
**Timeline:** Units 8-10  
**Project Type:** Team-based Mobile App Development  
**Grading:** 50% of total course grade  

**Key Requirements:**
-  Uses the Internet and one or more APIs
-  Uses a RecyclerView
-  Uses consistent custom styling
-  Contains multiple user action points ()

##  Activity 1: Brainstorm Ideas
### Instructions
Brainstorm at least 3 different app ideas with your team. For each idea, document the core concept, potential APIs, and key screens.
---

## Project Requirements Checklist

- [x] Uses the Internet and one or more APIs
- [x] Uses a RecyclerView
- [x] Uses consistent custom styling
- [x] Contains multiple user action points

---

## **Idea 1: QuoteDaily - Daily Motivation & Wisdom**

### Core Concept
A simple inspiration app that delivers daily quotes with beautiful backgrounds. Users can browse quotes by category (motivation, wisdom, humor), save favorites, and share quotes with friends. Perfect for users seeking daily positivity and inspiration.

### Potential APIs
| API | Purpose | Link |
|-----|---------|------|
| Quotable | Free random quotes with author info and tags, | https://api.quotable.io |
| Unsplash API | Background images for quote cards | https://unsplash.com/developers |
| ZenQuotes API | Alternative quote source with categories | https://zenquotes.io/ |

### Key Screens

### Daily Quote Screen: 
- Full-screen quote card with background image
- User actions: Swipe for next quote, tap to save, share button


### Quote Feed Screen: 
- RecyclerView of quote cards by category
- User actions: Scroll, tap categories, filter by author, pull-to-refresh


### Favorites Screen: 
- Saved quotes collection
- User actions: View saved quotes, swipe to delete, share quotes

### Categories Screen: 
- Browse quotes by theme (motivation, success, life, humor)
- User actions: Tap category tiles in RecyclerView, search authors

### RecyclerView Usage
- Quote feed cards
- Category grid
- Favorites collection
- Author list

---

## **Idea 2: CryptoWatch - Cryptocurrency Price Tracker**
### Core Concept
A straightforward crypto tracking app that displays real-time cryptocurrency prices, market trends, and basic stats. Users can monitor Bitcoin, Ethereum, and other popular coins, view price charts, and track their favorite cryptocurrencies.

### Potential APIs

| API | Purpose | Link |
|-----|---------|------|
| CoinGecko API | Free crypto prices, market data, and coin info | https://www.coingecko.com/en/api |
| Coincap API | Real-time crypto market data | https://docs.coincap.io/|

### Key Screens

### Market Overview Screen: 
- RecyclerView of top cryptocurrencies with prices and 24h changes

- User actions: Scroll, tap coins, sort by price/volume, pull-to-refresh


Coin Detail Screen: Detailed coin info with price history and stats

- User actions: View price chart, add to watchlist, check market cap details


### Watchlist Screen: 
-User's tracked cryptocurrencies

- User actions: View tracked coins in RecyclerView, swipe to remove, reorder


### Search Screen: 
-Find specific cryptocurrencies

- User actions: Text input, tap search results
- 
### RecyclerView Usage
- Crypto price list with icons
- Market stats display
- Watchlist
- Search results
---

## **Idea 3: PetPedia - Dog & Cat Breed Explorer**

### Core Concept
An educational app for pet lovers to explore dog and cat breeds with photos, characteristics, temperaments, and care requirements. Helps potential pet owners research breeds and learn about different animals.

### Potential APIs

| API | Purpose | Link |
|-----|---------|------|
| The Dog API | Dog breed data with images and characteristics | https://thedogapi.com/|
| The Cat API | Cat breed information with photos| https://thecatapi.com/ |

### Key Screens

### Breed Gallery Screen: 
- RecyclerView of dog/cat breeds with photos
- User actions: Scroll, tap breed cards, switch between dogs/cats, search

### Breed Detail Screen: 
- Comprehensive breed information with image gallery
- User actions: Swipe through photos, view traits, save to favorites

### Favorites Screen: 
- Saved breeds for comparison
- User actions: View saved breeds, compare characteristics, swipe to delete

### Random Breed Screen: 
- Discover random breeds with fun facts
- User actions: Tap for new random breed, save favorites

### RecyclerView Usage
- Breed card grid with photos
- Image gallery (horizontal scroll)
- Favorites list
- Characteristic traits list

---

## **Idea 4: JokeBox - Comedy & Humor Hub**

### Core Concept
A light-hearted entertainment app that delivers jokes across various categories (dad jokes, puns, programming jokes, knock-knock jokes). Users can browse, rate jokes, share with friends, and save their favorites for later laughs.

### Potential APIs

| API | Purpose | Link |
|-----|---------|------|
| JokeAPI | Multi-category jokes with filtering options | https://jokeapi.dev/ |
| Official Joke API | Simple random jokes and programming jokes | https://official-joke-api.appspot.com/|
| icanhazdadjoke | Dedicated dad joke database| https://icanhazdadjoke.com/api |

### Key Screens

### Joke Feed Screen: 
- RecyclerView of jokes with setup/punchline cards
-User actions: Scroll, tap to reveal punchline, rate jokes, share


### Categories Screen: 
-Browse jokes by type (dad jokes, puns, dark humor, programming)
- User actions: Select category tiles, view filtered jokes


### Favorites Screen: 
- Collection of saved jokes
- User actions: Browse saved jokes, swipe to delete, share with friends


### Random Joke Screen: 
- Single random joke display with large text
- User actions: Tap for new joke, save to favorites, share

### RecyclerView Usage:
- Joke cards feed
- Category grid
- Favorites collection
- Joke ratings list
---

## **Idea 5: WordWise - Dictionary & Word Learning**
### Core Concept
A vocabulary building app that provides word definitions, synonyms, antonyms, and examples. Users can search words, learn word-of-the-day, save vocabulary to study lists, and play word games to improve language skills.

### Potential APIs

| API | Purpose | Link |
|-----|---------|------|
| Free Dictionary API | Word definitions, phonetics, and examples | https://dictionaryapi.dev/ |
| Datamuse API | Word associations, rhymes, and related terms | https://open-platform.theguardian.com/ |
| Random Word API |Generate random words for learning| https://random-word-api.herokuapp.com/ |

### Key Screens

### Word Search Screen: 
- Search functionality with definition results
- User actions: Text input, view definitions in RecyclerView, hear pronunciation


### Word of the Day Screen: 
- Featured word with detailed explanation
- User actions: View definition, see examples, save to study list


### Study List Screen: 
- Saved vocabulary words
- User actions: Browse saved words in RecyclerView, quiz mode, swipe to delete


### Explore Screen: 
- Browse words by category or difficulty
- User actions: Tap categories, scroll word lists, tap for definitions



### RecyclerView Usage:

- Search results with definitions
- Example sentences list
- Study vocabulary collection
- Word categories grid
- Synonyms/antonyms lists

---

## Idea 6: AstroPic - Space Image Explorer
### Core Concept
A space enthusiast app that showcases NASA's Astronomy Picture of the Day (APOD), Mars rover photos, and other stunning space imagery. Users can browse cosmic photos with scientific explanations, save favorites, and learn about the universe through beautiful visuals.

### Potential APIs

| API | Purpose | Link |
|-----|---------|------|
| NASA APOD API| Astronomy Picture of the Day with explanations | https://api.nasa.gov/ |
| NASA Mars Rover Photos API| Images from Mars rovers (Curiosity, Perseverance) | https://api.nasa.gov/ |
| NASA Image and Video Library | Searchable NASA media archive|https://images.nasa.gov/docs/images.nasa.gov_api_docs.pdf |

### Key Screens:

### Today's Cosmos Screen: 
- Large featured APOD with title and explanation
- User actions: Read description, save image, share, view full resolution

### Gallery Screen: 
- RecyclerView of space images by date or rover
- User actions: Scroll, tap images, filter by date/source, pull-to-refresh


### Image Detail Screen: 
- Full-screen image with scientific description
- User actions: Pinch to zoom, save to favorites, read explanation, share


### Favorites Screen: 
- Saved space images collection
- User actions: Browse saved images in grid RecyclerView, swipe to delete

### RecyclerView Usage
- Image gallery grid
- Mars rover photo timeline
- Favorites collection
- Search results
#### Top 3
- 1️⃣ QuoteDaily - Daily Motivation & Wisdom (Idea 1)
- 2️⃣ JokeBox - Comedy & Humor Hub 
- 3️⃣ AstroPic - Space Image Explorer

