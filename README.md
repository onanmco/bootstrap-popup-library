## Bootstrap Popup Library
This library allows you to prepare quick, nice looking and **stackable** popup alerts.
> **Note:** This library depends on the Twitter Bootstrap (v.3 or later)
> I preferred to use Bootstrap via CDN. But it can be used offline as well.
>  [Click here to visit official site of Bootstrap](https://getbootstrap.com/) for further details.
## Usage:
Make sure you have included the **popup.css, popup.js and the svg files** into your project.

>Syntax is simple:

    show_popup(<title>, <message>, <type>);
   >Type can be either 'danger' or 'info'. This is going to specify the look of popup. **You can omit the type**, but in this case it's going to has 'info look' by default.
   >
   >Here are some examples and their outputs:
   

    show_popup('An Error', 'There must be a warning.', 'danger');
	show_popup('Information', 'Very informative message.', 'info');
	show_popup('Another Error', '...', 'danger');

![A screenshot](https://i.hizliresim.com/KXPVBO.jpg)
	
## ENJOY !