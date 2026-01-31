# Sign-Up Form (HTML/CSS Basics)

Live Preview:

A simple sign-up form project built to practice:
- Form structure and accessibility basics (labels, inputs, required fields)
- Client-side input validation (names, phone number length, passwords)
- Flexbox layout (two-column form rows)
- Positioning in CSS (relative/absolute positioning and layering elements over an image)

This project was inspired by common “landing page + signup form” layouts and focuses on building strong fundamentals rather than using libraries or frameworks.

---

## Features

### ✅ Form Inputs
- First Name
- Last Name
- Email
- Phone Number
- Password
- Confirm Password

### ✅ Validation Practice
This project includes basic client-side validation to ensure:
- **First name / last name** meet minimum length and aren’t blank
- **Phone number** matches expected length (e.g., 10 digits)
- **Email** uses proper email format (via HTML input type + optional JS checks)

> Validation is implemented with a mix of HTML attributes (like `required`, `minlength`, `type="email"`) and JavaScript (for custom rules and messaging).

### ✅ Layout + CSS Positioning Practice
- Left-side background image fills its container
- Logo banner layered on top of the image using `position: absolute`
- Content column on the right uses a constrained width so text wraps nicely on large screens
- Responsive behavior (layout stacks on smaller screens)

---

## Tech Stack

- HTML5
- CSS3 (Flexbox + positioning)
- JavaScript (validation + interaction)

No frameworks.

---
