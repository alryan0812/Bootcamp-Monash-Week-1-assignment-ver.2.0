# Bootcamp-Monash-Week-1-assignment-ver.2.0
"# Bootcamp-Monash-Week-1-assignment-ver.2.0" 
<!DOCTYPE html>
<html lang="en-us">

<head>
    <meta charset="UTF-8" />
    <link rel="stylesheet" href="Develop/assets/css/style.css"
    <title> Online Management & Optimization</title>
    <!-- Change title of the website to show better consistancy throughout the page -->
</head>

<body>

    <header class="header">
        <!-- Change from a div tag to the <header> tag to increse the use of semantics within the html code -->
        <h1>Hori<span class="seo">seo</span>n</h1>
        <nav>
            <ul>
                <li><a href="#seo-section">Search Engine Optimization</a></li>
                <li><a href="#orm-section">Online Reputation Management</a></li>
                <li><a href="#smm-section">Social Media Marketing</a></li>
            </ul>
        </nav>
    </header>
         <!-- replacement the </div> tag and Close out using the </nav> tag, shorten the # links to include id tags and class attributes  -->
    
    <!-- In the "hero" class and content area below, I will be changing the <div> tags of the html to the <section> tags to include the use
        of consistant semantics throughout each section of the html code -->
    <!-- Change of the div class to add in the section and article classes with increase semantic elements throughout the <section class="hero">.
        I have also adding the alt tag attribute for image descriptions to enhance accessibility.  -->
    <section class="hero"></section>
        <section class="content">
        <article id="seo-section" class="Search Engine Optimization">
            <img src="Develop/assets/images/search-engine-optimization.jpg" class="float-left" alt="Search Engine Optimization Image" />
            <h2>Search Engine Optimization</h2>
            <p1>
                The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase your visibility and find the right customers for your business.
            </p1>
        </article>
        <!-- change of div to article and replaced the id tag to include the href section from the NAV bar and have included the class tag. I have also adding in the alt tag attribute for image descriptions to enhance accessibility -->
        <article id="orm-section"  class="online-reputation-management">
            <img src="Develop/assets/images/online-reputation-management.jpg" class="float-right" alt="Online Reputation Management"/>
            <h2>Online Reputation Management</h2>
            <p1>
                The web is full of opinions, and some of these can be negative. Social media allows anyone with an internet connection to say whatever they want about your business. Online Reputation Management gives you the control over what potential customers see when they search for your business.
            </p1>
        </article>
        <!-- change of div to article and replaced the id tag to include the href section from the NAV bar and have included the class tag. I have also adding in the alt tag attribute for image descriptions to enhance accessibility. -->
        <article id="smm-section" class="social-media-marketing">
            <img src="Develop/assets/images/social-media-marketing.jpg" class="float-left" alt="Social Media Marketing" />
            <h2>Social Media Marketing</h2>
            <p1>
                Social media continues to have a sizable influence on buying habits. Social media marketing helps you determine which platforms are suited to your brand, using analytics to find the right markets and increase your lead generation.
            </p1>
        </article>
    </section>
    <!--  Changing from the outer div tags to the </section> attibute to continue, replacing the inner 'div' tag with the 'article' elements and added the 'alt' attributes -->
    <section class="benefits">
        <article class="benefit-lead">
            <h3>Lead Generation</h3>
            <img src="Develop/assets/images/lead-generation.png" alt="LeadGeneration Icon" />
            <p2>
                Inbound strategies for lead generation require less work for your business, bringing customers directly to your website.</p>
        </article>
        <article class="benefit-brand">
            <h3>Brand Awareness</h3>
            <img src="Develop/assets/images/brand-awareness.png" alt="Brand Awareness Icon" />
            <p2>Users find your business through paid and organic searches, increasing the search ranking and visibility for your business.</p>   
        </article>
        <article class="benefit-cost">
            <h3>Cost Management</h3>
            <img src="Develop/assets/images/cost-management.png" alt="Cost Management Icon" />
            <p2>As the search ranking for your business increases, your advertising costs decrease, and you no longer need to advertise your page.</p>
        </article>
    </section>
    
<footer>    
    <section class="footer">
        <h2>Made with ❤️️ by Horiseon</h2>
        <p>&copy; 2023 Horiseon Social Solution Services, Inc.</p>

</footer> 
</body>

</html>
