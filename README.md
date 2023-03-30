QR Code Scanner with Next.js and Tailwind
This is a simple QR Code scanner app built with Next.js and Tailwind CSS. The app allows users to scan QR codes and send the scanned data to Google Sheets using the Google Sheets API.

Prerequisites
Node.js (>=14.x)
A Google account to create and access a Google Sheets spreadsheet
Installation
Clone the repository and install dependencies:
bash
Copy code
git clone https://github.com/<your-username>/qr-code-scanner-nextjs.git
cd qr-code-scanner-nextjs
npm install
Create a .env.local file at the root of the project and set the following environment variables:
makefile
Copy code
GOOGLE_CLIENT_EMAIL=your-google-service-account-email
GOOGLE_PRIVATE_KEY=your-google-service-account-private-key
SPREADSHEET_ID=your-google-spreadsheet-id
The GOOGLE_CLIENT_EMAIL and GOOGLE_PRIVATE_KEY are used to authenticate your app with the Google Sheets API. The SPREADSHEET_ID is the ID of the Google Sheets spreadsheet where you want to store the scanned data.

Run the development server:
bash
Copy code
npm run dev
Open http://localhost:3000 in your browser to see the app.
Usage
Click on the "Scan" button to launch the QR code scanner.
Point your camera at a QR code to scan it.
The scanned data will be displayed on the screen.
Click the "OK" button to send the scanned data to the Google Sheets spreadsheet.
To view the scanned data, open the Google Sheets spreadsheet and navigate to the sheet where the data is being stored.
Contributing
Contributions are welcome! Please feel free to submit a pull request.
