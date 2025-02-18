# React Router Dom v6 Nested Route Parameter Issue

This repository demonstrates a common issue encountered when working with nested routes and parameters in React Router Dom v6. The problem arises when nested routes fail to receive the expected parameters passed from their parent routes. The solution involves correctly structuring the nested routes and leveraging the `useSearchParams` hook to access parameters effectively.

## Bug Description

The original `App.js` (bug.js) showcases the incorrect implementation where nested routes do not receive parameters. The corrected version (`AppSolution.js` - bugSolution.js) provides the solution.

## How to Reproduce

1. Clone the repository.
2. Navigate to the project directory.
3. Run `npm install` to install dependencies.
4. Run `npm start` to start the development server.
5. Observe the incorrect behavior in the original implementation.
6. Compare with the corrected implementation and observe the proper functionality.

## Solution

The solution involves using the `useParams` hook correctly within the nested route component to access the parameters passed from the parent route.  Additionally, ensuring correct route path definitions is crucial.

## Technologies Used

* React
* React Router Dom v6