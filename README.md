
# Password Reset System from Hell

## Overview

This project implements a **Password Reset System** with a deliberately chaotic user experience designed to simulate frustration and randomness, hence the name "from Hell." The interface guides users through a three-step password reset process while introducing unpredictable delays, random errors, shifting password requirements, and subtle visual glitches to create a stressful but secure experience.

## Features

- Multi-step password reset flow:

1. Email address entry
2. Verification code input \& new password creation
3. Confirmation and login with new password
- Dynamic password complexity rules that randomly change during interaction.
- Randomized error messages to simulate system instability.
- Visual glitch and shake animations triggered at high "chaos" levels to frustrate but entertain users.
- "Chaos Indicator" showing system stability percentage, which decreases as the chaos level increases.
- Help modal with troubleshooting tips for users encountering issues.
- Loading spinner and simulated network/API delays to add realism.


## User Interface Design

- Modern, responsive layout with a gradient background and a white centered container.
- Accessible form inputs with clear labels and password rule hints.
- Progress indicated by step dots at the top of the form.
- Smooth fade-in animations between steps.
- Color-coded messages for errors, warnings, and successes.


## Technical Details

- Written entirely in HTML, CSS, and vanilla JavaScript.
- Uses CSS variables for primary colors and easy theme modification.
- JavaScript handles state management, UI updates, simulated API calls, random events, and animations.
- Chaos level state governs error frequency, glitch effects, and password rule changes.
- Modular code structure with clear separation of UI elements and logic.


## How to Use

1. Enter your email address and request a reset code.
2. Enter the received code along with a new password that meets the current complexity rules.
3. Reset your password and then log in using the newly created password.

## Known Issues (Intentional)

- Random failures and misleading success messages simulate a frustrating experience.
- Password rules may change mid-process to confuse users.
- Glitches and shaking effects can be distracting but add to the chaos theme.

---

## Customization

- Password complexity rules can be modified in the `passwordRules` array in the script.
- Error messages can be updated or extended in the `errorMessages` array.
- Chaos behavior thresholds and effects are adjustable via the `chaosLevel` logic.

---

## Support

If you encounter issues, click the "?" icon for help. Troubleshooting tips are provided in the help modal for common problems like browser compatibility, spam folder checks, and password requirements.

---

