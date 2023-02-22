# Basic_Layout_Website_HTML_and_CSS

In the HTML code, we have a basic structure for a web page. The container div is used to set the maximum width of the page to 1200 pixels and center it horizontally on the page. The header div contains the title of the page. The main div wraps the content and sidebar divs, and the footer div contains the copyright information.

In the CSS code, we have styles to control the layout and appearance of the page.

The .container class sets the maximum width of the page to 1200 pixels and centers it horizontally on the page using the margin: 0 auto; property.

The .header class sets the width and height of the header section, and sets the background color, text color, and text alignment.

The .main class sets the display property to flex, which enables the use of the flexbox layout. The flex-wrap property is set to wrap, which allows the elements to wrap onto the next line if the container's width is too small.

The .content class sets the flex property to 1, which makes it take up all the available space. It also sets the minimum height, background color, and padding.

The .sidebar class sets the flex property to 0 0 30%, which sets its width to 30% of the container's width and prevents it from growing or shrinking. It also sets the minimum height, background color, and padding.

The .footer class sets the width and height of the footer section, and sets the background color, text color, and text alignment.

Overall, the CSS code uses flexbox to create a two-column layout with the content section on the left and the sidebar section on the right
