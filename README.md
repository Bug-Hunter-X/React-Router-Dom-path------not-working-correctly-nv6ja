# React Router Dom path="/*" Issue

This repository demonstrates a common issue encountered when using the `path="/*"` route in React Router Dom v6.  The catch-all route, intended to handle any unmatched paths, is not working correctly as expected.  While other routes function properly, this specific route fails to match correctly, leading to unexpected behavior or rendering issues.

## Steps to Reproduce

1. Clone this repository.
2. Run `npm install` to install dependencies.
3. Run `npm start` to start the development server.
4. Navigate to a URL that should trigger the `NotFound` component (e.g., `/incorrect-path`).

You will observe that the `NotFound` component does not render as expected.