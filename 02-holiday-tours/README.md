### Project Worflow

- Set the Tours component
- Set useState hook to set tours empty array and setTours function
- Use fetch api to get list of tours.
  - Set useEffect to load the tours list, when page renders
- Set setLoading to false and tours array from response to setTours state
- Pass tours props to Tours component and destructure that in Tours.js as well
- Map through the tours array inside the section to display all tours
- Destructure single tour props in Tour.js func, and display all functionality
- set state for readMore functionality, and use ternary to display substring of paragraph
- Add button to toggle the state. Set setReadMore to show full paragraph or a part of it
- Removing a single tour from list
  - set removeTour func in App.js, to filter out tour that is to be removed
  - Pass in as a prop to Tours component, and then in Tour component (Prop drilling)
- Display condition for no tours to display and refresh btn to fetch back all tours
