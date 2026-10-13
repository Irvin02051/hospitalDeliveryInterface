# PharmaTrac

PharmaTrac is a comprehensive delivery requisition management system designed to streamline the process within hospital pharmacy settings. It replaces the traditional binder-based method of tracking delivery history with a digital solution. PharmaTrac aims to enhance efficiency and accuracy in managing delivery requisitions.

## Purpose

The purpose of PharmaTrac is to replace the existing manual process used in hospital pharmacies for tracking the delivery history of narcotics. Traditionally, this process involves maintaining a binder to record and manage delivery requisitions. However, PharmaTrac offers a modern digital alternative that simplifies the creation, management, and tracking of delivery requisitions.

## Key Features

**User Authentication:** Users log in with employee credentials to access the application.

**Delivery Requisitions:** Users can create, edit, sign off, deliver orders, and return orders to the pending queue.

**Hierarchy:** The application distinguishes between Admin and Staff roles, with Admin having additional privileges such as managing user accounts and deleting delivery requisitions.

**Order Management:** Orders are categorized as pending or completed, providing a clear overview of the delivery status.

**Search Functionality:** Users can search for orders based on various criteria, facilitating efficient order management.

**Real-time Updates:** Changes made to the order queues are instantly reflected across all application instances.

**Additional Features:** PharmaTrac offers additional features such as light and dark mode, language switching (utilizing LibreTranslate API: https://github.com/dynomake/libretranslate-java.git), and integration with Algolia Search API (https://www.algolia.com/developers/search-api/) for enhanced search capabilities.

## My Contribution

As part of the CSC 325 project team, I:

- Developed login and account-creation interfaces using JavaFX and FXML, with Java logic connected to Firebase-backed employee records.
- Implemented input validation, duplicate-account checks, and user-facing error messages.
- Added password hashing and credential verification for the application's custom login flow.
- Implemented login-status tracking and checks for accounts already marked as logged in.
- Updated interface controls based on login status and administrator or staff account type.

## Technologies Used

- **Java:** Application logic.
- **JavaFX and CSS:** Desktop user interface and styling.
- **Google Firebase:** Data storage and real-time updates.
- **Algolia:** Order search functionality.
- **LibreTranslate:** Language translation.
- **Maven:** Dependency and build management.
- **IntelliJ IDEA and Scene Builder:** Development and interface design tools.

## How to Start
**To get started with PharmaTrac, follow these steps:**
- Clone the repository.
- Configure Firebase credentials and the Firestore database.
- Configure Algolia Search API.
- Run the application using IntelliJ or your preferred IDE.
