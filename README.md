
# Responsive Web Design - Critical Rationale

## Usability Principles

### Back to top button

I used a back to top button to make returning to the top more convienient.

### Circular Icons and buttons

I used circular `border-radius` to make the items feel more visually appealing or clickable.

## Techniques

Thoughout my time with this assessment, I learnt how Media Queries can call from the devices screen resolution in order to make special changes for smaller and larger devices. During this, I designed queries for desktop, tablets, and mobile phones (Large, Medium, and Small) 

### Relative measuring units, em and rem

Using the relative units for the text, spacing, margins, and padding was a great habit to get into. I only used px for some drop shadows and border widths. The use of relative units made it easy to scale the size of the aformentioned elements seamlessly, and without having to constantly change the size through media queries.

I did not really get the relative width *for* media queries though. I don't understand why specifically the resolution needs to be in relative units, as the reason everything requires changing is because of the pixel resolution. 

### Navigation and Header

I needed to change the navigation around for it to fit on the smaller screen. For the header, I used a simple `display: flex` for the higher resolutions, and `display block` for the low ones. I also changed the `justify-content` to center on mobile resolutions. 

It was difficult to align the heading to the navigation bar on the Small Mobile resolution, however. 

### Percentages instead of fixed sizes

Using the percentage sizes made it easy to scale images. It also allowed me to scale width of general sectioned elements.

### Using overflow

For the cards, I wanted to make the feeling of going through them naturally. In smaller resolutions, I used `overflow-x: scroll` and I made the gaps a little smaller to signify scroll-ability. 

## References