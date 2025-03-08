# flexreporting
A React-based Flex catering  reporting system
# The FIRM (The Flex Improved Report Module)

## Overview

The FIRM (The Flex Improved Report Module) is a React-based web application designed to streamline and enhance reporting functionality for catering operations. This tool generates professional delivery documentation for kitchen and delivery teams, providing clear, formatted reports based on Flex catering system data.

## Purpose

The application serves as an extension to the Flex catering system, offering improved reporting capabilities with:

- Enhanced delivery docket generation
- Organized delivery schedules
- Professional PDF exports
- User-friendly interface for kitchen and delivery staff

## Features

### Delivery Docket Generation

The application creates detailed delivery dockets that include:

- Order identification and dispatch information
- Comprehensive delivery location details
- Categorized inventory lists (Food, Equipment, Tea & Coffee)
- Component breakdowns for complex items
- Special instructions and temperature requirements

### Delivery Schedule Management

The system produces organized delivery schedules featuring:

- Date-specific delivery planning
- Driver assignment tracking
- Chronological delivery routing
- Customer contact information
- Delivery notes and special instructions
- Temperature indicators for hot/cold items

### PDF Export Functionality

The application supports exporting reports to PDF format for:

- Printing physical copies for delivery staff
- Digital record-keeping
- Sharing with team members

## Technical Structure

The FIRM is built with modern web technologies:

- **Frontend**: React.js
- **Runtime Environment**: Node.js
- **Styling**: Tailwind CSS
- **PDF Generation**: PDF generation library (implementation ready)

### Core Components

1. **DeliveryDocketPreview**: Renders order-specific delivery documentation
2. **DeliverySchedulePreview**: Displays driver-oriented delivery schedules
3. **PDF Generation Module**: Handles export of reports to PDF format

## Installation

1. Ensure Node.js is installed on your system
2. Clone the repository to your local machine
3. Navigate to the project directory
4. Install dependencies:
   ```
   npm install
   ```
5. Start the development server:
   ```
   npm start
   ```

## Usage

1. **Accessing the Application**:
   - Open the application in your web browser
   - Navigate to the desired report type (Docket or Schedule)

2. **Creating a Delivery Docket**:
   - Select the order from the Flex data
   - Review the generated docket
   - Make any necessary adjustments
   - Export to PDF if needed

3. **Generating a Delivery Schedule**:
   - Choose the delivery date
   - Confirm driver assignments
   - Review the complete schedule
   - Export for distribution to delivery team

## Integration with Flex Catering System

The FIRM seamlessly integrates with existing Flex catering software:

- Imports order data directly from Flex exports
- Maintains consistent information across systems
- Enhances reporting without modifying the core Flex system

## Future Development

Potential enhancements for future versions:

- Direct API integration with Flex
- Mobile application for delivery drivers
- Customer notification system
- Route optimization
- Electronic signature capture

## Support

For questions or issues regarding The FIRM, please contact the system administrator.

## License

[Your license information here]

---

© 2025 [Your Company Name]. All rights reserved.
