# 📚 AM Legal Documentation Project — Building AI for Justice, Together ⚖️

Welcome to the **AM Legal Documentation Project**, an open-source initiative dedicated to improving lives across the United States by making legal information more accessible, structured, and usable for AI systems and human beings alike.

This project gathers and organizes publicly available legal content, sourced primarily from [American Legal Publishing](https://www.amlegal.com/), to train, fine-tune, and evaluate artificial intelligence systems—helping them understand, interpret, and communicate the law more clearly and fairly. 🤖✨

Whether you're a **developer**, **data scientist**, **researcher**, **law student**, **policy advocate**, or just someone who wants to help make legal knowledge more open and available—we welcome you! 🙌

---

## 🌎 Why This Project Matters

Legal information is everywhere, but it's often scattered, inconsistently formatted, and hard to understand. This creates barriers for people trying to:

- Understand their rights 🧑‍⚖️
- Navigate city or state regulations 🏛
- Advocate for themselves or their communities 🗣
- Access affordable legal services 📄

By organizing this data and making it machine-readable, we make it easier to train powerful, responsible AI models that **support people—not replace them.**
We believe that when technology understands the law, **everyone benefits.**

---

## 🤖 How This Powers AI for Good

Our documentation can be used to:

- 🧠 Train legal AI assistants to understand local codes and ordinances
- 🛠 Build tools that improve access to justice for underserved communities
- 📊 Analyze legal trends across jurisdictions to inform better policymaking
- 📚 Teach large language models (LLMs) how to interpret legal documents more reliably
- 🔍 Create transparency in civic systems using open data

This is more than just a dataset—this is a movement to **democratize legal knowledge** in the age of AI.

---

## 💡 How to Use This Repo

- Browse and explore legal documents in structured formats (HTML, JSON, etc.)
- Use it for AI/ML training and fine-tuning tasks
- Build applications, dashboards, or search engines for public legal information
- Help parse, clean, and expand the dataset for more cities and states
- Leverage it in academic or research projects on law, language, or public policy

---

## ⚙️ Data Structure and Region Processing

### 🧭 How `REGION_START_PERCENT` Works

If your script processes a list of **42 regions (U.S. states)**, each one equals about **2.38%** of the total list.
That means every **2.4% jump** in your percentage moves you roughly one state forward.

You can use this table to decide **where to start** your script.
_(Example: `REGION_START_PERCENT = 60` starts at New York.)_

---

### 📊 Full Reference Table

| % to Start | State (Index)        | Description                        |
| ---------- | -------------------- | ---------------------------------- |
| **0%**     | Alaska (0)           | Start from the very beginning      |
| **2%**     | Arizona (1)          | 1 step in                          |
| **5%**     | Arkansas (2)         | Early in the list                  |
| **7%**     | California (3)       | Getting started strong             |
| **10%**    | Colorado (4)         | Just a few states in               |
| **12%**    | Connecticut (5)      | Small but mighty                   |
| **14%**    | Florida (6)          | Sunny checkpoint                   |
| **17%**    | Hawaii (7)           | Island vibes 🌺                    |
| **19%**    | Idaho (8)            | Potato country 🥔                  |
| **21%**    | Illinois (9)         | Around one-fifth through           |
| **24%**    | Indiana (10)         | Quarter of the way                 |
| **26%**    | Iowa (11)            | Cornfields incoming 🌽             |
| **29%**    | Kansas (12)          | Heartland checkpoint               |
| **31%**    | Kentucky (13)        | One-third through                  |
| **33%**    | Maryland (14)        | East Coast line-up begins          |
| **36%**    | Massachusetts (15)   | Northeast hub                      |
| **38%**    | Michigan (16)        | Great Lakes ahead                  |
| **40%**    | Minnesota (17)       | Near halfway mark                  |
| **43%**    | Missouri (18)        | Midwest solid ground               |
| **45%**    | Montana (19)         | Big Sky Country 🌄                 |
| **48%**    | Nebraska (20)        | Halfway through the list           |
| **50%**    | Nevada (21)          | Western line-up                    |
| **52%**    | New Hampshire (22)   | Small but scenic                   |
| **55%**    | New Jersey (23)      | Garden State 🌿                    |
| **57%**    | New Mexico (24)      | Desert magic 🌵                    |
| **60%**    | New York (25)        | Empire State – great test point 🗽 |
| **62%**    | North Carolina (26)  | Heading southbound                 |
| **64%**    | Ohio (27)            | Buckeye base                       |
| **67%**    | Oklahoma (28)        | Mid-country zone                   |
| **69%**    | Oregon (29)          | Pacific Northwest begins           |
| **71%**    | Pennsylvania (30)    | Industrial backbone ⚙️             |
| **74%**    | Rhode Island (31)    | Smallest but mighty                |
| **76%**    | South Carolina (32)  | Near the end stretch               |
| **79%**    | South Dakota (33)    | Great Plains checkpoint            |
| **81%**    | Tennessee (34)       | Music hub 🎶                       |
| **83%**    | Texas (35)           | Big section 🤠                     |
| **86%**    | Utah (36)            | Mountain views 🏔️                  |
| **88%**    | Virginia (37)        | Almost the final group             |
| **90%**    | Washington (38)      | Near completion ☔                 |
| **93%**    | West Virginia (39)   | Wrapping up soon                   |
| **95%**    | Wisconsin (40)       | Last few states                    |
| **98%**    | Wyoming (41)         | End of the list 🎯                 |
| **100%**   | wraps back to Alaska | Full loop — starts over again 🔁   |

---

### ⚙️ Example in Code

```js
const REGION_START_PERCENT = 60; // Start from New York
```

This tells the script to **skip the first 60%** of the list,
start from **New York**, and **wrap back around** to Alaska after finishing.

---

### 💡 TL;DR

> Each **2.4% ≈ 1 state**
> Multiply the **state’s index (0–41)** × **2.4** to get your `REGION_START_PERCENT`.
> Example: Index 25 → `25 × 2.4 = 60%` → Start at **New York** 🗽

---

## 🤝 We Want You to Join Us!

This is a community-driven effort—and you’re invited! 🎉

Here’s how you can get involved:

- ⭐ Star the repo to show support
- 🍴 Fork the repo and contribute improvements
- 🐛 Open issues for bugs or suggestions
- 📢 Share the project with others in civic tech, AI, and legal aid spaces
- 🧾 Help structure and clean legal data for new jurisdictions
- 🧠 Offer ideas to make this more useful for people and machines

---

## 🪪 Licensing & Usage

Released under the [MIT License](LICENSE).

✅ You are **free to use, modify, and share** this data and code for **personal, academic, commercial, or nonprofit** use—just include attribution and stay aligned with the mission.

> This data belongs to the people. Let’s make it useful for everyone.

---

## 🙏 Acknowledgments

Special thanks to:

- The open data community
- Civic technologists and public interest lawyers
- AI researchers who believe in justice and accessibility
- Everyone who contributes, shares, or supports this project

Together, we can build **AI that understands and respects the laws that shape our lives.**

---

With gratitude and hope,
**The Strong Foundation Team** 💙
