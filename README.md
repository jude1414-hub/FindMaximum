# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:

    i)	# To find the maximum of marks using the list method sort.
    #developed by:Jude Clement Jose G
    #register number:24005310

    def max_marks(array):
        array.sort()
        return array[-1]

    ii) # To find the maximum marks using the list method max
    #developed by:Jude Clement Jose G
    #register number:24005310

    def max_marks(array):
        return max(array)


    iii) # To find the maximum marks without using builtin functions.
    #developed by:Jude Clement Jose G
    #register number:24005310

    def max_marks(array):
        max1=array[0]
        for i in range(1,len(array)):
            if max1<array[i]:
                max1=array[i]
        return max1


## Output:
![alt text](image.png)
![alt text](image-1.png)
![alt text](image-2.png)
## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
