# CareerMap

A polished, responsive CareerMap website built as a self-contained browser application.

## Included functionality
- Student and employer registration/login
- Role-based navigation and dashboards
- Opportunity search, filtering and sorting
- Interactive Leaflet map
- Browser geolocation + nearest-first sorting
- Save/unsave opportunities
- Opportunity details
- Student applications and withdrawal
- Employer opportunity creation/editing/deletion
- Employer application status management
- Student/employer notifications
- Student and organisation profiles
- Recommendations based on profile information
- Responsive blue-first design
- Loading/empty/error/success-style UX states
- Local persistence using localStorage

## Run
Open `index.html` in a modern browser. An internet connection is recommended for the Leaflet/OpenStreetMap map.

## Demo
Create a Student account to test the student journey.
Create a separate Employer account to test the employer journey and create opportunities.

## Important production note
This standalone version intentionally uses localStorage so it can run immediately without installing a database/server. For a production deployment, replace the persistence/authentication layer with the requested Node/Express/PostgreSQL API, bcrypt password hashing, server-side sessions/JWT, secure file storage for CVs, and backend ownership/role checks.
