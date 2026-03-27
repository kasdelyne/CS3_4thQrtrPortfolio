# CS3_4THQuarter Seatwork 2
### Answers

[K02] AGNIR, Kacey Adelyne O.
**Pair**: [K15] GONZAGA, Germione Naj G.
**Date Performed**: 03/27/2026

---

### Step 1 (Static vs Relative)
Guided Question: What changed compared to the default static positioning? Try to give different values to top and left or you can change it to bottom, right.
**Answer**: Relative positioning shows that you can create small relative shifts in the element's position as it uses the top and left to move it, whereas static position ignores the shifts used (top, bottom, left, and right).

### Step 2 (Fixed)
Guided Question: What happens when you scroll the page? Why does the footer behave differently from position relative?
**Answer**: When we scrolled the page, the footer did not move or change its position at all--it remained fixed on where it was. Position relative, on the other hand, remains in the normal flow of the page. The only thing position relative can do is shift its position on the page and when scrolled, will simply just stay where it currently is.

### Step 3 (Absolute)
Guided Question: What is the effect of position: absolute on an element? How is it different from fixed?
**Answer**: This made the element's position to be relative to its nearest positioned ancestor. It stays in place even when we scroll down. This is different from fixed as position fixed is positioned relative to the viewport, not the nearest positioned ancestor.

### Step 4 (Absolute)
Guided Question: Why does the notice appear on top of the content? What happens if you swap the z‑index values?'
**Answer**: Because the z-index has a high value, "notice" would appear on the top of the content. When we swap the z-index values, the stacking order will change and notice will appear behind the content, while content will appear in front of notice.

### Challenge
* What changes that you have to do on the code that will position .notice box on the top right corner of the .content box? Please write the code on paper as well (both html and css on the part of .notice and .content).
**Answer**:

* Try to change the position of .content to relative then to fixed. What do you observed each time?
**Answer**: .content followed the top and left property values when the position was changed to relative. When we use fixed, it ignores the given property values.

* What do you observe on about the effect of z-index on .notice and .content boxes?
**Answer**: The z-index with the higher value will be positioned "on top" of the element with the lesser value.

### Please answer the following reflection questions (15 minutes)

a. Could you summarize the differences between the CSS position values (static, relative, absolute, fixed)?
**Answer**: The difference between the four CSS position values (static, relative, absolute, fixed) is that first. Static position ignores the shifts used, Fixed position makes it anchored to the viewport, Absolute position makes the element's position relative to its nearly positioned ancestor, and finally Relative position creates relative shifts in the element's positions by using property values like top, left, right, and bottom.

b. How does absolute positioning depend on its parent element?
**Answer**:It is positioned relative to its nearest positioned ancestor.

c. How do you differentiate sticky from fixed (you can research on sticky)?
**Answer**: Sticky is a hybrid of relative and fixed. This means that it will be fixed when the scroll position is reached; the cool thing about this is that you MUST specify at least one threshold like top, left, right, and bottom.

d. If you were designing a webpage for a school event, how might you use positioning to highlight important information? Please give concrete examples.
**Answer**: We could use positioning elements to highlight mainly the header or the navigation bar on school event webpages. Moreover, you can place the elements containing the information you want to share either it being fixed on one area or if it will follow the user when scrolled.



