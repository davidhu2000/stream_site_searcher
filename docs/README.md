# Eezee

## Background

Over the past few years several digital streaming services have gained considerable traction. Due to licensing restrictions the full library of multimedia is now fragmented across these platforms, which puts a burden on the user to find the location of the content they seek. The resulting nuisance has created a gap in the market that we intend to fill. Our initial goal is to provide a digital service that queries all relevant streaming services and informs the user where to find the content they seek. For instance, if a Netflix user wants to watch "The Shawshank Redemption" they will log into their account only to find that the film isn't available. Instead of wasting their time looking through other streaming application one at a time, the user can visit Eezee and immediately see which platforms contain their desired content. Future Implementation will include logic to recommend films to the users based on their previous searches and current search.

## Functionality & MVP

With this mobile app, the user will be to:
- Sign up and login user.
- User profile page
- Search for movies and be able to see which streaming service has those movies.
- Utilize Netflix and Amazon APIs to query for movies.
- Create React Native mobile application.

## Wireframes

#### Home screen
The landing screen features a simple, intuitive UI with a search field, collapsible menu, and the application logo.

![home_screen][home_screen]

#### Search movies by title
The search feature allows users to search for movies by title with an autocomplete function, and displays which streaming services (if any) the movie is available on, with links directly to the site.

![search][search_results]

[All wireframes][wireframes]

## Technologies & Technical Challenges

The mobile application will be create using the following technologies:

- React Native to create frontend interface
- Redux to manage state
- Rails as backend API

We will also utilize several public APIs to fetch the necessary information.

- Netflix API
- Amazon Prime Video API

## Group Members & Work Breakdown

Our group consists of three members: Alex Sherman, David Hu, and Tom Ogasawara

Alex's primary responsibilities will be:

- Setup react native skeleton.
- Setup basic html layouts.
- Setup bootstrap for mobile responsiveness.
- Create form component for signup and login.
- Setup react redux cycles for signup and login.
- Create navbar component.

David's primary responsibilities will be:

- Setup Netflix API.
- Setup Amazon API.
- Implement autocomplete feature.
- Create user profile component and search component.
- Create redux cycle for profile and search.
- Setup genre database and many-to-many association with user.

Tom's primary responsibilities will be:

- Setup Rails skeleton.
- Create results index and film show page components.
- Setup frontend redux cycle for index and show components.
- Setup backend user authentication.
- Setup backend APIs.
- Setup user database structure.

## Implementation Timeline

**Day 1**: Set up basic React Native / Rails project skeleton
- [ ] Complete `package.json`.
- [ ] Setup frontend skeleton.
- [ ] Setup backend skeleton.

**Day 2**: Learn how to create React Native App and how to deploy to Apple Store
- [ ] Create a functional mobile application with basic layouts and styling.
- [ ] Create backend structure for signing up and login.
- [ ] Create the react/redux cycle for login/signup page.

**Day 3**: Set up all the necessary React components and external APIs
- [ ] Create search, result index, film show page, and navbar components.
- [ ] Create the necessary redux cycle for those components.

**Day 4**: Set up all external APIs.
- [ ] Setup Netflix API.
- [ ] Setup Amazon API.

**Day 5**: Install mobile app to phones and test all functionalities.
- [ ] Ensure mobile responsiveness for every page.
- [ ] Test all features and check for errors.

## Future Implementation
- Utilize Electron to create a desktop application.
- Create the full-stack web application.
- Add additional APIs, such as Hulu, HBO Now, etc.
- Add more search functionalities to query other types of data, such as riding sharing services.
- Add user recommendation based on prior searches and related movies to current search.
- Setup Facebook Login.

[home_screen]: ./wireframes/home_screen.png "Home Screen"
[search_results]: ./wireframes/search_results.png "Search Results"
[wireframes]: ./wireframes
