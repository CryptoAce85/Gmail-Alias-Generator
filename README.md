Gmail-Alias-Generator

Creates Gmail Dot Alias

Use it Here!! 👉 https://cryptoace85.github.io/Gmail-Alias-Generator/


A simple and stylish web app to generate all possible Gmail dot aliases for a given username. All aliases deliver to the same Gmail inbox, making it perfect for sign-ups, email filtering, or privacy.
Visit the Live App
Features

Generate Aliases: Enter a Gmail username to create all possible dot variations (e.g., abc generates abc@gmail.com, a.bc@gmail.com, etc.).
Save as TXT: Download all generated aliases as a .txt file for easy storage or sharing.
Copy to Clipboard: Copy all aliases to your clipboard with one click for quick pasting.
Responsive Design: Modern, clean UI with Tailwind CSS, Inter font, and a gradient background.
Fast & Client-Side: Generates aliases in the browser, ensuring privacy and speed.
Loading Indicator: Shows progress for long usernames (e.g., 8,192 aliases for a 14-character username).

How It Works
Gmail ignores dots in the username part of an email address (e.g., john.doe@gmail.com and johndoe@gmail.com are the same). This app generates all possible dot combinations for a given username, allowing you to use unique aliases for different services while receiving emails in the same inbox.
For a username with n characters, the app generates 2^(n-1) aliases. For example:

abc (3 chars) → 4 aliases
viralbeatsbyai (14 chars) → 8,192 aliases

Usage

Open the app at cryptoace85.github.io/Gmail-Alias-Generator.
Enter your Gmail username (e.g., viralbeatsbyai) in the input field.
Click Generate Emails to create all dot variations.
View the aliases in the textarea, with a counter showing the total.
Use the Save as TXT button to download the aliases as a .txt file.
Use the Copy all button to copy the aliases to your clipboard for pasting elsewhere.

Screenshots
Enter a username, generate aliases, and save or copy them with ease.
Installation (Local Testing)

Clone the repository:git clone https://github.com/CryptoAce85/Gmail-Alias-Generator.git


Navigate to the project folder:cd Gmail-Alias-Generator


Open index.html in a browser to test locally.

Optional: Host the Gmail Logo Locally

Download the Gmail logo from serif.ai/gmail-logo.
Save as gmail-logo.png in the repo’s root or assets/ folder.
Update index.html to reference the local logo:<img src="gmail-logo.png" alt="Gmail Logo" class="h-10 mr-2 object-contain">
<link rel="icon" href="gmail-logo.png" type="image/png">



Deployment
The app is deployed on GitHub Pages. To deploy your own version:

Push index.html (and gmail-logo.png if hosted locally) to your GitHub repository.
Enable GitHub Pages in Settings > Pages:
Set Source to main branch and /root directory.


Access the app at https://yourusername.github.io/Gmail-Alias-Generator/.

Dependencies

Tailwind CSS (CDN): Styling
Font Awesome (CDN): Icons
Inter Font (Google Fonts): Typography
FileSaver.js (CDN): File downloads

Contributing
Contributions are welcome! To contribute:

Fork the repository.
Create a new branch (git checkout -b feature/your-feature).
Make changes and commit (git commit -m "Add your feature").
Push to the branch (git push origin feature/your-feature).
Open a Pull Request.

Please ensure your changes align with the project’s style (Tailwind CSS, clean code) and test thoroughly.
License
This project is licensed under the MIT License. See the LICENSE file for details.
Note: The Gmail logo is used under Google’s brand guidelines (google.com/permissions/logo.html). Ensure compliance for commercial use.
Contact
Developed by CryptoAce85 GitHub ProfileMade with ❤️ | All variations deliver to your main inbox.
