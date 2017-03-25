# NSS Static-Web Exercise: Banking Form

### Description:
Build a form that accepts a loan application. It must have the following fields.

1. Applicant first name
2. Applicant middle initial
3. Applicant last name
4. Applicant address
5. Applicant occupation
6. Applicant employer
7. Employer address
8. Type of loan select element with these options:
	i. Commercial
	ii. Real estate
	iii. Personal
	iv. Mortgage
9. Requested amount of loan
10. Radio button elements for loan length
	i. 5 years
	ii. 15 years
	iii. 30 years
11. Checkbox group for special conditions
	i. I have a down payment
	ii. Out-of-state resident
	iii. Married
	iv. Loan will be co-signed
12. A text area to allow for additional comments
13. Applicant email address
14. Applicant telephone number
15. Applicant LinkedIn URL

Validation:
>There are CSS selectors that you can use to check for the validity of the new HTML5 input types of email, tel, phone, etc. Your task is to enhance your Google Fu and find out what they are.

>Paste the banking form HTML into your document.
When a valid web URL or email address is entered into the corresponding field, the color of the field should be green.
If the value is invalid, the color should be red.

### Final Result:
Demonstrates basic form and input field validation understanding.

![Banking Form Screenshot](https://raw.githubusercontent.com/hhthacker/banking-form/master/bankingform.png)


### How to run:
```
git clone https://github.com/hhthacker/banking-form.git
cd banking-form
npm install http-server -g
http-server -p 8080
```

This will show in your browser at:
`http://localhost:8080`

### Contributors:
[Heather Thacker](https://github.com/hhthacker)