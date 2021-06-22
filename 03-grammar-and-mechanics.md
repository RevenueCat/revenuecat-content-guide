 # <div align='center'> Grammar and Mechanics

To keep our content consistent, we adhere to the following grammar rules and mechanics. This guide will define our style for how we write technical documentation.

[Links](#links)
<br/>
[Click vs Select](#click-vs-select)
<br/>
[Italics](#italics)
<br/>
[Bold](#bold)
<br/>
[Capitlization](#capitalization)
<br/>
[Code in Text](#code-in-text)
<br/>
[Contractions](#contractions)
<br/>
[Dates](#dates)
<br/>
[Hyphens](#hyphens)
<br/>
[Numbers](#numbers)
<br/>
[Emojis](#emojis)
<br/>
[Writing About Revenuecat](#writing-about-revenuecat)
</br>

## Links

Write links that are descriptive and have meaning. Link descriptions should have words describing where they go and what content is there. It is best to use keywords from the linked page. Using descriptive links allows the reader to scan pages and assists with screen reading technologies. 

<pre>
❌  You will find more documentation <a href="url">here</a>.
</pre>
<pre>
✅  For additional information, review the <a href="url">Configuring Products</a> guide. 
</pre>
<br/>

## Click vs. Select

We use the word **select** instead of **click** when addressing our readers. This action is used agnostically across devices. 

<br/>

## Italics

In general, we don’t *italicize*. Only use this when defining a word/phrase or when referring to books, movies, and other full-length works.

<br/>

## Bold

**Bold** content is more accessible when scanning our documentation. Use this when referring to UI elements or when drawing emphasis to something. 

<br/>

## Capitalization

We use a couple of different capitalizations: title case and sentence case. 


### Headers/Titles - Title Case
Title case is when the first letter of every word except articles, prepositions, and conjunctions is capitalized.  

When writing titles and headers, we follow title case guidelines. 
<pre>
❌  Create an In-app purchase
 </pre>
<pre>
✅  Create an In-App Purchase
</pre>



### Other Content - Sentence Case 
Sentence case is when the first letter in the first word and proper nouns in a phrase are capitalized.


We write all other content (except tiles and headers) in sentence case. 
<pre>
✅  Capitalize the name of RevenueCat terms such as the Purchases SDK or Offerings. 
</pre>
<pre>
❌  We don’t capitalize words such as email, internet, etc. 
</pre>

### Referencing Other Companies
Honor the company by capitalizing their name and thier products the same way that they do according to their official website. 
<pre>
✅  In the Google Play Console.
</pre>

<br/>

## Code in Text

When writing code in the documentation, it’s best to separate the code from regular text.

### Large Code Blocks

For longer blocks of code, use a code snippet block to keep all of the code contained and formatted.

````Swift
✅  Purchases.shared.offerings { (offerings, error) in
    if let packages = offerings?.current?.availablePackages {
        // Display packages for sale
    }
}
````

### Small Code References 

For small code references, such as an SDK method or a parameter from a webhook event, always contain the code in backticks.

> ✅   The `getOfferings` method will fetch the Offerings from RevenueCat


> ❌  The getOfferings() method will fetch the Offerings from RevenueCat


<br/>

## Contractions

We like to keep our tone conversational, so we use contractions regularly. 

<br/>

## Dates

Spell out months and days of the week in either short or long form. 

### Short form:  Abbreviate to 3 letters, no period 
<pre>
✅  Mon, Tue, Wed - Jan, Feb, Mar
</pre>
### Long form: Spell out whenever other words frame the day or month
<pre>
✅  Saturday, April 17
</pre>

<br/>

## Exclamation Points

We love sharing our enthusiasm with an exclamation point! It can help keep communication light. Use it when needed. 

<br/>

## Hyphens 

### Email vs E-mail

We reference email without the hyphen.


### Sign -in/up vs Sign in/up 

When used as an adjective, it’s hyphenated. 
<pre>
✅  The sign-up page crashed
</pre>

When used as a verb, it’s two words.
<pre>
✅  Please sign in to your account
</pre>

### Log-in vs Login vs Log in

When used as an adjective or noun, it’s one word or hyphenated.
<pre>
✅  Enter your login (log-in) information
</pre>

When used as a verb, it’s two words.
<pre>
✅  Log in with your account
</pre>

<br/>

## Numbers 

When referring to numbers, it’s best to use digits instead of spelling out the word in most cases. This helps draw the eye of the reader to the critical content. 
<pre>
✅  The Apple subscription terms require users to cancel subscriptions at least 24 hours before the next renewal.
</pre>
When a number represents a generalization instead of a fact, spell out the word.
<pre>
✅  We have thousands of developers using RevenueCat.
</pre>

<br/>

## Emojis

Emojis are a fun way to add humor and visual interest to your writing but use them infrequently and deliberately.


<br/>

## Writing About RevenueCat 

When we refer to ourselves, we always capitalize the ‘R’ and ‘C’ and use ‘we’ not ‘it’.
