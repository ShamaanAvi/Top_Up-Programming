# Top_Up-Programming
# Aurora Skin Care Appointment System

Aurora Skin Care Appointment System is a comprehensive C# Windows Forms application that automates and manages key operations in a dermatology clinic. The application covers appointment booking, updating and viewing appointments, fee processing, and invoice generation, ensuring smooth clinic operations with optimized scheduling and payment features.

## Features
- **Secure Login**: User authentication with validation for secure access to clinic management functionalities.
- **Appointment Booking**: Allows clinic staff to book appointments, select dermatologists and treatments, with real-time availability checks to prevent scheduling conflicts.
- **Update and View Appointments**: Modify and review appointments with filters for date, patient name, or appointment ID.
- **Payment Processing**: Accept registration fees and process treatment payments, with automated tax calculations.
- **Invoice Generation**: Generates detailed invoices showing treatment breakdown, taxes, and total amounts.
- **Validation and Conflict Management**: Ensures no double bookings by checking dermatologist availability and preventing overlapping appointments.

## Project Structure
- **`fLogin`**: Manages user authentication.
- **`fMain`**: Primary navigation menu for accessing core features.
- **`fMakeApp`**: Handles appointment booking, with validation methods like `IsDermatologistAvailable` and `IsAppointmentAvailable`.
- **`fViewApp`**: Allows users to view appointments filtered by date.
- **`fUpdateApp`**: Enables updates to appointments, with restrictions on paid appointments.
- **`fPayment`**: Manages registration fees and calculates total treatment costs, including a 2.5% tax.
- **`fInvoice`**: Generates invoices with itemized amounts, taxes, and patient details.

## Database Structure
The application uses a SQL Server database with the following tables:
- **DoctorSchedule**: Defines doctor availability with consultation timings.
- **Patient**: Stores patient data.
- **Doctor**: Stores dermatologist information.
- **Treatment**: Stores available treatments and their costs.
- **Appointment**: Stores details of booked appointments.
- **Payment**: Records payment details, with tax calculations and final amounts.

## Setup and Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/Aurora-Skin-Care-System.git
