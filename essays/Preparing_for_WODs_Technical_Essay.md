---
layout: essay
type: essay
title: "Preparing for WODs Technical Essay"
# All dates must be YYYY-MM-DD format!
date: 2022-10-03
published: true
labels:
  - WOD
  - Essay
---
<h4>BrowserHistory6</h4>
<p>
The BrowserHistory6 WOD required us to take BH3 and split it into separate web pages. We had buttons that would display the appropriate browser picture when moused over. And when clicked, it would take us to the correct webpage. This WOD was definitely harder than the previous 3 browser history WODs for me, with the number of attempts reaching 4. I thought it would come a bit easier since I've had some experience in my pocket doing the previous WODs. I especially had trouble with the buttons and trying to configure them. I had trouble with placing double quotes and single quotes. I confused myself often during the attempts.
</p>

<h4>SmartPhoneProducts1 with Variables</h4>
<p>
The SmartPhoneProducts1 with Variables WOD called for the use of variables. The purpose was to eliminate the hard code for the product information when displaying it. We also had to separate the product information from the rest of the code, which made it cleaner to look at and in turn, easier to change if we needed to. We moved the product data from being in the HTML file with the main code, to the JS file, on its own. I missed the Rx time by just a few minutes during my first two attempts because I failed to read all of the directions and kept forgetting what to do. But other than that, this WOD was fairly easy because it mainly consisted of us copying and pasting the code from the ITM352 GitHub site into VSC (in the right places).
</p>

<h4>Invoice1</h4>
<p>
We had to create a sales receipt for the Invoice1 WOD, and in this receipt contained 5 different products. We utilized expressions and variables to compute the different values like price, ext. price, subtotal, tax and total all dynamically. This meant that if one value changed, the following values that included this particular value would change too. This was as opposed to hard coding each value. Since this was a lengthy WOD, I made sure to reread the directions multiple times so I knew what I had to do. This made it easier for me and I was able to achieve the Rx time after my second try. Calculating the different values at the top of the document came easy, what gave me trouble was getting it to display in the table properly. Little mistakes made some of the table rows not display at all.
</p>

<h4>Invoice2</h4>
<p>
For Invoice2, we had to make a copy of Invoice1 and add an algorithm to determine shipping cost. After making a new row for shipping in the sales receipt, we had to define it in at the top where the rest of our variables were. Shipping was based on how much the subtotal was, and to determine the correct cost of shipping, we used if, else if, and else statements. Because there were 3 tiers of shipping costs, we set the first tier (0-50 dollars) to be in the if statement, then set the second tier (50-100 dollars) to be in the else if statement, and then anything over a 100 dollars would go into an else statement. It was basically saying that if the subtotal was below $50, it would cost $2. Or else, if was above $50 but below $100 then the shipping would be $5, and anything else (above $100), shipping would equal to the 5% of the subtotal. This WOD went pretty smoothly for me.
</p>

<h4>SmartPhoneProducts2</h4>
<p>
For the SmartPhoneProducts2 WOD, we used a loop to get rid of the repeating code to display products. We displayed the products by pulling from the data as opposed to hard coding each section. This is so the main HTML file looks cleaner and data can be changed dynamically. My SmartPhoneProducts1 was done differently so I ended up grabbing a copy from the GitHub site, this made it easier to reference the screencast when I needed help. I had trouble configuring the string templates, I was having trouble with the eval() part because instead of ${eval("name" + i)}, I put ${eval("name" + 1)}. I guess the directions confused me a bit. After the first try, I watched the screencast and realized my mistake and was able to get the Rx time during the second try.
</p>

<h4>Summary of WODs</h4>
<p>
In the WODs we've done so far, we had to utilize a number of different code like loops, string templates, eval, and if/else if statements to name a few. As we progressed through the different WODs, we've learned to display data by pulling it from variables. In the beginning the variables were inline with the main code, to moving it to the top of the document, and then finally moving it all into one JS file. This makes it so the main document is cleaner to look at, and the variables and values can all be changed dynamically. There's no need to repeat hard code. It's interesting to see how many different ways there are to go about doing things while coding but overall I've learned that it's best to keep it simple and clean always.
</p>

<h4>Conclusion</h4>
<p>
To better prepare for future WODs, I shall go over the material and resources provided to me in the respective modules multiple times so I know what the material means and how I can apply it to the WOD. I could also look up any terms that may not be clear at first, so I can further my understanding of it. To help me remember what I read and learn, I should put go back to each WOD and put comments to explain what was done at certain parts, and maybe add definitions for terms to help me recall better. After immersing in the material, I should then read the directions of the WOD over and over again so I know what to expect when I'm actually doing the WOD. Watching the screencast for the respective WOD and trying to understand the professor's explanation will help me as well.
</p>