# 🌾 AGRO TECH -- Agriculture Knowledge Hub

AGRO TECH is a static website that provides categorized agriculture
knowledge including **technologies, fertilizers, fruits, vegetables,
crops, flowers, trees, and government schemes**.\
Built entirely using **HTML, CSS, and JavaScript**, it is simple, fast,
and easy to deploy.

------------------------------------------------------------------------

## 🚀 Features

-   ✔ Category-based agriculture information\
-   ✔ Crop suggestion system\
-   ✔ Search bar with auto-routing\
-   ✔ Fully static website\
-   ✔ Clean and organized folder structure

------------------------------------------------------------------------

## 🛠 Tech Stack

  Technology       Use
  ---------------- ---------------------------
  **HTML5**        Website structure
  **CSS3**         Styling & layout
  **JavaScript**   Navigation, Search, Logic

------------------------------------------------------------------------

## 📁 Project Structure

    home page/          → Main home page (index.html)
    css file/           → Global CSS styles
    script/             → JavaScript logic
    Technology/         → Technology pages
    vegetable/          → Vegetable pages
    fruit/              → Fruit pages
    flower/             → Flower category pages
    TREES/              → Tree & fruit tree pages
    Crops/              → Kharif / Rabi / Zaid crop pages
    Fertilizer/         → Organic & inorganic fertilizers
    Schemes/            → Government schemes
    About Us/           → About page
    crop suggestion/    → Crop suggestion tool

------------------------------------------------------------------------

## ⚡ How to Run Locally

Because the website uses **absolute paths (`/folder/file`)**, opening
files with `file://` will break navigation.\
Use any local server:

### **1️⃣ VS Code Live Server**

1.  Open project in VS Code\
2.  Right-click `home page/index.html`\
3.  Choose **Open With Live Server**\
4.  Go to:\

```{=html}
<!-- -->
```
    http://localhost:5500/home%20page/

### **2️⃣ Python HTTP Server**

``` bash
python -m http.server 8000
```

Open:

    http://localhost:8000/home%20page/

### **3️⃣ Node.js HTTP Server**

``` bash
npx http-server -p 8000 .
```

Open:

    http://localhost:8000/home%20page/

------------------------------------------------------------------------

## 🧭 How to Use

-   **Home Page:** `home page/index.html`\
-   **Navigation:** Technology, Vegetables, Fruits, Flowers, Crops,
    Fertilizer, Schemes, Crop Suggestion, About\
-   **Search:** Enter a keyword → redirects to matched page

------------------------------------------------------------------------

## 🔧 Development Notes

-   Edit CSS → `css file/style.css`\
-   Edit JS → `script/*.js`\
-   Add/edit HTML → respective folder\
-   If using **GitHub Pages**, convert absolute paths:\

```{=html}
<!-- -->
```
    /Technology/page.html → Technology/page.html

------------------------------------------------------------------------

## 🌐 Deployment

Deploy on:

-   GitHub Pages\
-   Netlify\
-   Vercel\
-   Azure Static Web Apps

------------------------------------------------------------------------

## 📜 License

Open-source for academic & learning use.
