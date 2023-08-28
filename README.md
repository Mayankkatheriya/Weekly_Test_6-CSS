# Weekly_Test_6-CSS
## Hosted Link: https://mayankkatheriya.github.io/Weekly_Test_6-CSS/
![image](https://github.com/Mayankkatheriya/Weekly_Test_6-CSS/assets/128832286/701044ac-7fdb-42f3-9eb3-9191b0038468)

HTML:\
The code you've shared is an HTML template for a webpage. It includes sections for the document type declaration, head content, and body content.

In the "head" section, there's a link to an external CSS file called "styles.css" for styling the webpage. The title of the webpage is set as "Electric Scooters." Google Fonts are imported to use the "Roboto" font family.

Inside the "body" section, there are two empty "div" elements with class names "black" and "grey," likely used for styling or layout purposes.

The webpage's header is defined using the "header" tag. Within the header, there's a navigation bar containing links for "Electric Bikes," "Skateboards," "Scooters," "Unicycles," "Accessories," and "More Info." Navigation icons, including a user icon and a shopping cart icon, are also present.

The "FontAwesome" library is integrated into the webpage using a script tag, allowing the use of FontAwesome icons throughout the page.

CSS part:\
Universal Reset:

Resets margin, padding, and box-sizing for all elements.

Body Styles:

Sets the font family to "Roboto" or a sans-serif font.\
Hides the default scrollbar in webkit-based browsers.

Typography Styles:

Sets a strong font weight (700) for headings and labels.\
Sets a regular font weight (400) for paragraphs, links, and buttons.\
Sets text color to black.\
Removes text decoration for links.

Styling Blocks:

Defines a black block with full width and 2.3vh height.\
Defines a grey block with full width and 1vh height.

Header Styles:

Sets a sticky header with white background and 0.8 opacity.\
Positions the header at the top with a high z-index.\
Uses flex layout for the navbar.\
Defines styling for the navigation logo and items.

Navbar Styles:

Defines the navigation logo's size, width, and margin.\
Adds a hover effect to the logo image.\
Defines styling for the navigation menu items.\
Defines an opacity class for items.

Individual Item Styles:

Sets margin and vertical alignment for header items.\
Defines hover styles for links and icons in header items.

Navigation Icons:

Sets font size for navigation icons.\
Adds a hover effect to navigation icons.
\
\
\
![image](https://github.com/Mayankkatheriya/Weekly_Test_6-CSS/assets/128832286/5d0816b1-cc07-401d-a65c-c7f7d5bfcacb)
![image](https://github.com/Mayankkatheriya/Weekly_Test_6-CSS/assets/128832286/765e6da1-a20c-45f8-9940-4c5a8a164b91)

HTML:\
The code represents a section with a class name "hero," likely used for showcasing featured content on a webpage. The section consists of three rows, each containing two columns.

In the first row:

The first column contains an image with a caption. The caption includes an image of the "Boosted Boards & Scooters" logo and a text message indicating that "Boosted Revs and Accessories are still In Stock!" The column also includes a background image showcasing a Boosted electric scooter.

The second column has a similar structure. It includes a caption with the "Super73" logo and a text message, "Boosted USA x Super73, Join the RIDE!" This column also contains a background image showcasing a collaboration between Boosted USA and Super73.

In the second row:

The third column contains an image with a caption featuring the "Evolve Skateboards" logo and the text "Boosted USA has Teamed Up with Evolve Electric Skateboards." The column also includes a background image showcasing an Evolve electric skateboard.

The fourth column is similar to the previous columns. It includes a caption with the "Minimotors Electric Scooters" logo and a message, "Boosted USA is now introducing Minimotors Electric Scooters." The column's background features an image of Minimotors electric scooters.

In the third row:

Four images are displayed side by side. These images appear to be press logos, possibly indicating coverage or partnerships. The logos include "Electrek," "TechCrunch," "Popular Mechanics," and "Wired."

This "hero" section is likely meant to highlight various collaborations, products, and press coverage related to Boosted USA and its range of electric scooters and skateboards.

CSS:\
Row 1:

Flex layout for the first row.\
50% width columns, max width 1472px.\
Image with caption, centered content.\
Caption includes paragraph and image.\
Hover effect scales image.

Row 2:
Black background row with centered content.\
Flex layout with gap and padding.
\
\
\
![image](https://github.com/Mayankkatheriya/Weekly_Test_6-CSS/assets/128832286/a3745a0d-ee40-4f97-9909-e85c00b83d0a)
![image](https://github.com/Mayankkatheriya/Weekly_Test_6-CSS/assets/128832286/5a69498c-1854-437c-b55d-dff56046bb6a)
![image](https://github.com/Mayankkatheriya/Weekly_Test_6-CSS/assets/128832286/3869620b-36b4-4eb3-9a90-b00145e82f98)
![image](https://github.com/Mayankkatheriya/Weekly_Test_6-CSS/assets/128832286/6ccf9aff-705e-43ed-bd8f-a0ab61aa186b)

HTML:\
The code represents a section with a class name "middle-hero," likely used for highlighting different products and their features. The section is divided into two main parts.

In the first part ("mid-content"):

Three heading tags (h1) are used to display a series of product names, including "Boosted Revs," "Super 73 bikes - Evolve Skateboards," and "Minimotors Dualtron / Speedway."

A paragraph with class "p1" contains a message emphasizing the appreciation for multiple brands: Boosted, Super73, Evolve, and Minimotors.

Another paragraph with class "p2" provides information about the products available from Boosted USA, including electric bikes, Evolve Skateboards, and Minimotors Electric Scooters.

A final paragraph with class "p3" informs that bikes, boards, and scooters are currently in stock and ready for shipping.

In the second part ("big-card"):

Three "big-card1" divisions are present, each containing information about a different product along with an image.

The first "big-card1" contains information about Super73 Electric Bikes. The content includes a heading, a description of the bikes' features and customization options, and a "Shop All Bikes" button.

The second "big-card1" focuses on Minimotors Electric Scooters, highlighting build quality, performance, and range. The content includes a heading, a description, and a "Shop All Scooters" button.

The third "big-card1" presents Evolve Skateboards, describing the high-performance and quality of the boards. The content includes a heading, a description of the brand's origin and focus, and a "Shop All Boards" button.

Each "big-card1" division is structured with an image and content, and they collectively provide information about the benefits and features of Super73 Electric Bikes, Minimotors Electric Scooters, and Evolve Skateboards. The section aims to showcase the unique qualities of each product and encourage users to explore and shop for these items.

CSS:\
Mid Content Styling:

Full width with vertical margin.\
Vertical and horizontal centering.\
Heading with centered text.\
Styled paragraphs with varying widths.\
Styled links and clickable elements.

Big Card 1 Styling:

Flex layout with spaced content.\
Hover effect for images.\
Transition for image scaling.\
Content section with spacing.\
Button with styling and hover effect.\
These styles create a responsive layout with centered content, styled paragraphs, images with hover effects, and a button with hover interaction for a visually engaging mid-content section and a card layout.
\
\
\
![image](https://github.com/Mayankkatheriya/Weekly_Test_6-CSS/assets/128832286/b2c14ac0-904c-4738-b56f-3279f0a52a7a)

HTML:\
The code defines a section with a class name "scooter." This section is meant to highlight and promote high-performance electric scooters. It consists of a container with content divided into headings and a button.

A heading level 3 (h3) states "High-performance."

A heading level 1 (h1) displays "Electric Scooters."

Another heading level 3 (h3) describes the versatility and enjoyment of using electric scooters for various activities such as cruising on campus, commuting to work, and running errands.

A button with the label "Shop Now" is included, encouraging users to explore and potentially purchase electric scooters.

The section's purpose is to attract attention to the range of high-performance electric scooters available for different use cases and prompt users to take action by visiting the online store ("Shop Now") to view and purchase the products.

CSS:\
Scooter Section:

Full viewport height and responsive background image.\
Centered content with flex layout.\
Background image settings: no repeat, centered position, cover size.\
Text alignment set to center.

Container Styles:

30% width, adaptive height.\
Top margin for spacing.

Heading Styles:

Different font sizes and line heights for h3 and h1.\
Margins for vertical spacing.

Button Styles:

Width, padding, and border radius for styling.\
Font size and line height for text.\
White text on a colored background.\
Hover effect changes background color.\
These styles create a visually appealing section with a background image, centered content, and a button with hover interaction.\
\
\
\
![image](https://github.com/Mayankkatheriya/Weekly_Test_6-CSS/assets/128832286/5d98f6f7-3bab-4efa-a2d0-3b23cec41066)

HTML:\
In the provided code, there is a section with the class name "video." Within this section, an iframe element is used to embed a YouTube video player. The embedded video has the source URL "https://www.youtube.com/embed/1eLZBg9Qdbw?si=cACcXMAMd7joiQwN" and its title is set to "YouTube video player." The iframe element has various attributes to control its behavior:

"frameborder" is set to "0" to remove the frame border around the embedded video.

"allow" attribute specifies a list of permissions for the embedded content. These permissions include accelerometer, autoplay, clipboard write, encrypted media, gyroscope, and picture-in-picture.

"allowfullscreen" allows the video to be played in fullscreen mode.

The purpose of this code is to embed and display a YouTube video within the specified section of a webpage. Users can interact with and play the video directly on the webpage.

CSS:\
Video Section:

Full viewport height.\
Padding for spacing.

Video iframe:

Full width and height to cover the section.\
These styles create a responsive video section with full viewport height and padding, and the embedded video within the iframe takes up the entire available space.
\
\
\
![image](https://github.com/Mayankkatheriya/Weekly_Test_6-CSS/assets/128832286/b738b155-6bab-4faa-8f10-f0178a7839e8)

HTML:\

In the provided code, there is a section with the class name "skateboard." Within this section, a container is used to structure the content. The content includes:

An h3 element with the text "All Terrain + Street."\
An h1 element with the text "The Best All Terrain Skateboard!"\
Another h3 element with the text "2-IN-1."\
A <button> element with the text "Shop Now."

This section seems to be promoting an all-terrain skateboard that is designed for both street and off-road use. The "Shop Now" button likely links to a page where users can learn more about and purchase this skateboard. The use of headings and the button creates a visually appealing way to present the product and encourage users to take action

CSS:\
Skateboard Section:

85vh height, responsive background image.\
White text color for contrast.\
Background image settings: no repeat, centered position, cover size.\
Centered content with flex layout and alignment.

Container Styles:

30% width, adaptive height.\
Top margin for spacing.

Heading Styles:

Different font sizes and line heights for h3 and h1.\
Margins for vertical spacing.

Button Styles:

Width, padding, and border radius for styling.\
Font size and line height for text.\
White text on a colored background.\
Hover effect changes background color.\
These styles create a visually appealing skateboard section with a responsive background image, centered content, and a button with hover interaction.
\
\
\
![image](https://github.com/Mayankkatheriya/Weekly_Test_6-CSS/assets/128832286/51152962-051c-4d71-9dd0-af2dd14e7d51)
![image](https://github.com/Mayankkatheriya/Weekly_Test_6-CSS/assets/128832286/c8a0302a-f572-4a0c-8882-7ec0db8489a3)

HTML:\
The "Accessories" section showcases a range of accessories for Boosted boards, Evolve skateboards, and Minimotors electric scooters. Each product category is presented within its respective "boosted" section. For each accessory, there's an image, a name, and a price displayed using "acc" divisions. This layout allows users to explore and purchase accessories tailored to their preferred product type.

CSS:\
Heading Styles:

Centered heading with hover effect.\
Hover changes color and cursor, with a transition.

Miscellaneous Section:

Flex layout with horizontal scrolling.\
Top margin for spacing.

Accessory Styles:

Images with full width.\
Styled paragraphs for text.\
These styles create a boosted section with a centered heading, a horizontal-scrolling accessory section, and styled accessory elements.
\
\
\
![image](https://github.com/Mayankkatheriya/Weekly_Test_6-CSS/assets/128832286/ebc5b713-5b88-479d-aec2-f06283776540)

HTML:\
The "Subscribe to our Newsletter" section invites users to sign up for the latest updates. It features a form with the following components:

Title: "Subscribe to our Newsletter"

Description: "Sign up to get the latest on sales, new releases and more ..."

Email Input: Users can enter their email address (required).

Consent Paragraph: By submitting the form, users consent to receive marketing emails. They can unsubscribe anytime using the SafeUnsubscribe® link.

Service Note: Emails are serviced by Constant Contact.

Subscribe Button: Users can click this button to sign up.

Logo: A Constant Contact logo is displayed at the bottom.

This form allows users to stay informed about new offers and releases from BoostedUSA.

CSS:\
Form Section:

Full width with background color.\
Flex layout for centering content.

Container Styles:

25.5rem width, centered.\
Spacing for top and bottom margin.

Heading Styles:

Font size and line height.\
Margins for vertical spacing.

Title Styles:

Font size and line height.\
Margin for spacing.

Label Styles:

Margin for bottom spacing.\
Adds asterisk before label text.

Input Styles:

Font size and line height.\
Full width, specific height, padding.\
Border, box shadow, outline, margin.

Paragraph Styles:

Font size and text alignment.

Underline Class:

Text decoration and cursor.\
Margin for spacing.

Button Styles:

Full width, specific height, border radius.\
Font size and line height.\
White text on a colored background.\
Hover effect changes opacity.

Logo Styles:

Background color with centered content.\
Specific width and height, padding, and border radius.\
Cursor pointer for interaction.

Logo Image Styles:

Full width image with auto height.

Links Section:

Black background color.\
These styles create a responsive form section with proper spacing, labels, inputs, buttons, and logo. The section provides a structured and user-friendly form for input.
\
\
\
![image](https://github.com/Mayankkatheriya/Weekly_Test_6-CSS/assets/128832286/7194dbfd-dbf7-42e4-8d6c-0856d5d9cc0f)

HTML:\
The "black-sec" section includes four "card" elements, each containing:

An image depicting different aspects of Boosted and Evolve products.
A title summarizing the key feature.\
A brief description highlighting the benefits.

These cards emphasize the following aspects:

"Go Fast": Highlighting premium performance and next-level experience.\
"Go Further": Emphasizing an extended range of up to 40 miles.\
"Go Anywhere": Showcasing the versatility to skate on various terrains.\
"Built to Last!": Stating the durability and reliability of the products.

CSS:\
Black Section:

Full width with black background.\
Flex layout for centering content.\
Gap and padding for spacing.

Card Styles:

23% width cards with centered content.\
Flex column layout with wrapping.\
Spacing between cards and at the bottom.

Card Image Styles:

30% width images within cards.

Card Heading and Paragraph Styles:

White color for text.\
Different font sizes and line heights.\
Centered text alignment for paragraphs.\
These styles create a black section with centered and wrapped cards containing images, headings, and paragraphs. The section presents content in a clean and organized layout.
\
\
\

![image](https://github.com/Mayankkatheriya/Weekly_Test_6-CSS/assets/128832286/23a4d1ce-a5d9-4635-95b9-09ea65d9044b)

HTML:\
The first content area includes an image and a list of links for exploration:

An image with a source URL pointing to an electric skateboard image.

A "div" with the class "explore" containing:
An "h2" heading with the text "Explore."\
An unordered list ("ul") with several list items ("li") representing different exploration options such as electric skateboards, scooters, accessories, FAQs, warranty, etc.

The second content area is about Boosted USA:

A "div" with the class "aboutUSA" containing:

An "h2" heading with the text "About Boosted USA."\
A paragraph ("p") describing Boosted's mission and purpose.\
An unordered list ("ul") with information about Boosted USA, including the company name, address, and location.\
This structure forms the footer of a webpage, containing relevant links for exploration and information about Boosted USA.

CSS:\
The "footer" class styles the footer element with the following properties:

Sets the width to 100%.\
Adds padding of 3% on the top and bottom.\
Sets a light gray background color.\
Displays its content in a flex layout, with space evenly distributed along the main axis.

"footer img" styling:

Sets the width to 15% of its container.\
Sets the height to 30% of its container.

"footer h2" styling:

Sets the font size to 20px.\
Sets the line height to 30px.

Styling for lists within the footer:

Removes the default list style type.\
Sets the font size and line height for the list items.\
Adds margin to the top of the lists.\
Sets a cursor indicating interactivity.

Styling for hovered list items:

Changes the text color to a specific shade of red.

Additional styling for the "aboutUSA" section:

Sets the width to 32%.\
Adds margin to the top of paragraph content.\
Sets font size and line height for paragraph content.\
Adjusts margin and cursor for the list within "aboutUSA" section.
Please note that the comments and certain properties (like border and cursor) have been summarized for brevity.

## Web page is ready
# Thank you
