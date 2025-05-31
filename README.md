# AI-Powered Supply Chain Validator

A modern web application for validating and analyzing supply chain data using AI models. This tool helps identify anomalies, validate data integrity, and provide real-time insights into supply chain operations.

## Features

- **Data Upload & Validation**
  - CSV file upload support
  - Real-time data validation
  - Multiple AI model options (Logistic Regression, Random Forest, AutoAI)
  - Automatic anomaly detection

- **Interactive Dashboard**
  - Real-time metrics and KPIs
  - Performance visualization
  - Anomaly detection charts
  - Detailed validation results

- **AI Model Selection**
  - Logistic Regression
  - Random Forest
  - AutoAI (recommended)

## Getting Started

### Prerequisites
- Python 3.x
- Modern web browser (Chrome, Firefox, Safari, Edge)

### Installation
1. Clone the repository:
```bash
git clone [repository-url]
cd supply-chain-validator
```

2. Start the local server:
```bash
python -m http.server 8000
```

3. Open your browser and navigate to:
```
http://localhost:8000
```

## Usage

### Data Upload
1. Click the upload area or drag and drop a CSV file
2. Supported columns: Product ID, Supplier, Quantity, Status
3. The system will automatically parse and validate the data

### Validation Process
1. Select an AI model from the options
2. Click "Validate Data" to start the analysis
3. View real-time validation results and metrics

### Understanding Results
- **Anomaly Detected**: Confirmed issues in the data
- **False Positive**: Incorrectly flagged valid records
- **Valid**: Records with no issues
- **Anomaly Missed**: Undetected issues

## Screenshots

### Dashboard Overview
![Dashboard Overview](screenshot1.png)


### Data Validation
![Data Validation](screenshot2.png)


### Anomaly Detection
![Anomaly Detection](screenshot3.png)


## Technical Details

### Built With
- HTML5
- CSS3
- JavaScript
- Bootstrap 5.3.0
- Chart.js 3.9.1
- PapaParse 5.4.1

### AI Models
- **Logistic Regression**: Basic anomaly detection
- **Random Forest**: Advanced pattern recognition
- **AutoAI**: Self-optimizing model selection

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



## Acknowledgments

- Bootstrap for the UI framework
- Chart.js for data visualization
- PapaParse for CSV parsing
- Font Awesome for icons 