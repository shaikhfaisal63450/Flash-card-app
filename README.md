# Flashy – French Vocabulary Flashcards 🇫🇷

## 📌 About the Project

Flashy is a Python-based flashcard application that helps users learn French vocabulary with English translations. It displays French words on flashcards and automatically reveals their English meanings after three seconds.

Users can mark words they already know, and the application saves the remaining vocabulary for future practice.

## ✨ Features

* Interactive flashcards with a graphical interface.
* Automatic card flipping after three seconds.
* French-to-English vocabulary learning.
* Buttons to mark words as known or unknown.
* CSV-based storage for vocabulary data.
* Personalized learning by saving words that still need practice.

## 🛠️ Technologies Used

* **Python** – Core programming logic.
* **Tkinter** – Graphical user interface.
* **Pandas** – Reading and writing CSV files.
* **Random** – Random selection of vocabulary cards.

## 📂 Project Structure

```text
Flashy/
├── data/
│   ├── french_words.csv
│   └── words_to_learn.csv
├── images/
│   ├── card_front.png
│   ├── card_back.png
│   ├── right.png
│   └── wrong.png
├── main.py
└── README.md
```

## ⚙️ Installation and Usage

1. Install Python on your computer.

2. Install Pandas:

   ```bash
   pip install pandas
   ```

3. Ensure the `data` and `images` folders contain the required files.

4. Run the application:

   ```bash
   python main.py
   ```

## 🎮 How to Play

1. View the French word displayed on the flashcard.
2. Try to recall its English meaning.
3. Wait three seconds for the English translation.
4. Click the green check button if you know the word.
5. Click the red cross button to move to another word without marking it as learned.

## 🎯 Learning Objectives

This project demonstrates Python functions, GUI development, event handling, CSV file operations, exception handling, and data manipulation using Pandas.

## 👨‍💻 Author

**Faisal**

A beginner-friendly Python project focused on vocabulary learning and practical programming skills.
