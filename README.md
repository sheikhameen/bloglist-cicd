Hello.

The structure of the project is as follows:

- `frontend/`
  - Contains the React frontend. This project is "built" and the build is then moved over to the `backend/` to be served.
- `backend/`
  - The backend contains the Express backend, that also serves our static React build.
  - The backend also has Jest tests.
- `cypress/`
  - This contains the e2e tests. It's placed in the root cuz it tests both the frontend and the backend.
