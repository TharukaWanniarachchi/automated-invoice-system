# Sunset Escape - Automated Invoice System

A professional, web-based invoice generator designed specifically for Sunset Escape villa bookings. This system provides an intuitive interface for creating, customizing, and managing invoices with automatic calculations and PDF export capabilities.

## 🌟 Features

- **Dynamic Invoice Generation**: Real-time invoice preview with automatic calculations
- **Professional Design**: Clean, branded layout matching Sunset Escape's identity
- **PDF Export**: One-click PDF generation and download functionality
- **Print Support**: Optimized print layout for physical invoices
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Easy Customization**: Simple form interface for editing invoice details
- **Item Management**: Add, edit, and remove invoice line items dynamically
- **Advanced Payment Tracking**: Built-in support for advance payments and balance calculations

## 🚀 Live Demo

Visit the live application: [Sunset Escape Invoice Generator](https://yourusername.github.io/automated-invoice-system)

## 💻 Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **PDF Generation**: html2pdf.js library
- **Styling**: Custom CSS with responsive design
- **Hosting**: GitHub Pages

## 📱 Usage

1. **Access the Application**: Open the web application in any modern browser
2. **Fill Invoice Details**: 
   - Enter invoice number and date
   - Add booking items with descriptions, quantities, and prices
   - Specify advance payment amount
3. **Preview**: Review the invoice in real-time as you make changes
4. **Export**: 
   - Print directly from browser
   - Download as PDF for digital sharing

## 🛠️ Installation & Setup

### For Local Development:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/automated-invoice-system.git
   cd automated-invoice-system
   ```

2. Open `index.html` in your browser or serve using a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx http-server
   ```

### For GitHub Pages Deployment:

1. Fork this repository
2. Go to repository Settings > Pages
3. Select "Deploy from a branch" 
4. Choose "main" branch and "/ (root)" folder
5. Your site will be available at `https://yourusername.github.io/automated-invoice-system`

## 📁 Project Structure

```
automated-invoice-system/
│
├── index.html          # Main application file
├── logo.png           # Sunset Escape logo
├── invoice.html       # Alternative/backup invoice file
└── README.md          # Project documentation
```

## 🎨 Customization

### Branding
- Replace `logo.png` with your company logo
- Update company information in the HTML header section
- Modify color scheme by changing CSS variables

### Invoice Template
- Edit the invoice layout in the `.page` section
- Customize form fields in the `.input-panel` section
- Adjust styling in the CSS section

## 📄 Invoice Features

- **Header Section**: Company branding, logo, and contact information
- **Invoice Details**: Invoice number, date, and customer information
- **Line Items**: Dynamic table for booking details with quantities and prices
- **Financial Summary**: Subtotal, advance payments, and final totals
- **Professional Footer**: Thank you message and branding

## 🖨️ Print & PDF Options

- **Browser Print**: Optimized print CSS for clean physical copies
- **PDF Export**: High-quality PDF generation with proper formatting
- **Mobile Friendly**: Responsive design ensures usability on all devices

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📧 Support

For support, email: your-email@example.com

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🏢 About Sunset Escape

Sunset Escape is a luxury villa located in Homagama, offering premium accommodations and unforgettable experiences "Beyond the ordinary, into luxury."

**Contact Information:**
- Phone: +94 71 417 5072
- Location: Sunset Escape Homagama

---

*Built with ❤️ for Sunset Escape*