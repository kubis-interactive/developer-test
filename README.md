# Kubis Web Developer Test

This test is conceived to test skillset ranging from junior developer to full stack.

# You have

- [data.json](data.json) which contains a product list (fields described below)
- EURO as currency for price attributes ( &euro; )
- index.php as application entry point

| Field   | Description  |
|---|---|
| *id*  | Unique product system identification   |
| *name*  | Product name |
| *description*  | Product description, can have html tags  |
| *slug* | Product url key |
| *base_price* | Manufacturer price, without taxes |
| *price* | Final product price, with taxes |
| *sku* | Unique product code |
| *visibility* | Product visibility: **1** = not visible, **2** = visible on listing, **3** = visible on search **4** = visible on listing & search |
| *status* | Product status: **1** = active, **2** = disabled |
| *categories* | Array of categories the product is part of |
| *categories.\*.id* | Unique category system identification |
| *categories.\*.name* | Category name |
| *categories.\*.slug* | category url key |
| *tax_class* | Tax identificator that sets additional product price changes: **1** = 9% tax, **2** = 19% tax |
| *main_image* | Product main image |

# You can

- Add any css/js file
- Import or use any libraries as long as you add reference to them
- Use the following languages: HTML, CSS (SASS, LESS), PHP, Javascript
- Use bundlers: Webpack, Mix, Gulp, Grunt, etc
- Use frameworks: Laravel, Codeigniter, Zend, VueJS, Angular, React, Bootstrap, Tailwind, Bulma or others
- Make mistakes
- Be creative
- Improve this test

# You must

- [ ] Build a search script that traverse [data.json](data.json) and returns results based on user input
- [ ] Build an UI interface that use the script above
- [ ] Clean coding style

# You may consider (grants extra points)

- [ ] Build or use an advanced searching algorithm
- [ ] Search script still returns results even if there are spelling errors
- [ ] Search script returns related results if nothing is found for user input
- [ ] Interface has working filters based on [data.json](data.json) fields
- [ ] Interface has working sorting options
- [ ] Search and show results without leaving or refreshing the page
- [ ] Store user's recent searches
- [ ] Multilanguage interface
- [ ] Have a docker file that spawns a virtual server to run your application

## Side note

The test will not be used commercially by Kubis or by third party


<br />
**Break a leg**