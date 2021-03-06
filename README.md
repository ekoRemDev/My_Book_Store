# My_Book_Store

An Online Book Store created with [Node JS](https://nodejs.org/en/docs), [Express JS](https://expressjs.com/) and [MongoDB](https://docs.mongodb.com/).

<hr>

## Features

<ul>
	<li>User Registration</li>
	<li>Welcome mail on Registration</li>
	<li>User Login</li>
	<li>User Password Reset</li>
	<li>Password reset link sent to registered mail</li>
	<li>User Additon/Removal of Products</li>
	<li>User Addition to/ Deletion from Cart</li>
	<li>User Purchasing Products via a payment gateway implemented through <a href="https://stripe.com/">stripe</a></li>
</ul>

<hr>

## Steps and Prerequisites to Run Project

<ul>
	<li><a href="https://nodejs.org/en/docs/">Node JS</a> must be installed</li>
	<li><b>git clone</b> via <b>terminal</b>(for linux/mac) or <b>git bash</b>(for windows)</li>
	<li><b>cd</b> to the cloned repository</li>
	<li>Run <b>npm install</b> and all the dependencies mentioned in <b>package.json</b> will be installed inside <b>node_modules</b> folder</li>
</ul>

<hr>

## Database

[MongoDB Atlas](https://www.mongodb.com/cloud/atlas/lp/general/try?jmp=search&utm_source=google&utm_campaign=gs_apac_india_search_brand_atlas_desktop&utm_term=mongodb%20atlas&utm_device=c&utm_network=g&utm_medium=cpc_paid_search&utm_matchtype=e&utm_cid=6501677905&utm_asagid=80628974280&utm_adid=382247561728&gclid=EAIaIQobChMIp6n7g7GR5QIVSyUrCh30lws3EAAYASAAEgLRe_D_BwE) has been used to create a database cluster and was monitered via [MongoDB Compass](https://www.mongodb.com/products/compass). [Mongoose](https://mongoosejs.com/) was used to implement [Object Document Mapping(ODM)](https://www.quora.com/What-is-Object-Document-Mapping).

<hr>

## Email server

[SendGrid](https://sendgrid.com/) was used to send mails