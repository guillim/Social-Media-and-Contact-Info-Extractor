## What does Email ✉️ & Phone ☎️ Extractor do?
This email and phone extractor allows you to scrape any website for contact information. That's right - any website 💪

Just enter a URL, and the crawler will begin to extract info and click on links (“a” anchors). These are some of the types of information that this contact details crawler can extract:

-   Email
-   Phone numbers (from phone links or extracted from text)
-   LinkedIn
-   Twitter
-   Instagram
-   Facebook

## Why do I need this scraper?
Email ✉️ & Phone ☎️ Extractor might be handy for your marketing and sales teams, whether you are just getting started with your company and looking to build up a database of potential clients or you are an established business and want to grow your network.

## How much will this scraper cost me?
The Apify Free plan will give you 10,000 results, the Personal plan will give you 100,000 results, and the Team plan will deliver 1 million results!

Check out [Apify pricing](https://apify.com/pricing) to see which plan is right for you.

## How to scrape contact details from any website
If you want to read more about this scraper, its functionalities, and its setup, you can find a [step-by-step tutorial](https://blog.apify.com/contact-information-scraper-7104cb0df25e/).

## Personal data and the legality of scraping contact information
You should be aware that your results might contain personal data. Personal data is protected by GDPR in the European Union and by other regulations around the world. You should not scrape personal data unless you have a legitimate reason to do so. If you're unsure whether your reason is legitimate, consult your lawyers. You can also read this Apify blog post on the [legality of web scraping](https://blog.apify.com/is-web-scraping-legal/).

## What will the results look like?
This actor stores its results into the default dataset associated with the actor run. You can then download the results in formats such as JSON, HTML, CSV, XML, or Excel. For each page crawled, the following contact information is extracted (examples shown):

- **Emails**
  ```
  alice@example.com
  bob.newman@example.com
  carl+test@example.co.uk
  ```
- **Phone numbers** - These are extracted from phone links in HTML (e.g. `<a href='tel://123456789'>phone</a>`).
  ```
  123456789
  +123456789
  00123456789
  ```
- **Uncertain phone numbers** - These are extracted from the plain text of the web page using a number of regular expressions. Note that this approach can generate false positives.
  ```
  +123.456.7890
  123456789
  123-456-789
  ```
- **LinkedIn profiles**
  ```
  https://www.linkedin.com/in/alan-turing
  en.linkedin.com/in/alan-turing
  linkedin.com/in/alan-turing
  ```
- **Twitter profiles**
  ```
  https://www.twitter.com/apify
  twitter.com/apify
  ```
- **Instagram profiles**
  ```
  https://www.instagram.com/old_prague
  www.instagram.com/old_prague/
  instagr.am/old_prague
  ```
- **Facebook profiles or pages**
  ```
  https://www.facebook.com/apifytech
  facebook.com/apifytech
  fb.com/apifytech
  https://www.facebook.com/profile.php?id=123456789
  ```
