In this In-Class Task, you will use structural elements as you create the Trillium Media Design home page, shown in Figure 2.19. Launch a text editor or IDE and open the template.html file from the In-ClassTask2.zip file found in eConestoga -> Evaluations -> In-Class Tasks. Edit the code as follows:
Figure 2.19 Trillium home page
 

1. Modify the title of the web page by changing the text between the <title> and </title> tags to Trillium Media Design.

2. Position your cursor in the body section and code the header element with the text, “Trillium Media Design” contained in an h1 element:
<header>
  <h1> Trillium Media Design</h1>
</header>


3. Code a nav element to contain text that will indicate the main navigation for the website. Configure bold text (use the b element) and use the &nbsp; special character to add extra blank space:
<nav>
  <b>Home &nbsp; Services &nbsp; Contact</b>
</nav>

4. Code a main element that contains the h2 and paragraph elements:
<main>
  <h2>New Media and Web Design</h2>
  <p>Trillium Media Design offers a comprehensive range of
services to take your company&#39;s Web presence to the next
level.</p>
  <h2>Meeting Your Business Needs</h2>
  <p>Our expert designers will listen to you as they create a
website that helps to promote and grow your business.</p>
</main>

5. Configure the footer element to contain a copyright notice displayed in small font size (use the small element) and italic font (use the i element). MAKE SURE to change ‘Your Name Here’ to your actual name. Be careful to properly nest the elements as shown here:
<footer>
  <small><i>Copyright &copy; 2020 Your Name Here</i></small>
</footer>

Save your page as structure.html. Test your page in a browser. It should look similar to Figure 2.19. 
