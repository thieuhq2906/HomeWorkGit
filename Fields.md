### Single line of text

It use to store short text strings such as names, titles, or descriptions. This type of column allows users to enter a single line of text **up to 255** characters and can be customized with additional settings such as _default values_, _validation rules_, and _indexing_.
   - _default values_: Automatically display specific text when someone adds a new item, while also allowing people to enter different text if they need to do so, that help user enter information faster
   - _validation rules_: setting that allows you to define certain conditions that must be met before a user can save an item to a list or library
   - _indexing_: we can creating an index on the column to improve the performance of queries and sorting on large lists or libraries.
note: you can change an existing _Single line of text_ column to a _Multiple lines of text_ column without losing any data stored in the column already.

### Multiple lines of text

This column allows users to enter longer pieces of text, up to a **maximum length of 63,999** characters, and can be customized to display a specified number of lines of text when users enter information about an item.
The multiple lines of text column can display formatted text, including rich text formatting, hyperlinks, and images. When the column is viewed in a list or library, it displays all the text entered by the user, making it a useful tool for displaying detailed descriptions, comments, or notes and can be customized with additional setting as _enhanced rich text_ or _append changes to existing text_
  - _enhanced rich text_: this allows users to format text using basic formatting tools, such as bold or italic text, bulleted or numbered lists, colored text, and background colors. Additionally, users can add hyperlinks, pictures, and tables to the text.
  - _append changes to existing text_: allows user to add new information to an item without replacing any existing information. When this option is selected, the column displays a hyperlink labeled "View Entries" instead of the text. By clicking on the hyperlink, users can see all the information stored in the column for that particular item, including the previously entered information and the date and time each entry was made. 

### Choice (menu to choose from)

This column allows users to select options from a list of choices provided by the column creator with two display options: a drop-down menu or option buttons. This type of column is very useful in situations where it is necessary to ensure consistency in the data entered in the column by limiting the available values. It can be customized to display the list of choices by two ways: _define the list by the creater_ or _enable additional custom choice_

### Number

This column is used to store numerical values, and it is suitable for mathematical calculations that don't require a high degree of accuracy. Number column in SharePoint can be customized to _limit the range of numbers that people can enter_, _specify the number of decimal places to store_, and _format the number as a percentage_. 

### Currency

This column is used to storing monetary values with _up to 15 digits to the left_ of the decimal point and _4 digits to the right_.
This column can be customized by specifiyng minimum and maximum allowed values, choosing whether to include decimal places and how many, and selecting a currency format from over 100 options. For more precise calculations, we have Automatic to use the appropriate number of decimal places based on the result. By selecting a specific currency format, that ensure all values in the column are based on the same currency.

### Date and Time

This column store calendar dates, or both dates and times. The format of the date is determined by the regional settings of the site. If we cannot find the desired format, the administrator can add support for the appropriate region to the site. To customize this type of column, we can choose to include either only the date or both the date and time.

### Lookup (information already on this site)

The search field enables users to locate information that is already available on the site. It allows for searching across various types of content, including Documents, Events, Form Templates, Site Assets, Site Pages, Libraries, and Lists.

### Yes/No (check box)

A Yes/No column stores boolean data, such as whether someone will attend an event, and is represented by a single check box. The check box is selected to indicate Yes and cleared to indicate No. The information stored in this column can be used in calculations for other columns, where Yes is treated as one (1) and No is treated as zero (0).

### Person or Group

This column allows people to choose from a searchable list of individuals and groups when adding or editing an item. This column is useful for tasks lists where a task can be assigned to a specific person  This column can be customized in the following ways:
-,Allow multiple selections: Users can select as many options as they want, or limit the selections to only one option.
Include or exclude groups of people: Specify whether the list includes only individual people, or also includes e-mail distribution lists and SharePoint groups.

### Hyperlink or Picture

This type of column is used to store the URL for a resource such as a webpage or graphic. Depending on the display format, it can show either a clickable hyperlink or a graphic in place of the URL. A hyperlink can be added to a list item by input the URL and descriptive text.

### Calculated (calculation based on other columns)

This column can stores values that can be auto-caculated based on other columns using provided fomulas, which is define at  [here] (https://support.office.com/en-US/client/results?Shownav=true&lcid=1033&ns=SPOStandard&version=16&omkt=en-US&ver=16&HelpId=WSSEndUser_FormulaSyntaxError).

### Image

This column store image file in a list or a library. To add the image, we have _add Image_ function, and we also have the garbage bin icon to do the delete function

### Managed Metadata

Managed metadata in SharePoint refers to a feature that allows users to create and manage a set of standardized terms and keywords that can be used to tag and classify content within a SharePoint site. These terms can be organized into a hierarchical structure, which provides a way to browse and search for content based on its metadata.

The managed metadata feature is based on a central term store, which serves as a repository for all the terms and keywords used within the SharePoint environment. This central store ensures that all users have access to the same set of terms, which helps to ensure consistency and accuracy in tagging and searching for content.

Managed metadata can be used to improve the findability and organization of content in SharePoint, making it easier for users to locate and use the information they need. It can also be used to support information management policies and compliance requirements, by enabling the application of consistent metadata across all content within a site or organization.
