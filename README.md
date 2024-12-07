**📚 Books Analyzer 🐉**

Unleashing the power of big data to decode book reviews like a total wizard!

**💭 What’s the Big Idea?**

This project is all about diving into huge datasets of book reviews and pulling out the juiciest insights. Whether it’s the top authors, the best Harry Potter books, or which titles have the most editions, this analyzer has got you covered like a true bookworm ninja.

With Apache Spark and MongoDB, we’re making data processing faster than a caffeinated cheetah. 🏃‍♂️💨

**🔥 Why It’s Fire**

- 🚀 Analyze Top 10 Authors who are absolutely crushing it.
- 🧙‍♂️ Count and list Harry Potter books (because magic matters).
- 📚 Spot the books with most editions (collector vibes 🤑).
- ⭐ Highlight 5-star rated books (the crème de la crème).
- 😬 Find 1-star flops (tea time ☕).
- 🅰️ Filter books with titles starting with A (alphabet flex ✨).
- ✍️ Locate books with the biggest reviews (wordy kings 👑).
- ❌ Identify books with no ratings (sad book club 😢).
- 📊 Compute average ratings (data nerd alert 📈).
- 🏆 Highlight books with the longest titles (wordsmith legends 🏅).
- 🛠️ How to Get Started (DIY Mode)

1️⃣ Clone the repo: git clone https://github.com/Sreenivas-Reddy-S/BookReviews.git
- cd BooksAnalyzer

2️⃣ Dependencies That Matter :
- Install the necessary libraries to flex your Spark skills:
- sbt clean compile

3️⃣ Run the Spark Magic: Local dataset? MongoDB integration? We've got scripts for both vibes:
- sbt run
- Analyze reviews from a CSV dataset. Quick and dirty. 😎

MongoDB Analyzer:

- spark-submit --class BooksAnalyzerMongo target/scala-2.12/books-analyzer_2.12-0.1.jar
- Dig into your MongoDB stash like a boss.

**📂 Project Breakdown**

- CSV Reviews: Works with raw .csv files to slice, dice, and analyze book reviews.
- MongoDB Integration: Hook up your data directly from MongoDB collections and unleash Spark for some heavy lifting.

🔍 Some Real Outputs 

1️⃣ Top 10 Authors:

- JK Rowling 🧙‍♀️
- George RR Martin 🐉
- Brandon Sanderson 🌌

2️⃣ Harry Potter Stats:

Total books: 42 🪄

3️⃣ Books with 5-star ratings:

- “The Alchemist” 💫
- “Atomic Habits” 🧠

4️⃣ Books with 1-star ratings:

- Not naming names, but 👀 yikes.
- 5️⃣ Longest Titles:

"A Really Long Title That Just Keeps Going and Going..."

**⚠️ Warnings and Fun Facts**

☢️ Set your MongoDB URI right, or Spark will give you the side-eye.
⚡ Local mode only for now – but hey, you can scale this to your cluster too!
🤓 Pro Tip: Use .persist() if your dataset is the size of a small country.

Made with 💻 + ☕ + 📚 by a fellow book-loving data nerd.

Cheers.

