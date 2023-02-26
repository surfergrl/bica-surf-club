![alt text](/assets/images/bica-logo.png "BICA surf club Logo")

The **BICA Surf Club** website hosts three pages of information about the surf club based in Llangrannog, West Wales. 

The club was set up in 2007, but the website is now badly out of date and the relaunch requires a new site. The club wants to attract new members, volunteers, sponsors and funding. 

Users of the site (and members of the club) are age 8+ and have differing levels of technological know-how. Users wil include the surf club members themselves, prospective members, volunteers, sponsors, local residents and visitors. 

The website is in Welsh and English, to be welcoming to all, and to meet the criteria for community sport funding. 

**Aims of this website:**

- To allow users to easily find information about what the club offers 
- To reduce the admin burden on the club Secretary by presenting information clearly 
- To show that the community welcomes all surfers 
- To promote the sponsors 
- To collect signup information for interested parties
- To allow people to ask for more information
- To showcase the talent of surfers locally   

-- insert screenshots for each aim 

I have chosen to use three different pages rather than sections on one page. This has allowed me to split the information up and organise it into more manageable sections.  

One page gives basic information on the club including sponsors. 

The Events page is organised to allow people to find suitable activities. Text appears in expandable sections with meaningful headings. It will also include some images of local surfing. 

The Sign Up page allows users to sign up to the club and ask for more information. This directly meets the last two aims of the site. 

**Validation**

HTML run through W3C validator 


CSS run through W3C CSS validator
<p>
    <a href="http://jigsaw.w3.org/css-validator/check/referer">
        <img style="border:0;width:88px;height:31px"
            src="http://jigsaw.w3.org/css-validator/images/vcss"
            alt="Valid CSS!" />
    </a>
</p>
Also run through Jigsaw: 

**Acknowledgements**
Horizontal navigation bar code via this tutorial: https://www.w3schools.com/css/css_navbar_horizontal.asp 

Acknowledgement must go to Flexbox Froggy [http://flexboxfroggy.com/] from Codepip for teaching me flex display and the Flexbox cheatsheet [https://flexbox.malven.co/] used for creating column displays. 

**Credits**
Contact Us page image of Carreg Bica rock: Visit Wales assets https://www.assets.wales.com/assets Crown Copyright 

Hero image by <a href="https://unsplash.com/es/@p_kuzovkova?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Polina Kuzovkova</a> on <a href="https://unsplash.com/photos/0-FBo3a8ytU?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>

**Bugs**

Footer and Sponnos 

Positioning the footer and sponsors sections at the bottom of the screen and having the design respond without main content overlapping them has been solved by extending the height of the main content containers. I think this could be done in a more elegant/true CSS way but have not worked out how. The design works so this has been accepted for now. 

Hero image

I initially chose the image panofeb23-header-s.jpeg (still available in /assets/images) but despite resizing and trying various dispaly options it only ever showed a small portion of the centre of the image. I wanted to include the whole beach panorama. Requested help from Tutor Support who explained that this was not a suitable image as the focus point is too wide. Replaced image with a stock image from Unsplash. 

Logo

I initially wanted the logo to sit neatly on the bottom left of the hero image and move along with it. In the end I am happy with it floating a little more freely - this works well with different viewport sizes. In the end I prefer the logo floating off the header image, as it has a different look in what is otherwise a standard aesthetic. 

**Deployment**

The site has been developed in GitPod using GitHub version control, and deployed on GitHub Pages. 