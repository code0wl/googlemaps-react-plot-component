## Close.io acceptance exam

This exam was to show if Oscar Lodriguez would be able to perform at Close.io's quality standards.

#### Start the project locally with
`npm start`

#### List of urls (test with postman or chrome)
Server starts at port 3000, can be configured in server.js
GET/ http://localhost:3000/addresses 
GET/ http://localhost:3000/address/id (zerobased starting at 0)
POST/ http://localhost:3000/addresses (creates new item(s))
PUT/ http://localhost:3000/addresses/id (creates new item(s))
DELETE/ http://localhost:3000/addresses/id (removes item id, has no interface can be tested with Postman)

PUT and DELETE do not have a user interface. Did not have time to complete assignment for the design, but this works inside of postman or any other REST tester

#### Delivery
- Add Address
- CRUD using node middleware (express)
- Modern UI with animations
- Address list search
- Mock server with json api responds
- Flexbox grid and styles
- Shims and polyfills for older browsers
- Markers
- Animate to position
- Rich user data
- Custom design
- Indicators of application state (how many users currently tracked
- Autosuggestion map correlation 
- Did not get to user test the UI; So, made a video of how it works 

#### On the roadmap
- Address validation with updating PUT requests
- Unit tests
- Continuous Integration
- Custom input UI for non webkit browsers
- Code documentation
- Notification system for updating events

#### Total time spent on exam is 14 hours. 
- concept and design 4 hours
- Architecture planning and project buildstreet with webpack/react and linting 2 hours
- construction 8 hours
- 5 minutes on tutorial video