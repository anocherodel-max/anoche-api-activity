#RESTful API Activity - Rodel Anoche

## Best Practices Implementation

**1. Environment Variables:**

- Why did we put `BASE_URI` in `.env` for our routes?
  -Answer: This is to keep the codes flexible and allows different values for development.

**2. Resource Modeling:**

- Why did we use plural nouns (e.g., `/dishes` )for our route?
- Answer : Plural names like /dishes represents the compilation of resources, this makes the API look clearer.

**3. Status Codes:**

- When do we use 201 Created vs 200 OK?
- Answer : We use 201 when we do POST request and creates a new resource, while 200 is for successfull request that does not create a new resource.

- Why is it important to return `404` instead of just an empy array or a generic error?
- Answer : Showing a 404 tells the client that the resource does not exist, which gives a clear feedback instead of just showing an empty result or screen.

**4. Testing:**

- (Paste a screenshot of a successful GET request here)
