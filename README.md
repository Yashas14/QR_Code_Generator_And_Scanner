# QR Code Generator & Scanner 🚀

Welcome to the **QR Code Generator & Scanner**! A powerful, lightweight, and easy-to-use Python-based tool for creating and scanning QR codes effortlessly. Whether you need to encode important data into a QR code or decode existing ones, this project has got you covered! 🔍📲


## 🌟 Features

✅ **Generate QR Codes** – Convert text, URLs, or any data into a QR code image.

✅ **Scan QR Codes** – Use your webcam or an image file to decode and extract data from QR codes.

✅ **Fast & Reliable** – Powered by OpenCV and QRCode libraries for high-speed processing.

✅ **Minimal Dependencies** – Works with lightweight libraries to ensure smooth performance.

✅ **User-Friendly** – Simple CLI-based interaction to generate and scan QR codes easily.


## 🚀 Getting Started

### 🔧 Installation

1️⃣ **Clone the repository**:

```bash
 git clone https://github.com/Yashas14/QR_Code_Generator_And_Scanner.git
 cd QR_Code_Generator_And_Scanner
```

2️⃣ **Create a virtual environment** (optional but recommended):

```bash
 python -m venv env
 source env/bin/activate   # Windows users: env\Scripts\activate
```

3️⃣ **Install dependencies**:

```bash
 pip install -r requirements.txt
```


## 🎨 How to Use

### 🖼️ Generating a QR Code

Run the following command:

```bash
 python qr_generator.py
```

📌 **Enter the text or URL** you want to encode, and the script will generate a QR code and save it in the `generated_qr_codes/` directory.

### 📸 Scanning a QR Code

Run the scanner script:

```bash
 python qr_scanner.py
```

📌 Use your **webcam** or an image file to scan a QR code, and the script will display the decoded data instantly!



## 📂 Project Structure

```
QR_Code_Generator_And_Scanner/
│
├── generated_qr_codes/   # Folder where generated QR codes are stored
│
├── qr_generator.py       # QR Code Generator Script
│
├── qr_scanner.py         # QR Code Scanner Script
│
└── requirements.txt      # Python dependencies
```


## 🛠️ Dependencies

To ensure a smooth experience, this project uses:
- **Python 3.x**
- `qrcode` (for QR code generation)
- `opencv-python` (for QR code scanning)

You can install them using:
```bash
 pip install qrcode opencv-python
```


## 🎯 Contribution & Support

💡 **Have ideas for improvement?** Feel free to **fork**, **open issues**, or submit **pull requests**!

🌎 Spread the word, and let's make QR codes even more accessible! 🚀



🚀 **Ready to generate and scan QR codes like a pro? Let's get started!** 🎉

