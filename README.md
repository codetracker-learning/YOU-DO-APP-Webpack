# YOU-DO App

You will be creating an application that allows users to CRUD on TODOs. There will NOT be user authentication in this app as the purpose is a refresher on VanillaJS and should be completed by the next class time.

## Get Started
- clone this repo to your local machine
- `npm i`
- `npm start`

Below are the steps to get setup, which you should already be very familiar with:
1. Create a firebase app named `YOU-DO App`
2. Setup a firebase database (NO AUTH)
3. Add Sample Data to Your Database
4. Add your firebase creds to the `.env` file
5. Review the [MVP wireframe](https://www.figma.com/file/4YVF79vgSfeSj0H1G9HYDy/YOU-DO-MVP)
6. CODE!

## MVP Acceptance Criteria
NOTE: **DO NOT** make style changes. Follow the wireframe as designed as it uses Bootstrap Components that will make your app development faster. If you are able to complete MVP, move on to the stretch goals.

- As a user, I can add an item to my YOU-DO list by typing in the input and pressing submit
- As a user, when I press submit, I should see the newly added YOU-DO on the DOM
- As a user, I can complete a YOU-DO item by pressing a green button that reads "COMPLETE"
- As a user, when I press complete, I should no longer see the item on the DOM and the done attribute should update in firebase to `true`
- As a user, I can delete a YOU-DO by pressing a red button that reads "DELETE"
- As a user, when I press delete, the YOU-DO should be deleted from firebase and I should no longer see it on the DOM
- As an engineering hiring manager, I want to see a README that reflects the details of the project with the software engineers details and not THESE instructions.

## STRETCH Acceptance Critieria
**DO THESE IN ORDER OR BE FIRED**
- Review the [STRETCH wireframe](https://www.figma.com/file/ggEHuoIjQoUOLTylmQZnTK/YOU-DO-STRETCH)
- As a user, I should see an affordance that allows me to swtich views (See wireframe)
- As a user, if I select "View Completed" I should only see the completed YOU-DOs and whatever is shown in the wireframe
- As a user, I should be able to select from a pre-defined list of categories for the YOU-DOs I create.
- As a user, when I complete the form to submit a YOU-DO, the newly created YOU-DO should be visible on the DOM under the specified category and the category should update in firebase to the category I selected.
- As a user, I should be able to edit a YOU-DO using the same form used to create a YOU-DO.
- As a user, when I edit a YOU-DO and submit it, I should see the updated YOU-DO on the DOM under the chosen category.
- As an engineering hiring manager, I want to see a README that reflects the details of the project with the software engineers details and not THESE instructions.

