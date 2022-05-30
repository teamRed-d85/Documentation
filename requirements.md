# Software Requirements

- *interpreted from the-power-coders*

## Vision

### What is the vision of this product?

 Creating a survey app that stores data in user accounts. Each account will have the ability to organize, take notes and delete survey data from their organization.

### What pain point does this project solve?

The survey app will persist the survey data over time and allow an organization to organize and view said data.

### Why should we care about your product?

This will allow our users to take the data they collect from each survey and provide meaningful interpretation of that data over time.

## Scope (In/Out)

IN - What will your product do

- Our application will allow multiple surveys
- Our application will allow Admins to access past surveys
- Our application will allow Admins to Delete past surveys within their organization
- Our application will allow Admins to add notes to specific past surveys within their organization
- Our application will allow Admins to create surveys with a unique title
- Our application will present results in a graph

OUT - What will your product not do.

- No Data sharing is allowed between organizations.

## Minimum Viable Product

### What will your MVP functionality be?

Our MVP will be met when:

- The survey app will have basic functionality
- Multiple surveys will be allows on the app simultaneously
- Admin can access past surveys within their organization
- Admins to Delete past surveys within their organization
- Admins can add notes to specific past surveys within their organization
- Admins can create a survey with a unique title

## Stretch

### What are your stretch goals?

Update all visuals

## Functional Requirements

List the functionality of your product. This will consist of tasks such as the following:

1. An admin can create and delete user survey data
2. An admin can add notes to surveys
3. A user can take an Admin created survey
4. Users and Admin can view current and past survey data rendered in a chart format
5. Multiple surveys can be hosted concurrently with Admins using their own API keys

## Data Flow

*USER*: When the user visits the site they can fill out the form. This form is selected by the admin. The user then fills out the questions and the data is sent to the database. I would like a complete message when I am done filling out the form.

*ADMIN*: As an admin I would like to render a specified survey. I would like to review the results of surveys, both present and past. I would like to manipulate the records. I would also like to add new surveys. As an admin I would like to add a note to the past records for future reference. 

STRETCH: Update all visuals

## Non-Functional Requirements

### Capacity

Admins will be able to create and administer multiple surveys and store those user/survey data within their organization database. With this in mind, per the functionality and limitations of the Jotform API we can only have 5 active surveys at once per Admin. Admins have the ability to add their own API key to their account rather than to the whole site.

### Security

Only allowing admins with the specific subdomain to access that organization’s data.

### Maintainability & Manageability

Refactoring and clearing out unnecessary code allows for better readability and ease of locating what needs to be edited.

### Usability

New functionality will be displayed clearly to users and organized on the page in a way that is intuitive to use.
