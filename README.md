# Health-Tech 
## Intelligent Patient Onboarding RPA Project

This project demonstrates a fully functional **UiPath Robotic Process Automation (RPA)** workflow for automating patient registration, PDF data extraction, database updates, and email notifications in a healthcare setting.

---

## Project Overview

Manual patient onboarding is time-consuming, error-prone, and often delays administrative processes. This RPA solution automates the process end-to-end:

1. **Extract patient data** from registration PDFs (including handwritten, scanned, and skewed forms).
2. **Validate and update records** in a database (Excel, Google Sheets, or SQL).
3. **Send confirmation emails** to patients after successful registration for Survey.
4. Include realistic **sample PDFs** to test the workflow.

---

## Architecture & Workflow

The project follows a modular structure:

[Input PDFs] --> [PDF Extraction Workflow] --> [Validation & Database Update] --> [Email Notification] --> [Logs/Reports]


- **PDF Extraction Workflow**: Extracts structured fields using regex and UiPath Document Understanding.
- **Validation & Database Update**: Checks if patient exists, validates data formats, updates database accordingly.
- **Email Notification**: Sends confirmation or survey emails to patients.
- **Logging**: Captures errors, missing fields, and workflow statistics.

---

## Key Features

- **PDF Extraction**: Reliable extraction using regex and structured mapping.
- **Database Access**: Automates patient verification and storage.
- **Email Automation**: Sends automated notifications post-registration.
- **Error Handling**: Handles missing/invalid data gracefully.
- **Logging & Metrics**: Generates process logs and summary reports.
- **Sample Data**: Includes 20+ realistic patient PDFs for testing.

---

## Setup Instructions

1. **Install UiPath Studio** (Community or Enterprise edition).
2. Clone or download the repository.
3. Open the project folder in UiPath Studio.
4. Update workflow variables for:
   - Database path (Excel, Google Sheets, or SQL)
   - Email SMTP credentials
5. Place sample PDFs in the `/PDFs` folder.
6. Run `Main.xaml` to start the end-to-end automation.

---

## Testing and Validation

- Use the sample PDFs to test workflow.
- Verify database entries and email notifications.
- Test error handling with PDFs missing fields or with invalid formats.

---

## Technologies Used

- **UiPath Studio** for RPA automation.
- **Excel / SQL Database** for storing and validating patient records.
- **SMTP** for email notifications.
- **Regex & Document Understanding** for PDF extraction.

---

## Business Value

- Reduces manual data entry and human error.
- Accelerates patient onboarding process.
- Improves efficiency for administrative staff.
- Scalable and maintainable for future automation expansions.

---

## Author

- Fanflor Theodore
