Devon Moulter
Homework 3

1. The software requirements specification must contain
the software's functions and constraints.

2. An example of an ambiguous requirement would be
"The software must be able to perform basic math
operations"; this requirement is ambiguous because
it does not specify what "basic math operations:
includes. While operations like addition and
multiplication are implied, basic math operations
may or may not include exponents, roots, and
many other operations depending on the context.

3. In the grade processing system, students
can use the grading system to upload their
assignment submissions (Submitted Work)
and retrieve their graded submissions
(Graded Work). Teachers can use the grading
system to retrieve student submissions
(Ungraded Work) and upload submissions they
have graded (Graded Work). The grading
system will store ungraded and graded work
(Submissions) in a repository labeled gradebook.

4. At the beginning of the shopping process,
the shopping cart will be empty. The user can
add items to the shopping cart, creating an
order and switching the cart to the "Collecting"
state. The user can also remove items from the
cart. When there is only one item left in the
cart when removing an item, the cart will
switch back to the Empty state; otherwise,
it will remain in the collecting state.
While shopping, the user can choose to Finish--
which will take him/her to a summary page--or
to Abandon the order--which will end the shopping
process. At the shopping summary screen, the user
can accept to go to Checkout or cancel to continue
collecting items. After going to checkout and
filling out the necessary information, the
shopping process ends.

5. In the entity-relation diagram, customers
and products are both entities while orders
represents the relationship between them.
The customer entity includes such attributes
as first name, last name, street address,
city, state, zip code, and a customer ID.
The product entity includes such attributes
as product name, description, and product number.

6. The SADT diagram for this project is very
simple due to the very nature of the
project. One function noted on the SADT
diagram is creating an account; this
function takes input user information and
uses that information to create an account.
The other major function is creating posts
and private messages; this function takes
text (and potentially some media attachment)
to create a post on the user's feed or a
private message to another user. The creation
of posts and messages may be influenced
by the user's own posts as well as the posts
and messages of other users.

7. Since the assignment called for a simple
SDL diagram, I decided to forgo the system
and block definitions and instead focus
on making a process diagram for sending
private messages. The system recieves
input and attachments from the user,
represented as the user sending this
information and the system receiving it.
The system then prepares a message to send
based on the input information. The
message is sent to the appropropriate
persons who then receive the message.
Finally, the recepients either reply or
simply do nothing; I wasnt's sure
how to represent message replies without
overcomplicating the diagram, so I
represnted that part as a process.

8. The Z Notation program I found defines
and updates a list of people and their
birthdays. The first part, BirthdayBook,
defines the major variables: a list of
names and the birthdays associated with
the names. The part below the line
within the BirthdayBook definition
states the relationship between the
names and the birthdays. The second
part, AddBirthday, is a function that
adds a new name and birthday to the list
created in BirthdayBook. The first item
notes that a change is going to be made
to BirthdayBook. The next two items define
the inputs for the operation. The first
item before the line is a check that
ensures the input name is not already in
the list. If name is not in the list of
names, then a new list of birthdays
that is the union of the old birthday
list and the new item to be added to the
list is created.