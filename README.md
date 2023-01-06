# UFOs

## Overview of the analysis

The objective of the project was to create a website thsat display UFO sightings data in a dynamic table and using filters to accurately display the data one is searching for.

The website was created using a combination of HTML, CSS, Bootstrap and JavaScript. CSS and Bootstrap were used for the styling on the website and JavaScript was used for the functionality of the website.

The website display a table with data of the sightings, which comes from the `data.js` file. Below is an example of the data the is in the `data.js` file:

````
{
    datetime: "1/1/2010",
    city: "benton",
    state: "ar",
    country: "us",
    shape: "circle",
    durationMinutes: "5 mins.",
    comments: "4 bright green circles high in the sky going in circles then one bright green light at my front door."
  }
````

There is a form on the page that allows the user to input different values, such as date, city, and shape, to filter the data and display the filters results in the table. The `app.js` controls the filters and how the table is built and refreshed with the filtered results.


## Results

Below is a image of website when you first land on the page. It displays all the data that is in the `data.js` file.

![](https://github.com/jhohing/UFOs/blob/main/static/images/UFOs_main_page.png)

Looking at the page there is a `Filter Search` section on the page. That section allows you to use the available filter to narrow down the data and find what the user is looking for. The user can filter on date, city, state, country, and shape. The table will automatically update as you add input to one of the five filters. Below is what the page will look like after using the state filter to search for sightings that ocurred in Florida.

![](https://github.com/jhohing/UFOs/blob/main/static/images/UFOs_state_filter.png)

The `app.js` file handles filtering the data. The user can also use more than one filter at a time. Below is a screenshot of what the table will look like using the state and shape filters.

![](https://github.com/jhohing/UFOs/blob/main/static/images/UFOs_multiple_filters.png)

To reset the table, the user can erase the input for all the filters they used or to click th e `UFO Sightings` title at the top left corner on the page.

## Summary

### Drawback

One draw to the webpage is there is no button to filter the data. If the user does not realize the data is updating as the add input to a filter, it can be a little confsuing and the user may feel like the data is not changing.

### Recommendations

The first recommendation is to add a filter and reset button to give the user more control as to when the table updates/reset to the full data set. The second recommendation is to add sort to each column so if the user does not want to filter the data but wants the data sorted a particular way, they can do so.
