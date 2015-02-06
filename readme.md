<h1>Sample App using Mongo (Mongoose) / Express / Angular / Node</h1>

A Portfolio app which allows the user to enter his stocks in portfolio and see the list of stocks in his portfolio

The serverside code just exposes REST API to add and get the entities

/stocks GET
would get the list of stocks added by the user / avaialble in the DB

/stocks POST
would add the current stock sent in the body of the post api call

<h2>Add your stock</h2>

Description:
This component should allow the user to add a stock to his portfolio


User should be able to add a stock by entering
<ul>
    <li>symbol</li>
    <li>count / number of stocks</li>
    <li>purchase price</li>
</ul>
Responsiblities of the component
<ul>
<li>component should allow the user to enter the stock symbol</li>
<li>component should allow the user to enter the number of stocks</li>
<li>component should allow the user to enter the purchase price</li>
<li>component should allow the user to save the stock entry</li>
</ul>
