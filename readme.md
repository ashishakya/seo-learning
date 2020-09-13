# SEO FOUNDATION:
## 1. Introduction to SEO
It is the practise of increasing the number and quality of visitors to website by improving rankings in the algorithmic search engine results.

Types of SEO:
* On page SEO
    * It relates to the content of your website.
    * Eg: Use of HTML elements
* Off page SEO
    * It helps strengthen the infuluence and relaionship of your website  with other websites.
    * Eg: Backlinks
* Technical SEO
     * It relates the non-content elements of the website.
     * Eg: Page speed

## 2. On-page SEO
- On page SEO consists of all the elements of SEO that you can control best.
- On page SEO should be done even if you rank #1 in the search because it is an ongoing process.

SEO factors which have direct or indirect ranking effects:
 - Website should be crawlable
 - User friendly urls
 - Well targeted content
 - Keyword optimisation
 - Website optimisation
 - HTTPS
 - Image optimisation
 - Readibility and UX
 - CTR
 - Mobile friendliness
 - Quality outbound links-
 - Website structure

## 3. Seach Engine working
- Indexer categories the sites then,
- SEO defines the ranking. 

## 4. Google Seach Console
- Incase of new website, it lacks prper backlinks. Then how does the google crawls this website?
- In such case, we register our website info into `GOOGLE SEACRH CONSOLE`. So that google could link our website and crawl the content. 

## 5. On Page SEO Factors (Keyword)
Keywords can be `PRIMARY` OR `SECONDARY`.

Some on-page SEO factors:
- Title tag (Page Title, It consists of `PRIMARY KEYWORD`)
- Description
- H1 tag (It consists of `PRIMARY KEYWORD`,  `Indirect ranking factor`)
- Formatted Text
- Outgoing links
- URL (domain, subdomain, folder name and page name)
- `Alt` tag
- Content

## 6. Meta title and description SEO
Element of title tag and best practises:
|||
|---|---
|Length| 50-60 character|
|Keywords|Use keywords in first 25%-40%|
|Uniqueness|Make sure the title is unique for each page |
|Use of action words|Eg: get, take, boost, learn, make, go |
|Title and branding|  `Primary Keyword | Secondary Keyword | Brand Name` |
|Description| 155-160 character summary that describes the content of a web page|


## 7. Write title and description practically

Best practise:
 `Primary Keyword | Secondary Keyword | Brand Name` 
Eg:
`Learn digital marketing in Kathmandu| SEO course| XYZ Tech`

Dont use marketing oriented text in description. For example: Get 50% off for students

Rather include CTA (Call to action). Eg: Want to learn digital marketing.

## 8. How to install Google Analytics with Google Tag Manager

## 9. Mobile friendly Website

- Mobile friendly test ( `https://search.google.com/test/mobile-friendly`)

## 10. Importance of H1 Tag
- To structure the content

Rules of using HEADING:
- It is usually the most visually notable content of the page.
- Use only one `h1` tag per page.  Crawler gives priority to h1 tag. When more than one such tags are used, the weightage is distributed.
- It can be 20-70 characters.
- Use a focused long-tail keywod on your `h1` tag.
- Answer user intent with your `h1`- 

## 11. How to write the Perfect `H1` Tag

- `SCREAMING FROG` for analysis the crawler

## 12. Canonicalization Tag

### Canonical Tags:
If you have the same or similar content available under different URLS, you can use canonical tags to specify which version is the main one and thus, should be indexed.

Eg: Having AMP and no AMP versions of a page
(example.com/page and amp.example/page )

Eg: having separate printable versions of a page
(eg: example.com/page and example.com/print/page)


### Canonical tags implementation

``<link rel='canonical' href='https://domain.com/url'/>``

The `rel=canonical` tag in action. Here, it indicates that the page on which this tag appears should be treated as a duplicate of the specified URL.

Note:
- Use one canonical tag per page.
- The canonical tag is a page-level meta tag that is placed in the HTML header of a website.

## 13. Robots.txt file

- A robots.txt file tells search engines where they can and can't go on your site
- Search spider arrives at a website with a pre-determined "allowance" for how many pages it will crawl (or, how muuch resources/time it will spend, based on  a site's authority, size or reputation)
- Sometimes you dont want certain page to be crawled and indexed due to certain reasons.
- Basically, `robots.txt` file is placed in the root directory. 

`Can also be tested using GOOGLE SEARCH CONSOLE`

## 14.Site map and its types    
- Simple xml file which defines the complete structure of a website.
- It helps in the proper resource utilisation of the crawler. 
- `XML sitemap` is for crawler whereas `HTML sitemap` is for users.

|XML Sitemap|HTML Sitemap|
|--|--|
|It is specially written for search engine spiders. A search engine spider can quickly and easily extract all the importance pieces of information about the site by looking at the XML file.|It enables lost users to find a page on the site that they are looking for.|

## 15. How to create sitemap for website

- Basically, `sitemap.xml` and `sitemap.html` files are placed in the root directory.
- Sitemap can be generated from `xml-sitemaps.com`
- Register the url of your websitte's sitemap in `Google Search Console` 

## 16. What is DA and PA 

### DA
- DA stands for Domain Authority
- Score ranges from 0-100 on 100-point logarithmic scale higher number means greater ability to rank.
- It is best used as a comparative metric
 - Actually based on `Link Profile`
 - It not no link with `GOOGLE`


### PA
- PA stands for Page Authority
- Score ranges from 0-100 on 100-point on logarithmic scale
- PA considers factor like `DOMAIN AUTHORITY`
- Also based on `LINK PROFILE` and other SEO factory.
- To improve page authority try to get external links from other high authority websites.

The stats of DA and PA can be views from google extension known as `MOZ` 

## 17. 301 and 302 redirection

### 301 Redirection
- Url has been permanently moved to another URL
- 301 redirect passes between 90-99% of link equity (ranking power) to the redirected page. (NEw url wont have any backlinks, hence when 301 redirection is carried out, all the seo value of previous url will be transfered to the new one)
- Implemented when you want to move all or the SEO value to the destination URl affter the source has changed permanetly.  

Eg: 
- When you want to update the domain permanently. (From www.example.com to www.example-updated.com)
- changing the sites protocol permanently. (From http://example.com to https://example.com)


### 302 Redirection
- It indicates that a URL has been temporarily moved to another URL.
- Search engines dont immediately pass pageranks to the destination url.
- It does not indicate that the destination url should be indexed.
- It can be used in cases of A/B testing
- For recurring temporary content

## 18. SEO friendly URL
- Use the keyword in the URL. (Use of permalink:customisable url; use of slug) 
- Never use special characters like &. These characters are not SEO friendly.
- Connect URL to the page title. (Not matching the exact but there should be some connection)
- Avoid automated numberic labels.
- Characters in a URL should be lowercase.
- Indirectly urls can help in `BACKLINKING`.

## 19. alt in SEO
- Known as alternative attribute or alternative description.
- Alt tag will be displayed if the image file cannot be loaded.
- It provides better image context/desciption to search engine crawlers, helping them to index an image properly. 

Desired format:

- Tyo to focus on describing the image as it is.
- Keep it optimum in the length.
- Use pirmary key
- Avoid keyword stuffing.
- Dont use `image of`, `photo of` keywords

## 20. SSL certificates
- On Aug 6,2014, Google concluded that websites with an SSl certificate would get an added advantange in the `Search Engine Results Pages (SERPs)`.
- It acts as a direct ranking factor for SEO.

### Types of SSL certificates:
- Single domain SSL certificates - not work for any sub domain (blog, website)
- Multi domain SSL certificates
- Wild card SSL certificates - covers all domains on a single root domain.
- Organisational SSL certificates. Works as single domain, also authenticate organisation related details
- Extended SSL
-  certificates (basically linked with BRANDING)

## 21. What is SEARCH INTENT
- It is the `WHY` behind the search query.

### Types of Searches
- Informational
    - Eg: What is digital marketing
- Navigational
    - Eg: facebook login
- Transactional
    - Eg: Buy JBL speaker
- Commercial
    - Eg: Anroid vs apple
    - Eg: offers on android
- Local searches
    - Eg: Restaurant near me
    - Eg: Burger near me
    - This search intent is basically satisfied by `GOOGLE MY BUSINESS`.

## 22. Difference between Keywords and queries

|Keywords|Queries|
|--|--|
|Basicaly used by marketers|Used by end users|
| |Queries lead to keywords. The queries used by users are later converted into target keywords by the marketers for rankings. |

## 23. SEOquake 
- Google extension for various SEO Stats.
- Cant be fully reliable to these tools.

## 24/25/26,27. Links Building and Link Earning. Link value in SEO

## 28. EAT in SEO
- EXPERTISE
- AUTHORITY
- TRUST

## 29. Generate keywords idea
- `ANSWER THE PUBLIC` (https://answerthepublic.com/)

## 30. Pogosticking
- When a users queries some keywords in search engines. The search engine provides a `SERP (Search Engine Request Page)`. 
- The use then clicks at first result and visits the landing page.
- Within a second, or so, the user again travels back to the `SERP` .
 
 **THIS ACTIVITY IS ACUTALLY CALLED AS `POGOSTICKING`.**
 
 This action provides false information to google. This action indicates that the user is not satisfied which the result.
 
 ## 31. Pogosticking vs Bounce Rate
 |Pogosticking|Bounce Rate|
 |--|--|
 | Pogosticking basicaly deals with SERP.|User lands on the landing page of the website. However it does travel any further of the website, i.e, the user does not travels any dipper to the website through its internal links. The user then exits the page. This is known as `BOUNCE.`|
 |User is not satisfied with the result|User may or may be satisfied.|

## 32. Which Meta Tag not to use in SEO 
The following tag does not have any SEO advantages.
### Tags to ignore
- Google does not use the keywords Meta tag in web rankings as on September 21, 2009.
- **Revisit after**: This HTML tag is a command to robots to return to a page after a specific period. 
    - `<meta name="revisit-after" content="7 days"/>`
- **Cache Control**: This tag allows web publishers to define how often a page is   cached. Generally, these are not required. We can simply use the HTTP header instead of HTML tags.
- **Geo meta tag:** Google does not use Geo meta tags to rank pages. Use hreflang + normal geo-targeting any kind of geographical SEO advantages.
- **Expiration/Date:** `<meta http-equiv="Expires" content="Fri, 28 April 2020:23:59:59 GMT">`

## 33 What Types of Backlinks Ignores and Why

- Spammy links on Comments-Blog Community
- Non- revalent reciprocal link Exchanges
- Automation tools like: Scrapebox and or Xrumer
- Buying link from Fiver
- Link velocity
## Reference
- Youtube Channel: WsCube Tech (https://www.youtube.com/playlist?list=PLjVLYmrlmjGdHM0dnLAs4OBkoopizGMBB)




 