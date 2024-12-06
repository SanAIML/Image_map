# Ex04 Places Around Me
# Date:07/10/2024
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
image map.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image map</title>
    
</head>
<body>
    
    

<img src="IM.png" usemap="#image-map">

<map name="image-map">
    <area target="_blank" alt="Sea Tales" title="Sea Tales" href="Sea Tales Restaurant.html" coords="1391,459,1602,506" shape="rect">
    <area target="_blank" alt="Marine Kingdom" title="Marine Kingdom" href="Marine kingdom.html" coords="1343,448,41" shape="circle">
    <area target="_blank" alt="Isckon temple" title="Isckon temple" href="isckon temple.html" coords="890,629,1075,732" shape="rect">
    <area target="_blank" alt="VGP" title="VGP" href="VGP .html" coords="1386,336,1589,414" shape="rect">
    <area target="_blank" alt="Cholamandalam" title="Cholamandalam" href="Cholamandalam.html" coords="1482,1,1640,104" shape="rect">
</map>
    
</body>
</html>

Cholamandalam.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>cholamandal artist village</title>
</head>
<body>
    <h1 style="font-family: cursive; color: rgb(128, 55, 0) ; text-align: center;"> Cholamandal artist village </h1>
    <img src="Cholamandal.png" width="100%" style="align-items: center;">
    <h2 style="font-size: large; font-style: normal; text-align: center;text-decoration: solid;">The Cholamandal Artists’ Village is an idyllic place located on 10 acres of land, about nine km from Adyar, Chennai – along the New Mahabalipuram road. Being India’s largest self-supporting artists’ village and one of the most successful in Asia, this beautiful village is truly a magnum opus of contemporary art. It is equipped with all that is needed for an arts village, esp. the open-air theatre Bharathi that is used for holding discussions and conferences. It has earned reputation world over and is now, one of the major tourist attractions in the Coastal city.

    
        </h2>

    <h3 style="text-align: center;"> For more details contact : +91 5900065551</h3>
    
</body>
</html>

isckon temple.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Iskcon temple</title>
</head>
<body>
    <h1 style="font-family: cursive; color: rgb(43, 205, 226) ; text-align: center;" > Isckon Temple </h1>
    <img src="ISCKON.png" style="border-image: auto;">
    <h2 style="font-size: large; font-style: normal; text-align: center;text-decoration: solid;">SKCON Chennai is located off the East Coast Road at the Hare Krishna land, Sholinganallur. The deities worshipped in the temple include those of Radha Krishna Lalita Vishaka, Jagannath Baladev Subhadra, and Sri Sri Nitai Gauranga.

        ISKCON has more than 500 centers all over the world. The Chennai chapter of ISKCON inaugurated the present gorgeous temple at Sholinganallur on April 26, 2012. It has a lot of unique features. Find the chakras that line the body of the temple-purusha on the steps, see the avatars of the Lord governing the eight directions in attractive glass paintings and more!
        
        Spread over an area of over 1.5 acres, the temple is constructed on five levels. There is a 7,000 sq ft temple hall on the first floor, an auditorium for cultural and spiritual programmes on the ground floor and a prasadam hall in the basement.
        
        In the temple hall, there are three teak-wood altars which house the deities of Lord Krishna with His consort Radharani and their assisting friends Lalita and Vishaka, Lord Chaitanya with Lord Nityananda and Lord Jagannath, Baladeva and Subhadra. These deities have been sourced from Jaipur and Orissa. Designed under the guidance of His Holiness Bhanu Swami, the temple has imbibed various attributes from Vedic scripture and is inspired by the Pallava and Kalinga architecture.
        
        The entrance to the temple is marked by the representation of the universe or the bhu-mandala on the marble floor. According to the cosmology of ancient Vedic puranas, the universe is described as series of circular islands surrounding a central pillar called Mount Meru. The design on the floor at the entrance depicts the same universal pattern. There is also a life-like statue of a cow feeding its calf at the portico.
        
        The primary purpose of the temple to transform the material self-centred identity into a spiritual identity of unconditional love is graphically represented by means of a magnificent chandelier that projects various colours on the walls and ceiling. The chandelier has 500 Himalayan quartz crystals supposedly meant to intensify the spiritual energy in the temple.
        
        The temple also visually displays various vastu shastra features.</h2>

    <h3 style="text-align: center;"> For more details contact : +91 5900065551</h3>
    
</body>
</html>

Marine Kingdom.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Marine kingdom</title>
</head>
<body>
    <h1 style="font-family: cursive; color: rgb(0, 19, 128) ; text-align: center;"> Marine kingdom </h1>
    <img src="Marine kingdom.png" style="align-content: center;">
    <h2 style="font-size: large; font-style: normal; text-align: center;text-decoration: solid;">

    
        The Marine Kingdom is the fourth in the many kingdoms unveiled by VGP. This is India’s first and largest walk-through aquarium housing everything from small to big aquatic animals. The animals here are housed in life-size tanks and over-head aquariums to give you a larger-than-life experience. So welcome to VGP Marine Kingdom, and while you are here, don’t forget to meet the sharks. </h2>

    <h3 style="text-align: center;"> For more details contact : +91 5900065551</h3>
    
    
</body>
</html>


Sea Tales Restaurant.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sea Tales Restaurant</title>
</head>
<body>
    <h1 style="font-family: cursive; color: rgb(0, 128, 51) ; text-align: center;">Sea Tales Restaurant  </h1>
    <img src="Sea Tales.png" width="100%" style="align-items: center;">
    <h2 style="font-size: large; font-style: normal; text-align: center;text-decoration: solid;"> Sea Tales is a restaurant that serves a variety of cuisines from different cultures, regions, and countries. They use different cooking methods, ingredients, and recipes to prepare their dishes. 
        Some common types of dishes served in this restaurant include: Chinese, Continental, Indian, Italian, and American.</h2>

    <h3 style="text-align: center;"> For more details contact : +91 5900065551</h3>
    
</body>
</html>

VGP.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VGP UNIVERSAL KINGDOM</title>
</head>
<body>
    <h1 style="font-family: cursive; color: purple ; text-align: center;"> VGP Universal kingdom </h1>
    <img src="VGP.png" width="100%" style="border-image: auto;">
    <h2 style="font-size: large; font-style: normal; text-align: center;text-decoration: solid;">VGP Universal Kingdom is an amusement park located in East Coast Road in Chennai, Tamil Nadu, India. 
        The park offering small rides during the early days of its history became a full-fledged amusement park in 1997 VGP Universal kingdom, spread over 44 acres provides several fun and adventure rides for children, youth and adults, including attractions such as Tamil Nadu's first Snow park, Petting Zoo, Beach Live Shows, Paneer fort, a massive water complex and more. VGP 2000 millennium tower, Water cascades, Paneer fort and statueman are some of the main attractions.</h2>

    <h3 style="text-align: center;"> For more details contact : +91 5900065551</h3>
    
    
</body>
</html>


```
# OUTPUT
![alt text](<Screenshot 2024-12-06 111838.png>)
![alt text](<Screenshot 2024-12-06 111204.png>)
![alt text](<Screenshot 2024-12-06 111504.png>)
![alt text](<Screenshot 2024-12-06 111656.png>)
![alt text](<Screenshot 2024-12-06 112320.png>)
![alt text](<Screenshot 2024-12-06 112447.png>)





# RESULT
The program for implementing image maps using HTML is executed successfully.
