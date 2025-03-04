We’ll see a further use of arrays when we build a bash debugger in Chapter 9.
 To end this chapter, here are some problems relating to what we’ve just covered:
 1. Improve the account ID script so that it checks whether the argument is a num
ber. Also, add a test to print an appropriate message if the user ID doesn’t exist.
 2. Make the script print out the username (field 5) as well. Hint: this isn’t as easy as
 it sounds. A username can have spaces in it, causing the for loop to iterate on
 each part of the name.
 3. As mentioned earlier, the built-in versions of pushd and popd use an array to
 implement the stack. Change the pushd, popd, and getNdirs code that we devel
oped in this chapter so that it uses arrays.
 4. Change the selection sort in the last task into a bubble sort. A bubble sort works
 by iterating over the list comparing pairs of elements and swapping them if they
 are in incorrect order. It then repeats the process from the start of the list and
 continues until the list is traversed with no swaps.
