# AirBnB Clone - Booking Management System

A simple booking and management system using AirBnB as a case study. This system will have a simple but lovely UI/UX that allows users to perform basic functionalities.

## Project Goals

At the end of this program, You will have developed adequate knowledge and skills to implement any type of system. You will:

- Understand the project scope.
- Identify key features to be implemented.
- Adhere to designated timelines and milestones.
- Utilize the necessary tools and technologies.
- Fulfill your roles and responsibilities within the project.

## Tech Stack

- **Frontend**: React with TypeScript, Next.js for server-side rendering and static site generation, TailwindCSS for styling.

- **Backend**: Python, Django, and MySQL (the backend is not the primary focus).

- **Other Tools**: Redux or Context API for state management, REST for API integration and Jest for testing.

## UI/UX Design Planning

A user-friendly design is important in a booking system in order to help users easily navigate the interface and perform basic functionalities.

The design goals for this project are as follows:

### Features

The key features to be implemented include:

- **Property Listings**: Display properties with relevant details and images.

- **Booking System**: Allow users to book properties, view booking details, and manage bookings.

- **Search Functionality**: Enable users to search for properties based on various criteria (location, price, availability).
- **User Authentication**: Secure login and registration for users.

### Primary Pages

| Page       | Description                                                                                                                                                                                                                                                                           | Image                                    |
| ---------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------- |
| **Page 1** | This will be the main interface of the AirBnB clone. It shows a clean and modern layout with various property listings displayed, each with a title, price and a brief description. The design focuses on user-friendly navigation and visual appeal.                                 | ![page 1 design](./designs/airbnb-1.png) |
| **Page 2** | This page illustrates a detailed view of a specific property listing within the AirBnB clone. It highlights key features such as the property’s name, location, price, and additional details like amenities. The interface emphasizes clarity and ease of use for potential renters. | ![page 2 design](./designs/airbnb-2.png) |
| **Page 3** | This page showcases the booking or reservation process for the selected property in the AirBnB clone. It may include options for selecting dates, the number of guests, and finalizing the booking. The design is streamlined to ensure a smooth user experience.                     | ![page 3 design](./designs/airbnb-3.png) |

### Design Properties

Identifying design properties of a mockup design is important because it helps make the design consistent and also ensures the finished product doesn't drift from the mockup design.

#### Colors

- Primary colors: #34967C
- Secondary colors: #161117, #BEBEBE, #FFA800,
- Other colors: #FAC02B, #262626, #F0FFFB, #8C8C8C, #F9F9F9, #131212, #FFFFFF, #000000, #CACACA, #222222, #616161, #F3F0F0, #6C6C6C, #929292, #747474, #8F8F8F, #F8FAFC
- Border colors: #E9E9E9, #ECECEC, #EAEAEA, #E7E6E6

#### Typography

- Font Family : Quicksand, Souce Sans Pro, SF Pro Display
- Font Weights: 400, 500, 600, 700
- Font Sizes: 12px, 13px, 14px, 16px, 17px, 19px, 20px, 22px, 23px, 24px, 25px, 27px, 31px, 94px

## Project Roles and Responsibilities

In a software development project, clearly defined roles and responsibilities are crucial for success. Here’s a breakdown of the typical roles within a development team and their key responsibilities:

#### Project Manager (PM)

The Project Manager is the leader of the project. They are responsible for planning, executing, and closing projects.

**Key Responsibilities:**

- Oversee project progress and ensure milestones are met.
- Facilitate communication within the team.
- Manage project timelines, budget, and resources.
- Identify and mitigate risks.
- Serve as the primary point of contact for stakeholders.

#### Frontend Developers

Frontend developers focus on the client-side of the application, ensuring a smooth and engaging user experience.

**Key Responsibilities:**

- Implement UI/UX designs using HTML, CSS, and JavaScript.
- Develop React components and integrate them with backend APIs.
- Ensure the application is responsive and performs well on various devices.
- Collaborate with designers to create visually appealing interfaces.
- Optimize the application for maximum speed and scalability.

#### Backend Developers

Backend developers work on the server-side of the application, managing data and ensuring seamless communication between the server and the frontend.

**Key Responsibilities**:

- Develop and maintain server-side logic using languages such as Python, Node.js, or Java.
- Design and manage databases.
- Create and maintain APIs for frontend integration.
- Implement security and data protection measures.
- Optimize server performance and scalability.

#### Designers

Designers are responsible for the visual and interactive aspects of the application, ensuring it is user-friendly and aesthetically pleasing.

**Key Responsibilities**:

- Create wireframes, mockups, and prototypes.
- Design the layout and visual elements of the application.
- Ensure a consistent brand identity across the application.
- Collaborate with frontend developers to implement designs.
- Conduct usability testing to gather feedback and improve designs.

#### QA/Testers

QA/Testers ensure the quality and reliability of the application by identifying and fixing bugs before release.

**Key Responsibilities**:

- Develop and execute test plans and test cases.
- Perform manual and automated testing.
- Identify, document, and track bugs.
- Verify bug fixes and perform regression testing.
- Ensure the application meets quality standards and user requirements.

#### DevOps Engineers

DevOps Engineers focus on the deployment and operational aspects of the software, ensuring smooth and efficient delivery.

**Key Responsibilities**:

- Automate deployment processes.
- Manage cloud infrastructure and server configurations.
- Monitor application performance and uptime.
- Implement continuous integration and continuous deployment (CI/CD) pipelines.
- Ensure security and compliance in the production environment.

#### Product Owner (PO)

The Product Owner is responsible for defining the vision of the product and ensuring it meets user needs.

**Key Responsibilities**:

- Define and prioritize product features and requirements.
- Create and manage the product backlog.
- Act as a liaison between stakeholders and the development team.
- Ensure the product delivers value to users and aligns with business goals.
- Make decisions on scope and accept completed work.

#### Scrum Master

The Scrum Master facilitates Agile processes and helps the team follow Scrum practices.

**Key Responsibilities**:

- Organize and facilitate Scrum ceremonies (e.g., daily stand-ups, sprint planning, retrospectives).
- Remove impediments that hinder the team’s progress.
- Foster a collaborative and productive team environment.
- Coach the team on Agile principles and practices.
- Ensure continuous improvement within the team.

## UI Component Patterns

Components from the figma design

- Navbar: The navbar component is a reusable one used in all three pages and helps the user navigate the app easily.

- Category: In the homepage, there are different categories, so this will also be a reusable component.

- Property Card: This component will contain the name of a property, location, utilities e.t.c of a property.

- Footer

- Button

- Review card: User reviews component

- User Input
