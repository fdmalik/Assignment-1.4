# Assignment-1.4

        Dim mName As String = ""
        Dim mId As Integer = 0
        Dim moreInfo As Char = "Y"

        FileOpen(1, "c:\Assignment 1\mRec.txt", OpenMode.Append)


        While moreInfo = "Y"

            Console.Write("Enter the new member`s name : ")
            mName = Console.ReadLine
            Console.Write("Enter the new members`s ID number : ")
            mId = Console.ReadLine
            

            WriteLine(1, mName)
            WriteLine(1, mId)



            Console.Write("Would you like to add any more records?(Y/N) : ")
            moreInfo = Console.ReadLine

        End While

        FileClose(1)
