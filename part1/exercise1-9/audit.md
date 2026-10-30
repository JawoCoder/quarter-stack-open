Exercise 1.9 – Website Audit

## Part A – Audit of the Original Page

Defect	How I proved it	Kind	How I fixed it
Tagline used as a heading	The heading outline shows an unnecessary h2 heading.	1	Changed it to a paragraph.
Image has poor alt text	The image uses alt=“image”, which does not describe it.	1	Added descriptive alt text or marked it for confirmation.
Services use fake bullet points	The HTML uses bullet symbols and br tags instead of ul and li.	1	Replaced them with a proper unordered list.
Incorrect heading structure	The h3 services heading does not follow a meaningful section hierarchy.	1	Corrected the heading structure.
Important warning uses b	The deposit warning uses a b element instead of strong.	1	Replaced b with strong.
Establishment year is invented	The original prompt never provided the year 1985.	2	Added a TODO for owner confirmation.
Customer number is invented	The prompt never mentioned 2,000 customers.	2	Removed the unsupported claim.
Award-winning claim is invented	No award information was supplied.	2	Removed the unsupported claim.
Prices use US dollars	The page displays dollar signs instead of confirmed Gambian currency.	2	Changed prices to GMD placeholders.
Opening hours are assumed	The owner did not provide working days or hours.	2	Marked opening hours for confirmation.
Phone number is invented	No telephone number was supplied.	2	Replaced it with a placeholder.
Email address is invented	No email address was supplied.	2	Replaced it with a placeholder.

## Part B – Testing Today’s AI

1. Defects avoided: Today’s AI avoided the invented establishment year, customer numbers, awards, US dollar prices, opening hours, phone number and email address.
2. Defects repeated: The services were still presented as assumed business information, although the original prompt did not specify the actual services.
3. Why improvement cannot prevent them: AI cannot know private business information that the owner never provided. The owner must supply the correct details.

## Part C – Asking Better

Constraint I added	Defect it removed	Kind
Use Gambian Dalasi (GMD).	US dollar pricing.	2
Specify Serrekunda, The Gambia.	Unclear business location.	2
Use proper heading hierarchy.	Incorrect heading structure.	1
Use proper HTML lists.	Fake bullet points.	1
Use strong for important warnings.	Incorrect warning markup.	1
Do not invent business information.	Unsupported business claims.	2
Use placeholders for missing contact details.	Invented contact information.	2
Do not assume opening hours.	Assumed working schedule.	2

Some defects can be prevented through better instructions, but missing business facts still require confirmation from the owner. No prompt can reliably provide information that the owner has never supplied.

## Part D – Final Corrections

I corrected the HTML structure, improved the headings, replaced fake bullet points with proper lists, improved the warning markup and removed unsupported business information.

I also added TODO comments wherever the owner needs to confirm information before publication.

## Conclusion

This exercise taught me that a website can pass HTML validation and still contain serious problems. I learned that checking facts, accessibility and proper HTML structure is important before publishing a website.