# Data Encoding - TryHackMe Writeup

## 🧠 Overview

This room introduces fundamental concepts of data encoding, focusing on how computers represent characters using standards like ASCII and Unicode.

Although the exercises were interactive and guided, the key takeaway is understanding how data is represented and interpreted at a low level.

---

## 🔑 Key Concept: What is Encoding?

Encoding is the process of converting data into a specific format for efficient storage or transmission.

* Encoding is **reversible**
* It does **not require a key**
* It is often used for **data representation**, not security

---

## 🔤 Task 2: ASCII Encoding

ASCII (American Standard Code for Information Interchange) is one of the earliest encoding standards, mapping characters to numerical values.

### Questions & Answers

* The ASCII code in decimal for `@` → **64**
* The character for decimal `35` → **#**
* ASCII code `7` corresponds to → **BEL (Bell character)**

### 🧠 Explanation

ASCII uses numbers (0–127) to represent characters:

* Letters
* Digits
* Symbols
* Control characters (like BEL)

The **BEL character (7)** is interesting—it was historically used to trigger a sound (a beep) on systems.

---

## 🌐 Task 3: Unicode Encoding

ASCII is limited, so Unicode was introduced to support a wide range of global characters, including emojis and symbols.

### Questions & Answers

* UTF-32 encoding of 😌 → **U+0001F60C**
* UTF-16 encoding of シ → **U+30B7**
* Character for UTF-32 `U+0001F60E` → **😎**
* Character for UTF-16 `U+2658` → **♘**

### 🧠 Explanation

Unicode assigns a **unique code point** to each character:

* Format: `U+XXXX`
* Supports languages, symbols, emojis, etc.

Encoding formats like:

* **UTF-8**
* **UTF-16**
* **UTF-32**

…define how these code points are stored in memory.

---

## ⚠️ Reflection on Learning Process

During this room, many answers could be obtained by directly interacting with the provided tools and websites.

At first, this felt like "cheating," but it actually highlights an important concept in cybersecurity:

> Knowing how to **use tools effectively** is just as important as understanding the theory.

The real skill is:

* Recognizing encoding formats
* Knowing which tool to use
* Understanding the output

---

## 🛠️ Tools Used

* Online encoding/decoding tools (provided in the room)
* Browser-based interactive labs

---

## 📌 Real-World Relevance

Understanding encoding is useful in:

* Malware analysis (encoded payloads)
* Web security (encoded inputs/outputs)
* CTF challenges (hidden or obfuscated data)

---

## 💡 Key Takeaways

* ASCII is limited but foundational
* Unicode enables global character representation
* Encoding ≠ encryption
* Tools are essential, but understanding patterns is key

---

## 🚀 Next Steps

To deepen understanding, I plan to:

* Practice encoding/decoding manually
* Explore how encoding appears in real attack scenarios
