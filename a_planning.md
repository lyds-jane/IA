Planning
==

Definition of the Problem
---
Maggie Downer is creating an educational program to teach young people about FNAI culture in Canada. She is looking for a website that can both advertise and run the program. This means that there will be a public site that gives some basic information on the program, and then a login page where registered users can access the lesson content. Additionally, since Ms. Downer is not finished developing the course, she wants to be able to login as an administrator to edit and change the information on the website at any time after the development is complete.

Rational for Proposed Solution
--
Since I will be creating a website, I will use a combination of HTML, CSS, and Javascript to fulfill my client's needs. While there are other options like Flask programming available, these three languages are still fairly common and are important skills to learn. Furthermore, Flask uses many code libraries that makes it less secure. For now, I will host the site on a local server. This will let me perform alpha testing and give the user video updates of the product. However, as the client is in a different country, they will be unable to access it. Therefore, once the project is ready to be shown to the client, I will likely use a commercial server like Amazon Cloud because it is cheap and reliable and will let the user access the site from anywhere.

Success Criteria
--

After discussing the product with the client over the phone, I developped the following success criteria: 

* The main website will let a student login to the private website with:
    * The program's modules
    * A function showing how much progress they have completed
  * Administrator logins will take them to a seperate welcome page that lets them:
    * Edit and delete existing modules
    * Add new modules that:
      * Contain a title, a brief description, text, and confirmation questions
      * Have multiple steps and the ability to save progress at the end of a step
      * Can include photos and videos
      * Can include links
    * An option to edit the text and photos of the main website
