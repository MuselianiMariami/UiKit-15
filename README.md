<h2> 1 გვერდი - Login page </h2>
გვერდზე უნდა იყოს: -  </br>
2 ცალი ტექსტფილდი (username/password) </br>
2 ცალი ღილაკი (sign-in/sign-up) </br>
1 ლეიბლი - ( რაიმე ერორისთვის) </br>

 <h2> 2 გვერდი - Registration page </h2>
გვერდზე უნდა იყოს: - </br>
3 ცალი ტექსტფილდი (username/email/password) </br>
1 ცალი ღილაკი (sign-up) </br>
back ღილაკი </br>
1 ლეიბლი - ( რაიმე ერორისთვის) </br>

<h2> 3 გვერდი - Details page </h2>
გვერდზე უნდა იყოს: - </br>
4 ცალი ლეიბლი - 2 სტატიკური ტექსტით "username: - "  და "email: - " . 2 ცალი ცარიელი კონტენტით </br>
1 ცალი ღილაკი(sign-out) </br>
</br>

<h3> Application Flow: - </h3>

*Login page - დან sign-up ღილაკზე დაჭერის შემდეგ უნდა გადადიოდეს  Registration page-ზე. </br>
*Registration page-ზე  sign-up ღილაკზე დაჭერისას უნდა მოწმდებოდეს რომ ყველა ველი შევსებულია. </br>
*Registration page-ზე მონაცემების შეყვანის შემდეგ sign-up ღილაკზე დაჭერის შემდეგ უნდა გადმოაწოდოთ შეყვანილი მონაცემები და დაბრუნდეს Login page-ზე. </br>
*Registration page-ზე back ღილაკზე დაჭერის შემდეგ უნდა ბრუნდებოდეს Login page-ზე მონაცემების გადმოწოდების გარეშე. </br>
*Login page-ზე, Registration page-ზე შეყვანილი username-ის და password-ის შესაბამის ველებში შეყვანის შემდეგ უნდა გადავიდეთ Details page-ზე. </br>
*Login page-ზე შეყვანილი მონაცემები თუ არ ემთხვევა Registration page-ზე შეყვანილ მონაცემებს ერორისთვის გაკუთვილ ლეიბლში ჩაიწეროს ტექსტი "incorrect credentials"  </br>
*Details page-ზე არსებულ ლეიბლებს უნდა მიენიჭოთ რეგისტრაციის გვერდზე შეყვანილი email და username მონაცემები. </br>
*Details page-ზე Sign-out ღილაკზე დაჭრის შემდეგ უნდა გადადიოდეს Login page-ზე.  </br>
*extra challenge: - შექმენით მეოთხე ინფუთი (confirm password) Registration page-ზე და დაწერეთ პასვორდის ვალიდაციის ლოგიკა: </br>
*password და confirm password ველებში შეყვანილი ინფუთი უნდა იყოს იდენტური წინაანღმდეგ შემთხვევაში Sign-up ღილაკის დაჭერის შემდეგ ერორლეიბლში უნდა ჩაიწეროს ტექსტი  "passwords doesn't match"
</br>
</br>

<div align="center">
<img src="https://github.com/MuselianiMariami/UiKit-15/assets/137683336/857e2b88-2a3f-437e-8943-8055b0f04276"  width="300">
<img src="https://github.com/MuselianiMariami/UiKit-15/assets/137683336/023f9e10-1d2b-40c7-a0cd-dce8ac1d894a"  width="300">
</br>
<img src="https://github.com/MuselianiMariami/UiKit-15/assets/137683336/897a9074-33ca-4951-9775-f99f36e96137"  width="300">
<img src="https://github.com/MuselianiMariami/UiKit-15/assets/137683336/c9618f06-b2e3-4a14-9f44-7b51f6be5030"  width="300">
</div>

