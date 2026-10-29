
layout: null
title: Product Backlog
---

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Product Backlog | Christian Hakizimana</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <nav aria-label="Portfolio sections">
        <a href="index.html">Home</a>
        <a class="cv" href="cv.html">My CV</a>
        <a href="charter.html">Agile Team Charter</a>
        <a href="user-stories.html">User Stories and Tasks</a>
        <a href="product-backlog.html" aria-current="page">Product Backlog</a>
        <a href="sprint-backlog.html">Sprint Backlog</a>
        <a href="logbook.html">Agile Logbook</a>
    </nav>
</header>

<main>

    <h1>Product Backlog</h1>

    <p class="subtitle">
        The prioritised list of features, improvements and requirements
        needed to develop the FundiShop service marketplace.
    </p>

    <section>
        <h2>Project Overview</h2>

        <p>
            FundiShop is a web-based service marketplace that connects
            homeowners with local service providers, known as Fundis.
            The application is intended to help homeowners discover
            professionals, create service bookings and monitor booking
            progress. Fundis need to manage their profiles and respond
            to incoming service requests.
        </p>

        <p>
            The product backlog organises the functionality required
            for the application. Each backlog item represents a feature,
            improvement or technical requirement. Items are prioritised
            according to their value to users, dependencies, risk and
            estimated effort. The backlog can be refined as the team
            learns more about the requirements.
        </p>
    </section>

    <section>
        <h2>Evidence</h2>

        <p>
            The evidence for this section should show the actual FundiShop
            product backlog on Trello, including the relevant cards and
            their priority order.
        </p>

        <figure>
            <img
                src="images/product-backlog.png"
                alt="Screenshot of the FundiShop product backlog showing prioritised backlog items"
                loading="lazy"
            >
            <figcaption>
                Figure 1: FundiShop product backlog on Trello, showing
                prioritised product requirements, 2026.
            </figcaption>
        </figure>
    </section>

    <section>
        <h2>Prioritised Product Backlog</h2>

        <p>
            The following table is a proposed backlog for FundiShop.
            The priority labels indicate suggested implementation order
            and must be checked against the team's actual Trello backlog.
        </p>

        <table>
            <thead>
                <tr>
                    <th scope="col">Priority</th>
                    <th scope="col">Backlog ID</th>
                    <th scope="col">Item</th>
                    <th scope="col">Description</th>
                    <th scope="col">User value</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>High</td>
                    <td>PB01</td>
                    <td>User Registration</td>
                    <td>Allow new users to create accounts and provide the required details.</td>
                    <td>Enables users to access personalised platform features.</td>
                </tr>
                <tr>
                    <td>High</td>
                    <td>PB02</td>
                    <td>User Login</td>
                    <td>Allow registered users to access their accounts securely.</td>
                    <td>Provides account access and supports role-based experiences.</td>
                </tr>
                <tr>
                    <td>High</td>
                    <td>PB03</td>
                    <td>Role-Based Access</td>
                    <td>Distinguish between homeowners, Fundis and administrators.</td>
                    <td>Ensures users access features appropriate to their roles.</td>
                </tr>
                <tr>
                    <td>High</td>
                    <td>PB04</td>
                    <td>Find a Fundi</td>
                    <td>Allow homeowners to view available Fundis and their trade categories.</td>
                    <td>Helps homeowners find suitable service providers.</td>
                </tr>
                <tr>
                    <td>High</td>
                    <td>PB05</td>
                    <td>Fundi Profiles</td>
                    <td>Display details such as trade, biography, rates and service area where available.</td>
                    <td>Helps homeowners assess whether a Fundi suits their needs.</td>
                </tr>
                <tr>
                    <td>High</td>
                    <td>PB06</td>
                    <td>Create a Booking</td>
                    <td>Allow homeowners to submit a booking request with a date, time and job description.</td>
                    <td>Creates the main connection between a homeowner and a Fundi.</td>
                </tr>
                <tr>
                    <td>High</td>
                    <td>PB07</td>
                    <td>Booking Management</td>
                    <td>Allow Fundis to view requests and update permitted booking statuses.</td>
                    <td>Helps Fundis respond to and manage service requests.</td>
                </tr>
                <tr>
                    <td>High</td>
                    <td>PB08</td>
                    <td>Homeowner Dashboard</td>
                    <td>Display a homeowner's bookings and their current statuses.</td>
                    <td>Allows homeowners to monitor their service requests.</td>
                </tr>
                <tr>
                    <td>Medium</td>
                    <td>PB09</td>
                    <td>Fundi Dashboard</td>
                    <td>Provide Fundis with an overview of their profiles and booking requests.</td>
                    <td>Organises important information in one place.</td>
                </tr>
                <tr>
                    <td>Medium</td>
                    <td>PB10</td>
                    <td>Booking Status Updates</td>
                    <td>Support relevant status changes, such as accepting, declining or completing a booking.</td>
                    <td>Improves communication about booking progress.</td>
                </tr>
                <tr>
                    <td>Medium</td>
                    <td>PB11</td>
                    <td>Validation and Error Handling</td>
                    <td>Validate user input and show helpful messages when operations fail.</td>
                    <td>Improves reliability and user experience.</td>
                </tr>
                <tr>
                    <td>Medium</td>
                    <td>PB12</td>
                    <td>Responsive User Interface</td>
                    <td>Ensure key pages remain usable across supported screen sizes.</td>
                    <td>Makes the application easier to use on different devices.</td>
                </tr>
                <tr>
                    <td>Medium</td>
                    <td>PB13</td>
                    <td>Integration Testing</td>
                    <td>Test communication between the frontend, backend APIs and database.</td>
                    <td>Helps identify integration errors before release.</td>
                </tr>
                <tr>
                    <td>Medium</td>
                    <td>PB14</td>
                    <td>Administrator Functions</td>
                    <td>Provide appropriate administrative access for managing platform information.</td>
                    <td>Supports platform administration.</td>
                </tr>
                <tr>
                    <td>Low / Future</td>
                    <td>PB15</td>
                    <td>Reviews and Ratings</td>
                    <td>Allow homeowners to provide feedback about completed services.</td>
                    <td>Could help users evaluate service providers.</td>
                </tr>
                <tr>
                    <td>Low / Future</td>
                    <td>PB16</td>
                    <td>Notifications</td>
                    <td>Notify users of relevant booking events.</td>
                    <td>Could improve awareness of booking updates.</td>
                </tr>
            </tbody>
        </table>

        <p>
            <strong>Important:</strong> This table is a proposed planning
            example, not proof that every listed feature is implemented
            or present on the team's Trello board. Remove, rename or
            reorder items to match the actual project backlog.
        </p>
    </section>

    <section>
        <h2>How Priorities Were Considered</h2>

        <h3>High Priority</h3>
        <p>
            Core features that support the main marketplace workflow are
            proposed as high priority. Users need to access the platform,
            discover Fundis and create and manage bookings for FundiShop
            to deliver its primary purpose.
        </p>

        <h3>Medium Priority</h3>
        <p>
            Features that improve usability, visibility and reliability
            are proposed as medium priority. Dashboards, validation,
            responsive layouts and integration testing help make the
            core functionality easier and safer to use.
        </p>

        <h3>Low or Future Priority</h3>
        <p>
            Additional features such as reviews and notifications are
            proposed for later consideration because the main booking
            workflow can be developed without them. Their priority
            should be reviewed if user feedback or project requirements
            make them more important.
        </p>
    </section>

    <section>
        <h2>Backlog Refinement</h2>

        <p>
            The product backlog should be reviewed regularly as development
            progresses. New requirements, testing results, technical
            dependencies and feedback can lead to changes in priority.
            Large items should be broken down into smaller stories that
            the team can estimate, implement and test.
        </p>

        <p>
            Each item should have a clear description and, where appropriate,
            acceptance criteria. The team should also identify dependencies.
            For example, creating and tracking bookings depends on having
            the relevant user accounts, Fundi profiles and booking data
            available.
        </p>
    </section>

    <section>
        <h2>Reflection</h2>

        <p>
            The purpose of the product backlog is to organise the features
            required for FundiShop and provide the team with a shared view
            of what needs to be developed. The proposed priority order
            places the main marketplace workflow first: users must be able
            to access the platform, find a suitable Fundi and request a
            service before additional features can provide their full value.
        </p>

        <p>
            When deciding priorities, user value, dependencies, risk and
            effort should all be considered. Registration and login support
            access to personalised features, while Fundi discovery and
            booking functionality support the main purpose of the product.
            Features such as validation and integration testing are also
            important because errors in account handling or bookings can
            prevent the core workflow from working correctly. The final
            order should reflect the decisions recorded by the team rather
            than priority labels assigned only for this portfolio page.
        </p>

        <p>
            The backlog can change during development as the team discovers
            missing requirements, identifies technical problems or receives
            feedback. Some items may need to be divided into smaller stories,
            while others may be moved to a later stage if they are not
            essential to the current project goals. Refinement helps ensure
            that the team works on the most valuable and achievable items
            first.
        </p>

        <p>
            One potentially difficult prioritisation decision is choosing
            between adding extra features and improving the reliability of
            existing functionality. For FundiShop, a dependable booking
            process is central to the marketplace, so validating booking
            data and testing the connection between the frontend and backend
            should be considered alongside new features. The team's actual
            Trello discussions should be used to identify the specific item
            that was hardest to prioritise and explain how the decision was
            reached.
        </p>

        <p>
            The product backlog connects to the user stories because each
            backlog item can be described from the perspective of a homeowner,
            Fundi or administrator. Those stories can then be divided into
            development and testing tasks and selected for a sprint. The
            Agile Team Charter supports this process by establishing team
            roles, communication expectations and working agreements.
            Together, these artefacts help connect user needs, planning,
            implementation and review.
        </p>

        <p>
            <strong>Personal example to add before submission:</strong>
            Identify one real item on your Trello backlog that the team
            moved up or down in priority. Explain why the change was made,
            who contributed to the decision and what you learned from it.
        </p>
    </section>

    <nav aria-label="Previous and next portfolio pages">
        <a href="user-stories.html">← User Stories and Tasks</a>
        |
        <a href="sprint-backlog.html">Sprint Backlog →</a>
    </nav>

</main>

<footer>
    <p>
        © 2026 Christian Hakizimana · 219117675 · CPUT Diploma in ICT · PRP370S/371S/372S
    </p>
</footer>

</body>
</html>
