Web Development Projects -- HTML5 and CSS3
A collection of three beginner-level web development projects created
using HTML5 and CSS3. The projects demonstrate webpage
structure, styling, navigation between page sections, image display,
card layouts, and basic responsive design.
Author
- Name: THOKA NAVEEN
- Roll Number: 26001251
- Branch: CSE (AI & ML)
- Section: 06
- University: DR. RVR NRI UNIVERSITY
- Course: B.Tech – CSE (AI & ML)
- Academic Year: First Year

1. Project Title
Web Development Projects -- HTML5 and CSS3

This repository contains three small webpages:
- Wedding Invitation
- Food Ordering Website -- Foodie
- Travel Destination -- Welcome to Goa
2. Project Description
This project collection demonstrates the basic process of creating
webpages with HTML and styling them with CSS.

The Wedding Invitation page presents wedding information in a decorative
invitation-card layout. The Foodie page displays restaurant information,
food menu cards, prices, a promotional offer, and customer reviews. The
Goa page introduces a tourist destination and organizes information
about places to visit, activities, and local food.

These are front-end demonstration webpages. The supplied project
material does not describe a server-side application, database, payment
system, or working order-processing system.
3. Project Objectives
- Understand the basic structure of an HTML webpage.
- Use HTML elements to organize headings, paragraphs, images, links,
  lists, and sections.
- Apply CSS to control colors, fonts, spacing, borders, backgrounds,
  and layouts.
- Create simple webpage designs for different purposes.
- Use links to navigate between sections of a webpage.
- Practice card-based layouts and CSS Flexbox.
- Apply basic responsive styling for smaller screens where included.
4. Features
A. Wedding Invitation
- Displays a wedding invitation heading and welcome message.
- Shows placeholder names for the couple and a "Weds" label.
- Displays the event date, day, and venue.
- Includes wedding image areas and a closing message.
- Uses an ivory invitation card, gold border, rounded corners, and
  shadow.
- Includes a CSS media query for screens narrower than 480 pixels.
B. Food Ordering Website -- Foodie
- Displays Foodie branding and navigation links for Home, Menu,
  Offers, and Reviews.
- Shows restaurant information, cuisine type, rating, and delivery
  estimate.
- Displays three menu cards: Pizza, Burger, and Biryani.
- Shows the listed prices: ₹249, ₹179, and ₹229 respectively.
- Includes an "Order Now" link on each menu card; these links navigate
  to the Offers section.
- Displays a 20% first-order promotional offer.
- Includes customer review text, a footer, and an HTML audio control.
- Uses CSS Flexbox with wrapping and a media query for smaller
  screens.
Note: The "Order Now" links are section-navigation links in the
supplied code. The project does not document a functional checkout or
order-placement system.
C. Travel Destination -- Welcome to Goa
- Displays a welcome heading and a Goa beach image.
- Includes a short introduction to Goa.
- Lists places to visit: Baga Beach, Fort Aguada, and Dudhsagar Falls.
- Lists activities: water sports, watching the sunset, and exploring
  beaches.
- Lists foods to try: Goan Fish Curry, Prawn Curry, and Bebinca.
- Uses a centered content container with a white background and blue
  border.
- Applies styling to headings, paragraphs, images, and list items.
5. Technologies Used
  Technology / Resource               Purpose
  HTML5                               Structures webpage content,
headings, sections, links, images,
and lists.

  CSS3                                Controls colors, typography,
spacing, borders, shadows, layouts,
and responsive styling.

  External image URLs                 Supply images referenced by the
webpages.

  Local image file (m.jpg)          Referenced by the Wedding
Invitation page; the file was not
included in the supplied report.
Local audio file (audio.mp3.mp3)  Referenced by the Foodie page; the
file was not included in the
supplied report.
No JavaScript framework, backend language, or database is identified in
the supplied project report.
6. Project Architecture
The projects use a simple front-end structure:
1. The HTML file defines the content and page elements.
2. The linked CSS file controls the visual appearance and layout.
3. Images and audio are loaded from external URLs or local files
   referenced in the HTML.
4. The browser renders the HTML and applies the CSS.
User
  |
  v
Web Browser
  |
  +---- HTML pages (content and structure)
  |
  +---- CSS stylesheets (appearance and layout)
  |
  +---- Referenced images / audio resources
  |
  v
Rendered Webpages
There is no documented backend, database, API, authentication, or
payment architecture.
7. Project Folder Structure
The report identifies the following source filenames. A suggested
repository layout is shown below; place each file in the corresponding
folder and ensure the stylesheet references match the actual filenames.
web-development-projects/
|
+-- wedding-invitation/
|   +-- naveen.html
|   +-- abcd.css
|   +-- m.jpg                 # Required local image; not supplied
|
+-- foodie/
|   +-- abcd(1).html
|   +-- style(1).css          # Report's CSS source filename
|   +-- audio.mp3.mp3         # Required local audio; not supplied
|
+-- goa-travel/
|   +-- pdr(1).html
|   +-- ddd(1).css             # Report's CSS source filename
|
+-- README.md
Important filename checks before running:
- The Foodie HTML refers to style.css, while the report labels the
  supplied stylesheet source as style(1).css. Rename the CSS file to
  style.css or update the HTML link.
- The Goa HTML refers to ddd.css, while the report labels the
  supplied stylesheet source as ddd(1).css. Rename the CSS file to
  ddd.css or update the HTML link.
- The Wedding Invitation HTML refers to m.jpg. Add that image to the
  same folder or change the image path.
- The Foodie HTML refers to audio.mp3.mp3. Add that audio file to
  the same folder if the audio control is to play a local file.
The folder structure above is a suggested organization, not a claim that
the original upload already contains these folders.
8. Installation Steps
These are static HTML and CSS webpages. No package installation or build
process is documented.
1. Install or use a modern web browser, such as Google Chrome,
   Microsoft Edge, or Firefox.
2. Download or clone this repository.
3. Extract the project files if they were downloaded as a ZIP archive.
4. Check that each HTML file and its linked CSS file are in the correct
   locations.
5. Resolve the filename differences listed in the Project Folder
   Structure section.
6. Add the missing local image and audio resources if available.
7. Keep an internet connection available for externally hosted images.
9. How to Run the Project
You can open each HTML file directly in a web browser.

For example:
- Open wedding-invitation/naveen.html for the Wedding Invitation
  page.
- Open foodie/abcd(1).html for the Foodie page.
- Open goa-travel/pdr(1).html for the Goa travel page.
Alternatively, open the project folder in Visual Studio Code and use a
local development server or an HTML preview extension if one is
installed.

No Python, Node.js, or other runtime command is required by the supplied
HTML/CSS project description.
10. Input and Output Details
Input
These webpages do not describe a form-based data-entry workflow. Their
displayed content is written directly in the HTML source.
  Project                             Content provided in the source
  Wedding Invitation                  Couple-name placeholders,
invitation text, date, day, venue,
and image references.

  Foodie                              Restaurant details, menu item
names, prices, offer text, review
text, and image/audio references.
Welcome to Goa                      Destination description, places to
visit, activities, food list, and
beach image reference.
Output
  Project                             Expected browser output
  Wedding Invitation                  A centered decorative invitation
card with wedding details and image
areas.

  Foodie                              A restaurant webpage with
navigation, restaurant details,
three menu cards, an offer,
reviews, footer, and audio control.
Welcome to Goa                      A Goa information page with a beach
image and sections for places,
activities, and food.
The outputs above describe the webpage structure from the supplied
source and report. They are not claims of newly captured browser
screenshots.
11. Screenshots / Output Images
Add genuine screenshots of each webpage to the repository when
available. The supplied report does not contain clean browser
screenshots for all three pages, so no new screenshots are claimed here.

Suggested screenshot locations:
screenshots/
+-- wedding-invitation.png
+-- foodie.png
+-- welcome-to-goa.png
After adding the screenshots, you can display them in this section
using:
### Wedding Invitation
![Wedding Invitation webpage](screenshots/wedding-invitation.png)

### Foodie – Food Ordering Website
![Foodie webpage](screenshots/foodie.png)

### Welcome to Goa
![Welcome to Goa webpage](screenshots/welcome-to-goa.png)
Replace these image paths with the actual screenshot files you add. The
wedding reference image described in the report is a photograph of a
laptop screen, not a clean browser capture.
12. Future Enhancements
The following are possible improvements, not features confirmed in the
current project:
- Add meaningful alternative text to images that do not already have
  it.
- Verify and correct all local image, audio, and stylesheet paths.
- Validate the HTML and CSS and correct markup or stylesheet errors.
- Test the pages on different screen sizes and browsers.
- Improve keyboard navigation, color contrast, and accessibility.
- Add a functional order form and order-processing workflow to Foodie.
- Add backend and database support if persistent data or real orders
  are required.
- Replace placeholder couple names with final event details.
- Add genuine browser screenshots to document the final webpage
  appearance.
13. Conclusion
This project collection demonstrates the use of HTML5 and CSS3 to create
three different types of webpages: a wedding invitation, a food
information and menu page, and a travel destination page. It provides
practice in structuring webpage content, applying styles, arranging
elements, using images and links, and introducing responsive layouts.
Checking resource paths, validating the source, and testing the pages in
a browser will help improve the completeness and reliability of the
projects.
14. Author Details
  Detail              Information
  Author          THOKA NAVEEN
University      DR. RVR NRI UNIVERSITY
Course          B.Tech -- CSE (AI & ML)
Academic Year   First Year
Project Type: Beginner-level Front-End Web Development
Technologies: HTML5 and CSS3
