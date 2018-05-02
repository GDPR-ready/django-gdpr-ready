# GDPR Compliance for Django
This is a Django module to make your project GDPR compliant.

 ### Roadmap/Goals

Following is a list of featuress from [GDPR - A Practical Guide for developers](https://techblog.bozho.net/gdpr-practical-guide-developers/). Some of the features may not be realistic to implement for every use case and will be updated as and when required.

- “Forget me” – Implement a method method that takes a userId and deletes all personal data about that user (in case they have been collected on the basis of consent or based on the legitimate interests of the controller (see more below), and not due to contract enforcement or legal obligation).
- Notify 3rd parties for erasure – Implement invoking third party API's (Salesforce, Hubspot, etc) do delete the pushed data about a user.
- Restrict Processing - Add a "restrict processing" button in the admin panel next to the list of users. (The user settings page may also have that button with a dropdown to select from the Article 18(1) options). When clicked (after reading the appropriate information), it should mark the profile as restricted. That means it should no longer be visible to the backoffice staff, or publicly.
- Export Data - Add an 'Export Data' functionality which exports all the data related to a single user.
- Consent Checkboxes - Add a new model for managing consents
- See all my data - Similar to the 'Export Data' function, allow the user to view all the data, including the data collected through third party like Facebook login.
- Age Checks - Allow for a flow where when a user is below 16, ask for a parent's email for their consent. So during the registration two confirmation mails should be sent: One to the user to confirm email and another to the parent's email (provided during registration) for their consent.
- Keeping data for no longer than necessary - Delete the data after it has served the purpose for which it was collected.

### Contributing

I'm actively looking for people to contribute on this project. If you have something you'd like to contribute, the best approach is to send a well-formed pull request.
This project is in a very early stage and welcomes contribution from developers, Privacy enthusiasts, policy makers, lawyers, etc.
