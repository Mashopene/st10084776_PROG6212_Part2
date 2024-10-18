Contract Monthly Claim System (CMCS) Readme:

Overview
The Contract Monthly Claim System (CMCS) is a Windows Presentation Foundation (WPF) application designed to streamline the process of managing claims for contract lecturers in educational institutions. This system provides an efficient and user-friendly interface for submitting, reviewing, and approving claims.
Features

User Dashboard: Provides an overview of recent claims and system notifications.
Claim Submission: Allows lecturers to submit new claims with details such as course, hours worked, and hourly rate.
Document Upload: Supports uploading of supporting documents (PDF, DOCX, XLSX) with file size validation.
Claim Management: Enables users to view their submitted claims and track their status.
Admin Approval System: Allows program coordinators and academic managers to review and approve/reject pending claims.
Data Validation: Implements robust input validation to ensure data integrity.
Secure File Handling: Manages secure storage of uploaded documents.

Framework: .NET (WPF)
Language: C#
UI: XAML
Testing: MSTest

Project Structure

CMCS/: Main project directory

MainWindow.xaml: Main application window UI
MainWindow.xaml.cs: Backend logic for the main window


CMCS.Tesst/: Test project directory

UnitTest1.cs: Unit tests for the application



Setup and Installation

Open the solution file CMCS.sln in Visual Studio.
Restore NuGet packages if necessary.
Build the solution.
Run the application using Visual Studio or compile and run the executable.

Usage: For Lecturers

Launch the application and navigate to the "Submit Claim" tab.
Fill in the claim details (course, hours worked, hourly rate).
Upload any supporting documents if necessary.
Submit the claim.
View submitted claims in the "My Claims" tab.

For Administrators

Navigate to the "Approve Claims" tab.
Review pending claims.
Approve or reject claims as appropriate.

Testing
Run the unit tests in the CMCS.Tesst project to ensure core functionalities are working as expected.
Contributing

Fork the repository.
Create a new branch for your feature or bug fix.
Make your changes and commit them with descriptive commit messages.
Push your changes to your fork.
Submit a pull request to the main repository.
