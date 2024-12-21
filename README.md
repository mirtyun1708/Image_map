# Ex04 Places Around Me
# Date:11.11.2024
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Map Example</title>
    <style>
        img {
            max-width: 100%;
            height: auto;
        }
    </style>
</head>
<body><center>
    <h1>MADURAI</h1>
    <p>SANTHOSH P(24900693)</p>
    <img src="map.png" alt="Sample Image" usemap="#image-map">
    <map name="image-map">
        <area shape="rect" coords="95,50,402,169" href="kovil.html" alt="Rectangle Area" target="_blank">
        <area shape="circle" coords="575,156,93" href="kovil2.html" alt="Circle Area" target="_blank">
        <area shape="poly" coords="82,335,43,383,113,427,255,428,336,360,277,330" href="kovil3.html" alt="Polygon Area" target="_blank">
        <area shape="poly" coords="387,201,527,268,410,348,321,292" href="kovil4.html" alt="Polygon Area" target="_blank">
        <area shape="poly" coords="491,412,603,398,663,457,590,507,429,508" href="kovil5.html" alt="Polygon Area" target="_blank">
    </map></center>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
    <meta charset="UTF-8">
    <head>
        <title>
            THE MEENAKSHI AMMAN TEMPLE
        </title>
    </head>
    <body><center>
        <style>
            body{
                background-color: rgb(145, 211, 52);
            }
        </style>
        <br>
        <h1> THE MADURAI MEENAKSHI AMMAN TEMPLE</h1><h1 style="color: red;">MADURAI SOUTH</h1>
        <br>
        <br>
       <img src="/static/madurai-meenakshi-temple.jpg" alt="image">
       <br>
       <br>
       <br>
       <h3>Arulmigu Meenakshi Sundareswarar Temple, also known as Arulmigu Meenakshi Amman Thirukkovil, is a historic Hindu temple located on the southern bank of the Vaigai River[3] in the temple city[4] of Madurai, Tamil Nadu, India. It is dedicated to the goddess Meenakshi Amman, a form of Parvati, and her consort, Sundareshwarar, a form of Shiva.[5] The temple is at the centre of the ancient temple city of Madurai mentioned in the Tamil Sangam literature, with the goddess temple mentioned in 6th-century CE texts.[6] This temple is one of the Paadal Petra Sthalams, which are 275 temples of Shiva that are revered in the verses of Tamil Saiva Nayanars of the 6th-9th century CE.

        The west tower (gopuram) of the temple is the model based on which the Tamil Nadu State Emblem is designed.[7][8]
        
        </h3>
        <br>
        <br>
        <br>
        <p>Madurai Meenakshi Sundareswarar temple was built by Pandyan Emperor Sadayavarman Kulasekaran I (1190 CE–1205 CE). He built the main portions of the three-storeyed Gopuram at the entrance of Sundareswarar Shrine and the central portion of the Goddess Meenakshi Shrine are some of the earliest surviving parts of the temple. The traditional texts call him a poet-saint king, additionally credit him with a poem called Ambikai Malai, as well as shrines (koil) each for Natarajar and Surya near the main temple, Ayyanar in the east, Vinayagar in the south, Kariamalperumal in the west and Kali in the north. He also built a Mahamandapam. Kulasekara Pandya was also a poet and he composed a poem on Meenakshi named Ambikai Malai.[9] Maravarman Sundara Pandyan I built a gopuram in 1231, then called Avanivendaraman, later rebuilt, expanded and named as Sundara Pandya Thirukkopuram.[9] Chitra gopuram (W), also known as Muttalakkum Vayil, was built by Maravarman Sundara Pandyan II (1238-1251). This gopuram is named after the frescoes and reliefs that depict secular and religious themes of Hindu culture. Maravarman Sundara Pandyan II also added a pillared corridor to the Sundareswara shrine and the Sundara Pandyan Mandapam.[9] It was rebuilt after the 14th-century damage, its granite structure was renovated by Kumara Krishnappar after 1595.[10]

            Though the temple has historic roots, most of the present campus structure was rebuilt after the 14th century CE, further repaired, renovated and expanded in the 17th century by Tirumala Nayaka.[11][12] In the early 14th century, the armies of Delhi Sultanate led by Malik Kafur plundered the temple, looted it of its valuables and destroyed the Madurai temple town along with many other temple towns of South India.[13][14][15] The contemporary temple is the result of rebuilding efforts started by the Vijayanagara Empire rulers who rebuilt the core and reopened the temple.[13][16] In the 16th century, the temple complex was further expanded and fortified by the Nayak ruler Vishwanatha Nayakar and later others. The restored complex now houses 14 gopurams (gateway towers), ranging from 45–50 m in height, with the southern gopura tallest at 51.9 metres (170 ft). The complex has numerous sculpted pillared halls such as Aayirankaal (1000-pillared hall), Kilikoondu-mandapam, Golu-mandapam and Pudu-mandapam. Its shrines are dedicated to Hindu deities and Shaivism scholars, with the vimanas above the garbhagrihas (sanctums) of Meenakshi and Sundaresvara gilded with gold.[16][17][18]
            
            The temple is a major pilgrimage destination within the Shaivism tradition, dedicated to Meenakshi Devi and Shiva. However, the temple includes Vishnu in many narratives, sculptures and rituals as he is considered to be Meenakshi's brother.[19] This has made this temple and Madurai as the "southern Mathura", one included in Vaishnava texts.[20][21] The Meenakshi Amman temple also includes Lakshmi, flute playing Krishna, Rukmini, Brahma, Saraswati, and other Vedic and Puranic deities, as well as artwork showing narratives from major Hindu texts. The large temple complex is the most prominent landmark in Madurai and attracts tens of thousands of visitors a day.[22] The temple attracts over a million pilgrims and visitors during the annual 10-day Meenakshi Tirukalyanam festival, celebrated with much festivities and a ratha (chariot) procession during the Tamil month of Chittirai (overlaps with April–May in the Georgian calendar, Chaitra in North India).[23] The Temple has been adjudged the best 'Swachh Iconic Place' in India on 1 October 2017 under Swachh Bharat Abhiyan.[24]</p>
    </center></body>
</html>

<!DOCTYPE html>
<html lang="en">
    <meta charset="UTF-8">
    <head>
        <title>
            Arulmigu Sri Kallazhagar Perumal Temple 
        </title>
        
    </head>
    <body >
        <center>
            <style>
                body{
                    background-color: rgb(168, 122, 22);
                }
            </style>
            <br>
            <h1>
                Arulmigu Sri Kallazhagar Perumal Temple <h1 style="color: rgb(211, 28, 28);">MADURAI NORTH</h1>
            </h1>
            <br>
            <br>
            <img src="/static/Kallazhagar_(31).jpg" width="40%" height="30%"
            <br>
            <br>
            <br>
            <h3>Alagar Kovil is a village in Madurai district in the South Indian state of Tamil Nadu. The history and living of the village is centered around Kallazhagar Temple. Constructed in the Dravidian style of architecture, the temple is glorified in the Nalayira Divya Prabandham, the early medieval Tamil canon of the Alvar saints from the 6th–9th centuries CE. It is one of the 108 Divya Desams dedicated to Vishnu, who is worshiped as Kallalagar and his consort Lakshmi as Tirumamagal.[1]</h3>
        <br>
        <br>
        <br>
        <p>Alagar Kovil is a village in Madurai district in the South Indian state of Tamil Nadu. The history and living of the village is centered around Kallazhagar Temple. Constructed in the Dravidian style of architecture, the temple is glorified in the Nalayira Divya Prabandham, the early medieval Tamil canon of the Alvar saints from the 6th–9th centuries CE. It is one of the 108 Divya Desams dedicated to Vishnu, who is worshiped as Kallalagar and his consort Lakshmi as Tirumamagal.[1]</p>
        </center>
    </body>
</html>

<!DOCTYPE html>
<html lang="en">
    <meta charset="UTF-8">
    <head>
        <title>
            Shri Arulmigu Subramaniya Swami Temple
        </title>
    </head>
    <body>
        <center>
            <style>
                body{
                    background-color: rgb(173, 204, 22);
                }
            </style>
            <br>
            <h1>
                Shri Arulmigu Subramaniya Swami Temple <h1 style=" color: rgb(214, 23, 23);">THIRUMANGALAM</h1>
            </h1>
            <br>
            <br>
            <img src="/static/Thiruparankundram-Murugan-Temple.jpg" width="30%" height="50%"
             <br>
             <br>
             <br>
             <h3>Thiruparankundram Murugan Temple is the first of the six houses of Murugan . This temple is about 8 km southwest of Madurai . It is in a distant town called Tiruparangunram . Legend has it that this is where Murugan married Deivanai . In this temple, Murugan is seen in Manakolam.</h3>
             <br>
             <br>
             <br>
             <p>Turnovers
                Subramaniaswamy's sanctum sanctorum Inscriptions indicate that the cave temple was built for Lord Shiva in 773 AD during the reign of the Pandya king Parantaka Nedunchadayan (765-815) by his general, Satan Ganapati . Among the Nayaka kings of Madurai , Veerappar (1572-1595), Thirumalai king (1623-1659) and Queen Mangammal (1689-1706) have thiruppanis in this temple. [ 1 ]
                
                Temple structure
                The sanctum sanctorum of Tiruparangunram Subramaniaswamy Temple is a cave temple. The sanctum sanctorum has five caves carved into the mountain. There are five sannidhis here namely Subramaniaswamy Sannidhi, Durgadevi Sannidhi, Karpaka Vinayar Sannidhi, Sathyakriswarar Sannidhi and Pavalkanivai Perumal Sannidhi.
                
                The drapery art and other sculptural features found in the figures of Dwarapalas at the gate of the Sathyagriswara Sannidhi are awe-inspiring. Apart from the five Sannidhis, Tiruparangundra temple has Annapurani cave temple and cave temple dedicated to Goddess Jeshta.
                
                In the Artha Mandapam, there are bas-reliefs representing incarnations of Thirumal on the rock next to the Sathyagriswarar Sannidhi and on the rock next to the Pavalkanivai Perumal Sannidhi. The 10 large pillars at the entrance of the temple show the sculptural artistry of the Nayak period. There are pillars like 'Murugan Deivanai Wedding Column'.\</p>
            </center>
    </body>
</html>

<!DOCTYPE html>
<html lang="en">
    <meta charset="UTF-8">
    <head>
        <title>
            Vandiyur Mariamman Theppakulam
        </title>
    </head>
    <body><center>
        <style>
            body{
                background-color: rgb(145, 211, 52);
            }
        </style>
        <br>
        <h1> Vandiyur Mariamman Theppakulam</h1><h1 style="color: red;">MADURAI SOUTH</h1>
        <br>
        <br>
       <img src="theppakulam.jpg" alt="image">
       <br>
       <br>
       <br>
       <h3>
        Vandiyur Mariamman Theppakulam is located near Vandiyur Mariamman temple in Vandiyur area of ​​Madurai city . This pond is 304.8 meters long and wide. There are 12 long steps on four sides of Theppakulam and a stone wall about 15 feet high. In the middle of this there is a Ganesha temple with a garden in the Neerazhi mandapam. There is a connection to the Vaigai River water barge through tunnels . [ 1 ] It is the largest Theppakulam in Tamil Nadu.
        </h3>
        <br>
        <br>
        <br>
        <p>The sand required for the construction of the Tirumala Nayak Palace was dug here by Tirumala Nayak, the king of Madurai . The king, who wanted to repair the area that was hollowed out due to sand digging, cut the area in a square shape and in 1645 [ 2 ] converted it into a Theppakulam and built a Vasantha Mandapam in the middle of it. [ 3 ]

            specialties
            The Pillaiyar, who was found during the excavation, is now in the Meenakshi Amman temple as Mukkuruni Pillaiyar .
            On Thaipusam, theppathruvizha is celebrated here for Goddess Meenakshi and Sundareshwar . More and more people come to Madurai to witness this colorful festival. [ 4 ]</p>
    </center></body>
</html>

<!DOCTYPE html>
<html lang="en">
    <meta charset="UTF-8">
    <head>
        <title>
            Koodal Azhagar Temple
        </title>
    </head>
    <body><center>
        <style>
            body{
                background-color: rgb(145, 211, 52);
            }
        </style>
        <br>
        <h1> Koodal Azhagar Temple</h1><h1 style="color: red;">MADURAI SOUTH</h1>
        <br>
        <br>
       <img src="Koodalazhagar-temple.webp" alt="image">
       <br>
       <br>
       <br>
       <h3>
        This temple is located in the center of the Madurai city and is famous among the temples in Madurai. Again, it is dedicated to Lord Vishnu. Koodal is another name of Madurai, and Azhagar means ‘the beautiful one.’ So, the name defines how beautiful the temple is to visit. A 10-day boat festival is celebrated here on Masi Magam day. This temple has a beautiful architecture that genuinely awe-struck the beholder.

        Timings: 5:30 am to 12:00 pm & 4:00 pm to 9:00 pm
        Dresscode: Decent would work best
        Address: Near Periyar Bus Stand, Madurai 625001
        </h3>
        <br>
        <br>
        <br>
        <p>The sand required for the construction of the Tirumala Nayak Palace was dug here by Tirumala Nayak, the king of Madurai . The king, who wanted to repair the area that was hollowed out due to sand digging, cut the area in a square shape and in 1645 [ 2 ] converted it into a Theppakulam and built a Vasantha Mandapam in the middle of it. [ 3 ]

            specialties
            The Pillaiyar, who was found during the excavation, is now in the Meenakshi Amman temple as Mukkuruni Pillaiyar .
            On Thaipusam, theppathruvizha is celebrated here for Goddess Meenakshi and Sundareshwar . More and more people come to Madurai to witness this colorful festival. [ 4 ]</p>
    </center></body>
</html>

```
# OUTPUT
![Screenshot 2024-12-21 202804](https://github.com/user-attachments/assets/8e26eadc-bbf0-4d01-9312-c9f4b0dabbe5)


![Screenshot 2024-12-21 202524](https://github.com/user-attachments/assets/10b09648-eb50-47d5-986e-8b495de90d37)


![Screenshot 2024-12-21 202536](https://github.com/user-attachments/assets/778f528d-beef-45ca-919e-b5fc58886341)


![Screenshot 2024-12-21 202549](https://github.com/user-attachments/assets/3b072169-6b29-4e66-b2fb-adb141f80448)


![Screenshot 2024-12-21 202601](https://github.com/user-attachments/assets/1f8d2e8d-d244-40f6-a4c9-01c99f1738de)


![Screenshot 2024-12-21 202613](https://github.com/user-attachments/assets/a60ef44a-43ca-4f5e-b54f-5fa92b57a45f)


# RESULT
The program for implementing image maps using HTML is executed successfully.
