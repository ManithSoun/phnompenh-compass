# Phnom Penh Compass

## How to Run

1. **Clone the project**

   ```bash
   git clone https://github.com/ManithSoun/phnompenh-compass.git
   cd phnompenh-compass

   ```

2. **Install dependecies**
   ```bash
   npm install
   ```
3. **Run the project**
   ```bash
   npm run dev
   ```

## Project Structure

```bash
phnompenh-compass/
│
├── public/
│ ├── index.html → main homepage
│ ├── pages/ → write code of each pages in this folder except homepage write in index.html
│ │ ├──explore-page/
│ │ ├──choose-your-vibe-page/
│ │ ├──services-page/
│ ├── components/ → navbar, footer (for copy-paste reuse)
│ ├── assets/ → images, logos, icons
│
├── src/
│ └── output.css
│ └── input.css
│
├── tailwind.config.js
├── package.json → project dependencies & scripts
└── README.md
```

## Structure in each code file (.html file)

```bash
  <body class="flex flex-col min-h-screen bg-[#FBFCF6]">

    <header>
      *[navbar code is in the header]*
    </header>

    <main class="flex-grow">
        *[write your code here in the main]*
    </main>

    <footer>
      *[footer code]*
    </footer>

  </body>
```

## Things to do when write the code

1. **Always pull the latest version before you start:**

```bash
git pull origin main
```

2. **Writing the code**
3. **Commit & Push** also dont't forget to comment about what you have changed
