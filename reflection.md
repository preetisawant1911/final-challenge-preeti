   1. What accessibility enhancements were the most challenging to implement, and why?

The hardest part was using ARIA attributes. I didn’t know how screen readers work, so I had to learn what things like `role="navigation"` and `aria-describedby` mean. It was new for me, but I understood that these help blind or low-vision users know what each part of the page does. I’m happy I learned it, and now I know how small changes can help many people.

 2. How do ARIA attributes improve the experience for users relying on assistive technologies?

ARIA attributes help blind or low-vision users who use screen readers. These attributes give extra information about what each part of the page does. For example, `role="navigation"` tells the user this part is a menu, and `aria-label` or `aria-describedby` gives helpful instructions. This makes it easier for users to move around and understand the page

 3. What tools did you use to check color contrast, and how did they help?

I used [WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/) to check if the text and background colors had enough difference. It helped me make sure people with low vision can read the text easily. The tool showed me if my colors were okay or if I needed to change them to follow accessibility rules.
