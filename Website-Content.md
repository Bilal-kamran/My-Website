# Website Building Guide:
The following things should be done to build the website and the following steps --> (This won't be available in the start as I am not
                            providing any services at all)
be followed to keep things simple and clean:

## Website Project File Structure:
My-Website:
- public/
    - css/
    - images/
    - html files
- .gitignore
- README.md
- LICENSE

## Website Prototype:
The following should be the structure of the webpage:

- **All the pages should contain this navbar:**
    + My Logo: The website Logo.
    + Home: Link to the index.html page.
    + Portfolio: Link to a portfolio page where I explain each and every project of mine.
    + About: Link to a page where I explain everything about myself clearly.
    + Contact: Link to the page with my contact info.
    + Service: Link to the page where I explain the services I provide.

- **The Main/Home page should have the following:**
    + A hero section with the following:
        * The main heading with my name:
            ```html
            <h1>Bilal Kamran</h1>
            ```
        * A main paragraph with a brief intro and my goals and what I look forward to:
            ```html
            <p>Hello! I'm Bilal Kamran, an aspiring artist and a programmer passionate about learning. I look forward to promote a thriving community where diverse talents can collaborate and create together in a supportive environment.</p>
            ```
        * A collage of the following images on the right side of the page:
            - A high quality blender render.
            - A high quality image that was edited.
            - A screenshot of a code snipped written in neovim.
        * A smooth fade in and out animation

    + Beneath the hero section there should be a horizotal scrollable section
      where some of the selective projects are showcased and can be visited by
      clicking.

    + In the end the footer should contain basic links and copyright detail
      along with the link to the github page where I have the source code available
      for my website with a CTA of "Help us improve the website by contributing".

- **The Portfolio page should contain the following:**
    + All the projects should be categorized into sections according to their
      selective field.
    + They all should lead to a separate page where they are explained in detail.

- **The About page should contain the following:**
    + It should contain three sections:
        * A detailed introduction
        * An Education section
        * An Experience section
    + They should contain the details of the respective subject in great detail

- **The Contact page should contain the following:**
    + It should contain a form which the viewer can get into contact with me.
    + It should contain a separate nav section where there are links to different
      pages.

- **The services page should contain the services I provide and on which platform
    I provide services** --> (This won't be available in the start as I am not
                                providing any services at all)
