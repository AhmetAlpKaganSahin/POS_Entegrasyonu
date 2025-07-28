# POS Integration Project (Flask + TürkPOS SOAP API)

This project is a Python Flask application that integrates with TürkPOS payment services. It enables users to process credit card payments, handle cancellations and refunds, and see payment receipts (dekont).

The main goal of this project was to gain a deeper understanding of how online payment systems operate behind the scenes. I began working on it on my third day as an intern at TÜRK Finansal Teknoloji A.Ş. (Paramtech) and completed it by the fifth day. After grasping the core concepts, I decided to pause further development and focus on other projects.

I truly enjoyed building this application and learned a great deal about fintech during my internship. I hope you find this project insightful as well!

## Features
- Credit card payment processing
- Cancel and refund transactions
- Query and send payment receipts via email
- Communicates with SOAP web services using XML requests and parses XML responses
- User-friendly web interface

## Technologies
- Python 3
- Flask
- Requests (for HTTP requests)
- xml.etree.ElementTree (for XML parsing)
