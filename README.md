# Document Comparison

### Description
Document comparison is a process of comparing two documents to identify similarities, differences, and changes between them. Tracking changes made to a document over time, or identifying similarities between two documents.

### Perquisites
* IFrame widget
*	An account in Draftable API [Click here to create an account](https://api.draftable.com/account/login).
*	Once the Account is created, Click the three dots on the right side then go to Account->API credential.  Scroll down, and Copy your access token and Account ID.
  -H "Authorization: Token {auth_token}"

### Configuration
1. Add your Account ID in the AccountID constant
2. Add your access token in the Access_Token constant
3. Configure the Comparison overview page in the navigation

### Implementation 
1.	Create comparison
2.	Delete comparison 
3.	Export comparison as PDF with 4 different kinds
  *	single page: Displays the right side document only with highlights and deletion markers showing the diff
  *	combined: Displays both right and left sides
  *	left: Displays left side only
  *	right: Displays right side only

### Result
Results all the minor and major changes including style changes.

### Supported files
*	PDF - pdf
*	Word - docx, doc, docm, rtf
*	PowerPoint - pptx, ppt, pptm
*	Text - txt

### Features
Accurate comparison: Draftable is known for its highly accurate comparison technology, which can accurately detect and highlight changes between two documents, even for complex formatting or layout changes. This makes it easy to identify and review changes, and to make informed decisions about which changes to accept or reject.

### Limitations
Some types of documents can’t be compared and may require users to convert or reformat their documents to use the API.

 
 
 
