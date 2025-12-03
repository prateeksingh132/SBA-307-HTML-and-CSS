##### SBA 307: HTML and CSS #####


# My Application Name: GadgetShack

**Brief Description:**

I create a small and simple electronics e-commerce website called GadgetShack.

My website has 3 main pages:

1. **Home:** Home page has hero message and hero banner with the gif and some featured products.
2. **Products:** This page shows catalog of products with their prices. I also have a table here which compare the product's specs.
3. **Account** This page has my 2 forms: Login form and Register form.

# Technologies Used:
- HTML
- CSS

## Reflection

**What could you have done differently during the planning stages of your project to make the execution easier?**

I should have drawn the layout on paper or at least created a wireframe first. I started creating my code first with the plan in my head and have to rewrite some 'div' structure later on because the containers would not align properly. I should have created a parent-child container layout first as we did during some of the lecture activity.

**Were there any requirements that were difficult to implement? What do you think would make them easier to implement in future projects?**

a. The dropdown menu gave me the most trouble. I tried to use the lecture slide example to create it, but it messed up my flexbox layout. So, finally I looked up a tutorial on w3schools for it, which had hover to reveal example and it combines position ('position: absolute'), display ('display: none and block') and pseudo class (':hover') concept to achieve the same.  

b. Checkbox on my form pages gave me issue with alignment. The issue was the default input width in my css code was messing it up, I had to use a separate inline styling for the checkboxes to corect it.

**What would you add to or change about your website if given more time?**

a. Add more cool animations using transition and transform concepts.

b. Use media queries. maybe try bootstrap to achieve cool animations.


**Use this space to make notes for your future self about anything that you think is important to remember about this process, or that may aid you when attempting something similar again.**

a. Maybe have different styling for different inputs. Make sure if I have a default styling for inputs, it does not messes the alignment for certain inputs (for example text input and checkbox input).

b. Use 'object-fit:cover' to make sure that your image/gif fully covers the box without distortion when stretched

c. I find using flexbox 'gap' much easier than playing with margins.


# References

I referred some examples from w3school and mdn website. Here are the links:

https://www.w3schools.com/howto/howto_css_dropdown_navbar.asp

https://www.w3schools.com/howto/howto_css_login_form.asp

https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Table_accessibility

