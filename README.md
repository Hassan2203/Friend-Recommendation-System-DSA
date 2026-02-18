📌 Project Overview

This project simulates a basic social networking platform using core Data Structures and Algorithms (DSA) concepts.

The system allows users to:

Register and Login

Send and Accept Friend Requests

Receive Friend Recommendations

Search Users

Send Messages

Manage Profiles

The purpose of this project is to demonstrate how theoretical DSA concepts can be applied to solve real-world inspired problems.

🧠 Core Data Structures Used
🔹 Graph (Adjacency List)

Each user is represented as a node.
Friendships are represented as edges.

Time Complexity:

Traversal: O(V + E)

🔹 Hash Tables (Dictionary)

Users are stored using username as key.

Lookup Time: O(1)

🔹 Sets

Used for friend lists to:

Avoid duplicates

Enable fast membership checking

Time Complexity:

Membership check: O(1)

🔹 Queues & Lists

Friend requests follow queue behavior

Messages stored in list to maintain order

🔹 Sorting Algorithm

Friend suggestions use sorting (TimSort in Python).

Time Complexity:

O(n log n)

⚙️ Features
✅ User Management

Secure Registration

Hashed Password Storage

Login Authentication

✅ Friend Request System

Send Request

Accept Request

Prevent duplicate requests

Graph edge update on acceptance

✅ Friend Recommendation System

Suggests users based on mutual friends

Uses graph traversal logic

Ranked suggestions

✅ Search System

Substring-based username search

Linear scanning

✅ Messaging System

Send messages to friends

Track unread messages

Store messages persistently

✅ Data Persistence

Data stored in JSON file

Serialization & Deserialization used

🏗 System Architecture

User stored in hash table

Friendships stored in graph

Requests stored in queue-like structure

Messages stored in list

Data saved in JSON

📊 Time Complexity Summary
Operation	Complexity
User Lookup	O(1)
Friend Check	O(1)
Search	O(n)
Friend Suggestion	O(V + E)
Message Retrieval	O(m)
▶️ How to Run
Step 1: Clone Repository
git clone https://github.com/Hassan2203/DSA-Social-Network-Simulator.git

Step 2: Install Dependencies
pip install -r requirements.txt

Step 3: Run Project
python main.py

📂 Repository Structure
Folder	Purpose
main.py	Core program
Data	Stores JSON data
Screenshots	UI examples
Report	Full academic report
🔒 Security Implementation

Password hashing

Input validation

Session management

Sanitization of profile uploads

📈 Results

The system successfully:

Handles multiple users

Maintains graph-based friendships

Generates accurate friend recommendations

Preserves data between sessions

Maintains optimal performance using efficient data structures

🚀 Future Improvements

GUI version (Tkinter / Web)

Database integration (MySQL)

Advanced recommendation algorithm

Mutual interest scoring

AI-based ranking system

Deployment as web application

📚 Academic Purpose

This project demonstrates practical implementation of:

Graph Theory

Hash Tables

Sets

Queues

Sorting Algorithms

Algorithm Design

Time Complexity Analysis
