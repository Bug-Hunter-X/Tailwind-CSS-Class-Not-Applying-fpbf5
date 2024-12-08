# Tailwind CSS Class Not Applying Bug Report

This repository demonstrates a bug where a Tailwind CSS class fails to apply despite correct usage and configuration. The class `bg-red-500` is not being applied to the element, even after purging CSS and restarting the development server.

## Bug Reproduction

1. Clone the repository.
2. Install dependencies (if any).
3. Run the development server (e.g., using `npm run dev` if applicable).
4. Observe that the element with the `bg-red-500` class does not have the expected red background.

## Solution

The solution involves ensuring that the Tailwind directives are properly configured within your HTML file, the CSS file is being imported correctly, and that the Tailwind plugin is set up to compile and process the classes correctly.  See `bugSolution.html` for a corrected version.