This OpenRefine code is intended to be used with Wikidata items, based on the example of the Women in Red project below. It should work with any set of Wikidata items, however, as long as it is formatted according to the steps below.

https://en.wikipedia.org/wiki/Wikipedia:WikiProject_Women_in_Red/Missing_articles_by_occupation/University_teachers  1.) Highlight the entire set of WikiData items from the webpage

2.) Copy it

3.) Paste it into a new Excel spreadsheet

4.) The code was created with the assumption that the spreadsheet should has the following columns: 
#, name, image, description, country of citizenship, date of birth, date of death, place of birth, place of death, item, site links.
(If the spreadsheet does not have these columns, the code should work as long as the Wikidata QID item is in Column H)

5.) Ensure that the column with the QID is titled "item". Save the spreadsheet.

6.) Open the OpenRefine program

7.) Select "Create Project", then "This Computer", then "Browse". Select the file on your computer, and click "Next". Then click "Create project".

8.) On the left panel, click on the "Undo/Redo" tab. Click "Apply" on the lower part of the left panel.

9.) Highlight all of the text from the "Library Holdings OpenRefine Code" document, copy it, and paste it in the "Paste an extracted JSON history of operations to perform:" section of OpenRefine. Click "Perform Operations".

10.) Wait for the process to complete. Depending on the size of the list, this could take several hours.











