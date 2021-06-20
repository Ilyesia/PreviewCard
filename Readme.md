## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

### Links
* Solution URL:
* Live Site URL:

## Process
For this challenge I mainly applied Flexbox to help maintain the projects alignment. I started the challenge styling around the mobile format with that in mind the usage of a container element allowed me to modify media queries easily for the site to adjust to desktop and larger formats. Overall a major focus on individual CSS properties.

I decided that this layout lent itself well to using CSS Grid. The mobile first approach did not require that the grid container be set at the outset, I still set it on the container element. This way I just had to add the grid-template-columns setting within the media quiry for larger screens. As I mention below, one of the main challenges within the desktop layout is preventing the paragraph from offsetting the alignment og the 'Learn More' buttons. In order to solve for this I added a flex container lement and used the justify content setting to keep the buttons in horizontal alignment. Finally, another element I spent some time on was the application of the border radius to the first card content and last card content elements. I wanted a solution that would allow for the addition of more card content elements. So, I used the first-child and last-child selectors to apply the border radius.

## Tools Used
* HTML
* CSS
* Google Fonts

## What I Learned
This was my first real test of my CSS and HTML abilities allowing me to better understand the language and understanding how to apply it in a real-world setting.