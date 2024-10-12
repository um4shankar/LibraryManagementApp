# Library Management App - IIT Jodhpur
This Library Management App, developed for IIT Jodhpur, is currently live and serves over 1000 users. (To be increased, data of 3 weeks after launch) It provides a seamless experience with advanced features such as QR code-based self-check-in and checkout, book searches, and more. The app is integrated with the institute’s Koha LMS and offers both a mobile app for students and an admin portal for the library management team.

# Technology Stack:
- Frontend: Flutter
- Backend: MERN (MongoDB, Express.js, React.js, Node.js)
- Database: SQL, MongoDB
- SSH: ssh2 for secure server communication
- Library System: Koha LMS
- Web Scraping: Apify Web Scraper
- Authentication: OAuth, Koha LMS login integration

# Problem Solved:
The institute required a mobile app for its library system to enable students to perform self-service tasks such as self-check-in/out of books using QR codes. Our app solves this by integrating multiple features from the Koha Library Management System into a mobile-friendly platform.

# Background:
IIT Jodhpur uses Koha LMS for its library system. Koha is an open-source library management software that offers features like book check-in, check-out, book availability search, and more. Our app provides students with mobile access to these features, improving convenience and ease of use.

# Connectivity:
The app connects to Koha LMS via Koha APIs and direct database access for performing various operations such as book searches, check-ins, and checkouts.

# Key Features:
- Login: Users can log in using their institute ID and Koha LMS password or through OAuth.
- Password Management: Users can reset or create passwords via email token requests.
- Book Search: Search for books by title, author, ISBN, call number, barcode, or subject.
- Book Details: View detailed book information, including the number of available copies, due 
  dates, and current checkouts. Users can also view and provide ratings for books.
- Current & Past Checkouts: Users can view their current and past checkouts.
- Dues and Transactions: Users can view their outstanding dues and transaction history.
- Feedback and Suggestions: Users can provide feedback, report bugs, and give ratings for the     app.
- Notifications: Admins can send notifications to users for Instagram, YouTube, and LinkedIn 
  posts using Apify web scraper.

# Admin Portal:
To support administration tasks, we developed an admin portal with the following features:

- Statistics: Admins can view stats like total logins, app opens, and searches, as well as 
  month-wise and last seven days’ data.
- User Feedback Management: Admins can resolve user feedback and send emails directly via the 
  portal.
- Social Media Posting: Admins can post to Instagram, YouTube, and LinkedIn via links, using 
  Apify web scraper.
- User Data: Admins can access individual user data, including total logins, app opens, and 
  searches.
  
This app brings an innovative and mobile-friendly solution to the institute’s library management, making the student experience more efficient and accessible.

# Credentials
Install the apk file. You can login the app using these credentials:
Username: playcheck@gmail.com
Password: hello123
Apk file link: [https://drive.google.com/drive/folders/1RxuJaX-nOOr7iTNm_VbldGATk_EIK00W?usp=sharing
](url)

PS.: The app codes are a private repository beacuse of privacy issues regarding IITJ Adminsitration and Library.
