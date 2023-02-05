# CSC309_A1_Homework
CSC309A1 for HomeWork. A Static Web Page

## about.html
## contact.html
## index.html
## style.css


## Header  
   - [x] Number of Links Should be 3
   - [x]  Active Page Font Weight 
   - [x]  Active Page Link Color
   - [x]  Other Pages Link Should be #00b8d4

  Content  
    1) Details Element  
    2) Test toggling details  
    3) There should be 3 class codes when opened  
   - [x] "I have read and understood the University of Toronto's Code of Behaviours on Academic Matters." should exist (167ms)  
   - [x] Padding 0.5rem on left and right (139ms)  
    PDF  
    - [ ] Verify Embed PDF Existence (145ms)  
    - [ ] Max Width 720px (139ms)  
    - [ ] Height Always 60% of Viewport (142ms)  
  
  
  9 passing (16s)  
  3 failing  

# Common Test (For <strong>index.html</strong>)  
   - [x]  no script tag (224ms)  
   - [x]  no style tag (156ms)  
   - [ ]  no inline style attribute (132ms)  
   - [ ]  no links other than style.css (125ms)  
   - [ ]  Only one title (102ms)  
   - [ ]  Header Footer Both Exist (173ms)  
    Header  
     - [ ]  Link Color Turns White On Hover (142ms)  
     - [ ]  Space between links should be 2rem (162ms)  
     - [ ]  Links should be left justified (135ms)  
     1) Header Offset Height between 65 and 75px  
    Footer  
     - [ ]  Footer Height Should be 3rem (48px) (152ms)  
     2) Footer Copyright Text  
    Main  
     - [ ]  Every Immediate Child of <main> should be centered
    Navigation Between Pages  
     - [ ]  Navigation Between Pages
  
# Common Test (For <strong>about.html</strong>)  
   - [x]  no script tag (118ms)  
   - [x]  no style tag (114ms)  
   - [x]  no inline style attribute (113ms)  
   - [x]  no links other than style.css (112ms)  
   - [x]  Only one title (118ms)  
   - [x]  Header Footer Both Exist (134ms)  
    Header  
     - [ ]  Link Color Turns White On Hover (194ms)  
     - [ ]  Space between links should be 2rem (148ms)  
     - [ ]  Links should be left justified (146ms)  
      3) Header Offset Height between 65 and 75px  
    Footer  
     - [ ]  Footer Height Should be 3rem (48px) (125ms)  
      4) Footer Copyright Text  
    Main  
     - [ ]  Every Immediate Child of <main> should be centered (126ms)  
    Navigation Between Pages  
     - [ ]  Navigation Between Pages (1121ms)  
  
 # Common Test (For <strong>contact.html</strong>)  
   - [ ]  no script tag (141ms)  
   - [ ]  no style tag (150ms)  
   - [ ]  no inline style attribute (169ms)  
   - [ ]  no links other than style.css (139ms)  
   - [ ]  Only one title (138ms)  
   - [ ]  Header Footer Both Exist (146ms)  
    Header  
     - [ ]  Link Color Turns White On Hover (141ms)  
     - [ ]  Space between links should be 2rem (153ms)  
     - [ ]  Links should be left justified (147ms)  
      5) Header Offset Height between 65 and 75px  
    Footer  
     - [ ]  Footer Height Should be 3rem (48px) (142ms)  
      6) Footer Copyright Text  
    Main  
     - [ ]  Every Immediate Child of <main> should be centered (172ms)  
    Navigation Between Pages  
     - [ ]  Navigation Between Pages (1133ms)  
  
  
  36 passing (11s)  
  6 failing  

  Header  
   - [ ]  Number of Links Should be 3 (159ms)  
   - [ ]  Active Page Font Weight (124ms)  
   - [ ]  Active Page Link Color (75ms)  
   - [x]  Other Pages Link Should be #00b8d4 (140ms)  
  
  Content  
   - [x]  Portrait (143ms)  
   - [x]  Full Name in Bold (122ms)  
    Email Address  
     - [ ]  Existence (125ms)  
     - [ ]  Font Family: 'Times New Roman' (121ms)  
      1) Email URL Content  
    Form  
     - [ ]  Expect 1 Textarea with correct placeholder (132ms)  
     - [x]  Expect 3 or 4 Labels (125ms)  
     - [x]  Expect Label Keywords (142ms)  
     - [x]  Keywords: "You agree to receive emails from me" (132ms)  
     - [ ]  Checkbox Exists (126ms)  
      2) Checkbox 50% Larger default  
     - [ ]  Send Feedback Button Exists (135ms)  
      3) Form Inputs Have Correct Names (for form submission)  
  
  Responsive Design  
    4) Don't stack label and input when width > 480  
   - [ ]  Stack Label and Input when Width <= 480 (154ms)  
  
  
  15 passing (7s)  
  4 failing  

| Spec | q                   | Passing | Failing | Pending |
|------|---------------------|---------|---------|---------|
| ✖    | about.cy.js         | 12      | 9       | 3       |
| ✖    | common.cy.js        | 42      | 36      | 6       |
| ✖    | contact.cy.js       | 19      | 15      | 4       |
| ✔    | index.cy.js         | 10      | 10      | -       |
| ✖    | 3 of 4 failed (75%) | 83      | 70      | 13      |
