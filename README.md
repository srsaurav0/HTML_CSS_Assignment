# HTML_CSS_Assignment
This is a basic web page developed using HTML5 and CSS3. The webpage is made responsive with appropriate measures.

To run this project, you need to follow these steps:
1. At first go to the directory you want to save my repository and open Git Bash there.
2. Initialize git with the command: git init
3. Then clone the repository with the command:` git clone https://github.com/srsaurav0/HTML_CSS_Assignment.git `
4. Navigate to the directory with command: ` cd HTML_CSS_Assignment `
5. Open the Project in a Code Editor (Optional). To open the directory in Visual Studio Code, enter command: ` code . `
6. Open the file `HomePage.html` and run it to visit the website.

Modify the `HomePage.html` and `styles.css` files to achieve desired outputs.

The website is made responsive using Media Queries. The meadia queries can be found on the bottom section of `styles.css` file inside the `@media` section.

Overall Structure:

    HTML:
        A basic HTML structure with a header, main, and footer section.
        Within the main section, you would have containers for the image, details, and reviews.
    CSS:
        Grid layout or Flexbox to organize the layout of different sections.
        Responsive design using media queries to adjust the layout for different screen sizes.

Image Section:

    HTML:
        An img tag to display the image.
        An optional figure element with a figcaption for the image caption.
    CSS:
        Positioning the image within its container.
        Setting appropriate width and height for the image.
        Adding a border-radius to create the rounded corners.
        Using box-shadow to add a subtle shadow effect.

Details Section:

    HTML:
        A combination of div elements and semantic HTML elements like h2, p, ul, li, etc. to structure the information.
        Use of icons or font icons for visual elements like stars, location, etc.
    CSS:
        Styling the typography (font family, font size, color, line height).
        Using a grid layout or flexbox to organize the information into columns or rows.
        Adding spacing between elements using margins or padding.
        Using a consistent color palette and typography to maintain visual harmony.

Reviews Section:

    HTML:
        A container div for all reviews.
        Individual review sections, each with an author's avatar, name, rating, date, and review text.
    CSS:
        Styling the review container, including background color, border-radius, and padding.
        Styling the author's avatar, name, and rating (e.g., using star icons).
        Formatting the review text with appropriate font size, color, and line height.
        Adding spacing between reviews.

Additional Considerations:

    Responsiveness: Ensure the design adapts to different screen sizes using media queries.
