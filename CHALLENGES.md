# Challenges

-   I struggled with the **select element in the header** where I wanted space between the text and the dropdown arrow. Finally, I added that arrow externally to get the right look.
-   My major challenge was the **floating label**. I figured out that I needed to set the input to `position: relative` and the label to `position: absolute`. On focus, I changed its position and size — and that solved it.
-   When I wanted the **numbers to float on the cards**, I applied a similar concept: setting the card as `position: relative` and the number as `position: absolute` with a higher `z-index`.
-   I struggled with creating the **number’s outline and inner color** (black stroke with fill). It took some experimenting, but I managed to pull it off.
-   While making it responsive, I had a hard time with the **input and button scaling properly**. That’s where I learned about `flex` properties and `flex-shrink`. Eventually, I got them to behave the way I wanted.
-   Another issue was that when I zoomed out, my website wasn’t centering — it kept shifting to the left. Later, I understood the power of using `margin: 0 auto;` along with `overflow-x: hidden;`. That finally centered it perfectly.
-   Surprisingly, **media queries felt like the easiest part** of the whole process for me.

# Final Thoughts

I think I’ve covered all the key challenges I faced. This clone boosted my confidence a lot, and I felt genuinely proud of the final result. The design came out so well that I could hardly see any difference between the original and my clone.
