#software-engineering #software-design #UML #use-case-diagram

Texture use case:

A borrower walks into a library wanting to loan a book
They **search for the book** but do not find it
They approach a librarian and give them the name of the title
The librarian **searches for the book** and finds it.
The borrower gives the librarian their name and account information.
The librarian scans the book and lends it to the borrower

Is this not more of a [[Story]]?

**What actors can be discovered from the passage texture use case?**
1. Borrower
2. Librarian

**What is the first use case we can discover from the texture use case?**
Look for the first thing that must happen, or if multiple things can occur simultaneously first, the first mentioned thing. In this case **Search for book**

"They approach a librarian and give them the name of the title" is not a use case? Probably because that is part of the search for a book use case. I guess it would describe that we need functionality to find books based on title

**IMPORTANT**: The use case must belong in the [[System]]. Walk into a library is not a use case because it does not belong in the system. But if we were making something like an entrance to a library than maybe we would. Its system dependent.

**Which [[Actor]]s can search for a book?** 
The librarian and the borrower




Source: https://www.youtube.com/watch?v=uN-zt7bXbnQ&list=PLlup9oTyUUAtzyYN30-qRrscg17EtQFbT&index=6