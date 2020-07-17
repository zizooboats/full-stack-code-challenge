# Zizoo Code Challenge

## Goal

Create a single web page rendering search results similar to https://www.zizoo.com/en/search/

## Tasks

- Create simple react component for a search listing card based located in this repo.
- Request search results from a GraphQL API for all **active** boats.
- Render the results using the API response and the react component.
- Create a basic filtering solution for boat length (< 15 OR >= 15) and boat year (< 2010 OR >= 2010).
- Bonus (not mandatory): Instead of a static boat photo, implement a photo-slider.

## GraphQL details

- Endpoint: https://sls-sandbox.zizoo.com/graphql
  - _See the schema in the endpoint above. (GraphQL Playground)._ ☝️

## Test submission process and evaluation

- Upload a zip file containing the solution’s source code to [Greenhouse](https://greenhouse.io). `Do not include the node_modules folder`.
- Provide a `README` file containing instructions on how to run your application.
- The search result page should be accessible using the path http://localhost:[PORT]/search
- The solution will be evaluated for functionality, UI/UX and coding style *In that order*.
- *Important* Pixel perfect implementation is not a priority.

## Estimated solution Time

4-6 hours

## UI Design
![](design.png)
