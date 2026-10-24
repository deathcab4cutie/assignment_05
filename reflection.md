# Reflection

## Instructions

Reflections are a metcognitive activity where you are encouraged to think about your own thinking. It helps you build a strong understanding of your own learning. A good learner not only "knows what they know", but they "know what they don't know", too. Learning to reflect takes practice, but if your goal is to become a self-directed learner where you can teach yourself things, reflection is imperative.

- Now that you've completed the assignment, think about what you did and share your thoughts. What did you learn? What confuses you? Where did you struggle? Where might you need more practice?
- A good reflection is: **specific as possible**,  **uses the terminology of the problem domain** (what was learned in class / through readings), and **is actionable** (you can pursue next steps, or be aided in the pursuit). That last part is what will make you a self-directed learner.
- Flex your recall muscles. You might have to review class notes / assigned readings to write your reflection and get the terminology correct.
- Your reflection is for **you**. Yes I make you write them and I read them, but you are merely practicing to become a better self-directed learner. If you read your reflection 1 week later, does what you wrote advance your learning?

Examples:

- **Poor Reflection:**  "I don't understand loops."   
**Better Reflection:** "I don't undersand how the while loop exits."   
**Best Reflection:** "I struggle writing the proper exit conditions on a while loop." It's actionable: You can practice this, google it, ask Chat GPT to explain it, etc. 
-  **Poor Reflection** "I learned loops."   
**Better Reflection** "I learned how to write while loops and their difference from for loops."   
**Best Reflection** "I learned when to use while vs for loops. While loops are for sentiel-controlled values (waiting for a condition to occur), vs for loops are for iterating over collections of fixed values."

`--- Write your reflection in the file code/reflection.txt ---`

The most confusing part of this assignment was putting together the logic for the Streamlit app. I was confused about how to filter the data by category, and going through this assignment taught me how exactly to sort these logs by date.

I understand .str methods, melt, and pivot tables a lot better now. I started out understanding melt and pivot conceptually, but using melt inside the missed_weeks function helped clarify a lot of the logic to me; the purpose of melt within this program was to turn each of the cells into a row that could be filtered. I was really stuck on that function for a while, since the tests were running because it was checking for order but not checking my code to see if I actually sorted it. I also got a lot more practice with writing functions.

In the future, I want to get more practice with melt on different datasets. In this assignment I tried to run each test and ruff check individually after all my code, which was really useful for debugging.
