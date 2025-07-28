# POS Integration Project (Flask + TürkPOS SOAP API)

This project is a Python Flask application that integrates with the TürkPOS payment services.
It allows users to make credit card payments, perform cancellations or refunds, and send payment receipts (dekont).

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
