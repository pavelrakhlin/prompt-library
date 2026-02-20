**Planning an app:**
Context:
Let’s create an app to help people writing documents to reference any other documents or knowledge as they write, and use AI to write the document with them as they go referencing those added documents.

User journey:
The app should have a landing page that leads to a login/signup screen and then after users sign up or login take them into the app. They should see a simple dashboard that allows them to create new documents and open any document they have already created. When opening a document, the user should go into a document view showing the document they're editing in the center of the screen with rich text editing controls and a left hand sidebar to let them add knowledge to this document they are editing. Knowledge should just be plain text for now and should be added as context for the AI document editing controls. There should also be a right-hand sidebar with an AI chat that can write or edit text in the main document and uses any added knowledge as context when doing so. The user should also be able to name this document, navigate back to the dashboard, and also see when the document was last saved.

Pages:
The pages that should be created are a landing page, a login and signup page, the dashboard page, and a document editor page.
Technical considerations (APIs, tech, tools, libraries, etc.)
For the AI writing functionality, use OpenAI, and setup the database and authentication using Convex following the Convex documentation @Convex

Design direction (rough):
The design direction for this app should be a clean, minimal document editor using serif fonts for a classic and traditional look with soft shadows and rounded corners.

Send request:
Create a thorough plan to build this application.

***

***Figma to Cursor:***
Implement this design from Figma using React JS:
URL
Pay close attention to the details and variables that are used in this file. Create a design system file in JSON format to keep future designs consistant.
