# PERSONAL-PORTFOLIO-WEBPAGE
*COMPANY* : CODETECH IT SOLUTIONS

*NAME* : GURRALA KISHORE KUMAR 

*INTERN ID* : CT04DN1839

*DURATION* : 4-WEEKS

*MENTOR* : NEELA SANTOSH

*DESCRIPTION * :
The provided code is a complete personal portfolio website developed using HTML and CSS. This portfolio is designed for Gurrala Kishore Kumar, a third-year B.Tech student specializing in Computer Science. The purpose of the site is to showcase the individual's background, technical skills, education, language proficiencies, projects, and contact information in a well-organized and visually appealing manner. The structure follows a clean, semantic approach using modern HTML5 elements like <header>, <section>, and <footer>.

At the top of the HTML document, the <head> section includes essential meta tags such as charset="UTF-8" for character encoding and viewport settings for responsive design on different devices. The <title> tag sets the page title as "My Portfolio," and a link is included to an external CSS file (style.css) for styling the page.

The <body> section starts with a <header> that contains a navigation bar. The navigation bar is defined within a <nav> element with the class navbar. Inside it, there's a heading (<h1>) representing the logo with the name “MyPortfolio” and a list of navigation links wrapped in an unordered list (<ul>) with the class nav-links. Each list item (<li>) includes an anchor tag (<a>) that links to different sections of the page via anchor IDs like #home, #about, #languages, and so on. These anchor links enable smooth navigation within the single-page layout.

Following the header is the #home section, which serves as the landing section. It contains the user’s full name in an <h2> tag and a subheading that describes their role as a "Front-End Developer | Web Enthusiast." There's also a <div> with the class focusing, which displays the phone number. This section is meant to capture the visitor’s attention immediately and provide key identity information.

Next is the #about section, labeled as "OBJECTIVE." This area provides a detailed paragraph that outlines the user’s academic status, current interests, programming languages of focus (Python, Java, C++, HTML, CSS, JavaScript), and motivation to gain practical experience through internships. This statement is helpful for potential employers or recruiters who want to understand the individual’s goals and capabilities.

The #education section comes next. It includes an <h2> tag for the section title and an unordered list that outlines academic background. Two list items describe the B.Tech degree at VISWAM Engineering College (2023–2027) with a CGPA of 8.7, and Intermediate studies at Sri Krishna Reddy Siddartha Junior College (2021–2023) with a CGPA of 8.4. This structured layout ensures that academic history is easy to read and clearly presented.

The #projects section highlights key practical work. It contains a heading and a grid layout of project cards. The two projects mentioned are a major project (a responsive portfolio website) and a mini project (a password generator web app built with HTML, CSS, and JavaScript). The description for each project is encapsulated within individual <div> tags with the class project-card, nested inside a parent project-grid div. The project descriptions emphasize real-world problem solving and web development skills.

The #skills section follows, although it is mistakenly nested inside the projects section. This might be corrected by properly closing the projects section before starting skills. It features a heading "Technical Skills" and a grid layout (skills-grid) of skill boxes (skill-box) that list technologies such as HTML, CSS, JavaScript, Python, Java, Git & GitHub, and basic SQL. Each skill is shown in a styled box to visually distinguish them and enhance readability.

The #languages section lists the spoken languages: English, Telugu, and Kannada. It uses an unordered list to display them under a header <h2>LANGUAGES</h2>. This adds a personal touch, showing the user’s multilingual abilities, which can be valuable in multicultural or regional workplaces.

The #contact section includes two primary contact methods: an email address and a link to the user’s GitHub profile. The GitHub URL is clickable and opens in a new tab (target="_blank"), allowing viewers to explore code repositories and contributions, which are often important for tech-related roles.

Lastly, the <footer> tag at the bottom provides a copyright statement. It uses a &copy; HTML entity to denote copyright, includes the year (2025), and the creator's name.

Now moving on to the CSS part of the code: the styling starts with a universal selector *, which resets margin and padding for all elements and applies box-sizing: border-box, a standard practice to maintain consistent sizing. The font-family is set to "Segoe UI", a modern and clean sans-serif font.

The body is given a light background color #edf1f3 and a line-height of 1.6 for better readability. The header section is styled with a dark background (#222), white text, and internal padding. Inside the .navbar, display: flex is used along with justify-content: space-between to space out the logo and navigation links horizontally. align-items: center vertically centers the content. The navigation links are styled to be bold and white, without underlines, and spaced apart using gap: 1.2rem.

Each .section is given generous padding, a maximum width for readability, and centered using margin: auto. The home section has centered text and a distinct background color (#c5dfe2) to differentiate it from the rest. The .about, .projects, and .contact sections are styled with a white background, rounded corners (border-radius: 8px), padding, and a light box-shadow for depth and separation from the page background.

The .project-grid uses CSS Grid with auto-fit and minmax to ensure responsiveness. It adjusts the number of columns based on screen size, making it mobile-friendly. Each .project-card has its own padding, border, and subtle background styling to visually organize projects.

The .skills-grid is styled using Flexbox to wrap items and ensure equal spacing. Each .skill-box has a light blue background (#e0f7fa), padding, bold text, and a slight shadow to make the skills pop visually. Similarly, the language and education lists have increased padding and margin to enhance spacing.

The footer uses the same dark background as the header for visual consistency, with centered white text. A media query ensures the navbar is responsive: below 768px screen width, the navigation links stack vertically, with reduced gaps and margin for compactness on smaller devices.

* OUTPUT*:
  *Vedio Output*:

  
