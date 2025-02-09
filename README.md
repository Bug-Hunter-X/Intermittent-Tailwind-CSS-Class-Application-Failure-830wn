# Intermittent Tailwind CSS Class Application Failure

This repository demonstrates a bug where Tailwind CSS classes are not consistently applied to elements, even with seemingly correct configuration and build processes. The issue is intermittent and seems to affect specific classes more than others.  The bug.js file contains an example of the affected code, and the bugSolution.js file offers a potential solution involving a more explicit purge configuration or a more thorough check of CSS file loading.

## Steps to Reproduce

1. Clone this repository.
2. Run the necessary commands to start the development server (e.g., `npm run dev` if using a framework like Next.js or Vite).
3. Observe the inconsistent application of Tailwind CSS classes to the affected element. The element should have a red background and transition to blue on hover, but the behavior may be inconsistent.

## Potential Solution

The bugSolution.js file outlines a possible approach to fix this: adjusting purge options or checking your css files are being correctly loaded and used.