# 🧠 OCR-to-JSON Parser

A modern, browser-based web app that extracts text from images using OCR and returns structured JSON output.

🔗 **Live Demo**: [https://oc-rmridul.vercel.app](https://oc-rmridul.vercel.app)

---

## 📌 Features

- ✅ Upload images (JPG, PNG, etc.)
- ✅ Extract text using Tesseract.js (client-side OCR)
- ✅ Get JSON output with:
  - Extracted text
  - Confidence score
  - Word count
- ✅ Clean and responsive UI (built with Tailwind CSS)
- ✅ Entirely browser-based — no server or API calls

---

## 🖼️ Example Output

```json
{
  "text": "Hello, I am Mridul Tiwari",
  "confidence": 91,
  "wordsFound": 5
}
⚙️ Tech Stack
Frontend Framework: Vite + React

OCR Engine: Tesseract.js

Styling: Tailwind CSS

🚀 Getting Started Locally
Clone the repo and run the app locally:

bash
Copy
Edit
git clone https://github.com/yourusername/ocr-to-json-parser.git
cd ocr-to-json-parser
npm install
npm run dev
Then open http://localhost:5173 in your browser.

📁 Project Structure
pgsql
Copy
Edit
ocr-to-json-parser/
├── public/
│   └── index.html
├── src/
│   ├── App.jsx
│   ├── main.jsx
│   └── components/
├── index.css
├── tailwind.config.js
├── vite.config.js
└── package.json
