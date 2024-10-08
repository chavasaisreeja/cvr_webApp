# CVR College of Engineering Website

This project is a React-based website for CVR College of Engineering. It aims to provide a modern and user-friendly interface for students, faculty, and visitors to access information about the college.

## Features

- Responsive design for various screen sizes
- Navigation menu with dropdown for "About Us" section
- Home page with college information
- About Us pages including Vision & Mission and Chairman's Message
- Contact page
- User-specific dashboards for admin, faculty, and students

## Technologies Used

- React.js
- React Router for navigation
- Tailwind CSS for styling
- Font Awesome icons
- React Icons

## Getting Started

To run this project locally:

1. Clone the repository
2. Navigate to the `client` directory
3. Install dependencies with `npm install`
4. Start the development server with `npm start`

## Project Structure

- `src/components`: Contains React components
- `src/Images`: Stores image assets
- `src/App.js`: Main application file

## Routes

The website uses React Router for navigation. Here are the main routes and their purposes:

- `/`: Home page - Displays general information about the college
- `/aboutus/visionMission`: Vision & Mission page - Shows the college's vision and mission statements
- `/aboutus/chairmanMessage`: Chairman's Message page - Displays a message from the college chairman
- `/contact`: Contact page - Provides contact information and possibly a contact form
- `/login`: Login page - Allows users to authenticate and access their respective dashboards
- `/admin/dashboard`: Admin dashboard - Accessible after successful admin login
- `/faculty/dashboard`: Faculty dashboard - Accessible after successful faculty login
- `/student/dashboard`: Student dashboard - Accessible after successful student login

Users can navigate to these routes to access specific information and functionalities:
- Use the home page to get an overview of the college
- Visit the Vision & Mission page to understand the college's goals and objectives
- Read the Chairman's Message for insights from college leadership
- Access the Contact page to get in touch with the college administration
- Use the Login page to authenticate and access role-specific dashboards

## User Dashboards

After successful login, users are directed to their respective dashboards:

### Admin Dashboard (/admin/dashboard)
Administrators can:
- Manage user accounts (create, update, delete)
- View and update college information
- Manage course offerings and schedules
- Generate reports and analytics

### Faculty Dashboard (/faculty/dashboard)
Faculty members can:
- View and update their profile information
- Access their teaching schedule
- Upload course materials and assignments
- View and grade student submissions
- Communicate with students and other faculty members

### Student Dashboard (/student/dashboard)
Students can:
- View their personal and academic information
- Check their course schedule and grades
- Access course materials and submit assignments
- Communicate with faculty and other students
- View announcements and important notifications

## Contributing

Contributions to improve the website are welcome. Please follow these steps:

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a pull request

## License

This project is licensed under the MIT License.
