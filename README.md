# Interactive-Form   
**HTML and CSS made this minimal form look simple, yet Javascript does the heavy lifting behind the scenes with regex and conditionals (if, then). 
This is easily one of my favorite Javascript tools because it is so helpful for users to understand how you need their data input entered.** 
\
\
**With helper text in each form field the user understands what type of data is needed. The red asterisk signals which form field inputs are required to submit. The green success checkmarks 
let user know they entered their data correctly. Lastly, the red error messages not only inform the data input was incorrect, it tells user how to enter it correctly. This is one of my FAVORITE projects as this is work I knew my focus was with helping BOTH the user with help filling out the form while structuring the data input so that it is received in helpful
format for the programmers, data engineers, data analysts, etc who will use this data.** 
\
\
\
**Form Rendering** 
\
\
![form rendering](https://github.com/JCPTrevillian/Interactive-Form/assets/95890754/13501d52-50a1-4297-a390-734db46860c0)

\
\
**Form untouched by user - note the helper text in the form fields and the red asterisk before user starts input** 
\
\
![a](https://github.com/JCPTrevillian/Interactive-Form/assets/95890754/55220c3c-a33c-4b8c-8bf6-3c394f96f735)
\
\
**Color: Red for error messages and Green for check mark circle in style.css**
\
\
![red:green for error:ok messages](https://github.com/JCPTrevillian/form_w_validation/assets/95890754/1d3588ff-331d-4e6e-b089-0178aefb6571)
\
\
**Red Asterisk (globally in style.css- ::before is to place it before the input label group (ie: NAME on form)**
\
\
![before](https://github.com/JCPTrevillian/Interactive-Form/assets/95890754/1850875f-0c03-4d31-a8eb-eeac43de7dc6)
\
\
![a](https://github.com/JCPTrevillian/Interactive-Form/assets/95890754/54b849ef-d1c1-4e77-877b-64d7a9df83d4)
\
\
**Red asterisk (globally)in style.css - ::after is to place it after label input group (ie: NAME on form)**
\
\
![css red asterisk](https://github.com/JCPTrevillian/form_w_validation/assets/95890754/642c87fe-b4dd-4863-968f-4c04a2a1ba03)
\
\
![after](https://github.com/JCPTrevillian/Interactive-Form/assets/95890754/7ed1ac42-c11d-4d6e-b97d-d3bd24999521)
\
\
**Alt red asterisk (locally) in case I wanted to display it in a few of the form fields - it appears after the entire input line** 
\
\
![Alt- local red asterisk ](https://github.com/JCPTrevillian/Interactive-Form/assets/95890754/85672214-ba0b-4e15-8edb-fde67cd95a21)
\
\
**Helper text lets users know what data to input in the form fields**
\
\
![helper text ](https://github.com/JCPTrevillian/form_w_validation/assets/95890754/1a6bf632-1b4e-48a2-b023-8a387561ad24)
\
\
**Helper text in index.html**
\
\
![html helper text ](https://github.com/JCPTrevillian/form_w_validation/assets/95890754/1a259e7c-0120-4fe6-b870-0cb75eb15b77)
\
\
\
**NAME FORM FIELD**
\
\
**Name is required: prevents user submission without information on required areas of form **
\
\
![name is required](https://github.com/JCPTrevillian/form_w_validation/assets/95890754/998e4b85-0ee0-475d-a56f-d49e2cd13981)
\
\
**index.html**
\
\
![html name](https://github.com/JCPTrevillian/Interactive-Form/assets/95890754/b2279404-945b-4c48-acbf-fb7b5fca1e46)
\
\
**script.js**
\
\
![js name](https://github.com/JCPTrevillian/Interactive-Form/assets/95890754/53b18eec-0782-443b-ae36-913a905e40f9)
\
\
**Regex criteria not met so error with helper message triggered: "Enter full name"**
\
\
![enter full name ](https://github.com/JCPTrevillian/form_w_validation/assets/95890754/3bd9d83c-de32-4f2a-a32e-7a55cfd3b1e0)
\
\
**Regex: - first name, space, last name will satisfy requirement. Capital and lower case letters acceptable**
\
\
![name validation](https://github.com/JCPTrevillian/form_w_validation/assets/95890754/2e534125-3e9e-4b71-b300-ecabfd5f851d)
\
\
**Full name entered correctly, green checkmark for visual validation to user**
\
\
![full name correct ](https://github.com/JCPTrevillian/form_w_validation/assets/95890754/f2b009cc-9eaa-4bc9-a82d-f350381a2e73)
\
\
\
**PHONE NUMBER FORM FIELD**
\
\
**Phone number required: prevents user submission without information on required areas of form**
\
\
![phone number required](https://github.com/JCPTrevillian/form_w_validation/assets/95890754/7fbc95de-e679-4c32-9b54-f27298ca469b)
\
\
**Phone number error with helper text 10 total numbers are required (area code and 7 digit phone number)** 
\
\
![phone number error](https://github.com/JCPTrevillian/form_w_validation/assets/95890754/2e0d0a72-4c17-4879-9931-3bf8f35788e4)
\
\
**Regex with conditional (if, then): total 10 digits only if not - error message "Digits only please", if not "!" 10 numbers then error helper message "phone number should be 10 digits"** 
\
\
![phone number validation](https://github.com/JCPTrevillian/form_w_validation/assets/95890754/ad8433cc-7d3e-4c6a-a4f2-2c48db6450d3)
\
\
**Phone number entered correctly, green checkmark for visual validation to user** 
\
\
![name and ph# input correct ](https://github.com/JCPTrevillian/form_w_validation/assets/95890754/b01d05fd-74c3-443d-b5bb-f3706cec6b4d)
\
\
\
**EMAIL FORM FIELD**
\
\
**Email invalid if user enters incorrect format (one character, no @...)**
\
\
![email invalid ](https://github.com/JCPTrevillian/form_w_validation/assets/95890754/2f362a3a-e80e-492d-b319-3a0b2b70aa20)
\
\
**Alternate variant of incorrect data input if user enters full email without @...**
\
\
![invalid email](https://github.com/JCPTrevillian/form_w_validation/assets/95890754/c7160581-aef6-4c70-abdd-9f95f0288f90)
\
\
**Regex:any combination of alphabets upper/lower case, and numbers @ then more alphabets** 
\
\
![email validation](https://github.com/JCPTrevillian/form_w_validation/assets/95890754/f4f8147a-4553-453e-a879-71848c1505ab)
\
\
**Email entered correctly, green checkmark for visual validation to user** 
\
\
![name ph# email input correct](https://github.com/JCPTrevillian/form_w_validation/assets/95890754/920a0781-d028-4091-b523-d35617d763f8)
\
\
\
**MESSAGE FORM FIELD**
\
\
**Message error: not enough data entered**
\
\
![message error - not enough input](https://github.com/JCPTrevillian/form_w_validation/assets/95890754/94be84ad-0560-4363-92af-9b23f31b49c5)
\
\
**Regex: total of 30 characters needed for this form field to be accepted, helper text provides number of remaining characters to meet requirement** 
\
\
![message validation](https://github.com/JCPTrevillian/form_w_validation/assets/95890754/61af6b16-32e7-45d1-b087-982133f232c0)
\
\
**All form fields meet regex conditionals - requirements met** 
\
\
![entire form correct ](https://github.com/JCPTrevillian/form_w_validation/assets/95890754/6d1e1ccd-4aab-49b3-adf7-d9a3f3d58699)
\
\
\
**FINAL FORM VALIDATION**
\
\
**Entire Form Validation. if all 4 form fields meet regex format/conditionals = submit, if not, trigger error message "Correct error to submit")** 
\
\
![form validation ](https://github.com/JCPTrevillian/form_w_validation/assets/95890754/ff0eb582-86f7-46ea-b473-fa9b0d1e38dc)

