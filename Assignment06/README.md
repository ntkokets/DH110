## Assignment 6: Interface Design

Nathan Koketsu | DH 110 | Spring 2023

### Introduction
The goal of this project is to improve communication about dietary restrictions to inform grocery buying as well as organize and expedite the process of forming grocery lists. The app is designed to allow people to connect in a way similar to apps like Venmo while sharing specific information about their specific dietary restrictions. This project is very helpful after creating a wireflow since it allows for further refinement on the visual design side of the website. By trying out different iterations, it is helpful to find the most effective designs.

#### Process

I started by considering the goals of the app and the ideas I wanted the app interface to prompt for the user such as simplicity and intuitiveness. Then, I tried testing different settings within Figma and assessed whether they fit these guiding concepts. As I progressed through different iterations of the interface, I conducted 5-second impression tests. The feedback from these tests as well as my personal assessments informed the final design for the interface.

### Digitized Wireflow and Interface Design
The digitized wireflow is present on [this](https://www.figma.com/file/yhxrfdiStRzQVorkyg7KzF/Digitized-Wireflow?type=design&node-id=1%3A9208&t=XYVwyF6TJrmqdG7z-1) page.

The variations in layout, typography, shape, and color are present on [this](https://www.figma.com/file/gexS2VV4N2rfExWLMhSoUk/Interface-Design-System---Nathan-Koketsu?type=design&node-id=32%3A12161&t=JMgBrDlSaU4iPgwL-1) page. The file also includes notes regarding the impression tests conducted for the app.

### Layout

<p align="center">
  <img src="https://github.com/ntkokets/DH110-NathanKoketsu/assets/130080795/3b0b9d1b-3f60-4975-93a0-09d2e84d395d" alt="Layouts screenshot" height = "400px"/>
</p>

In determining a layout, I wanted to prioritize readability while making sure that the spacing ensures optimal grouping of elements and does not feel too crowded into the screen space.

**Iterations**

5 rows, 5 columns

Margins: 40

Gutter: 10

> While this was a helpful layout for placing the title, back button, and “Edit” button, it may be more useful to implement more rows and columns to improve the placement of text within the list boxes.

6 rows, 4 columns

Margins: 30

Gutter: 10

> With this layout, the interface felt more crowded at the top and on the sides. The boxes feel too long, and the text does not feel as well-spaced as the previous iteration.

8 rows, 3 columns

Margins: 40

Gutter: 10

> Based on the previous layouts, I found that this has the best balance of spacing out different sections of the interface while providing guidance for text within the boxes. The text used next to the back button, title, and text in the boxes all match up more effectively. Fewer columns are more appropriate for the number of sections in the interface.

> The top elements (device header, back button, “Folders” text, and “This Month” title are all spaced 15 px away from each other height-wise). The small profile icons are spaced 6 px away from the text above them height-wise.

### Typography

<p align="center">
  <img src="https://github.com/ntkokets/DH110-NathanKoketsu/assets/130080795/238868ec-6299-42fd-8aa0-30fb90d54ee1" alt="Fonts screenshot" height = "400px"/>
</p>

While I knew I wanted a sans serif font for simplicity, I wanted one that could be readable, even in a smaller size, while also feeling more intentionally chosen for the app rather than being a default font.

**Iterations**

Font: Inter

> Fits the simple concept and is easily readable.

Font: Nunito Sans

> Maintains some of the readability while adding some uniqueness, though some aspects like having curved lower-case “L’s” may make the font harder to read with a 0 tracking setting.

> Therefore, tracking is increased to 1, and Nunito Sans will be used for the app interface.

Font: Quicksand

> While it does not have the readability issue when at 0% tracking, the letter lines are too thin to be easily readable compared to the other fonts.

### Shape

<p align="center">
  <img src="https://github.com/ntkokets/DH110-NathanKoketsu/assets/130080795/e0c33eb0-0799-4de9-8130-40fce0469b9f" alt="Shapes screenshot" height = "400px"/>
</p>

In choosing a shape, I wanted to avoid the harsh feel of using sharp corners while also ensuring not to make them too rounded, as this would make the boxes feel much smaller and more cramped.

**Iterations**

Roundness: 17

> I think that this shape design has a good balance between being too round, which could make the boxes feel too small, and having sharp edges. Ultimately, I decided to use this setting for the final interface.

Roundness: 0

> The sharp edges can create some discomfort in interacting with this page, especially with the outlines used for the boxes. Therefore, it should not be used.

Roundness: 30

> Here, the edges are so rounded that it makes the boxes feel more cramped. This goes to the opposite end of making them feel more uncomfortable to interact with. This setting should not be used either.

### Color

I wanted to find a color scheme that would reflect simplicity, since one of the goals of the app is to make grocery shopping more efficient and intuitive. Additionally, I wanted one that would create a general association with grocery shopping.

**Iterations**

<p align="center">
  <img src="https://github.com/ntkokets/DH110-NathanKoketsu/assets/130080795/2c9f51ca-37a7-44e1-8243-231d14df14f1" alt="Color 1 screenshot" height = "500px"/>
</p>

<p align="center">
  <img src="https://github.com/ntkokets/DH110-NathanKoketsu/assets/130080795/2387ecea-419b-41f0-bf71-94d07a4d8549" alt="Color 1 A11y screenshot light" height = "400px"/>
</p>

<p align="center">
  <img src="https://github.com/ntkokets/DH110-NathanKoketsu/assets/130080795/434e278f-e9c9-4879-8147-2ee7defa432f" alt="Color 1 A11y screenshot dark" height = "400px"/>
</p>

> I found that this color scheme is simple in a good way, and the green, gray, and off-white colors are appropriate to an app that focuses on grocery shopping. The green is noticeable while being somewhat calming, which works for the app’s goal. There are not any gradients used, which fits the idea of making grocery shopping more efficient and simple.

> Additionally, both the light and dark mode displays pass the A11y color contrast checks.

<p align="center">
  <img src="https://github.com/ntkokets/DH110-NathanKoketsu/assets/130080795/bc571b3d-1a69-4560-80c8-51b04f821f8b" alt="Color 2 screenshot" height = "500px"/>
</p>

<p align="center">
  <img src="https://github.com/ntkokets/DH110-NathanKoketsu/assets/130080795/34f7d4d3-729c-40ff-ac57-35b24c9b4e0f" alt="Color 2 A11y screenshot light" height = "400px"/>
</p>

<p align="center">
  <img src="https://github.com/ntkokets/DH110-NathanKoketsu/assets/130080795/182aedbd-4cd1-451d-ae6a-17ad7bb31376" alt="Color 2 A11y screenshot dark" height = "400px"/>
</p>

> This color scheme has subtle differences from the first color scheme since the background color and gray used are only slightly different than the first color scheme. This is mainly because, with a relatively simple color scheme with basic secondary colors, it does not appear very different. The primary difference is in the focus color, which is orange-brown rather than green.
Like the first color scheme, this passes the A11y color contrast checks.

> However, based on impression tests, this design did not evoke a grocery shopping focus as well as the first color scheme. Instead, it reflected locations such as coffee shops. Therefore, this does not communicate the goals of the app as effectively.

### Impression Test Link

The link to a video of the second impression test is [here](https://drive.google.com/file/d/1v1AlS94XAR1jkvvhXcct14oTBxLdBg5d/view?usp=sharing). There are Zoom messages available from the first test, and notes are available on the Figma document.

#### Notes

**Impression Test 1**

<p align="center">
  <img src="https://github.com/ntkokets/DH110-NathanKoketsu/assets/130080795/3cec02da-6d81-4525-97ce-c95a734b7b62" alt="Impression test 1 screenshot" height = "400px"/>
</p>

The above design was shown to the first impression test participant over Zoom, who provided the feedback below.

* The participant did not see any significant issue in the layout
* While it was not necessarily a critique, the participant commented that the color scheme brought a coffee shop to mind, which is different than the grocery shopping theme intended
* The participant also commented that more colors and images should be added, which was a good indicator to substitute the “no profile photo” image for real profile photos. This way, there could be a better sense of how the app would look with colors
* While the chosen wireframe is meant to showcase much of the app’s overall interface, it didn’t seem like a main page

**Impression Test 2**

<p align="center">
  <img src="https://github.com/ntkokets/DH110-NathanKoketsu/assets/130080795/bea6b4f4-bbb9-4d97-bf65-19d090393548" alt="Impression test 2 screenshot" height = "400px"/>
</p>

The above design was shown to the second impression test participant on an iPad. Notably, this was intended to be more complete by including the top iOS display and profile photos, which have their own colors. While this was not fully accurate to the true appearance of the interface, the participant provided the feedback below.

* The participant liked the “cleaner” layout and the simple green and off-white color scheme
* The participant noted that the “+” button and back button drew the most attention from the interface and that the profile photos tended to draw some attention away from the rest of the interface
* Recommended making the profile photos smaller to draw less attention, though this could be impacted by the size of the iPad used for the test
* Liked the use of rounded shapes rather than sharp corners, as it was easier to look at
* Noted that the text next to the smaller profile photos within each box created a crowded feel. Recommended potentially adjusting the height of the boxes and the size and boldness of the text. A potential fix could also be to rearrange the text and profile photos so they are no longer on the same line.
* The participant also indicated that there could be more fit within the display so that there is not wasted space 

**Impact on Final Design**

<p align="center">
  <img src="https://github.com/ntkokets/DH110-NathanKoketsu/assets/130080795/ca4adc69-734e-4512-aceb-46e0725b386a" alt="Impression test impact" height = "400px"/>
</p>

The feedback received during the two impression tests helped to shape the final design above. As shown, the finalized design has some alterations in the layout and typography, though the color scheme and shapes have remained the same.

### Final Design Choosing Process
Ultimately, the final design for the interface was chosen based on multiple factors. For example, in choosing the layout, the selected design best separated the different sections of the interface for organizational purposes while creating the most effective guideline for text on the page, as the list boxes only have text on the left-hand side while featuring profile pictures and icons. The chosen typography maximized readibility while including greater uniqueness to the app itself. The shape chosen was the most effective balance between the harshness of sharp corners and the cramped feel of corners that were too rounded. This matched findings from the impression tests. Finally, the color scheme was mainly chosen based on how well the colors matched the theme of the app, as some color schemes seemed less evocative of a grocery list app and related more to other ideas.
