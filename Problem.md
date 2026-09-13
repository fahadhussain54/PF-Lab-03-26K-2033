# Problem Pseudocode

## 1. Display Student Information
START
    DECLARE name AS STRING
    DECLARE rollNo AS STRING
    PRINT "Name: Fahad Hussain"
    PRINT "Roll No: 26K-2033"
END

## 2. Read and Display a Character using getchar() and putchar()
START
    DECLARE ch AS CHARACTER
    PRINT "Enter a character: "
    READ ch USING getchar()
    PRINT "You entered: "
    WRITE ch USING putchar()
END

## 3. Display a Floating-Point Value with Different Precision
START
    DECLARE num AS FLOAT = 12.345678
    PRINT num WITH 2 DECIMAL PLACES (%.2f)
    PRINT num WITH 4 DECIMAL PLACES (%.4f)
END 
