# Pipalates

The live link can be found here - [Pipalates](https://xakkusu.github.io/1_project_pilates/index.html)


## SITE OWNER GOALS
## USER STORIES
## DESIGN
## WIREFRAMES
## FEAUTURES
## TESTING

### FIXED BUGS
1. header and navbar were styled incorrectly so that the header fully covered navbar/menu when its position is fixed:
    - added top margin in main element which is the same as the height of header
    - added high z-index (99) so that the menu will stay on top of the layout when scrolling
    Now menu didn't fit screen and positioning was off:
    - added absolute position in navbar so that its position stay relative to the header and is taken out of the normal flow
    - menu items were placed directly under header with top:100% and placed left:0
2.  table wasn't wholy visible on smaller screens
    - the table for weekdays was horizontally too large for mobile devices but adding the days below one another would have taken too much space and could be confusing for user to compare days and time
    - added overvlow-x:auto to tabble element to add a horizontal scroll bar for table content which was too big for its block level element; user can however always rotate their phone which would show it wholy either way
3. From 992px and upwards the size of the index-page was dislocated from the size of the screen, which after some testing was found out to have come from the Why Pilates?-section on that page
    - width of why-pilates and of best-courses section were to wide, especially the may width with no min width attribute in the why pilates section
    - added min width attribute which is smaller than starting screen size of this media query and giving it a new max width attribute, same with the best-course section
    - content were well fitted to screen size again

## TECHNOLOGIES USED

## DEPLOYMENT
The steps to deploy this project using GitHub pages were the following:
1. Go to the Settings tab of your GitHub repository.
2. On the left-hand sidebar, in the Code and automation section, select "Pages§.
3. Make sure to select the following:
    - Source is set to 'Deploy from Branch'.
    - Main branch is selected.
    - Folder is set to / (root).
4. Click Save next to /root.
5. "Your GitHub Pages site is currently being built from the main branch." shows up.
6. Go back to the Code tab. Wait a few minutes for the build to finish and refresh your repository where a Deployments section will show the deployed project.

The live link can be found here - [Pipalates](https://xakkusu.github.io/1_project_pilates/index.html)

## CREDITS
## ACKNOWLEDGMENTS
