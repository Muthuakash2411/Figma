# Ex09 Event Registration Web Application
## Date: 31/05/2026

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:

```html
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="styleguide.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <img class="img" src="img/033ada160fb2de27865db6c8f4175f67-1.png" />
      <button class="button"><div class="text-wrapper">Register</div></button>
      <button class="div"><div class="text-wrapper">Login</div></button>
      <div class="text-wrapper-2">Cultural Festival!</div>
      <img class="text-on-a-path" src="img/text-on-a-path.svg" />
      <img class="whatsapp-image" src="img/whatsapp-image-2025-10-15-at-8-45-45-PM.png" />
      <img class="whatsapp-image-2" src="img/whatsapp-image-2025-10-15-at-8-45-47-PM-1.png" />
    </div>
  </body>
</html>
@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}
.iphone-pro-max {
  background-color: #ffffff;
  width: 100%;
  min-width: 430px;
  min-height: 932px;
  position: relative;
}

.iphone-pro-max .img {
  position: absolute;
  top: 0;
  left: 0;
  width: 430px;
  height: 932px;
  aspect-ratio: 0.56;
  object-fit: cover;
}

.iphone-pro-max .button {
  all: unset;
  box-sizing: border-box;
  top: 751px;
  background-color: var(--color-background-brand-default);
  display: flex;
  width: 191px;
  height: 79px;
  align-items: center;
  justify-content: center;
  gap: var(--size-space-200);
  padding: var(--size-space-300);
  position: absolute;
  left: 105px;
  border-radius: var(--size-radius-200);
  overflow: hidden;
  border: 1px solid;
  border-color: var(--color-border-brand-default);
}

.iphone-pro-max .text-wrapper {
  position: relative;
  width: fit-content;
  font-family: var(--single-line-body-base-font-family);
  font-weight: var(--single-line-body-base-font-weight);
  color: var(--color-text-brand-on-brand);
  font-size: var(--single-line-body-base-font-size);
  letter-spacing: var(--single-line-body-base-letter-spacing);
  line-height: var(--single-line-body-base-line-height);
  white-space: nowrap;
  font-style: var(--single-line-body-base-font-style);
}

.iphone-pro-max .div {
  all: unset;
  box-sizing: border-box;
  top: 641px;
  background-color: #0088ff;
  display: flex;
  width: 191px;
  height: 79px;
  align-items: center;
  justify-content: center;
  gap: var(--size-space-200);
  padding: var(--size-space-300);
  position: absolute;
  left: 105px;
  border-radius: var(--size-radius-200);
  overflow: hidden;
  border: 1px solid;
  border-color: var(--color-border-brand-default);
}

.iphone-pro-max .text-wrapper-2 {
  position: absolute;
  top: 400px;
  left: 41px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #fffcfc;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .text-on-a-path {
  position: absolute;
  top: 90px;
  left: 105px;
  width: 305px;
  height: 151px;
}

.iphone-pro-max .whatsapp-image {
  position: absolute;
  top: 28px;
  left: 32px;
  width: 341px;
  height: 90px;
  aspect-ratio: 3.79;
  object-fit: cover;
}

.iphone-pro-max .whatsapp-image-2 {
  position: absolute;
  top: 164px;
  left: 119px;
  width: 168px;
  height: 156px;
  aspect-ratio: 1.08;
  object-fit: cover;
:root {
  --single-line-body-base-font-family: "Inter", Helvetica;
  --single-line-body-base-font-weight: 400;
  --single-line-body-base-font-size: 16px;
  --single-line-body-base-letter-spacing: 0px;
  --single-line-body-base-line-height: 100%;
  --single-line-body-base-font-style: normal;
  --color-text-brand-on-brand: var(--color-primitives-brand-100);
  --color-background-brand-default: var(--color-primitives-brand-800);
  --color-border-brand-default: var(--color-primitives-brand-800);
  --color-primitives-brand-100: rgba(245, 245, 245, 1);
  --color-primitives-brand-900: rgba(30, 30, 30, 1);
  --color-primitives-brand-800: rgba(44, 44, 44, 1);
  --size-space-200: 8px;
  --size-space-300: 12px;
  --size-radius-200: 8px;
  --colors-colors-blue: rgba(0, 136, 255, 1);
}
[data-color-mode="SDS-light"] {
  --color-text-brand-on-brand: var(--color-primitives-brand-100);
  --color-background-brand-default: var(--color-primitives-brand-800);
  --color-border-brand-default: var(--color-primitives-brand-800);
}

[data-color-mode="SDS-dark"] {
  --color-text-brand-on-brand: var(--color-primitives-brand-900);
  --color-background-brand-default: var(--color-primitives-brand-100);
  --color-border-brand-default: var(--color-primitives-brand-100);
}

[data-color-mode="brand-b-light"] {
  --color-text-brand-on-brand: var(--color-primitives-brand-100);
  --color-border-brand-default: var(--color-primitives-brand-800);
}

[data-colors-mode="light"] {
  --colors-colors-blue: rgba(0, 136, 255, 1);
}

[data-colors-mode="dark"] {
  --colors-colors-blue: rgba(0, 145, 255, 1);
}

[data-colors-mode="IC-light"] {
  --colors-colors-blue: rgba(30, 110, 244, 1);
}

[data-colors-mode="IC-dark"] {
  --colors-colors-blue: rgba(92, 184, 255, 1);
}

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="styleguide.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <img class="img" src="img/e1b7d907d114e6d3a921ca2cfdc7c11c-1.png" />
      <div class="text-wrapper">Events To Be Conducted</div>
      <div class="rectangle"></div>
      <img class="arrow" src="img/arrow-1.svg" />
      <img class="arrow-2" src="img/arrow-2.svg" />
      <img class="arrow-3" src="img/arrow-3.svg" />
      <img class="arrow-4" src="img/arrow-4.svg" />
      <img class="arrow-5" src="img/arrow-5.svg" />
      <img class="arrow-6" src="img/arrow-6.svg" />
      <p class="dance-DJ-night">
        <span class="span"
          >Dance<br />DJ night<br />Fashion walk<br />Theme day<br />Sports<br />Drama<br />Singing<br />Rangoli<br />Food
          stalls<br
        /></span>
        <span class="text-wrapper-2"></span>
      </p>
    </div>
  </body>
</html>
@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}
.iphone-pro-max {
  background-color: #ffffff;
  width: 100%;
  min-width: 430px;
  min-height: 932px;
  position: relative;
}

.iphone-pro-max .img {
  position: absolute;
  top: 0;
  left: 0;
  width: 430px;
  height: 932px;
  aspect-ratio: 0.56;
  object-fit: cover;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 118px;
  left: 10px;
  width: 410px;
  font-family: var(--m3-display-medium-font-family);
  font-weight: var(--m3-display-medium-font-weight);
  color: #fffbfb;
  font-size: var(--m3-display-medium-font-size);
  text-align: center;
  letter-spacing: var(--m3-display-medium-letter-spacing);
  line-height: var(--m3-display-medium-line-height);
  font-style: var(--m3-display-medium-font-style);
}

.iphone-pro-max .rectangle {
  position: absolute;
  top: 265px;
  left: 49px;
  width: 330px;
  height: 507px;
  background-color: #fffdfd;
  opacity: 0.6;
}

.iphone-pro-max .arrow {
  top: 326px;
  left: 49px;
  width: 41px;
  position: absolute;
  height: 15px;
}

.iphone-pro-max .arrow-2 {
  top: 397px;
  left: 51px;
  width: 39px;
  position: absolute;
  height: 15px;
}

.iphone-pro-max .arrow-3 {
  top: 459px;
  left: 53px;
  width: 37px;
  position: absolute;
  height: 15px;
}

.iphone-pro-max .arrow-4 {
  top: 536px;
  left: 56px;
  width: 34px;
  position: absolute;
  height: 15px;
}

.iphone-pro-max .arrow-5 {
  top: 605px;
  left: 51px;
  width: 39px;
  position: absolute;
  height: 15px;
}

.iphone-pro-max .arrow-6 {
  top: 683px;
  left: 68px;
  width: 22px;
  position: absolute;
  height: 15px;
}

.iphone-pro-max .dance-DJ-night {
  position: absolute;
  top: 306px;
  left: 96px;
  width: 233px;
  font-family: "Roboto-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  text-align: center;
  letter-spacing: 0;
  line-height: 36px;
}

.iphone-pro-max .span {
  line-height: var(--m3-display-small-line-height);
  font-family: var(--m3-display-small-font-family);
  font-style: var(--m3-display-small-font-style);
  font-weight: var(--m3-display-small-font-weight);
  letter-spacing: var(--m3-display-small-letter-spacing);
  font-size: var(--m3-display-small-font-size);
}

.iphone-pro-max .text-wrapper-2 {
  font-size: var(--m3-display-medium-font-size);
  line-height: var(--m3-display-medium-line-height);
  font-family: var(--m3-display-medium-font-family);
  font-style: var(--m3-display-medium-font-style);
  font-weight: var(--m3-display-medium-font-weight);
  letter-spacing: var(--m3-display-medium-letter-spacing);
}
:root {
  --m3-display-medium-font-family: "Roboto", Helvetica;
  --m3-display-medium-font-weight: 400;
  --m3-display-medium-font-size: 45px;
  --m3-display-medium-letter-spacing: 0px;
  --m3-display-medium-line-height: 52px;
  --m3-display-medium-font-style: normal;
  --m3-display-small-font-family: "Roboto", Helvetica;
  --m3-display-small-font-weight: 400;
  --m3-display-small-font-size: 36px;
  --m3-display-small-letter-spacing: 0px;
  --m3-display-small-line-height: 44px;
  --m3-display-small-font-style: normal;
}
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="styleguide.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <img class="img" src="img/8aba16bcfe2f755902869df3346ef14a-1.png" />
      <div class="text-wrapper">Register</div>
      <button class="button"><div class="div">Submit</div></button>
      <div class="input-field" data-color-mode="SDS-dark">
        <div class="label">Enter student no.</div>
        <div class="input"><div class="value">Mobile No.</div></div>
      </div>
      <div class="input-field-2" data-color-mode="SDS-dark">
        <div class="label">Event</div>
        <div class="input"><div class="value">Event to be register</div></div>
      </div>
      <div class="input-field-3" data-color-mode="SDS-dark">
        <input class="label-2" placeholder="Age" type="number" />
        <input class="value-wrapper" placeholder="Enter age" type="number" />
      </div>
      <div class="input-field-4" data-color-mode="SDS-dark">
        <input class="label-2" placeholder="Name" type="text" />
        <input class="value-wrapper" placeholder="Enter full name" type="text" />
      </div>
      <div class="input-field-5" data-color-mode="SDS-dark">
        <div class="label">Register No.</div>
        <div class="input"><div class="value">Enter register ID</div></div>
      </div>
      <div class="input-field-6" data-color-mode="SDS-dark">
        <div class="label">Department</div>
        <div class="input"><div class="value">Enter the department</div></div>
      </div>
    </div>
  </body>
</html>
@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}
.iphone-pro-max {
  background-color: #ffffff;
  width: 100%;
  min-width: 430px;
  min-height: 932px;
  position: relative;
}

.iphone-pro-max .img {
  position: absolute;
  top: 0;
  left: 0;
  width: 430px;
  height: 932px;
  aspect-ratio: 0.56;
  object-fit: cover;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 63px;
  left: 70px;
  width: 270px;
  font-family: var(--m3-display-small-font-family);
  font-weight: var(--m3-display-small-font-weight);
  color: #ffffff;
  font-size: var(--m3-display-small-font-size);
  text-align: center;
  letter-spacing: var(--m3-display-small-letter-spacing);
  line-height: var(--m3-display-small-line-height);
  font-style: var(--m3-display-small-font-style);
}

.iphone-pro-max .button {
  all: unset;
  box-sizing: border-box;
  display: inline-flex;
  align-items: center;
  justify-content: center;
  gap: var(--size-space-200);
  padding: var(--size-space-300);
  position: absolute;
  top: 762px;
  left: 170px;
  background-color: var(--color-background-brand-default);
  border-radius: var(--size-radius-200);
  overflow: hidden;
  border: 1px solid;
  border-color: var(--color-border-brand-default);
}

.iphone-pro-max .div {
  position: relative;
  width: fit-content;
  margin-top: -1.00px;
  font-family: var(--single-line-body-base-font-family);
  font-weight: var(--single-line-body-base-font-weight);
  color: var(--color-text-brand-on-brand);
  font-size: var(--single-line-body-base-font-size);
  letter-spacing: var(--single-line-body-base-letter-spacing);
  line-height: var(--single-line-body-base-line-height);
  white-space: nowrap;
  font-style: var(--single-line-body-base-font-style);
}

.iphone-pro-max .input-field {
  display: inline-flex;
  flex-direction: column;
  align-items: flex-start;
  gap: var(--size-space-200);
  position: absolute;
  top: 522px;
  left: 101px;
}

.iphone-pro-max .label {
  position: relative;
  align-self: stretch;
  margin-top: -1.00px;
  font-family: var(--body-base-font-family);
  font-weight: var(--body-base-font-weight);
  color: var(--color-text-default-default);
  font-size: var(--body-base-font-size);
  letter-spacing: var(--body-base-letter-spacing);
  line-height: var(--body-base-line-height);
  font-style: var(--body-base-font-style);
}

.iphone-pro-max .input {
  display: flex;
  min-width: 240px;
  align-items: center;
  padding: var(--size-space-300) var(--size-space-400) var(--size-space-300)
    var(--size-space-400);
  position: relative;
  align-self: stretch;
  width: 100%;
  flex: 0 0 auto;
  margin-bottom: -1.00px;
  margin-left: -1.00px;
  margin-right: -1.00px;
  background-color: var(--color-background-default-default);
  border-radius: var(--size-radius-200);
  overflow: hidden;
  border: 1px solid;
  border-color: var(--color-border-default-default);
}

.iphone-pro-max .value {
  position: relative;
  flex: 1;
  margin-top: -0.50px;
  font-family: var(--single-line-body-base-font-family);
  font-weight: var(--single-line-body-base-font-weight);
  color: var(--color-text-default-default);
  font-size: var(--single-line-body-base-font-size);
  letter-spacing: var(--single-line-body-base-letter-spacing);
  line-height: var(--single-line-body-base-line-height);
  font-style: var(--single-line-body-base-font-style);
}

.iphone-pro-max .input-field-2 {
  top: 626px;
  left: 102px;
  display: inline-flex;
  flex-direction: column;
  align-items: flex-start;
  gap: var(--size-space-200);
  position: absolute;
}

.iphone-pro-max .input-field-3 {
  top: 237px;
  left: 83px;
  display: inline-flex;
  flex-direction: column;
  align-items: flex-start;
  gap: var(--size-space-200);
  position: absolute;
}

.iphone-pro-max .label-2 {
  position: relative;
  align-self: stretch;
  margin-top: -1.00px;
  font-family: var(--body-base-font-family);
  font-weight: var(--body-base-font-weight);
  color: var(--color-text-default-default);
  font-size: var(--body-base-font-size);
  letter-spacing: var(--body-base-letter-spacing);
  line-height: var(--body-base-line-height);
  font-style: var(--body-base-font-style);
  background: transparent;
  border: none;
  padding: 0;
}

.iphone-pro-max .value-wrapper {
  min-width: 240px;
  padding: var(--size-space-300) var(--size-space-400) var(--size-space-300)
    var(--size-space-400);
  position: relative;
  align-self: stretch;
  width: 100%;
  margin-bottom: -1.00px;
  margin-left: -1.00px;
  margin-right: -1.00px;
  background-color: var(--color-background-default-default);
  border-radius: var(--size-radius-200);
  overflow: hidden;
  border: 1px solid;
  border-color: var(--color-border-default-default);
  flex: 1;
  margin-top: -0.50px;
  font-family: var(--single-line-body-base-font-family);
  font-weight: var(--single-line-body-base-font-weight);
  color: var(--color-text-default-default);
  font-size: var(--single-line-body-base-font-size);
  letter-spacing: var(--single-line-body-base-letter-spacing);
  line-height: var(--single-line-body-base-line-height);
  font-style: var(--single-line-body-base-font-style);
}

.iphone-pro-max .input-field-4 {
  top: 153px;
  left: 83px;
  display: inline-flex;
  flex-direction: column;
  align-items: flex-start;
  gap: var(--size-space-200);
  position: absolute;
}

.iphone-pro-max .input-field-5 {
  top: 414px;
  left: 95px;
  display: inline-flex;
  flex-direction: column;
  align-items: flex-start;
  gap: var(--size-space-200);
  position: absolute;
}

.iphone-pro-max .input-field-6 {
  top: 323px;
  left: 92px;
  display: inline-flex;
  flex-direction: column;
  align-items: flex-start;
  gap: var(--size-space-200);
  position: absolute;
}
:root {
  --m3-display-small-font-family: "Roboto", Helvetica;
  --m3-display-small-font-weight: 400;
  --m3-display-small-font-size: 36px;
  --m3-display-small-letter-spacing: 0px;
  --m3-display-small-line-height: 44px;
  --m3-display-small-font-style: normal;
  --single-line-body-base-font-family: "Inter", Helvetica;
  --single-line-body-base-font-weight: 400;
  --single-line-body-base-font-size: 16px;
  --single-line-body-base-letter-spacing: 0px;
  --single-line-body-base-line-height: 100%;
  --single-line-body-base-font-style: normal;
  --body-base-font-family: "Inter", Helvetica;
  --body-base-font-weight: 400;
  --body-base-font-size: 16px;
  --body-base-letter-spacing: 0px;
  --body-base-line-height: 139.9999976158142%;
  --body-base-font-style: normal;
  --color-text-brand-on-brand: var(--color-primitives-brand-100);
  --color-text-default-default: var(--color-primitives-gray-900);
  --color-background-default-default: var(--color-primitives-white-1000);
  --color-border-default-default: var(--color-primitives-gray-300);
  --color-background-brand-default: var(--color-primitives-brand-800);
  --color-border-brand-default: var(--color-primitives-brand-800);
  --color-primitives-brand-100: rgba(245, 245, 245, 1);
  --color-primitives-gray-900: rgba(30, 30, 30, 1);
  --color-primitives-white-1000: rgba(255, 255, 255, 1);
  --color-primitives-brand-900: rgba(30, 30, 30, 1);
  --color-primitives-gray-300: rgba(217, 217, 217, 1);
  --color-primitives-gray-600: rgba(68, 68, 68, 1);
  --color-primitives-brand-800: rgba(44, 44, 44, 1);
  --size-space-400: 16px;
  --size-space-300: 12px;
  --size-radius-200: 8px;
  --size-space-200: 8px;
}

/*

To enable a theme in your HTML, simply add one of the following data attributes to an HTML element, like so:

<body data-color-mode="SDS-light">
    <!-- the rest of your content -->
</body>

You can apply the theme on any DOM node, not just the `body`

*/

[data-color-mode="SDS-light"] {
  --color-text-brand-on-brand: var(--color-primitives-brand-100);
  --color-text-default-default: var(--color-primitives-gray-900);
  --color-background-default-default: var(--color-primitives-white-1000);
  --color-border-default-default: var(--color-primitives-gray-300);
  --color-background-brand-default: var(--color-primitives-brand-800);
  --color-border-brand-default: var(--color-primitives-brand-800);
}

[data-color-mode="SDS-dark"] {
  --color-text-brand-on-brand: var(--color-primitives-brand-900);
  --color-text-default-default: var(--color-primitives-white-1000);
  --color-background-default-default: var(--color-primitives-gray-900);
  --color-border-default-default: var(--color-primitives-gray-600);
  --color-background-brand-default: var(--color-primitives-brand-100);
  --color-border-brand-default: var(--color-primitives-brand-100);
}

[data-color-mode="brand-b-light"] {
  --color-text-brand-on-brand: var(--color-primitives-brand-100);
  --color-text-default-default: var(--color-primitives-gray-900);
  --color-background-default-default: var(--color-primitives-white-1000);
  --color-border-default-default: var(--color-primitives-gray-300);
  --color-border-brand-default: var(--color-primitives-brand-800);
}

```


## OUTPUT:

<img width="724" height="475" alt="image" src="https://github.com/user-attachments/assets/c5ffd655-93b6-4a10-897e-90e2f3881a9f" />

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
