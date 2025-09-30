# Cyber Security Internship Task 6: Create a Strong Password and Evaluate Its Strength

## Introduction
This repository documents my completion of Task 6 from the Elevate Labs Cyber Security Internship program. The objective was to understand what makes a password strong by creating multiple passwords with varying complexity, testing them on a strength checker, noting scores/feedback, identifying best practices, researching common attacks, and summarizing how complexity affects security.

Key learnings: Password strength depends on length, character variety (uppercase, lowercase, numbers, symbols), and avoiding patterns. Strong passwords resist attacks like brute force by increasing guesswork time exponentially. I tested on passwordmeter.com, varying from simple (name+number) to complex (with symbols).

## Tools Used
- **Password Strength Checker**: passwordmeter.com (free online tool).
- **Operating System**: Windows 11.
- No additional paid tools or installations required.

## Steps Followed
I followed the task's Hints/Mini Guide step-by-step:

1. **Create Multiple Passwords with Varying Complexity**: Designed 3 passwords:
   - Weak: "stephen12" (name + numbers, no uppercase/symbols).
   - Good: "stephen2025" (name + longer numbers, no uppercase/symbols).
   - Very Strong: "stephen@2025#" (name + numbers + symbols).

2. **Use Uppercase, Lowercase, Numbers, Symbols, and Length Variations**: Varied lengths (9-13 chars), added symbols/numbers, but kept lowercase dominant for progression.

3. **Test Each Password on Password Strength Checker**: Input into passwordmeter.com.
   - Screenshot: stephen12-screenshot.png (35%, Weak).
   - Screenshot: stephen2025-screenshot.png (55%, Good).
   - Screenshot: stephen@2025#-screenshot.png (100%, Very Strong).

4. **Note Scores and Feedback from the Tool**:
   - "stephen12": 35% Weak. Additions: +36 (chars), +4 (lowercase), +8 (numbers). No bonuses for uppercase/symbols. Feedback: Lacks variety.
   - "stephen2025": 55% Good. Additions: +44 (chars), +8 (lowercase), +16 (numbers). Better length, but still no symbols/uppercase.
   - "stephen@2025#": 100% Very Strong. Additions: +56 (chars), +14 (lowercase), +16 (numbers), +18 (symbols), +12 (middle nums/symbols), +8 (requirements). Full variety met.

5. **Identify Best Practices for Creating Strong Passwords**: Use 12+ chars, mix types, avoid common words/patterns, use passphrases, change regularly.

6. **Write Down Tips Learned from the Evaluation**: Add symbols early for big bonuses (+6 per), meet requirements for +2 each, length gives +4 per char but deductions for repeats.

7. **Research Common Password Attacks**:
   - Brute Force: Tries all combinations; longer/more complex passwords take longer (e.g., 8-char alphanumeric: years vs. simple: seconds).
   - Dictionary: Uses word lists; avoids by not using real words/names.

8. **Summarize How Password Complexity Affects Security**: Complexity increases entropy (possible combinations), making attacks infeasible. E.g., "stephen12" (low entropy) crackable quickly; "stephen@2025#" (high) resists due to variety/length.

## Password Strength Results
- **Password 1: "stephen12"**
  - Score: 35% (Weak)
  - Complexity: Lacks uppercase/symbols; only lowercase + numbers.
  - Screenshot: stephen12-screenshot.png

- **Password 2: "stephen2025"**
  - Score: 55% (Good)
  - Complexity: Better length/numbers, but no symbols/uppercase.
  - Screenshot: stephen2025-screenshot.png

- **Password 3: "stephen@2025#"**
  - Score: 100% (Very Strong)
  - Complexity: Full mix—length 13, lowercase, numbers, symbols.
  - Screenshot: stephen@2025#-screenshot.png


## Conclusion
This task highlighted password best practices: Prioritize length/diversity to counter attacks. My tests showed simple additions (symbols) boost scores dramatically. For real use, combine with MFA/managers.

For questions or feedback, contact me at [stephenbrave@gmail.com]. Task description: task 6.pdf.
