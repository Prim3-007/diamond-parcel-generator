# 💎 Diamond Parcel Label Generator

A specialized, print-calibrated web application for generating standard **Avery 30-Up (3×10 layout)** diamond parcel paper labels with real-time live preview, position selector for partially used sheets, and dynamic Code128 barcodes.

Developed by **Ashwin Sonawane**.

---

## ✨ Key Features

- **Diamond Attributes Entry**: Shape, Carat, Color, Clarity, Cert/Report #, Stock #, Dimensions, Depth %, Table %, Polish, Symmetry, and Fluorescence.
- **Interactive 30-Slot Grid (3×10)**: Select any starting position (Index 0–29) to print seamlessly onto partially used label sheets.
- **Dynamic Barcodes**: Automated Code128 barcode rendering via `JsBarcode` for single certificates and dual/pair stones.
- **Multi-Page Auto-Paginating PDF**: Print-ready, high-precision vectorized PDF generation via `jsPDF` calibrated for US Letter / A4 Avery 5160 sheets.
- **Smart Stone Detection**: Automatically detects Lab-Grown stones (IGI) with `LG` prefix or natural stones (GIA), as well as pair certificates separated by `/` or `,`.
- **Responsive & Mobile Ready**: Clean, modern interface styled with Tailwind CSS, optimized for desktop and mobile browsers (iOS Safari & Android).

---

## 🚀 Running Locally

```bash
# 1. Clone the repository
git clone https://github.com/Prim3-007/diamond-parcel-generator.git
cd diamond-parcel-generator

# 2. Install dependencies
pip install -r requirements.txt

# 3. Launch Streamlit
streamlit run app.py
```

---

## ☁️ Deploying on Streamlit Community Cloud

1. Log in to [share.streamlit.io](https://share.streamlit.io) with your GitHub account (`Prim3-007`).
2. Click **"Create app"** (or **"New app"**).
3. Select this repository: `Prim3-007/diamond-parcel-generator`.
4. Set the Main file path to `app.py`.
5. Click **"Deploy"**!

---

## 📄 License & Ownership
Property of and created by **Ashwin Sonawane**. Unauthorised use is prohibited.
