In this project, we will build a screen for a library software app utilizing Lists.

Your objective is to build a GUI app (using Java swing for example) to show Library Book information details as read from a file. 

1. First download the book.csv file from here 

    https://github.com/zygmuntz/goodbooks-10k/blob/master/samples/books.csv (Links to an external site.)

    https://github.com/zygmuntz/goodbooks-10k/blob/master/books.csv (Links to an external site.)

1. Your program should include a class Book that contains data reflecting the columns in the dataset table

1. Using regular expressions and the string library, build a function to read the file record by record and stores them into a List of Book objects.

1. Implement two versions of this program one that uses ArrayLists and one that uses LinkedLists. You should be able to do that without duplicating all the code. (hint: review Task 1 of Assignment 2)

1. Your app should show the top 10 records in your list. 

1. Your app should allow the user to search for a certain book using book_id or isbn

1. Your app should allow the user to change the sorting of the list to be sorted based on 

    - authors 
    - original publication 
    in both ascending or descending order. 

    Hint: You can test your solution using a shorter book list first then apply to the larger file. 

    Note: feel free to trim the file ( use a shorter list of books) but we have to maintain a large number. 

1. For the book search feature implement the following:

    - for the ArrayList - Binary search 

    - for the LinkedList - linear search 

1. create a separate method to test the performance of the algorithms in 8.

    Compare the performance of the 2 methods by searching in the underling data structure for a large number of values. These values could be taken from the data set. (suggested number 500 values, if no difference is seen they could be increased to a 1000)

1. Report the running time for each of the two methods.  

1. Any added features like: adding a new book, editing book information, deleting books, or more features for search will be rewarded with a bonus! 

