# OCR
🖼️ Images and PDFs (multi-page)  

🧠 Multi-pass OCR for higher accuracy  

🧪 Optional binarization / contrast boost  

🌍 Multi-language support (English, Arabic, Chinese…) 

📈 Confidence indicator + “needs review” tag 

🔎 Page range: OCR all pages or from X → Y 

🔐 100% client-side (WebAssembly); privacy by design


**Run Locally (for ZIP download users)**


1. Extract the ZIP

Right-click the ZIP file → Extract All (or use any unzip tool).

Open the extracted folder in VS Code.

2. Install Node.js (if not installed)

Download & install Node.js LTS from 👉 https://nodejs.org

After installation, check it works:

**node -v
npm -v**


`You should see version numbers.`

3. Install dependencies

Open a terminal inside VS Code (Ctrl + `) and run:

npm install


This will install all required packages (React, Vite, Tailwind, pdf.js, tesseract.js, etc.).

4. Run the development server

After dependencies finish installing:

npm run dev


👉 The terminal will show something like:

  VITE v5.0  ready in 2s

 ** ➜  Local:   http://localhost:5173/**


Open http://localhost:5173
 in your browser. 🎉

**5. Build for production (optional)
**
**If you want to make a static build:**

**npm run build**


The optimized files will be in the dist/ folder.

✅ So in short, users only need 3 commands after unzipping:

**npm install**
**npm run dev**


(optional)

**npm run build**
