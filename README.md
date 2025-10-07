# Simple CRUD AppScript

A simple CRUD (Create, Read, Update, Delete) application built with Google Apps Script, HTML, CSS, and JavaScript. This project demonstrates how to create a web-based application using Google Spreadsheet as a database through Apps Script extensions.

## 📋 Overview

This application provides a complete CRUD interface that allows users to manage data stored in a Google Spreadsheet. The frontend is built with HTML, CSS, and JavaScript, while the backend leverages Google Apps Script to interact with Google Sheets.

## ✨ Features

- **Create**: Add new records to the spreadsheet
- **Read**: View and retrieve existing records
- **Update**: Modify existing records
- **Delete**: Remove records from the spreadsheet
- **Responsive UI**: Clean and user-friendly interface
- **Real-time Data**: Direct integration with Google Spreadsheet
- **No Database Required**: Uses Google Sheets as the database

## 🛠️ Technologies Used

### Frontend
- **HTML**: Structure and content
- **CSS**: Styling and layout
- **JavaScript**: Client-side logic and interactivity

### Backend
- **Google Apps Script**: Server-side logic and Google Sheets integration
- **Google Spreadsheet**: Data storage and management

## 📁 Project Structure

```
simple-crud-appsript/
├── Code.gs              # Apps Script backend code
├── index.html           # Main HTML file
├── styles.html          # CSS styles
├── script.html          # JavaScript code
└── README.md            # Project documentation
```

## 🚀 Getting Started

### Prerequisites

- A Google account
- Access to Google Sheets and Google Apps Script

### Installation & Setup

1. **Create a New Google Spreadsheet**
   - Go to [Google Sheets](https://sheets.google.com)
   - Create a new spreadsheet
   - Set up your data columns (e.g., ID, Name, Email, etc.)

2. **Open Apps Script Editor**
   - In your spreadsheet, click on `Extensions` → `Apps Script`
   - This will open the Apps Script editor

3. **Add the Code Files**
   - Copy the code from `Code.gs` to the Apps Script editor
   - For HTML files, create new HTML files in the Apps Script editor:
     - Click the `+` next to Files
     - Select `HTML` file
     - Name it appropriately (index.html, styles.html, script.html)
   - Copy the respective code to each file

4. **Deploy as Web App**
   - Click on `Deploy` → `New deployment`
   - Select type: `Web app`
   - Configure:
     - Description: "CRUD App"
     - Execute as: "Me"
     - Who has access: Choose based on your needs
   - Click `Deploy`
   - Copy the web app URL

5. **Access Your Application**
   - Open the deployment URL in your browser
   - Start using the CRUD application!

## 📖 Usage

### Creating a Record
1. Fill in the form fields
2. Click the "Create" or "Add" button
3. The record will be added to the spreadsheet

### Reading Records
- Records are automatically displayed in a table or list format
- You can view all existing records from the spreadsheet

### Updating a Record
1. Click the "Edit" button next to a record
2. Modify the values in the form
3. Click "Update" to save changes

### Deleting a Record
1. Click the "Delete" button next to a record
2. Confirm the deletion
3. The record will be removed from the spreadsheet

## 🔧 Configuration

You may need to configure the following in `Code.gs`:

- **Spreadsheet ID**: Update with your spreadsheet ID
- **Sheet Name**: Specify the sheet name where data is stored
- **Column Mapping**: Define which columns correspond to which fields

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

**Tyo-Dev**

## 🙏 Acknowledgments

- Google Apps Script Documentation
- Google Sheets API
- Community tutorials and resources

## 📞 Support

If you have any questions or need help, please open an issue in the repository.

---

Made with ❤️ using Google Apps Script