# Selling and Buying Web App

This web application simplifies the process of renting and buying properties, allowing users to post, search, and manage properties for rent or sale. Users can list various property types—such as lands, houses, or shops—and interested parties can browse the listings, communicate with the owners, and track their preferences. Property owners can manage rent payments through a dashboard, ensuring streamlined tracking of monthly payments.

## Tech Stack
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Java, Servlets, Jsp, JSTL
- **Database:** MySQL

## Key Features
- **Property Listings:** Users can post properties for rent or sale, including detailed descriptions, photos, and pricing.
- **Search and Filter:** Prospective buyers or renters can search listings by property type, location, price, and more.
- **Follow and Track:** Users can follow properties they are interested in, which are displayed in their personalized feed.
- **Chat and Communication:** Users can chat with property owners to discuss deals or request further information.
- **Payment Tracking:** Owners can keep track of rent payments, while renters can manage their payment history through the dashboard.
- **Session Management:** Users are automatically logged out after a session timeout for enhanced security.

## Data and Application Constraints
- **Multiple Properties:** A user can list multiple properties for rent or sale.
- **Follow Feature:** Users can follow multiple properties, and properties can have multiple followers.
- **Authentication:** Email, username, and password are required for registration. Passwords must contain at least 8 characters, including one alphabet, one special character, and one number.
- **Permissions:** Only property owners can edit, update, mark as sold/rented, or delete their listings.
- **Post Interactions:** Users can like or follow properties, and renters or buyers can also list their own properties.
- **Inactive Listings:** Properties marked as "done" (sold/rented) will remain in the system to allow reactivation. Users following these posts will see a yellow mark indicating the property status change.
- **Photo Uploads:** Users can upload up to 10 images for each property.
- **Property Details:** Title, address, price, and description are mandatory for each property listing, while phone numbers are optional and can be shared through the chat feature.
- **Password Recovery:** Users can recover their accounts using the registered email address in case they forget their password.

## Functional Overview
- **Post Creation:** Users can add property details via forms and post them for rent or sale. They can also manage their listings through the "Add Property" option in the sliding menu.
- **Browsing Properties:** Users can browse properties under the "Rent" or "Buy" sections, with search capabilities based on owner name, address, or title.
- **Post Management:** Owners can edit, delete, or mark their posts as done. All followed properties are displayed in the user's feed.
- **Payment Tracking:** Owners and renters can track payment statuses, ensuring rent dues are easily managed.
- **User Profile:** The user profile section displays all user activity, including their posted, sold, or bought items. Users can also update their personal information, including username, email, or password.

## Team Members
- Koteswarudu Akula
- V. Harsha Varadhan
- S. Sai Sandeep
- Nallani Rohan Rao
