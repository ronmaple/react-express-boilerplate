#### Personal use
- create-react-app boilerplate proxied to an express server
- concurrently runs both the react and express servers on 'npm dev' command
- create-react-app hosts its modules within its own development server,
    therefore to avoid having to deal with CORS for API calls, 
    a proxy to the express PORT is implemented.
