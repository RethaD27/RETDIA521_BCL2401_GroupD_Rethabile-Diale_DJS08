# DJS08 Project Brief: React Router 

🎥 INSERT LOOM PRESENTATION LINK: [Here]

# Van Rental Application
This is a React-based web application for a van rental service. The app includes various pages such as home, about, van listings, and host functionalities for managing van rentals. It also features authentication for host-specific routes.

## Features
* Home Page: Displays the main landing page.
* About Page: Provides information about the van rental service.
* Van Listings: Shows a list of available vans for rent.
* Van Details: Displays detailed information about a specific van.
* Login: Allows users to log in to their accounts.
* Host Dashboard: Hosts can manage their van listings, income, and reviews.
* Host Van Management: Hosts can view and edit details, pricing, and photos of their vans.

## File Structure
/src
  ├── components
  │   ├── Layout.jsx
  │   ├── HostLayout.jsx
  │   └── AuthRequired.jsx
  ├── pages
  │   ├── Home.jsx
  │   ├── About.jsx
  │   ├── Login.jsx
  │   ├── NotFound.jsx
  │   ├── Vans
  │   │   ├── Vans.jsx
  │   │   ├── VanDetail.jsx
  │   ├── Host
  │   │   ├─- Dashboard.jsx
  │   │   ├── Income.jsx
  │   │   ├── Reviews.jsx
  │   │   ├── HostVans.jsx
  │   │   ├── HostVanDetail.jsx
  │   │   ├── HostVanInfo.jsx
  │   │   ├── HostVanPricing.jsx
  │   │   ├── HostVanPhotos.jsx
  ├── App.jsx
  ├── index.jsx
  ├── index.css
  ├── server.js

## Dependencies
* react
* react-dom
* react-router-dom
* @fake-server/server

## Components
* Layout.jsx
  The main layout component that wraps around the non-host routes.

* HostLayout.jsx
  The layout component for host-specific routes.

* AuthRequired.jsx
  A higher-order component (HOC) that protects host routes and requires authentication.

## Pages
* Home.jsx
  The landing page of the application.

* About.jsx
  Contains information about the van rental service.

* Login.jsx
  User login page.

* NotFound.jsx
  Displays a 404 error for undefined routes.

## Vans
* Vans.jsx: Displays a list of vans.
* VanDetail.jsx: Shows details of a specific van.
## Host
* Dashboard.jsx: Host's dashboard showing an overview.
* Income.jsx: Displays the host's income.
* Reviews.jsx: Shows reviews for the host's vans.
* HostVans.jsx: Displays a list of the host's vans.
* HostVanDetail.jsx: Shows details of a specific van owned by the host.
* HostVanInfo.jsx: Displays information about the van.
* HostVanPricing.jsx: Allows the host to manage van pricing.
* HostVanPhotos.jsx: Allows the host to manage van photos.
