Google forms clone with advanced analytics and features; Capstone project for my undergrad CS course.

- domain by name.com
- smtp set up on mailgun  

TODO
1) add ai and vector embeddings for fast querying 
2) add signin with google
4) add captcha
6) make supabase session handling work throughout the app instead of relying on st.session_state
8) implement rls and dls in supabase tables
9) add functionality to edit forms and responses
10) figure out a way to add media files (profile pictures and pictures for forms and media in forms)
11) add actual use template functionality
12) add proper analytics with real data
13) enable search functionality in list forms
14) add functionality where user can start filling a form directly from published forms page
15) add sharing forms with a link functionality
16) add timer
17) add a sequence diagram for the whole infrastructure
18) add comparison with google forms for analytics
19) make a product page for the project
20) add better messages on the login/signup page - try to show the responses coming from mailgun to the user as well (eg. email doesnt exist)
21) shift form filling to st.experimental_dialogues
