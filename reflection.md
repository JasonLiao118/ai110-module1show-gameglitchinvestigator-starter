# 💭 Reflection: Game Glitch Investigator

Answer each question in 3 to 5 sentences. Be specific and honest about what actually happened while you worked. This is about your process, not trying to sound perfect.

## 1. What was broken when you started?

- What did the game look like the first time you ran it?
- List at least two concrete bugs you noticed at the start  
  (for example: "the secret number kept changing" or "the hints were backwards").

The first thing I notice is when I open the developer debug info I already have 1 attempt used. This is odd because I did not submit any guess yet.

The second thing is that when I do enter in a number and I click submit, I see the hint that says if my number is higher or lower but it does not get pushed to the history list in the debug info. Only when I click it a second time does it get pushed.

The third thing I notice is that when I follow the higher or lower hint and I enter in another number, it does not show me whether my new number is higher or lower than the real number/

The fourth thing I notice is that only sometimes the go higher or go lower message is inaccurate. The secret was 87 but I enter 10 and it said to go lower which was not correct.

The fifth thing I found is that when I click new game, it correctly resets my score back to 0 but the history does not clear and the score does not reset either.

The sixth thing I found was when I was spamming the same number as an input. The attempts go up to 7 and when it hits 7 and my attempts remaining to go 1, it already says out of attempts.

The seventh thing I found was that when it was game over and I clicked new game, it did not start a new game and let me submit any new guesses.

The eigth error I found was that when I make the correct guess, it gives the wrong score.

The ninth error was that the difficult did not affect the range that the answer was in.

---

## 2. How did you use AI as a teammate?

- Which AI tools did you use on this project (for example: ChatGPT, Gemini, Copilot)?
- Give one example of an AI suggestion that was correct (including what the AI suggested and how you verified the result).
- Give one example of an AI suggestion that was incorrect or misleading (including what the AI suggested and how you verified the result).

---

## 3. Debugging and testing your fixes

- How did you decide whether a bug was really fixed?
- Describe at least one test you ran (manual or using pytest)  
  and what it showed you about your code.
- Did AI help you design or understand any tests? How?

---

## 4. What did you learn about Streamlit and state?

- In your own words, explain why the secret number kept changing in the original app.
- How would you explain Streamlit "reruns" and session state to a friend who has never used Streamlit?
- What change did you make that finally gave the game a stable secret number?

---

## 5. Looking ahead: your developer habits

- What is one habit or strategy from this project that you want to reuse in future labs or projects?
  - This could be a testing habit, a prompting strategy, or a way you used Git.
- What is one thing you would do differently next time you work with AI on a coding task?
- In one or two sentences, describe how this project changed the way you think about AI generated code.
