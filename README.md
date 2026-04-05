# **MikroTik Router Catalog & Viewer**

A modern, responsive web viewer that displays MikroTik router images alongside their official names, file paths, and product descriptions. The project includes a structured JSON mapping (routers\_icons\_map.json) and a lightweight HTML/CSS/JS frontend to render the hardware catalog in uniformly-sized cards.

## **Features**

* Structured JSON mapping for 90+ MikroTik devices (name, file path, and product description).  
* Modern, responsive web viewer with a clean grid layout.  
* Includes branding logos for x86 hardware compatible with RouterOS installations.  
* Zero external dependencies (pure HTML, CSS, and vanilla JavaScript).  
* Fully responsive design that adapts to desktop, tablet, and mobile screens.

## **Project Structure**

.  
├── index.html                 \# Main viewer interface  
├── routers\_icons\_map.json     \# JSON data mapping images to product info  
└── rb\_images/                 \# Directory containing all .webp product images & logos  
    ├── 1001\_tm.webp  
    ├── Dell-Logo.webp  
    └── ...

## **Getting Started**

### **Prerequisites**

* Any modern web browser  
* A local web server (required due to browser CORS restrictions on local JSON fetching)

### **Setup**

1. Clone or download this repository.  
2. Ensure the rb\_images/ folder is in the same directory as index.html and routers\_icons\_map.json.  
3. Start a local server using your preferred method:

**Python 3**

python \-m http.server 8000

**Node.js (http-server)**

npx http-server

**PHP**

php \-S localhost:8000

4. Open http://localhost:8000 in your browser.

## **Data Source & Disclaimer**

* Product names, descriptions, and images are sourced from MikroTik's official hardware catalog.  
* This project is unofficial and created for educational, organizational, and personal use.  
* All trademarks and brand names belong to their respective owners (MikroTik, Dell, HP, Lenovo, ThinkPad, Fujitsu, Samsung, Toshiba, etc.).

## **Contributing**

Found outdated descriptions or missing a newly released model? Contributions are welcome:

1. Fork the repository  
2. Update routers\_icons\_map.json or add new .webp images to rb\_images/  
3. Submit a Pull Request

## **License**

This project is licensed under the MIT License. See the LICENSE file for details.