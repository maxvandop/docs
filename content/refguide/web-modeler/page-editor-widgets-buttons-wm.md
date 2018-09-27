---
title: "Button Widgets in the Web Modeler"
parent: "page-editor-widgets-wm"
description: "Describes button widgets in the Mendix Web Modeler."
menu_order: 50
tags: ["web modeler", "page editor", "button", "widgets"]
---

## 1 Introduction 

Button [widgets](page-editor-widgets-wm) allow the user to perform <!--trigger?--> various actions, for example, opening a page or executing a microflow.  

![](attachments/page-editor-widgets-buttons-wm/wm-button-widgets.png)

The following **Buttons** are available in the Web Modeler as *Default widgets*:

* Open Page
* Call Microflow
* Create Object
* Save Changes
* Delete Object
* Cancel Changes
* Close Page
* Sign Out
* Open Link

{{% alert type="info" %}}

Apart from the default <!-- in the widgets documentation you call them 'default --> button widgets, you can also [download widgets from the Mendix App Store](https://appstore.home.mendix.com/index3.html) to your app. For more information, see section 4 [Widgets by Origin](page-editor-widgets-wm#widgets-by-origin) in *Widgets in the Web Modeler*.

{{% /alert %}}

## 2 Button Properties

### 2.1 Events Section

Some of the properties in the **Events** section <!-- I think we need a picture here so we can see what you mean by the Events section --> are partially preset for buttons listed above. They depend on the action a button performs. For example, if the button is supposed to open a page, the **On Click Action** in the **Events** section will be **Page**. However, you need to specify what page exactly the button will open. For more information, see section [2.1 Preset Properties in the Events Section](#preset-properties). 

{{% alert type="info" %}}

You can change preset properties, and make the button perform another action. 

{{% /alert %}}

For more information on the **Events** section and on click actions, see [Events Section in Widgets of the Web Modeler](page-editor-widgets-events-section-wm).

**Preset Properties in the Events Section** <a name="preset-properties"></a>
<!-- Don't really want just a 2.1 section if there isn't going to be a 2.2 otherwise people will thing that something is missing -->
<!-- Should this not be "default" rather than "preset"? Preset implies to me that it cannot be changes, whereas defaul means the value that you have if you don't make any changes to it. Is there a problem with using the word "default"? Comment applies throughout this section. -->

**On Click Action** in the **Events** section is preset depending on the action of the button. <!-- Using "default" makes for much nicer sentences... "The default **On Click Action** in the **Events** section depends on the action performed by the button" --> You can find the list of preset actions and properties that need to be configured in the table below. 

| Button         | Preset Action  | Properties to be Configured                                  |
| -------------- | -------------- | ------------------------------------------------------------ |
| Open Page      | Page           | **Page** (Select page)                                       |
| Call Microflow | Microflow      | **Microflow** (Select microflow)                             |
| Create Object  | Create Object  | **Entity** and **Page**                                      |
| Save Changes   | Save Changes   | None                                                         |
| Delete Object  | Delete Object  | None                                                         |
| Cancel Changes | Cancel Changes | None                                                         |
| Close Page     | Close Page     | None                                                         |
| Sign Out       | Sign Out       | None                                                         |
| Open Link      | Open Link      | <!--Could do with a picture here - doesn't make much sense without --> **Link Type** (*Default value*: Web)<br />**Source** (*Default value*: Use literal value)<br />**Url**<br />For more information on these properties, see section [2.2 Open Link Action](page-editor-widgets-events-section-wm#open-link-action) in *Events Section in Widgets of the Web Modeler*. |

### 2.2 General Section

Properties available in the **General** section are described in the table below.

| Property    | Description                                                  |
| ----------- | ------------------------------------------------------------ |
| Caption     | Defines the text that will be shown on the button. Buttons have preset captions depending on the action they perform. For more information, see **[Preset Caption](#preset-caption)**, below. |
| Icon        | Determines the icon that will be shown in front of the caption of the button. |
| Render Mode | Defines the way the button will be shown to the end-user. Possible options are the following: <ul><li>**Button** – the widget will be rendered as a button</li><li>**Link** – the widget will be rendered as a hyperlink</li></ul><br />*Default value:* Button |
| Style       | Applies a predefined styling to the button. Possible options are the following: <ul><li>Default</li><li>Inverse</li><li>Primary</li><li>Info</li><li>Success</li><li>Warning</li><li>Danger</li></ul><br />*Default value for all buttons except the **Save Changes** button:* Default<br />*Default value for the **Save Changes** button*: Success<br />The color for each style depends on your settings in the **Theme Customizer**. For details, see [Theme Customizer in the Web Modeler](theme-customizer-wm). |

**Preset Caption** <a name="preset-caption"></a>

**Caption** in the **General** section is preset depending on the action of the button. The preset caption for each button type is shown in the table below. 

| Button         | Preset Caption |
| -------------- | -------------- |
| Open Page      | Page           |
| Call Microflow | Microflow      |
| Create Object  | New            |
| Save Changes   | Save           |
| Delete Object  | Delete         |
| Cancel Changes | Cancel         |
| Close Page     | Close          |
| Sign Out       | Sign Out       |
| Open Link      | Button         |

## 3 Design Section

For information on the **Design** section and its properties, see [Design Section in Widgets of the Web Modeler](page-editor-widgets-design-section-wm).

## 4 Related Content

* [Page Editor Overview in the Web Modeler](page-editor-wm) 
* [Widgets in the Web Modeler](page-editor-widgets-wm)
