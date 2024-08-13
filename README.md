Type	Description
404	Renders page content that is shown to customers if they enter an invalid URL for the store.
article	Renders the article page, which contains the full content of the article, as well as an optional comments section for customers. This template is used for items like individual posts in a blog.
blog	Renders the blog page, which lists all articles within a blog.
cart	Renders the /cart page, which provides an overview of the contents of a customer’s cart.
collection	Renders the collection page, which lists all products within a collection.
customers/account	Renders the customer account page, which provides an overview of the customer’s account.
customers/activate_account	Renders the customer account activation page, which hosts the form for activating a customer account.
customers/addresses	Renders the customer addresses page, which allows customers to view and manage their current addresses, as well as add new ones.
customers/login	Renders the customer login page, which hosts the form for logging into a customer account.
customers/order	Renders the customer order page, which displays the details of a customer’s past orders.
customers/register	Renders the customer register page, which hosts the form for customer account creation.
customers/reset_password	Renders the password reset page, which hosts the form to reset the password for a customer account.
gift_card.liquid	Renders the gift card page, which displays the gift card issued to a customer upon purchase.

This must be a Liquid template.
index	Renders the home page of the store, located at the root URL (/).
list-collections	Renders the collection list page, which lists all the store's collections. This page is located at the /collections URL of the store.
page	Renders the shop’s pages, such as About us and Contact us.
password	Renders the /password page, which is a landing page shown when you add password protection to your online store. This page includes a message that is editable by merchants, and the password form for customers to gain access to the store.
product	Renders the product page, which contains a product's media and content, as well as a form for customers to select a variant and add it to the cart.
robots.txt.liquid	Renders the robots.txt file, which is hosted at the /robots.txt URL. This file tells search engines which pages can, or can't, be crawled on a site.

This must be a Liquid template.
search	Renders the /search page, which displays the results of a storefront search.
metaobject	Renders metaobject pages, such as “artists” or “authors”. To render each metaobject entry as an individual page, the metaobject definition must have the web page capability.



https://shopify.dev/docs/storefronts/themes/architecture/templates