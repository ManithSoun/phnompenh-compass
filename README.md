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

##Project Structure

```bash
phnompenh-compass/
│
├── public/
│ ├── index.html → main homepage
│ ├── pages/ → other pages (explore page, choose your vibe page,... .)
│ │ ├──explore.html
│ │ ├──choose-your-vibe.html
│ │ ├──services.html
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

## Things to do when write the code

1. **Always pull the latest version before you start:**

```bash
git pull origin main
```

2. **Create your own branch**

```bash
git checkout -b your-name
```

3. **Writing the code**
