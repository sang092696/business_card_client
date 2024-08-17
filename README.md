# Business Card Generator

## NextJS frontend for FastAPI GraphQL backend with Supabase DB

- TailwindCSS for styling
- Uses Supabase Auth for Social Sign On
- Users can create a business card based on default cards displayed

### Structure

- Uses NextJS App directory
- Features a custom useResource hook to handle CRUD interactions with backend
- Two page app
  - index page and /gallery
- Supabase client component that can be imported to access the session
  - session is used to send authenicated requests to backend

### TODO 

- Use apollo client for requests 
- Refactor dyanmic route page
- Make form mobile friendly
- have digital gallery link to card page
- have slug randomize if not entered
