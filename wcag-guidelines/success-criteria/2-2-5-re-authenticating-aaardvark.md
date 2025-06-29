# 2.2.5 Re-authenticating - AAArdvark

[Operable](https://aaardvarkaccessibility.com/wcag-principle/operable/)

[Enough Time](https://aaardvarkaccessibility.com/wcag-guideline/enough-time/)

WCAG 2.0, 2.1, 2.2
Level AAA

[View official documentation for WCAG 2.2.5](https://www.w3.org/WAI/WCAG22/Understanding/re-authenticating.html)

# 2.2.5 Re-authenticating

If a logged-in session expires mid-way through a task, any data entered after expiry is kept, so that they don’t have to re-enter it when they log in again.

[Forms](https://aaardvarkaccessibility.com/wcag-theme/forms/) 

 

[Cognitive](https://aaardvarkaccessibility.com/wcag-disability/cognitive/), [Visual](https://aaardvarkaccessibility.com/wcag-disability/visual/) 

 

[Code](https://aaardvarkaccessibility.com/wcag-responsibility/code/) 

## What is it?

Websites must not erase users' work when a session times out. If someone gets logged out mid-task for security reasons, they must be able to log back in and keep going without losing everything they previously entered.
This success criterion covers situations like:

Being logged out after inactivity while filling out a form
Session timeouts while writing an email, forum post, or shopping checkout

Getting kicked out of a site because you logged in somewhere else

The goal of WCAG 2.2.5 is to allow users to re-authenticate and pick up right where they left off without losing progress or starting over on tasks.
Note that if no user data or interaction is involved, like reading a blog post, this success criterion doesn't apply.
A user fills out page 6 of 7 in a job application form, entering name, job title, email, and experience. A session timeout occurs, forcing the user to log back in. After login, the application restarts at page 1 of 7, and the user's previously entered information  is lost.

## Why does it matter?

People with disabilities often need more time to complete tasks. Making them redo everything because of a timeout can be frustrating and unfair. Saving their progress helps everyone, especially users who are reading carefully, using screen readers, or navigating with assistive devices.
Imagine carefully filling out a long form and getting kicked out right before you submit it. Now imagine that happening just because you needed more time to read the questions or move between fields.
People who need extra time, whether because of a disability, reading speed, motor control, or even working with an interpreter, shouldn't be punished by losing their work when a timeout happens.

## Who is affected?

People with cognitive disabilities. People who are blind. People with motor impairments. People who are d/Deaf.

People with cognitive disabilities may need extra time to process information and complete tasks. If their session times out without saving progress, they risk losing everything they worked hard to understand and finish.
People who are blind and use screen readers move through content slowly, reading it line by line. Without saved progress, a timeout could mean redoing an entire form or losing their place completely.
People with motor impairments often rely on alternative input devices like eye trackers or switch controls, which naturally slow down task completion. Losing progress because of a timeout can make finishing tasks nearly impossible.
People who are d/Deaf may take longer to read and process written text if sign language is their first language. If a session times out, they could lose their place in the middle of a task.

## How to implement 2.2.5

This section offers a simplified explanation and examples to help you get started. For complete guidance, always refer to the official WCAG documentation.

### Save User Progress During Reauthentication

When a timeout occurs, make sure users' work is saved, either temporarily on the server or securely encoded into the re-authentication process. After re-authenticating, users should resume exactly where they left off.
The sections below cover different ways you can meet this requirement depending on your site's setup and the type of data you're handling.
Forms and activities to check include:

Job applications
College admission forms
Health intake forms
Shopping cart checkouts
Subscription sign-ups
Event registrations
Hotel or travel bookings
Writing a blog post or forum reply
Completing online quizzes or surveys
Changing account settings or personal information

#### Save Data Temporarily on the Server

Temporarily store entered data like form answers, cart contents, or draft messages until the session is restored.
This relies on the concept of auto-saving, where the server holds onto the user's data. After they log back in, the site reloads the form or activity with the previously saved input.
A user fills out an event registration form with their name and phone number. When a session timeout occurs, the server automatically saves the entered information. After re-logging in, the form is restored with the previously entered name and phone number, and it says, "Saved Draft Restored."
#### Pass Data Through the Login Page

Pass data securely through the re-authentication page, so nothing gets lost even if you can't or don't want to store it server-side.
This method requires that you pass the data securely through the re-login page using hidden fields or encrypted tokens. This way, even sensitive info like credit card numbers stays protected and doesn't have to be stored on your servers.
A user begins filling out an event registration form. After a session timeout, the entered data is encrypted and passed securely to the login page through hidden fields. After re-logging in, the user's information is restored without loss.

## Conclusion

Security timeouts are important, but they shouldn’t cost people their hard work. Whether someone needs more time because of how they read, navigate, or interact with your site, saving their progress during reauthentication helps keep the experience fair and frustration-free.

## Related Success Criteria

