
layout: null
title: Sprint Backlog
---

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Sprint Backlog | Christian Hakizimana</title>
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
        <a href="product-backlog.html">Product Backlog</a>
        <a href="sprint-backlog.html" aria-current="page">Sprint Backlog</a>
        <a href="logbook.html">Agile Logbook</a>
    </nav>
</header>

<main>

    <h1>Sprint Backlog</h1>

    <p class="subtitle">
        The work selected for the sprint and the sprint goal.
    </p>

    <section>
        <h2>Project Overview</h2>

        <p>
            FundiShop is a web-based marketplace that connects homeowners
            with local service providers, known as Fundis. The platform
            aims to help homeowners find professionals, request bookings
            and track their service requests, while Fundis can manage
            their profiles and respond to incoming bookings.
        </p>

        <p>
            The sprint backlog identifies the work the team intends to
            complete during a sprint. It contains the selected product
            backlog items, the tasks needed to deliver them and the
            team's plan for achieving the sprint goal. The team can
            review progress throughout the sprint and adapt the plan
            when necessary.
        </p>
    </section>

    <section>
        <h2>Sprint Goal</h2>

        <p>
            The proposed sprint goal is to establish the main FundiShop
            user workflow by allowing users to register and log in,
            helping homeowners find Fundis, and supporting the creation
            and viewing of service bookings.
        </p>

        <p>
            This goal focuses on the core marketplace functionality
            before expanding the application with additional features.
            Confirm the goal against the sprint that your team actually
            planned in Trello.
        </p>
    </section>

    <section>
        <h2>Evidence</h2>

        <p>
            Add a screenshot of your actual FundiShop Trello sprint board.
            The screenshot should show the sprint goal, selected cards,
            task assignments and progress columns where available.
        </p>

        <figure>
            <img
                src="images/sprint-backlog.png"
                alt="FundiShop sprint backlog board showing selected sprint work and task progress"
                loading="lazy"
            >
            <figcaption>
                Figure 1: FundiShop sprint backlog showing the selected
                work items and sprint progress, 2026.
            </figcaption>
        </figure>
    </section>

    <section>
        <h2>Selected Sprint Backlog Items</h2>

        <p>
            The following items are proposed examples for planning a
            sprint around the main FundiShop workflow. Replace or reorder
            them to match the work your team selected from its product
            backlog.
        </p>

        <table>
            <thead>
                <tr>
                    <th scope="col">ID</th>
                    <th scope="col">Selected item</th>
                    <th scope="col">Tasks</th>
                    <th scope="col">Priority</th>
                    <th scope="col">Actual status</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>SB01</td>
                    <td>User Registration</td>
                    <td>
                        <ul>
                            <li>Create registration form.</li>
                            <li>Validate required information.</li>
                            <li>Connect the form to the backend API.</li>
                            <li>Test successful and unsuccessful registration.</li>
                        </ul>
                    </td>
                    <td>High</td>
                    <td>Update from Trello</td>
                </tr>
                <tr>
                    <td>SB02</td>
                    <td>User Login</td>
                    <td>
                        <ul>
                            <li>Create the login interface.</li>
                            <li>Connect login to backend authentication.</li>
                            <li>Display useful error messages.</li>
                            <li>Test login scenarios.</li>
                        </ul>
                    </td>
                    <td>High</td>
                    <td>Update from Trello</td>
                </tr>
                <tr>
                    <td>SB03</td>
                    <td>Find a Fundi</td>
                    <td>
                        <ul>
                            <li>Build the Fundi listing page.</li>
                            <li>Display available Fundi profiles.</li>
                            <li>Retrieve profile data from the backend.</li>
                            <li>Test the listing page.</li>
                        </ul>
                    </td>
                    <td>High</td>
                    <td>Update from Trello</td>
                </tr>
                <tr>
                    <td>SB04</td>
                    <td>Create a Booking</td>
                    <td>
                        <ul>
                            <li>Create the booking form.</li>
                            <li>Capture the service date, time and description.</li>
                            <li>Submit the booking to the backend.</li>
                            <li>Test booking validation and creation.</li>
                        </ul>
                    </td>
                    <td>High</td>
                    <td>Update from Trello</td>
                </tr>
                <tr>
                    <td>SB05</td>
                    <td>View Bookings</td>
                    <td>
                        <ul>
                            <li>Retrieve bookings for the logged-in homeowner.</li>
                            <li>Display booking details and status.</li>
                            <li>Handle loading and empty states.</li>
                            <li>Test booking retrieval.</li>
                        </ul>
                    </td>
                    <td>High</td>
                    <td>Update from Trello</td>
                </tr>
                <tr>
                    <td>SB06</td>
                    <td>Integration and Testing</td>
                    <td>
                        <ul>
                            <li>Check frontend-to-backend API requests.</li>
                            <li>Test database operations.</li>
                            <li>Identify and fix integration errors.</li>
                            <li>Verify the main user workflow.</li>
                        </ul>
                    </td>
                    <td>High</td>
                    <td>Update from Trello</td>
                </tr>
            </tbody>
        </table>
    </section>

    <section>
        <h2>Task Allocation</h2>

        <p>
            Sprint tasks should be assigned according to the team's
            agreed responsibilities and the actual Trello assignments.
            The examples below show how the team's roles can support
            sprint planning; they do not confirm who completed a task.
        </p>

        <table>
            <thead>
                <tr>
                    <th scope="col">Team member</th>
                    <th scope="col">Agreed role</th>
                    <th scope="col">Possible sprint contribution</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Kabelo Moloko</td>
                    <td>Scrum Master</td>
                    <td>Support sprint coordination, monitor blockers and help the team review progress.</td>
                </tr>
                <tr>
                    <td>Lisakhanya Mpahla</td>
                    <td>Product Owner</td>
                    <td>Clarify requirements, prioritise work and confirm acceptance criteria.</td>
                </tr>
                <tr>
                    <td>Christian Hakizimana</td>
                    <td>Backend Developer</td>
                    <td>Contribute to backend endpoints, database integration and booking operations.</td>
                </tr>
                <tr>
                    <td>Muhammad Siddeeq Rabin</td>
                    <td>Frontend Developer / QA</td>
                    <td>Contribute to frontend interfaces, API integration and testing.</td>
                </tr>
            </tbody>
        </table>
    </section>

    <section>
        <h2>Definition of Done</h2>

        <p>
            A sprint item should only be marked complete when it satisfies
            the team's agreed completion criteria. Suggested checks include:
        </p>

        <ul>
            <li>The functionality meets the story's acceptance criteria.</li>
            <li>Required input validation and error handling are included.</li>
            <li>The frontend and backend work together where required.</li>
            <li>Relevant tests have been performed and issues addressed.</li>
            <li>The implementation has been reviewed according to the team's process.</li>
            <li>The Trello card reflects the actual task status.</li>
        </ul>
    </section>

    <section>
        <h2>Sprint Progress and Review</h2>

        <p>
            During the sprint, the team should monitor the progress of each
            selected item and identify obstacles early. At the end of the
            sprint, the team should compare completed work with the sprint
            goal, review unfinished tasks and decide what needs to happen
            next.
        </p>

        <p>
            Use the actual Trello card history and sprint review to complete
            the table below. Do not mark work as completed unless there is
            evidence that it was finished.
        </p>

        <table>
            <thead>
                <tr>
                    <th scope="col">Review question</th>
                    <th scope="col">What to record</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>What was completed?</td>
                    <td>List the items moved to Done and verified by the team.</td>
                </tr>
                <tr>
                    <td>What was unfinished?</td>
                    <td>List items still in progress or not started at sprint end.</td>
                </tr>
                <tr>
                    <td>What blocked progress?</td>
                    <td>Describe actual technical issues, dependencies or availability problems.</td>
                </tr>
                <tr>
                    <td>What should improve?</td>
                    <td>Record specific planning, communication or testing improvements for the next sprint.</td>
                </tr>
            </tbody>
        </table>
    </section>

    <section>
        <h2>Reflection</h2>

        <p>
            Sprint planning helps translate the product backlog into a
            manageable set of tasks that supports a specific goal. For
            FundiShop, a sprint focused on the core marketplace workflow
            would prioritise features such as account access, Fundi
            discovery and booking management. These features are closely
            connected because homeowners need to find a suitable professional
            and submit a booking before they can track its progress.
        </p>

        <p>
            When deciding what to include in a sprint, the team should
            consider priority, dependencies, estimated effort and its
            availability. The selected items should be realistic for the
            sprint period and sufficiently clear for team members to
            implement and test. Breaking stories into smaller tasks makes
            progress easier to monitor and can help the team identify
            problems before they affect the overall sprint goal.
        </p>

        <p>
            Progress should be reviewed regularly through the team's
            task board and discussions. Completed work should meet the
            agreed acceptance criteria rather than simply being marked
            done. If an item cannot be completed because of a technical
            issue, unclear requirements or a dependency, the team should
            record the reason and reconsider the work during future
            planning.
        </p>

        <p>
            For the next sprint, I would aim to make task estimates more
            realistic, clarify acceptance criteria before development
            starts and allow enough time for integration and testing.
            I would also encourage the team to raise blockers early and
            keep Trello updated so that everyone has a shared understanding
            of progress. These practices can help the team plan more
            effectively and deliver reliable functionality.
        </p>

        <p>
            <strong>Personal example to add before submission:</strong>
            Describe one actual sprint task that your team completed or
            struggled with. Explain what happened, what your own contribution
            was, why the task was completed or delayed, and what you would
            change when planning the next sprint.
        </p>
    </section>

    <nav aria-label="Previous and next portfolio pages">
        <a href="product-backlog.html">← Product Backlog</a>
        |
        <a href="logbook.html">Agile Logbook →</a>
    </nav>

</main>

<footer>
    <p>
        © 2026 Christian Hakizimana · 219117675 · CPUT Diploma in ICT · PRP370S/371S/372S
    </p>
</footer>

</body>
</html>
