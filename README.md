#  Web Design Headphones Desktop and Mobile 
# Building a Web Page the Right Way

Creating a web page the right way is not easy - except if you put in place strong foundations. Follow these guidelines to ensure your web page is well-structured and maintainable.

## Foundations

1. **Reset CSS Styling**
   - Use a CSS reset to ensure consistent styling across different browsers.

2. **Use Variables**
   - Define variables for colors, fonts, and other reusable styles to maintain consistency and make updates easier.

3. **Simple/“As Generic As You Can” CSS Selectors**
   - Use generic selectors to keep your CSS maintainable and avoid specificity issues.

4. **Avoid Using Super Specific CSS Selectors**
   - Keep your CSS selectors simple to reduce complexity and improve readability.

5. **Simple HTML Structure**
   - Use div containers to organize your content and keep the structure clean and easy to follow.

6. **Building Strategy**
   - Start building your web page from the outside to the inside and from top to bottom. However, you can choose the strategy that suits you best, but always structure your implementation to avoid getting lost with HTML tags.

## Tasks

### Task 1: Create the Header/Hero Piece
- Build the header or hero section as the first task.
- Ensure it is visually appealing and sets the tone for the rest of the web page.

### Task 2: Create the "What we do…" Section
- Build the section that describes what the business does.
- Use custom font icons provided in the `holberton_school-icon.zip` archive.
- Refer to the demo page inside the archive to understand how to use the icons.

### Task 3: Create the "Our Results" Section
- Showcase the results or achievements of the business.
- Reuse components from the "What we do…" section to maintain consistency.

### Task 4: Contact Form
- A good landing page always includes a contact form.
- Add any necessary animations and/or constraints on fields to enhance user experience.
- Reuse components from previous tasks where applicable.

### Task 5: Footer
- Complete the web page with a footer section.
- Ensure it includes necessary links and information, maintaining the overall design consistency.

## File Structure

```plaintext
.
├── css
│   ├── reset.css
│   ├── variables.css
│   ├── main.css
├── fonts
│   └── holberton_school-icons
│       ├── demo.html
│       ├── icons.css
│       └── icons.woff
├── images
│   ├── hero-bg.jpg
│   └── logo.png
├── index.html

