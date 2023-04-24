# interview-bootstrap

## Requirements
- [Node.js](https://nodejs.org/) > 16
- [NPM](https://www.npmjs.com/) > 8

## Getting started

Install dependencies
```bash
$ npm install
```

Run dev server
```bash
$ npm start
```

Run tests
```bash
$ npm test
```

## Challenge

🚨 We're starting a new coding bootcamp and our website is down! We need you 🫵🏻 to save the day and implement and new form so users can signup!

Luckily our backend is up and running so you only need to worry about the frontend.

### Create the form

We need a form that supports the following inputs:
- Required first name
- Required last name
- Required birthdate (with a date picker)
- Optional text field on reasons why the user wants to apply to the bootcamp with an upper limit of 30 chars

We also want our users to feel reassured that they've successfully submitted their applications, so don't forget to add a submit button that displays a thank you message when clicked. Would be nice to include their first name in the message! ❤️ You can use any mechanism you feel is appropriate to trigger the notification, Window `alert()` method is a common one.

### Let's make it look nice

What would be of Academia de Código without our cool style and branding? 😎

Here's what our designers would like us to do:
- All elements should be aligned to the left
- All input fields should be vertically aligned (on top of each other)
- All input fields should be labelled (if not already)
- Add some padding of `36px` all around the form
- Paint the form background with our primary colour (`#e41f1a`)

Last but not least, we need to make sure they know they're applying to the best bootcamp in Portugal, possibly the best in the planet as well, so make sure you render our logo above the form. You can find the logo svg in [here](./src/logo.svg).

### We sure it's working?

We can never be sure it's properly working until we test it. We want you do add a small test to make sure our form is being successfully rendered.

You can add your test to the [App.test.js](./src/App.test.js) file. We're currently using [React Testing Library](https://testing-library.com/), so if you're not familiar with it you may want to take a look at the docs.
