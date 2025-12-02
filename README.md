🔐 Random Password Generator

A simple and beginner-friendly Random Password Generator built using HTML, CSS, and JavaScript.
It generates two secure random passwords using uppercase letters, lowercase letters, numbers, and special characters.

📌 Features

Generates two random passwords at once

Each password is 15 characters long

Includes a full set of secure characters (A-Z, a-z, 0-9, and symbols)

Clean UI with a Generate Password button

Lightweight and easy to customize

🛠️ Tech Stack

Technology	Purpose
HTML	Page structure
CSS	Styling and layout
JavaScript	Random password generation

📂 Project Structure
/project-folder
│── index.html
│── index.css
│── index.js
└── README.md

🚀 How to Use

Clone or download the project files

Open index.html in a browser

Click the Generate Password button

Two random passwords will appear on the screen

🧠 JavaScript Logic (Overview)

Uses a character array with alphabets, numbers, and symbols

Loops 15 times to build a password randomly

Inserts results into HTML using textContent / innerHTML

function genPasswords(){
    passwordEl_1.innerHTML = createPassword();
    passwordEl_2.innerHTML = createPassword();
}

🖥️ Screenshot (Optional)

Add your app screenshot here if available

✨ Future Improvements

Add copy to clipboard button

Add an option to set custom password length

Toggle for including/excluding symbols

🤝 Contributing

Feel free to fork the repository and submit pull requests to improve features.

📜 License

This project is open-source and free to use.
