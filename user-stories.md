
layout: null
title: User Stories and Tasks
---

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>User Stories and Tasks | Christian Hakizimana</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <nav aria-label="Portfolio sections">
        <a href="index.html">Home</a>
        <a class="cv" href="cv.html">My CV</a>
        <a href="charter.html">Agile Team Charter</a>
        <a href="user-stories.html" aria-current="page">User Stories and Tasks</a>
        <a href="product-backlog.html">Product Backlog</a>
        <a href="sprint-backlog.html">Sprint Backlog</a>
        <a href="logbook.html">Agile Logbook</a>
    </nav>
</header>

<main>

    <h1>User Stories and Tasks</h1>

    <p class="subtitle">
        Features written from the end user's perspective, broken down into tasks.
    </p>

    <section>
        <h2>Project Overview</h2>

        <p>
            FundiShop is a service marketplace designed to connect homeowners
            with local service providers, known as Fundis. The platform aims
            to make it easier for homeowners to find professionals, request
            services, arrange bookings and track their booking progress.
            Fundis can use the platform to manage their service requests.
        </p>

        <p>
            User stories help describe the functionality from the perspective
            of the people who will use the system. Each story explains who
            needs a feature, what they want to do and why the feature is useful.
            The stories can then be divided into smaller development and testing
            tasks.
        </p>
    </section>

    <section>
        <h2>Evidence</h2>

        <p>
            The evidence for this section should show the user stories and
            their related tasks as recorded on the FundiShop Trello board.
            Add a screenshot of the relevant Trello cards below.
        </p>

        <figure>
            <img
                src="images/user-stories.png"
                alt="Screenshot of FundiShop user stories and their related tasks from Trello"
                loading="lazy"
            >
            <figcaption>
                Figure 1: FundiShop user stories and related tasks recorded
                on the Trello board, 2026.
            </figcaption>
        </figure>
    </section>

    <section>
        <h2>Draft User Stories and Tasks</h2>

        <p>
            The following examples illustrate how FundiShop functionality
            can be expressed as user stories and divided into manageable
            development tasks. Confirm the final wording, assigned members
            and completion status against the actual Trello board.
        </p>

        <h3>User Story 1: User Registration</h3>

        <p>
            <strong>As a</strong> new user,
            <strong>I want</strong> to register for a FundiShop account,
            <strong>so that</strong> I can access the platform's services
            using my own account.
        </p>

        <p><strong>Example tasks:</strong></p>
        <ul>
            <li>Create the registration form and input fields.</li>
            <li>Validate the information entered by the user.</li>
            <li>Connect the registration form to the backend API.</li>
            <li>Save valid user details in the database.</li>
            <li>Test successful registration and invalid input.</li>
        </ul>

        <h3>User Story 2: User Login</h3>

        <p>
            <strong>As a</strong> registered user,
            <strong>I want</strong> to log in to FundiShop,
            <strong>so that</strong> I can access the features available
            to my account.
        </p>

        <p><strong>Example tasks:</strong></p>
        <ul>
            <li>Develop the login interface.</li>
            <li>Validate the email and password fields.</li>
            <li>Connect login to the backend authentication logic.</li>
            <li>Display suitable messages when login fails.</li>
            <li>Test login using valid and invalid credentials.</li>
        </ul>

        <h3>User Story 3: Find a Fundi</h3>

        <p>
            <strong>As a</strong> homeowner,
            <strong>I want</strong> to find local Fundis by their services,
            <strong>so that</strong> I can identify a suitable professional
            for my needs.
        </p>

        <p><strong>Example tasks:</strong></p>
        <ul>
            <li>Create the Find a Fundi page.</li>
            <li>Display available Fundi profiles and trade categories.</li>
            <li>Retrieve relevant Fundi information from the backend.</li>
            <li>Show useful profile information to homeowners.</li>
            <li>Test the page with available and empty result sets.</li>
        </ul>

        <h3>User Story 4: Create a Booking</h3>

        <p>
            <strong>As a</strong> homeowner,
            <strong>I want</strong> to request a booking with a Fundi,
            <strong>so that</strong> I can arrange help for a service I need.
        </p>

        <p><strong>Example tasks:</strong></p>
        <ul>
            <li>Design the booking form.</li>
            <li>Capture the selected Fundi, date, time and job description.</li>
            <li>Connect the form to the booking API.</li>
            <li>Store the booking and its initial status.</li>
            <li>Test booking submission and validation.</li>
        </ul>

        <h3>User Story 5: Track Bookings</h3>

        <p>
            <strong>As a</strong> homeowner,
            <strong>I want</strong> to view my bookings and their statuses,
            <strong>so that</strong> I can track the progress of my service
            requests.
        </p>

        <p><strong>Example tasks:</strong></p>
        <ul>
            <li>Create the homeowner dashboard and booking summary.</li>
            <li>Retrieve bookings associated with the logged-in homeowner.</li>
            <li>Display booking dates, service details and statuses.</li>
            <li>Handle loading, empty and error states.</li>
            <li>Test that the correct bookings appear on the dashboard.</li>
        </ul>

        <h3>User Story 6: Manage Booking Requests</h3>

        <p>
            <strong>As a</strong> Fundi,
            <strong>I want</strong> to view and manage incoming booking requests,
            <strong>so that</strong> I can respond to service requests from
            homeowners.
        </p>

        <p><strong>Example tasks:</strong></p>
        <ul>
            <li>Develop the Fundi booking-management interface.</li>
            <li>Retrieve bookings associated with the Fundi's profile.</li>
            <li>Display relevant booking information and current statuses.</li>
            <li>Implement the permitted booking status updates.</li>
            <li>Test booking retrieval and status changes.</li>
        </ul>
    </section>

    <section>
        <h2>Task Allocation</h2>

        <p>
            Tasks should be allocated according to the team's agreed roles,
            skills and availability. The table below is a planning template;
            the actual allocation must match the Trello cards.
        </p>

        <table>
            <thead>
                <tr>
                    <th scope="col">Team member</th>
                    <th scope="col">Agreed role</th>
                    <th scope="col">Example area of responsibility</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Kabelo Moloko</td>
                    <td>Scrum Master</td>
                    <td>Support sprint coordination, track blockers and help the team follow its Agile process.</td>
                </tr>
                <tr>
                    <td>Lisakhanya Mpahla</td>
                    <td>Product Owner</td>
                    <td>Clarify user needs, prioritize requirements and help confirm acceptance criteria.</td>
                </tr>
                <tr>
                    <td>Christian Hakizimana</td>
                    <td>Backend Developer</td>
                    <td>Contribute to backend APIs, data handling and integration with the database.</td>
                </tr>
                <tr>
                    <td>Muhammad Siddeeq Rabin</td>
                    <td>Frontend Developer / QA</td>
                    <td>Contribute to user interfaces, frontend integration and software testing.</td>
                </tr>
            </tbody>
        </table>

        <p>
            These responsibilities describe the team's agreed roles, not
            proof that a specific task was completed by a particular member.
            Use the assigned members and task statuses shown in Trello when
            recording actual contributions.
        </p>
    </section>

    <section>
        <h2>Reflection</h2>

        <p>
            When developing the FundiShop user stories, the main end users
            considered were homeowners and Fundis. Homeowners need a convenient
            way to find service providers, request bookings and track the
            progress of their requests. Fundis need a way to view incoming
            requests and manage their responses. These needs help guide the
            features included in the application and keep development focused
            on the people who will use the system.
        </p>

        <p>
            The user stories use the format "As a..., I want..., so that..."
            to identify the user, the requested feature and its purpose.
            This format makes each requirement easier to understand and discuss.
            Stories should be small enough to implement and test, with clear
            acceptance criteria that explain what must happen for a feature
            to be considered complete. For example, a booking story can be
            tested by checking that valid booking details are submitted and
            that the new booking is associated with the correct homeowner
            and Fundi.
        </p>

        <p>
            After defining a story, it can be broken down into tasks covering
            interface development, backend integration, database operations
            and testing. Breaking work into smaller tasks makes progress
            easier to track and helps team members understand what needs
            to be done. Task ownership and progress should be managed through
            the team's Trello board so that responsibilities and outstanding
            work remain visible.
        </p>

        <p>
            One improvement I would make is to ensure that every story has
            specific acceptance criteria and a clear definition of completion.
            For example, the booking story should specify which fields are
            required, what happens when the submitted information is invalid,
            and which booking status is shown after a successful request.
            Writing user stories has helped me understand how to translate
            user needs into manageable development work and how planning,
            communication and testing contribute to building a useful system.
        </p>

        <p>
            <strong>Personal example to add before submission:</strong>
            Describe one real user story or task from the Trello board that
            your team discussed, refined or had difficulty completing.
            Explain what you personally contributed and what you learned
            from that experience.
        </p>
    </section>

    <nav aria-label="Previous and next portfolio pages">
        <a href="charter.html">← Agile Team Charter</a>
        |
        <a href="product-backlog.html">Product Backlog →</a>
    </nav>

</main>

<footer>
    <p>
        © 2026 Christian Hakizimana · 219117675 · CPUT Diploma in ICT · PRP370S/371S/372S
    </p>
</footer>

</body>
</html>
