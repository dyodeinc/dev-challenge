# DYODE. Dev Challenges

## BigCommerce Proficiency Questions

#### These questions should be answered with real world solutions

1. Write a function with Stencil Utils that will return the contents of the cart object. With the response data, check if the a specific product exists in the cart. If true, then add a different product to the cart.
2. Using Front Matter, declare the following properties to be utilized in a new store page. What restrictions should be known when writing Front Matter?
   - 15 top seller products, loop through with handlebars to display the name and price in an HTML structure for a carousel plugin.
   - Cart, loop through with handlebars and display each item names and prices if more than 1 item exists.
3. Write your own Custom page template to display the 15 top seller products and cart HTML from question #2. What file structure would your template have to be in? What is required to insure local dev does not break?
4. Describe how you would add a javascript plugin.
5. Describe the importance of Page composition and why the `{{partial}}` and `{{block}}` helpers are useful.

## Frontend Challenge

Once you complete the challenge, you'll:

- You send us a github link to your repo and a public preview URL for quick access
  - Heroku, Netlify, GitHub pages are some free options for hosting
- We'll run `yarn install` and `yarn start` to view your result

### The Test

- Use a javascript framework to build out what you see in [this Figma link](https://www.figma.com/file/3LB4kjUhhXVN1cBU2QPIpu/DYODE-Developer-Test?node-id=0%3A1).
  - Acceptable frameworks: React, Next, Gatsby, Vue, Nuxt
- This should be built responsive using the mobile first philosophy.
- It contains two carousels, a hero carousel and a product carousel.
- Please find a good responsive carousel dependency to use.
- Please refrain from using any responsive libraries ie: Bootstrap, Material Ui, Foundation.

#### What we're looking for:

- How closely it resembles the original design
- How you organize your components
- Reusability
- How well your elements scale responsively
- An understanding of what the mobile first philosophy means
- A separation between javascript and scss.
