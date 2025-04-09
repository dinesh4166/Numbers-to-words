🔢 Number to Words Converter - Python Project

📌 Project Overview  
This interactive console-based Python project converts numeric values into their word equivalents in the Indian numbering system (thousand, lakh, crore). Whether it's an integer or a decimal number, positive or negative, this tool spells it out! 🧮✨

🚀 Features  
- 🧠 Handles numbers up to 100 crore  
- ➕ Supports both positive and negative numbers  
- 💧 Smoothly handles decimal points (e.g., 123.45 → one hundred twenty three point four five)  
- 🧪 Validates input and gracefully handles errors  
- 🔁 Continuously takes input until "quit" is entered

📚 Numbering System  
- ✅ Supports Indian format: thousand, lakh, crore  
- ✅ Modular functions for each range for clean and readable logic

🛠️ Tech Stack  
- 👨‍💻 Language: Python 3  
- 📦 Dependencies: None (pure Python)

🧩 Code Breakdown  
- `num2words(n)`: Main dispatcher for converting numbers  
- `lt_thousand()`, `lt_lakh()`, `lt_crore()` etc.: Handle different numeric ranges  
- 🧠 Smart logic to build and join parts like "thirty five lakh sixty two thousand one hundred and ten"  
- `func()`: User input loop with error handling and input sanitation

🎯 Sample Input/Output  
- Input: `4523` → Output: four thousand five hundred and twenty three  
- Input: `0.89` → Output: zero point eight nine  
- Input: `-1050000` → Output: minus ten lakh fifty thousand  

💡 How to Use  
1. Clone or download the repo  
2. Run the script using `python num_to_words.py`  
3. Enter any number or type `quit` to exit

🌈 Ideal For  
- 🔢 Practicing number logic in Python  
- 🧠 Building on for voice assistants or form validation tools  
- 👶 Beginners learning control flow and modular programming

🛡️ Error Handling  
- 🚫 Detects invalid inputs  
- 🧹 Catches common mistakes (e.g., decimal starting with `.` or `-.`)  
- 📏 Restricts range to safe limits (-100 crore to 100 crore)

📬 Contributions Welcome!  
Feel free to open issues or suggest improvements to make this tool more powerful or user-friendly! 💬

👨‍💻 Built with ❤️ by Dinesh V
