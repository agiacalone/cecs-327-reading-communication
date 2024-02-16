# CECS 327 Reading Assignment: Communication

### Assignment Description
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

### Deliverables
* Your writeup file *must* be done in [Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) format and must be included in the repository as a separate file. View the file [`README.md`](README.md?plain=1) for an example of Markdown.
* Any included images or screenshots should be done in `*.jpg`, `*.png`, or `*.gif` formats, and be included individually as files in your repository (i.e. no binary ‘document’ with the images pasted inside).
* Screenshots or images *may* be linked in your Markdown file writeup if you wish to do so.