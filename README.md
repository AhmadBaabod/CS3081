# Lab3_Search_and_knowledge_algorithms

🧠 AI Lab 3 – Search Algorithms & Knowledge Base Reasoning
👤 Student Information
Name: Ahmad Baabod
ID: S22208053
📌 Overview

This lab focuses on two main Artificial Intelligence concepts:

Search Algorithms – specifically Breadth-First Search (BFS)
Knowledge Base Reasoning – using logical inference to determine conclusions
🚀 Part 1: Search Algorithms
✅ Exercise 1 – BFS Search
Goal: Find a path from Makkah to Madinah using BFS.
Results:
Steps taken: 5 steps

Path found:

Makkah → Jeddah → Madinah
Conclusion:
Yes, this is the shortest path, as BFS guarantees the shortest path in an unweighted graph.
➕ Exercise 2 – Adding a New City
Task: Extend the graph by adding a new city and find a path.
Results:

New path from Makkah to Abha:

Makkah → Taif → Abha
🧩 Part 2: Knowledge Base (KB)
🕵️ Exercise 3 – Logical Inference
Question:

Does the Knowledge Base prove that Nora is guilty?

Answer:
❌ No, because the KB does not include a rule connecting possession of the key to guilt.
Required Addition:

To prove Nora is guilty, we must add the following rule:

kb.tell(Implication(nora_key, nora_guilty))
🔍 Exercise 4 – Changing the KB
Question:

Is Lina still guilty after removing a clue?

Answer:
❌ No, Lina is no longer guilty.
Explanation:
Previously, Lina was considered guilty because:
She was seen → she had the key → she was guilty.
After removing the clue that she was seen:
We can no longer prove she has the key.
Therefore, she cannot be proven guilty.
📚 Key Concepts Learned
Breadth-First Search (BFS) guarantees shortest path in graphs.
Graph traversal can model real-world navigation problems.
Knowledge Bases rely on rules and facts.
Small changes in logical rules can significantly affect conclusions.
🛠️ Technologies Used
Python
Logic-based AI (Knowledge Base reasoning)
📎 Notes
Ensure all rules in a Knowledge Base are explicitly defined.
Missing implications can prevent correct conclusions.
Always verify search results against the graph/map.
