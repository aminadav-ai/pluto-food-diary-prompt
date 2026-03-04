# Pluto Food Diary Prompt

![Version](https://img.shields.io/badge/version-v5.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)

AI prompt for structured food journaling, calorie estimation, and eating pattern analysis.

Keywords: chatgpt prompt, ai prompt, food diary, calorie tracking, nutrition journal, prompt engineering

Pluto is a conversational prompt designed for keeping a food diary inside a chat with an AI assistant.  
It allows the user to log food with timestamps, estimate calories and macros, observe hunger and satiety, and analyze eating patterns across multiple day.

If you find this project useful, please consider giving it a ⭐ on GitHub.

---

## Use Case

This prompt is designed for people who want to observe their eating behavior through conversational logging instead of traditional calorie tracking apps.

---

## Features

- Conversational food diary
- Automatic calorie and macro estimation
- Daily food summary
- Total food weight tracking
- Export of diary entries
- Eating pattern analysis
- Product analysis
- Body weight tracking
- Daily reflections about eating behavior

---

## Example

User input:

```
8:33 salad 70 g and olive oil
9:53 full
10:25 salad 500 g and cream 50 g
```

Assistant response:

Food analysis

| Food | K | P | F | C |
|-----|---|---|---|---|
| salad 500 g | 100 | 5 | 1 | 20 |
| cream 38% 50 g | 170 | 1 | 19 | 2 |
| **TOTAL** | **270** | **6** | **20** | **22** |

Current day

| Food | K | P | F | C |
|-----|---|---|---|---|
| 8:33 salad 70 g and olive oil | 36 | 1 | 2 | 3 |
| 10:25 salad 500 g and cream 50 g | 270 | 6 | 20 | 22 |
| **TOTAL** | **306** | **7** | **22** | **25** |

⚖ Total food weight for the day: 623 g

---

## How to use

1. Copy the prompt from `pluto-food-diary-prompt-v5.md`.

2. Start a new conversation with ChatGPT or another LLM assistant.

3. Paste the prompt into the chat.

4. Begin logging food entries using the time format:

```
08:30 eggs 2
13:10 tuna 200 g
19:45 salad 300 g and olive oil
```

The assistant will estimate calories and macros, maintain a daily table, and track food intake over time.

---

## Commands

### Day management

`new day`  
Closes the current day and starts the next calendar day.

`date YYYY-MM-DD`  
Sets the date manually.

---

### Food diary

`list`  
Shows the table of the current day and total food weight.

`today summary`  
Shows only totals: K, P, F, C and total food weight.

---

### Export

`export current day`  
Exports the current day.

`export YYYY-MM-DD`  
Exports a specific day.

`export all days`  
Exports the entire diary.

---

### Pattern analysis

`patterns`  
Shows observed eating patterns.

`patterns N days`  
Analyzes patterns for the last N days.

---

### Product analysis

`product X`

Example:

`product beef`

Shows:

- when the product was eaten
- average macros
- how often hunger appeared after it
- time until the next meal

---

### Body weight

`weight 97.2`

or

`weight: 97.2`

Records body weight for the current day.

`weight?`

Shows the last recorded weight and the date it was entered.

---

## Prompt Preview

This prompt turns an AI assistant into a structured food diary system.

The assistant can:

- estimate calories and macros
- track daily food intake
- calculate total food weight
- export diary entries
- analyze eating patterns

---

## Prompt

The full prompt is available in this repository:

`pluto-food-diary-prompt-v5.md`

You can copy the prompt and use it with ChatGPT or other LLM assistants.

---

## Example Conversation

![Example](.jpg)

## License

MIT License
