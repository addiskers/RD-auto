# TOC and RD Generator

## Overview
This project is a **Table of Contents (TOC) and Research Document (RD) Generator** web application. It allows users to input market data, segments, and company information, and generates professional market reports in Word format.

## Features
- Input fields for:
  - Market name
  - Value (2022)
  - CAGR (%)
  - Currency (Million, Billion, Trillion)
  - Segments and sub-segments
  - Company profiles
  - Key Market Insights (KMI)
- Auto-calculation of market values for 2023 and 2031 based on CAGR.
- Generates Word reports with:
  - Market insights
  - Segmental analysis
  - Company profiles
  - Customizable headings and content.

## Technologies Used
- **Python**: Backend logic and data processing.
- **Flask**: Web framework for creating the application.
- **python-docx**: Library to generate Word documents.
- **HTML/CSS**: Frontend for user interface.
- **JavaScript**: For dynamic UI components.

## Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/addiskers/RD-auto.git
   cd your-repo
   ```

2. **Set up a Virtual Environment** (Optional but recommended)
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Application**
   ```bash
   python app.py
   ```

5. **Access the Application**
   Open a browser and navigate to `http://127.0.0.1:5000/`.

## Usage
1. Fill in the required fields in the web interface:
   - Market Name, Value (2022), CAGR, etc.
2. Add headings, segments, and company profiles as needed.
3. Click on **Generate Documents** to download the TOC and RD files.

## Project Structure
```
.
├── app.py                 # Main application file
├── requirements.txt       # Python dependencies
├── templates/             # HTML templates
│   ├── index.html         # Main interface
├── static/                # Static files (CSS, JS)
│   ├── style.css          # Custom styles
├── Market_Report.docx     # Example output document
```

## Output Example
The generated Word document includes:
- **Title**: Market report title.
- **Market Insights**: Comprehensive details about market size, growth, and forecast.
- **Segmental Analysis**: Details about market segments and sub-segments.
- **Company Profiles**: List of top players in the market.

## Contributing
Contributions are welcome! Follow these steps:
1. Fork the repository.
2. Create a new branch.
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes.
   ```bash
   git commit -m "Add feature description"
   ```
4. Push to your branch.
   ```bash
   git push origin feature-name
   ```
5. Open a Pull Request.

## License
This project is licensed under the MIT License.

---
Feel free to modify the project to fit your needs and contribute to its development!
