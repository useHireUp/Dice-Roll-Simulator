# Dice Rolling Simulator 

Welcome to the Dice Rolling Simulator assessment!  
This project asks you to build an interactive console program that simulates rolling dice with different sides and quantities.

---

## Objective
Build a program that simulates rolling dice using Python's `random` module and prints each roll and summary statistics.

---

## Learning Goals
- Use Python's `random` module (`randint`) to generate random outputs  
- Work with loops and lists to collect multiple rolls  
- Parse and validate user input  
- Format console output clearly for users  
- (Optional) Compute basic statistics from roll history

---

## Requirements 

Your program must:

1. Prompt the user for:
   - Number of dice to roll (positive integer)  
   - Number of sides per die (common values: 4, 6, 8, 10, 12, 20, 100 — but accept any integer >= 2)

2. Use `random.randint(1, sides)` to simulate each die roll.

3. Display:
   - Individual roll results (e.g., `Rolls: 4, 2`)  
   - The total sum of the rolls (e.g., `Total: 6`)

4. Handle invalid input gracefully:
   - Non-numeric entries  
   - Zero or negative numbers  
   - Unsupported/senseless die sides (< 2)

5. (Optional bonuses)
   - Ask whether the user wants to roll again in a loop  
   - Keep a **history** of all roll sessions and display session stats (min, max, average)  
   - Add ASCII art for d6 faces or other fancy formatting


---

## ▶️ Running the Program

1. Save your file as:
```
dice.py
```
2. Run in terminal:
```bash
python dice.py
```
or
```bash
python3 dice.py
```

---

## Example Output

```
Welcome to the Dice Rolling Simulator!
Enter number of dice to roll: 3
Enter sides per die (e.g., 6): 6
Rolling 3 d6...
Rolls: 2, 6, 5
Total: 13
Do another roll? (yes/no): no
Goodbye!
```

---


## Bonus Ideas
- Save roll history and compute statistics (min, max, average)  
- Support commonly used dice notation like `2d6+3` (roll 2 six-sided dice and add 3)  
- Add ASCII art for d6 or other visual flair  
- Allow weighted dice or biased rolls (for experiments)

---

## Submission

When finished:
```bash
git add dice.py
git commit -m "Complete dice rolling simulator"
git push origin main
```

---

## Resources & References
- Real Python tutorial on building a dice roller.  
- GeeksforGeeks article on dice rolling with Python.  
- Example GitHub terminal dice roller projects.

---

> *Tip:* Use `random.randint(1, sides)` to simulate a die roll. See tutorials for ideas on ASCII art or extended features.
