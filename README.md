# Tax-Calculation
A web-based tax calculator that allows users to calculate their tax based on their income, deductions, and age. This project utilizes HTML, CSS, JavaScript (including jQuery), and Bootstrap for the frontend development.
**OVERVIEW**
![image](https://github.com/ImtiyazzH/Tax-Calculation/assets/112625050/fe1dfb40-5794-4ee2-b2b8-6edec2e9e255)
![image](https://github.com/ImtiyazzH/Tax-Calculation/assets/112625050/cce58ca3-82b1-4294-803a-5c8ea145b643)

**Features**
1. Users can input their gross annual income, extra income, deductions, and age.
2. Tax calculation is based on the provided formula:
    i) Income under 8 Lakhs is not taxed.
    ii) Income over 8 Lakhs is taxed according to the user's age group:
    iii) 30% for age < 40
    iv) 40% for age ≥ 40 but < 60
     v) 10% for age ≥ 60
3. Users are allowed to input incorrect values, and error icons will be displayed with tooltips indicating the error.
4. Age group selection dropdown with options for different age brackets.
5. Stylish UI with background image and Bootstrap components.
6. Info buttons next to each input field provide explanations on hover.
7. Results are displayed in a modal after submission, showing the overall income after tax reductions.
8. Close button functionality in the modal to reset the form.

  ** RUN**
  Open index.html in your web browser.

**  Usage**
Fill in the required information:
Gross Annual Income: Total income earned over the course of one year.
Extra Income: Additional income beyond the primary source.
Deductions: Amount subtracted from the gross income to arrive at the net income.
Age: Select the appropriate age group from the dropdown.
Click the "Submit" button to calculate tax.
View the calculated overall income after tax deductions in the modal.
Close the modal to reset the form for further calculations.
