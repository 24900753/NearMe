# Ex04 Places Around Me
## Date: 28-11-2024
## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
map.html

<html>
    <body>
        <h1 align="center">
            <font color="red"><b>OOTY</b></font>
        </h1>
        <h2 align="center">
          <b>
            Vignesh V (24900753)
          </b>  
        </h2>
        <h3 align="center">
<img src="Screenshot 2024-11-28 212147.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Ooty" title="Ooty" href="ooty.html" coords="769,286,921,338" shape="rect">
    <area target="" alt="murugantemple" title="murugantemple" href="temple.html" coords="1040,501,1175,571" shape="rect">
    <area target="" alt="lazosilverlake" title="lazosilverlake" href="lake.html" coords="590,301,757,342" shape="rect">
    <area target="" alt="governmentRoseGarden" title="governmentRoseGarden" href="garden.html" coords="1162,414,948,350" shape="rect">
    <area target="" alt="governmentmuseum" title="governmentmuseum" href="museum.html" coords="1120,218,1288,289" shape="rect">
</map>
        </h3>
    </body>
</html>

ooty.html

<html>

<body bgcolor="lavender">
    <h1 align="center">
        <font color="red">
            OOTY
        </font>
    </h1>
    <h2 align="center">
        Ooty
    </h2>
    <h3>
        <hr>
        <li>
            <font size="5">
                Ooty (Udhagamandalam) is a popular hill station in the Indian state of Tamil Nadu, known for its
                picturesque landscapes, cool climate, and historical significance.
            </font>
        </li>
        <li>
            <font size="5">
                Ooty enjoys a temperate climate, making it a popular summer retreat.
                </font>
                </li>
                <li>
                    <font size="5">
                Summer (March–June): Pleasant, with temperatures ranging from 15°C to 20°C.
            </font>
            </li>
            <li>
                <font size="5">
                Winter (November–February): Cold, with temperatures dropping to 5°C or lower.
            </font>
            </li>
            </font>
        </li>
        <li>
            <font size="5">
                Ooty Lake: A man-made lake offering boating activities.
                Botanical Gardens: Famous for a wide variety of plants, flowers, and trees.
            </font>
        </li>
    </h3>

</body>

</html>

museum.html

<html>

<body bgcolor="silver">
    <h1 align="center">
        <font color="red">
            Ooty
        </font>
    </h1>
    <h2 align="center">
        Government Museum
    </h2>
    <h3>
        <hr>
        <li>
            <font size="5">
                Established in 1989, the museum is managed by the Tamil Nadu Department of Museums.
            </font>
        </li>
        <li>
            <font size="5">
                The museum building reflects British colonial architecture with a blend of modern elements.
            </font>
        </li>
        <li>
            <font size="5">
                The museum showcases the rich cultural heritage, natural history, and art of the Nilgiri region.
            </font>
        </li>
        <li>
            <font size="5">
                Geology Section: Displays rocks, minerals, and fossils from the region.
                Botany Section: Features a variety of preserved plant species native to the Nilgiris.
                Zoology Section: Houses a collection of animal specimens, including butterflies, birds, and insects.
                Anthropology Section: Displays tribal artifacts and cultural items related to the indigenous people of
                the Nilgiris.
                Archaeology Section: Exhibits ancient tools and artifacts from the region’s history.
            </font>
        </li>
        </font>
        </li>
        <li>
            <font size="5">
                History and nature enthusiasts, school/college students, and tourists interested in learning about the
                local culture and ecology of Ooty.
            </font>
        </li>
    </h3>

</body>

</html>

lake.html

<html>

<body bgcolor="ivory">
    <h1 align="center">
        <font color="red">
            Ooty
        </font>
    </h1>
    <h2 align="center">
        lazo Silver Lake
    </h2>
    <h3>
        <hr>
        <li>
            <font size="5">
                The Lazio Silver River is located near Ooty in the Nilgiri District of Tamil Nadu, India.
                It flows through the scenic Nilgiri Hills and is a popular spot for nature lovers and tourists.
            </font>
        </li>
        <li>
            <font size="5">
                The ideal time to visit is during the summer (March to June) or post-monsoon (October to November), when
                the weather is pleasant, and the surroundings are lush.
            </font>
        </li>
        <li>
            <font size="5">
                Visitors can enjoy peaceful walks along the riverbanks, enjoy the scenic beauty, and indulge in bird
                watching.
                The river is not a major spot for water activities, but its beauty attracts those looking to experience
                the natural landscape.

            </font>
        </li>
        <li>
            <font size="5">
                It can be reached by road from Ooty, but since it’s a quiet and less commercialized spot, it may require
                some local guidance for direction.
            </font>
        </li>
        </font>
        </li>
        <li>
            <font size="5">
                Lazio Silver River adds to the natural charm of Ooty, offering a serene and picturesque spot for
                relaxation away from the usual tourist crowds.
            </font>
        </li>
    </h3>

</body>

</html>

garden.html

<html>

<body bgcolor="#E0FFFF">
    <h1 align="center">
        <font color="red">
            Ooty
        </font>
    </h1>
    <h2 align="center">
        government Rose Garden
    </h2>
    <h3>
        <hr>
        <li>
            <font size="5">
                Established in 1995 by the Tamil Nadu Horticulture Department.
            </font>
        </li>
        <li>
            <font size="5">
                Home to more than 2,000 varieties of roses, including hybrid tea roses, floribundas, climbers, and
                miniature roses.
            </font>
        </li>
        <li>
            <font size="5">
                The garden is most beautiful during the summer months (March to June) when the roses are in full bloom.
                It is also a great spot to visit during the annual flower show held in May.
            </font>
        </li>
        <li>
            <font size="5">
                Scenic Views: Offers stunning views of the surrounding Nilgiri Hills and Ooty.
                Photography Spot: Popular among photographers due to the vast array of colorful roses.
            </font>
        </li>
        </font>
        </li>
        <li>
            <font size="5">
                The Rose Garden is a major tourist attraction in Ooty, renowned for its vast collection of roses and its
                breathtaking scenic beauty.
            </font>
        </li>
    </h3>

</body>

</html>

temple.html

<html>

<body bgcolor="#E0FFFF">
    <h1 align="center">
        <font color="red">
            Ooty
        </font>
    </h1>
    <h2 align="center">
        Murugan Temple
    </h2>
    <h3>
        <hr>
        <li>
            <font size="5">
                The temple is dedicated to Lord Murugan, the Hindu god of war and the son of Lord Shiva and Goddess
                Parvati.
            </font>
        </li>
        <li>
            <font size="5">
                The temple features Dravidian-style architecture, with intricately carved pillars, and is known for its
                peaceful and spiritual ambiance.
            </font>
        </li>
        <li>
            <font size="5">
                The Murugan Temple in Ooty is believed to have been constructed several decades ago by the Tamil Nadu
                Government for the worship of Lord Murugan, and it holds significant cultural value in the region.
            </font>
        </li>
        <li>
            <font size="5">
                A popular pilgrimage site for devotees of Lord Murugan, especially during the festivals of Thaipusam and
                Skanda Shashti.
                The temple is also an important place for those seeking peace and spiritual solace.
            </font>
        </li>
        </font>
        </li>
        <li>
            <font size="5">
                Apart from its religious significance, the temple is also a popular spot for tourists who wish to enjoy
                a combination of spirituality and scenic beauty in the Nilgiri Hills.
            </font>
        </li>
    </h3>

</body>

</html>


## OUTPUT

![alt text](<balaji/mapapp/static/Screenshot (5).png>)

![alt text](<balaji/mapapp/static/Screenshot (6).png>)

![alt text](<balaji/mapapp/static/Screenshot (7).png>)

![alt text](<balaji/mapapp/static/Screenshot (10).png>)
 
![alt text](<balaji/mapapp/static/Screenshot (9).png>)

![alt text](<balaji/mapapp/static/Screenshot (8).png>)
## RESULT
The program for implementing image maps using HTML is executed successfully.
