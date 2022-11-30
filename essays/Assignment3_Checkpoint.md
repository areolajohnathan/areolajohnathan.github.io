---
layout: essay
type: essay
title: "Assignment 3 Checkpoint"
# All dates must be YYYY-MM-DD format!
date: 2022-11-29
published: true
labels:
  - Assignment 3
  - Checkpoint
  - Essay
---
<h4>1. Show what each page will look like. The pages do not have to be “functional” but the design should clear.</h4>
<p>
You can catch a glimpse of my non-functioning website <a href="https://youtu.be/netnsDvtAK8">here</a>.
</p>

<h4>2. Describe your design for your site’s shopping cart. That is, will it be a separate page that the user can view and edit, or will it be integrated into the product pages? If so, describe in detail how this will work on your site. Provide several examples of using the cart.</h4>
<p>
For my site's shopping cart, users will be directed to a separate page where they wil be able to view their cart and edit the quantities they desire.
</p>

<h4>3. Explain specifically how you will use sessions to manage your shopping cart. In particular, what shopping cart data will be stored in the session, what data format will be used (NOT what data type, but the format like with the data format used for your registration data). Use code examples showing what data structures (such as arrays and their objects) you will use to manage the shopping cart data and how they will be used in a session.</h4>
<p>
In the shopping cart, sessions will be used to store product data. Specifically, the quantity that the user wants to purchase. I will have my products categorized by product type so it would basically look like:
{
  Plungers: [2, 0, 0, 0, 0, 0]
  Air Fresheners: [1, 1, 1, 1, 1, 1]
  Toothbrushes: [1, 0, 0, 2, 0, 3]
}
Or something like that. With 6 products minimum required on each page, it will correspond with the correct place in the session quantity array.
</p>

<h4>4. How will you avoid access to your application when the user has not logged in or registered? What are the particular security concerns you must address?</h4>
<p>
The server will check for <i>existing cookies</i> for that user so it will know whether they have logged in or registered yet. When the user has not logged in or registered yet, they will not have access to their shopping cart. They will be redirected to the log in or registration page so they can either log in or register. When the user has successfully logged in, a cookie will be established for that user and only then can they access the shopping cart and therefore check out. A security concern would be someone gaining access to the user's account when the user is in a public space (a coffee shop for example) while they're using the restroom or something and they forget to lock their device. The established cookie will be set to expire after 5 minutes just in case the user is away from their device. Hopefully any suspects won't gain access to one's account in this time!
</p>

<h4>5. Upon a successful login, how do you provide personalization in your UI? Explain how you did or will do this (paste code if necessary)</h4>
<p>
When a user successfully logs in, their data will be stored into a cookie. Then, they will be able to see their full name in the shopping cart, invoice, and thank you page after they checkout. Their email address will aslo be displayed in the thank you page.
</p>

<h4>6. If you are working with partners, how will you split up the work in your team so that you are working in parallel as effectively as possible? That is, who is doing what and when?</h4>
<p>
I will not be working with a partner for Assignment 3.
</p>

<h4>7. How are you approaching Assignment 3 differently than Assignment 2?</h4>
<p>
With Assignment 3 I am making sure that I will start early, earlier than I did with Assignment 1 and 2 anyway. I will ensure that I tackle the assignment piece by piece, taking it slowly one day at a time as opposed to rushing during the end when it is due. I recall that for Assignment 3, that we can't turn it in late since it's toward the end of the semester and grades will be due immediately. So, I really have to get on it to get it in on time. Also, since the assignment will require us to use cookies and sessions to store data, I will have to shift my focus away from what I learned in Assignment 2 and bring in a fresh perspective when it comes to Assignment 3. Since it will be required to have 3 separate pages of products, I will need to change the theme of my store from just plungers to maybe a store full of bathroom products.
</p>

