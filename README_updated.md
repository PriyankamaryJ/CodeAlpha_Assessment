# 🐍 CodeAlpha Python Programming Internship

This repository brings together my work for the **CodeAlpha Python Programming Internship**. It contains three console-based Python projects, one for each task:

| Task | Project | File |
|------|---------|------|
| Task 1 | [🎮 Hangman Game](#-task-1--hangman-game) | `hangman.py` |
| Task 2 | [📈 Stock Portfolio Tracker](#-task-2--stock-portfolio-tracker) | `stock_portfolio_tracker.py` |
| Task 3 | [🤖 Simple Chatbot](#-task-3--simple-chatbot) | `chatbot.py` |

---

## 🎮 Task 1 — Hangman Game

A simple text-based Hangman game built in Python.

### 📌 Features

- 5 predefined words, chosen randomly each round
- Maximum of 6 incorrect guesses allowed
- Console-based input/output with a visual hangman stage tracker
- Option to replay after each game

### 🧠 Concepts Used

`random`, `while` loops, `if-else`, strings, lists

### ▶️ How to Run

```bash
python hangman.py
```

### 📸 Demo

[Watch the demo](https://lnkd.in/p/gpyxevqE)

---

## 📈 Task 2 — Stock Portfolio Tracker

A simple Python command-line application that lets users track their stock investments and calculate the total value of their portfolio.

### 🚀 Features

- Uses a dictionary of stock symbols with predefined prices
- Lets the user enter a stock symbol and the number of shares they own
- Calculates the investment value for each stock
- Displays a portfolio summary with the total investment value
- Saves the results as TXT and CSV files with a timestamp

### 💹 Available Stocks

| Symbol | Price (USD) |
|--------|-------------|
| AAPL   | $180 |
| TSLA   | $250 |
| GOOGL  | $140 |
| AMZN   | $145 |
| MSFT   | $415 |
| META   | $480 |
| NFLX   | $650 |

### 🛠️ Technologies and Concepts Used

- Python 3
- Dictionaries
- User input handling
- Calculations
- File handling (TXT)
- CSV processing (`csv` module)
- Date and time functionality (`datetime` module)

### ▶️ How to Run

1. Make sure Python 3 is installed on your system.
2. Clone this repository:

   ```bash
   git clone https://github.com/PriyankamaryJ/CodeAlpha_Stock-Portfolio-Tracker.git
   ```

3. Go to the project folder:

   ```bash
   cd CodeAlpha_Stock-Portfolio-Tracker
   ```

4. Run the program:

   ```bash
   python stock_portfolio_tracker.py
   ```

### 📖 How It Works

1. The program displays the available stocks and their prices.
2. Enter a stock symbol, then the quantity of shares you own.
3. Repeat for as many stocks as you like.
4. Type `done` as the stock symbol to finish.
5. The program shows your portfolio summary and total investment value.
6. Choose `y` when asked to save the results to a file.

### 🧪 Sample Run

```
Stock symbol: AAPL
Quantity of AAPL: 40
Added 40 share(s) of AAPL.

Stock symbol: META
Quantity of META: 80
Added 80 share(s) of META.

Stock symbol: NFLX
Quantity of NFLX: 100
Added 100 share(s) of NFLX.

Stock symbol: done

--- Portfolio Summary ---
AAPL: 40 shares x $180 = $7200
META: 80 shares x $480 = $38400
NFLX: 100 shares x $650 = $65000
-----------------------------
Total Investment: $110600

Save results to file? (y/n): y
```

### 💾 Output Files

When you choose to save, two files are created with a timestamp in the name:

- `portfolio_summary_YYYY-MM-DD_HH-MM-SS.txt`
- `portfolio_summary_YYYY-MM-DD_HH-MM-SS.csv`

### 🎥 Demo

[Watch the demo video](https://lnkd.in/p/gskSaijr)

---

## 🤖 Task 3 — Simple Chatbot

A simple rule-based chatbot built with Python that runs in the command line and responds to basic user messages.

### 🚀 Features

- Shows a welcome banner when the program starts
- Responds to basic messages such as greetings, questions about the bot, and thank-you messages
- Uses simple conditional logic to match the user's input with the right response
- Keeps the conversation going in a loop until the user ends it
- Ends the conversation when the user types `bye`, `exit`, or `quit`

### 💬 Sample Conversation

```
=== Simple Chatbot ===
Type 'bye', 'exit', or 'quit' to end the conversation.

You: hi
Bot: Hi!
You: what is your name
Bot: I'm a simple chatbot built with Python!
You: what can you do
Bot: I can chat about basic things! Try saying hello, asking how I am, or saying bye.
You: thank you
Bot: No problem!
You: bye
Bot: Goodbye!
```

### 🛠️ Technologies and Concepts Used

- Python 3
- User input handling
- Loops
- Conditional statements (`if` / `elif` / `else`)
- String processing

### ▶️ How to Run

1. Make sure Python 3 is installed on your system.
2. Clone this repository:

   ```bash
   git clone https://github.com/PriyankamaryJ/CodeAlpha_Chatbot.git
   ```

3. Go to the project folder:

   ```bash
   cd CodeAlpha_Chatbot
   ```

4. Run the chatbot:

   ```bash
   python chatbot.py
   ```

5. Start chatting. Type `bye`, `exit`, or `quit` to end the conversation.

### 📖 How It Works

1. The program prints a welcome banner and instructions.
2. It waits for the user to type a message.
3. The message is checked against known keywords and phrases.
4. The bot prints the matching response.
5. This repeats in a loop until the user types `bye`, `exit`, or `quit`.

### 🎥 Demo

[Watch the demo video](https://lnkd.in/p/gyszjjaj)

---

## 📁 Project Structure

```
CodeAlpha_Python_Internship/
│
├── hangman.py                  # Task 1 – Hangman Game
├── stock_portfolio_tracker.py  # Task 2 – Stock Portfolio Tracker
├── chatbot.py                  # Task 3 – Simple Chatbot
└── README.md
```

---

## 👩‍💻 Author

**Priyanka Mary J**
B.Tech Artificial Intelligence and Data Science
CodeAlpha Python Programming Intern

## 🙏 Acknowledgement

Thanks to CodeAlpha for the internship opportunity and for the hands-on learning experience.
