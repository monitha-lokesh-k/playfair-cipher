# Playfair Cipher — VTU CNS Project

A browser-based Playfair Cipher implementation using only HTML, CSS and vanilla JavaScript.

## Features

- Keyword-based 5 × 5 Playfair matrix
- I/J treated as one letter
- Plaintext preprocessing and X filler
- Encryption
- Decryption
- Step-by-step rule explanation
- Interactive matrix generator
- Responsive UI
- No backend
- No external libraries
- GitHub Pages compatible

## Run locally

Open `index.html` in a browser.

## Deploy on GitHub Pages

1. Create a GitHub repository.
2. Upload `index.html`, `style.css`, and `script.js`.
3. Commit the files.
4. Go to **Settings → Pages**.
5. Under **Build and deployment**, select **Deploy from a branch**.
6. Select your main branch and `/ (root)`.
7. Save.
8. GitHub will provide your website URL.

## Example

Keyword:

`MONARCHY`

Plaintext:

`BALLOON`

The plaintext is prepared as:

`BA LX LO ON`

The website then applies the Playfair rules pair by pair.

## Important note about decryption

Because the cipher uses X as a filler, automatic removal of X after decryption is inherently ambiguous. The application therefore shows both the raw decrypted text and a best-effort "likely filler removed" version.
