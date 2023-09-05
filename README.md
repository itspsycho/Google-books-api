# Google-books-api
This is a simple python script that uses Google Book's API to return the metadata of a list of books, I have used this small script to help me list around 2000 books online for a bookstore that wanted to upload their books on their new website that I have built for them. 


# How to use:
**1. Find the path of your book list with the names of all the books you want to extract the metadata for**

**2. Change it in the code at line#37**

**3. Edit the book list excel file to have the following columns and then run the program:**
 - Column A: Book Name (Input)

      This column should contain the names of the books for which you want to retrieve metadata.
 - Column B: ISBN (Output)

      This column will be populated with the ISBN information retrieved from the Google Books API.
- Column C: Title (Output)

  This column will contain the book title retrieved from the API.
- Column D: Authors (Output)

    This column will store the authors' names retrieved from the API. If there are multiple authors, they should be comma-separated.
- Column E: Cover Link (Output)

    This column will contain links to the book covers retrieved from the API.
- Column F: Description (Output)

    This column will store the book's description retrieved from the API.
- Column G: Categories (Output)

    This column will contain the book's categories or genres retrieved from the API. If there are multiple categories, they should be comma-separated.
- Column H: Published Date (Output)

    This column will hold the book's publication date retrieved from the API.
- Column I: Page Count (Output)

    This column will contain the number of pages in the book retrieved from the API.
- Column J: Language (Output)

    This column will store the language of the book retrieved from the API.
- Column K: Maturity Rating (Output)

    This column will contain the maturity rating of the book retrieved from the API.
