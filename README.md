# UFOs

## Overview of Project

The purpose of this project was to create a webpage on UFO sightings. The webpage should include a dynamic table that has multiple search filters.

## Results

### Performing a search:
- Start by entering a value in any one of the five filter boxes. For example, entering "1/10/2010" in the <i>Enter Date</i> field
- Press the <i>Enter</i> key on your keyboard to refresh the page with your selected filter <img src="static/images/first_filter.png">
- Enter a value in any one of the other field boxes For example, entering "unknown" in the <i>Shape</i> field
- Press the <i>Enter</i> key on your keyboard to refresh the page with your selected filter <img src="static/images/second_filter.png">
- Note, if no results match the filters entered, the table will be blank. <img src="static/images/blank_result.png">

## Summary

### Drawbacks
- **Allowing the user to type in the criteria themselves.** For the search to work accurately, the user must type in a value as it exists in the data. This means that if there is a typo, it will not show results even if the intended value exists.

### Additional recommendations for further development:
1. **Having the table automatically refresh as the user is typing in a value in the filter.** For example, if the user has typed san" in the <i>City</i> filter, all cities starting with "san" will automatically show (e.g. Santa Fe and San Diego).
2. **Adding a dropdown menu for possible selections.** This would allow the user to search for criteria that exists. This would also take care of any user-end errors such as typos.
    - Additionally, having dropdown selections for other fields automatically update if another filter is selected. For example, if "TX" is chosen in the <i>State</i> filter, the <i>Date</i> filter would only allow the user to select "1/8/2010" as it is the only existing value that matches the search.