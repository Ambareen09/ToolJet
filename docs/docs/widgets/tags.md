---
id: tags
title: Tags
---
# Tags

Tags widget can be used to show array of data as tags.

<div style={{textAlign: 'center'}}>

![ToolJet - Widget Reference - Tags](/img/widgets/tags/tags.png)

</div>

## Properties

### Data

It can be used to set array of tags. It must be an array of objects like this:

```js
[ { title: 'tag1', color: '#000000', textColor: '#fff' }, { title: 'tag2', color: '#fefefe', textColor: 'green' } ]
```

Each object should contain a title, color code of a particular tag, and also a text color.

### General
#### Tooltip

A Tooltip is often used to specify extra information about something when the user hovers the 
mouse pointer over the widget.

Under the <b>General</b> accordion, you can set the value in the string format. 
Now hovering over the widget will display the string as the tooltip.

<div style={{textAlign: 'center'}}>

![ToolJet - widget- button](/img/tooltip.png)

</div>

## Layout

### Show on desktop

Toggle on or off to display the widget in desktop view. You can programmatically determine the value by clicking on `Fx` to set the value `{{true}}` or `{{false}}`.
### Show on mobile

Toggle on or off to display the widget in mobile view. You can programmatically determine the value by clicking on `Fx` to set the value `{{true}}` or `{{false}}`.

## Styles

### Visibility

Toggle on or off to control the visibility of the widget. You can programmatically change its value by clicking on the `Fx` button next to it. If `{{false}}` the widget will not be visible after the app is deployed. By default, it's set to `{{true}}`.