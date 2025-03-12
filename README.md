# Swiss IBAN to QR-IBAN Converter

This is a simple **Swiss QR-IBAN Converter** built using **HTML, TailwindCSS, and JavaScript**. It allows users to convert a **standard IBAN** into a **QR-IBAN**, which is required for Swiss QR invoices.

> Here is the link for this converter :
> https://alexin-tech.github.io/Swiss-IBAN-to-QR-IBAN-Converter/

## 🚀 Features
- ✅ **Step-by-step tutorial** to help users find their QR-IID.
- ✅ **Automatic checksum calculation** using modulo 97 algorithm.
- ✅ **Copy button** for easy QR-IBAN usage.
- ✅ **Fully responsive design** with TailwindCSS.

---

## 📌 How to Use

### **Step 1: Enter Your IBAN**
- Input your **standard IBAN** (e.g., `CH21 8080 8001 2345 6789 0`).
- The system validates the IBAN format.

### **Step 2: Find Your QR-IID**
- If you don't know your **QR-IID**, click **"How to Find Your QR-IID?"**.
- Follow the **tutorial instructions** to search for your bank's QR-IID on the SIX Group website.

### **Step 3: Convert**
- Click the **"Convert to QR-IBAN"** button.
- The system calculates the correct **QR-IBAN checksum** and displays the result.

### **Step 4: Copy and Use**
- Click **"Copy"** to copy the QR-IBAN for use in invoices.

---

## 📖 Tutorial: How to Find Your QR-IID
If you don’t know your QR-IID, follow these steps:

1. Go to the **[SIX Group IID Inquiry Page](https://www.six-group.com/en/products-services/banking-services/interbank-clearing/online-services/inquiry-iid.html)**.
2. Enter your bank name in the **"Bank/Institution"** field.
3. Click the **"Search"** button.
4. Find a **QR-IID** in the results (values between **30000 - 31999**).
5. Copy the QR-IID and paste it into the converter.

---

## 🛠️ Technologies Used
- **HTML** for structure
- **TailwindCSS** for styling
- **JavaScript** for logic
- **Modulo 97 Algorithm** for checksum validation

---

## 📜 License
This project is licensed under the **MIT License**. See the `LICENSE` file for more details.

---

## 🤝 Contributing
Contributions are welcome! If you find a bug or want to enhance the project, feel free to open an issue or submit a pull request.
