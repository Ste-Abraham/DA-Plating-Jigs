# DA Plating Jigs

The DA Plating Jigs project is a simple effective website. It is based on a manufacturing company in Birmingham. It has 3 separate pages and an additional thank you page following the submission of a contact form. The website allows customers to locate DA Plating via a map on the ‘contact us’ page, submit a query via an enquiry form and learn what services are available via the ‘about us’ page.

![Responsive site on different devices](/assets/readme-images/responsive-img.png)

The above screen shot was generated in [Am I Responsive Site](https://ui.dev/amiresponsive) which shows the responsiveness of the site. It demonstrates how the site changes when using different devices. Using media queries ensured the website never lost its structural integrity across the variety of devices.

## UX

### Site Purpose

The purpose of the DA Plating website is to provide a quick and clear overview of DA Plating, a Midlands based company providing specialised metal jig manufacturing. The site provides details of the services they provide and serves as a convenient way for potential customers to send enquiries.

### Site Goal

The goal of the website is to drive new business into the company giving users an overview of DA Plating history, their services, benefits and contact information.

### Audience

The target audience for this site are 25-60 year olds, typically already within the fabrication industry, interested in metal joinery and specialist jig manufacturing.

### Design

The DA Plating Jigs website follows a simple design that is user friendly. The colour scheme comprises of mainly three colours:

- shade of blue: #45b6fe
- shade of white for the font: rgb(248, 247, 242)
- shade of grey: #989898

The typography used for the website was found on google fonts and imported from here. Font name is Montserrat.

![Font sample from google fonts](/assets/readme-images/googlefont-monts.png)

## Features: Existing

The Nav menu used to navigate through the site was designed to be large and clear, visible at the top of screen on every page. The white stands out against the blue background, whilst complimenting each other well. All the pages are linked to the relevant html pages to be able to navigate through the site as designed. The logo serves as an alternative method to return to the home page in addition to clicking the ‘home’ button.

![Screenshot of Nav Menu](/assets/readme-images/nav-menu.png)

The ‘contact us’ page includes a contact form feature which allows potential customers, existing customers, suppliers and other stakeholders to find company information and get in touch with a unique query. All the fields have the required element, meaning you cannot submit an empty form. The email field designed to require a valid email address in order to submit.

![Screenshot of Form](/assets/readme-images/contactus-form.png)

The footer was designed for users to locate all the linked social media accounts, which also includes LinkedIn, as users may be interested in work opportunities and employee information. All the links open to a new tab for optimal user experience.

![Screenshot of Footer](/assets/readme-images/footer.png)

The iframe feature is a map linked to Google Maps, which allows users to locate DA Plating in real time, moving around the pinned area.

![Screenshot of map](/assets/readme-images/map-iframe.png)

## Features: Future

A future development will be the FAVICON feature as this will improve user experience for visitors navigating between different tabs.

Another feature to develop in future is a toggle menu. A toggle menu is designed to collapse down when switching to smaller devices. A burger icon improves screen real estate and is aesthetically pleasing for users.

A testimonial page will showcase completed jobs, but this will come over time as the company needs to collate these examples.

## Testing and Bugs/solutions

### Manual Testing

Manual testing was carried out on the deployed website in two browsers, chrome and safari. All the features displayed as designed across both. For example, all the fonts showed up as expected, the links worked and opened in new tabs as expected, and all of the images loaded in place as expected

The responsiveness of the site was checked from 280px which is for a Galaxy Fold, up to tablet and desktop size. The site looks good in all formats, and nothing is lost on any of the screens.

The form was also manually tested to ensure it was functioning correctly. There was an initial issue with the code producing an error when submitting. This was due to the form leading nowhere (as it is a test). To resolve this, a thankyou.html page was created for forms to be sent to. This made the code pass and now it is showing no errors.

![Screenshot of thank.you message](/assets/readme-images/thank-you.png)

### Validator Testing

<https://validator.w3.org/>

An error was found on the index.html page due to putting a div in the wrong place this is now resolved and the page passes.

![Screenshot of index passing testing](/assets/readme-images/index-html-check.png)

Errors were found on the aboutus.html page as a width property was put inside the img tag, causing it to fail. The width property was removed by putting it into the css style sheet instead. The about us page now passes.

![Screenshot of about us passing testing](/assets/readme-images/about-us-html-check.png)

As discussed in the manual testing section, the contatcus.html page failed as the form was being sent nowhere, resulting in an error code. This was resolved by making a thankyou.html page, which resulted in the page passing the validator with no errors.

![Screenshot of contact us passing testing](/assets/readme-images/contact-html-check.png)

<https://jigsaw.w3.org/css-validator/>

The style.css sheet was run through the css jigsaw validator, resulting in one error where a space was put between a value and the rem unit. The space was removed which corrected the issue and the page now passes with no errors.

![Screenshot of css style sheet passing testing](/assets/readme-images/css-check.png)

The website has a great accessibility score achieved by running lighthouse in the devtools. It does highlight one way to increase the accessibility by having more of a contrast between font colour and background, however this is a slight improvement which wasn’t crucial and therefore will be considered for future developments.

![Screenshot of lighthouse score](/assets/readme-images/lighthouse-score.png)

## Unfixed Bugs

As far as I am aware, there are no unfixed bugs.

## Deployment

The website was coded in codeanywhere which provides a preview of the site. Once it was ready, the site was deployed GitHub pages - where a live version is available.

The steps to achieve this were:

- From my GitHub repository go to the settings tab.
- In this tab you will find the source section drop-down menu you have to select the Master Branch.
- When the Master Branch is selected you will see that the page will automatically refresh. A ribbon display will be there to indicate the deployment was a success.
- The link to my live site can be found here [DA Plating Jigs](https://ste-abraham.github.io/DA-Plating-Jigs/)

## Credits

The credits are as follows:

- Wildcard selector piece of code from Love running project.
- Inspiration for the form code was taken from Coders Coffeehouse learning content.
- The coding method for the Iframe map was taken from Coders Coffeehouse learning content.
- The Iframe code was obtained via google maps.
- Icons for footer the same process was followed love running project.
- Font awesome for icons.
- Google fonts for font.
- A lot of inspiration from love running walkthrough project and was using course materials.
- All images are taken from google images creative common license tool.
- Thank you to my mentor Spencer
