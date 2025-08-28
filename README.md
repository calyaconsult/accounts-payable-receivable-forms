# Accounts Payable and Receivable Management Forms

This repository contains HTML forms for managing accounts payable and receivable invoices with JSON output functionality. The forms are designed to help streamline financial workflows by providing a user-friendly interface for entering and validating invoice data.

## Files Included

- `form-filler-accounts-receivable-1.html` - Invoice management form for accounts receivable
- `form-filler-accounts-receivable-2.html` - Alternate version of accounts receivable form
- `form-filler-accounts-payable-1.html` - Invoice management form for accounts payable
- `form-filler-accounts-payable-2.html` - Alternate version of accounts payable form

## Features

### User-Friendly Interface
- Clean, responsive design that works on all devices
- Organized sections for easy data entry
- Visual feedback for interactive elements
- Real-time calculations for financial values

### Data Validation
- Required field validation
- Automatic calculation of:
  - Days outstanding
  - Balance due/amount outstanding
  - Aging buckets
- Currency selection with default values

### JSON Output
- All forms display submitted data as formatted JSON
- Helpful for debugging and data integration
- Scrollable output display for easy viewing

### Specialized Forms

#### Accounts Receivable Forms
Fields include:
- Invoice Number
- Customer ID and Name
- Contact Information
- Invoice and Due Dates
- Amounts in local currency and CHF
- Payment tracking
- Status management
- Notes and comments

#### Accounts Payable Forms
Fields include:
- Invoice Number
- Vendor ID and Name
- Invoice and Due Dates
- Amounts in CHF and local currency
- Payment tracking
- PO Number
- Paying account selection
- Status management

## Usage

1. Open any HTML file in a web browser
2. Fill in the required fields
3. Click "Save Invoice" to see the data as JSON
4. Use "Reset Form" to clear all fields

## Technologies Used

- HTML5
- CSS3 (with Flexbox and Grid layouts)
- JavaScript (ES6)
- Font Awesome icons

## Browser Compatibility

The forms work in all modern browsers including:
- Chrome
- Firefox
- Safari
- Edge

## Contributing

Feel free to fork this repository and submit pull requests with improvements. Suggestions for enhancements include:

- Integration with backend databases
- Export functionality (CSV, PDF)
- Additional validation rules
- Multi-language support

## License

This project is open source and available under the MIT License.

## Creator

Qwen3-Coder

Created to help streamline financial data entry workflows with a focus on usability and data integrity.
