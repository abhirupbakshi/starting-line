# MasaiSchool-CW-17-1-23-finishline.com

# Finish Line
Finish Line, Inc. is an American retail chain that sells athletic shoes and related apparel and accessories owned by JD Sports. The company operates 660 stores in 47 states and Puerto Rico, mostly in shopping malls, as well as Finish Line-branded athletic shoe departments in more than 450 Macy's stores. On June 18, 2018, the company was acquired by multinational retailer JD Sports after the completion of its merger at a price of $13.50 per share in cash.

[Deployed Link](https://stirring-griffin-705e95.netlify.app/)

A [finishline.com](https:www.finishline.com) clone for MasaiSchool's CW project

# Tech Stack Used:
* HTML
* CSS
* Java Script

# Each product contents:

* id: "ID of the product"
* img: "Image of the Product"
* name: "Name of the product"
* brand: Nike|Jordan|Adidas|New Balance|On|Converse|Under Armour|Fila
* rating: {avg: "Rating out of 5", count: "No of people who have rated"}
* price: "price of the product"
* trending: "Trending status - true or false value"
* gender: women|men|girls|boys
* type: [shoe|clothing, (if it's show) running|casual|formal|slippers || (if it's clothing) Bottom|jacket|swetshirt|jeans|socks]
* size: (if it's shoe) 6.0|6.5|7.0|7.5|8.0|8.5|9.0|9.5|10.0|10.5|11.0|11.5|12.0|12.5|13.0|14.0|15.0|16.0|17.0|18.0 || (if it's clothing) S|M|L|XL|XXL
* description: "some description"
* review: [{user id: "review"}, {user id: "review"}, ...]

# Each user contents:

* id: "User ID"
* email: "Email of the user"
* name: "Name of the user"
* password: "Password of the user"
* cart: [{id: "product id", quantity: "product quantity"}, ...]
* given-rivews: [product id, product id, ...]

API Documentation:

* base_url/ : Returns all the products
* base_url?gender="gender name"&type="product.type[0], product.type[1]" ...etc: Query Parameters, only for genders, types,  brands or single products(identified by ids)

## Security: 
The website uses encryption and secure connections to protect the user's personal and payment information. It also implements standard security measures to protect against data breaches and unauthorized access.

## Support: 
The website provides a contact page with an email address and a phone number where users can reach out to the website's support team with any questions or issues. The website also includes a FAQ page and a knowledgebase where users can find answers to common questions.

Overall, this website provides a comprehensive e-commerce platform that is easy to use, well-designed, and secure. It provides all the necessary features for an e-commerce website and it is designed to provide a great user experience for the customers.
