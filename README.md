# 🎮 Game Glitch Investigator: The Impossible Guesser

## 🚨 The Situation

You asked an AI to build a simple "Number Guessing Game" using Streamlit.
It wrote the code, ran away, and now the game is unplayable. 

- You can't win.
- The hints lie to you.
- The secret number seems to have commitment issues.

## 🛠️ Setup

1. Install dependencies: `pip install -r requirements.txt`
2. Run the broken app: `python -m streamlit run app.py`

## 🕵️‍♂️ Your Mission

1. **Play the game.** Open the "Developer Debug Info" tab in the app to see the secret number. Try to win.
2. **Find the State Bug.** Why does the secret number change every time you click "Submit"? Ask ChatGPT: *"How do I keep a variable from resetting in Streamlit when I click a button?"*
3. **Fix the Logic.** The hints ("Higher/Lower") are wrong. Fix them.
4. **Refactor & Test.** - Move the logic into `logic_utils.py`.
   - Run `pytest` in your terminal.
   - Keep fixing until all tests pass!

## 📝 Document Your Experience

- [ ] Describe the game's purpose.
   To guess number for different levels we have option to use hint-  if we got number in given attempts we will get some score or it will deduct otherwise.
- [ ] Detail which bugs you found.
   Initially it was giving hints in opposite way, I cannot able to start new game and I was not able to enter the guess instead I have to use mouse to enter my guess.
- [ ] Explain what fixes you applied.
   For the above problems, I made changes in logic_utils and apps python code with use of AI Copilot.

## 📸 Demo

- [ <img width="1431" height="846" alt="Screenshot 2026-03-10 at 7 38 07 PM" src="https://github.com/user-attachments/assets/92ccb8d5-947e-4850-acff-6f9ef945d0f9" />
] [Insert a screenshot of your fixed, winning game here]
  <img width="1423" height="764" alt="Screenshot 2026-03-10 at 7 56 35 PM" src="https://github.com/user-attachments/assets/f6243b35-5eec-4cba-b545-82dc39ca5e1e" />
    

## 🚀 Stretch Features

- [ ] [If you choose to complete Challenge 4, insert a screenshot of your Enhanced Game UI here]
