# CECS 327 Reading Assignment: Communication

# Assignment Description
Answer the following questions from the Chapter 4 reading from your textbook. Be complete with your answers. You may work on these questions with one or two other partners, but all students must submit the document individually in their own repositories along with each student's name documented with the submission.

1. Why are transport-level communication services often 
  inappropriate for building distributed applications? 

2. Assume a client calls an asynchronous RPC to a server, and 
  subsequently waits until the server returns a result using 
  another asynchronous RPC. Is this approach the same as letting 
  the client execute a normal RPC? What if we replace the 
  asynchronous RPCs with synchronous RPCs? 

3. Would it be useful to also make a distinction between static 
  and dynamic RPCs? Why? 

4. Describe how connectionless communication between a client and 
  a server proceeds when using sockets. 

5. Suppose that you could make use of only transient asynchronous 
  communication primitives, including only an asynchronous 
  receive primitive. How would you implement primitives for 
  transient synchronous communication? 

6. With persistent communication, a receiver generally has its 
  own local buffer where messages can be stored when the receiver 
  is not executing. To create such a buffer, we may need to 
  specify its size. Give an argument why this is preferable, as 
  well as one against specification of the size. 

7. Give an example where multicasting is also useful for discrete 
  data streams.  

8. How could you guarantee a maximum end-to-end delay when a 
  collection of computers is organized in a (logical or physical) 
  ring? 

9. How could you guarantee a minimum end-to-end delay when a 
  collection of computers is organized in a (logical or physical) 
  ring? 

10. Despite that multicasting is technically feasible, there is 
  very little support to deploy it in the Internet. The answer to 
  this problem is to be sought in down-to-earth business models: 
  no one really knows how to make money out of multicasting. What 
  scheme can you invent?

# Deliverables
Commit the answers to the questions in a readable file to your git repository by the due date and time indicated with your repository. Approved file submission formats are: plain text (\*.txt), Markdown (\*.md), PDF (\*.pdf) or web-renderable HTML (\*.html). Github will look for one of these file formats to confirm your "submission" of the assignment. Other formats will only be accepted with *explicit* approval. **NOTE: \*.docx is *not* acceptable. I will not make exceptions for this rule being violated**.
