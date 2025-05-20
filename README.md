
Queestion 1: 

I would fit my automated tests in a github actions .yaml file that runs a script to run all automated tests so that it is easy to see which tests fail and pass as changes are made to the software.


Question 2:

No, primarily because E2E tests, as I understand them, are meant to test the software as a whole instead of smaller individual components. It is unreasonable to use them constantly to test relatively small functionality.

Question 3:

Navigation mode does a full reload of the whole page to monitor how well a page does on first load.

Snapshot mode does not do a reload of the page, instead it takes a "snapshot" of the current page state after you do some arbitrary action like clicking a button.

Question 4:

- Improve Accessibility
- Cut unused JavaScript/CSS
- Add 'alt' attributes to images, add meta description to the document