# Gmail Alias Generator

A simple and stylish web app to generate all possible Gmail dot aliases for a given username. All aliases deliver to the same Gmail inbox, making it perfect for sign-ups, email filtering, or privacy.

# **[Visit the Live App](https://cryptoace85.github.io/Gmail-Alias-Generator/)**

# Features

- **Generate Aliases**: Enter a Gmail username to create all possible dot variations (e.g., `abc` generates `abc@gmail.com`, `a.bc@gmail.com`, etc.).
- **Save as TXT**: Download all generated aliases as a `.txt` file for easy storage or sharing.
- **Copy to Clipboard**: Copy all aliases to your clipboard with one click for quick pasting.
- **Responsive Design**: Modern, clean UI with Tailwind CSS, Inter font, and a gradient background.
- **Fast & Client-Side**: Generates aliases in the browser, ensuring privacy and speed.
- **Loading Indicator**: Shows progress for long usernames (e.g., 8,192 aliases for a 14-character username).

# How It Works

Gmail ignores dots in the username part of an email address (e.g., `john.doe@gmail.com` and `johndoe@gmail.com` are the same). This app generates all possible dot combinations for a given username, allowing you to use unique aliases for different services while receiving emails in the same inbox.

For a username with `n` characters, the app generates `2^(n-1)` aliases. For example:
- `abc` (3 chars) → 4 aliases
- `viralbeatsbyai` (14 chars) → 8,192 aliases

# Usage

1. Open the app at [cryptoace85.github.io/Gmail-Alias-Generator](https://cryptoace85.github.io/Gmail-Alias-Generator/).
2. Enter your Gmail username (e.g., `viralbeatsbyai`) in the input field.
3. Click **Generate Emails** to create all dot variations.
4. View the aliases in the textarea, with a counter showing the total.
5. Use the **Save as TXT** button to download the aliases as a `.txt` file.
6. Use the **Copy all** button to copy the aliases to your clipboard for pasting elsewhere.

# Screenshots

![App Screenshot](screenshot.png)  
*Enter a username, generate aliases, and save or copy them with ease.*

# Installation (Local Testing)

1. Clone the repository:
   ```bash
   git clone https://github.com/CryptoAce85/Gmail-Alias-Generator.git
   ```
2. Navigate to the project folder:
   ```bash
   cd Gmail-Alias-Generator
   ```
3. Open `index.html` in a browser to test locally.

# Deployment

The app is deployed on GitHub Pages. To deploy your own version:

1. Push `index.html` and `README.md` (and `screenshot.png` if added) to your GitHub repository.
2. Enable GitHub Pages in Settings > Pages:
   - Set Source to `main` branch and `/root` directory.
3. Access the app at `https://yourusername.github.io/Gmail-Alias-Generator/`.

# Dependencies

- [Tailwind CSS](https://tailwindcss.com/) (CDN): Styling
- [Font Awesome](https://fontawesome.com/) (CDN): Icons
- [Inter Font](https://fonts.google.com/specimen/Inter) (Google Fonts): Typography
- [FileSaver.js](https://github.com/eligrey/FileSaver.js/) (CDN): File downloads

# Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make changes and commit (`git commit -m "Add your feature"`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a Pull Request.

Please ensure your changes align with the project’s style (Tailwind CSS, clean code) and test thoroughly.

# License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

**Note**: Previously used Gmail logo has been removed; ensure compliance with Google’s brand guidelines if reintroduced ([google.com/permissions/logo.html](https://www.google.com/permissions/logo.html)).

# Contact

<span style="font-size: 20px;">Developed by CryptoAce85</span>  
[<i class="fab fa-github"></i> GitHub Profile](https://github.com/CryptoAce85)  
Made with ❤️ | All variations deliver to your main inbox.
