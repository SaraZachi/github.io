# Wedding Invitation HTML Template

## Overview

This project is a fully customizable, elegant wedding invitation website built as a single HTML file.

The invitation includes:

- Interactive opening screen
- Animated transitions
- Background music
- Countdown timer
- Wedding details section
- Event schedule timeline
- RSVP form
- Flower petal animation
- Fully responsive design for desktop, tablet, and mobile devices

The template was designed so that anyone can easily personalize it without needing extensive HTML, CSS, or JavaScript knowledge.

---

# Customization Philosophy

Almost everything in the invitation can be changed from the configuration section at the beginning of the JavaScript.

You do not need to search through the entire code to update names, dates, locations, colors, images, or music.

Simply edit the configuration values and the invitation will automatically update.

---

# What Can Be Customized

## Couple Information

You can change:

- Bride name
- Groom name

Example:

```javascript
brideName: "Sara",
groomName: "Vinicius",
```

---

## Wedding Information

You can change:

- Display date
- Countdown date/time
- Ceremony time
- RSVP deadline
- Location
- Full location text
- Dress code
- Additional wedding information

Example:

```javascript
displayDate: "Tuesday, April 20, 2027",
countdownDate: "2027-04-20T16:00:00",
location: "Piracicaba, Brazil",
```

---

## Opening Screen Images

The invitation starts with an animated image sequence.

You can replace all opening images with your own:

### Picture 1

Displayed immediately when the page loads.

Example:

```javascript
openingImage1: "opening-photo.jpg",
```

### Picture 2

Displayed after the user taps the screen.

Example:

```javascript
openingImage2: "transition-photo-1.jpg",
```

### Picture 3

Displayed before entering the invitation.

Example:

```javascript
openingImage3: "transition-photo-2.jpg",
```

These can be:

- Wedding photos
- Engagement photos
- Travel photos
- Family photos
- Floral artwork
- Any image you want

---

## Hero Section Background Image

The main invitation page can also have a custom background image behind:

> We joyfully invite you to celebrate

> Bride & Groom

> Wedding date

> Location

Example:

```javascript
heroBackgroundImage: "hero-background.jpg",
```

---

## Countdown Section Background Image

The countdown section can also have its own background image.

Example:

```javascript
countdownBackgroundImage: "countdown-background.jpg",
```

Popular choices:

- Flowers
- Engagement photos
- Landscape photography
- Soft watercolor textures

---

## Music

You can replace the background music with any audio file.

Example:

```javascript
backgroundMusic: "music.mp3",
```

The music automatically begins when the guest taps the opening screen.

Recommended formats:

- MP3
- M4A
- AAC

---

## Event Schedule

Every timeline item can be edited.

Example:

```javascript
schedule: [
  {
    time: "15:30",
    title: "Guest Arrival",
    description: "Welcome drinks and reception"
  },
  {
    time: "16:00",
    title: "Ceremony",
    description: "Exchange of vows"
  }
]
```

You can:

- Add events
- Remove events
- Change times
- Change descriptions

The timeline will update automatically.

---

## RSVP Form

The RSVP section can be customized.

Examples:

- RSVP deadline
- Confirmation messages
- Field labels
- Form options

You may also connect it to your own backend, Google Forms, or database if desired.

---

# Color Palette

All colors are centralized into a single configuration object.

You can easily change the entire visual identity of the invitation.

Example:

```javascript
colors: {
  background: "#f7f0eb",
  accent: "#b89a6a",
  text: "#3a2e28",
  secondary: "#e8c4c4"
}
```

Possible themes:

- Elegant ivory and gold
- Modern black and white
- Sage green
- Dusty rose
- Navy and champagne
- Terracotta
- Boho neutrals
- Tropical summer

---

# Fonts

Fonts can be changed globally.

Example:

```javascript
fonts: {
  serif: "Cormorant Garamond",
  sans: "Jost"
}
```

Popular combinations:

- Cormorant Garamond + Jost
- Playfair Display + Montserrat
- Cinzel + Lato
- Great Vibes + Poppins

---

# Flower Petal Animation

When entering the invitation, flower petals appear and gently fall across the screen.

You can customize:

- Petal colors
- Number of petals
- Animation speed
- Petal size
- Opacity

The animation is designed to feel romantic and elegant.

---

# Mobile Optimization

The template is designed to work on:

- iPhone
- Android
- Tablets
- Desktop computers

The layout automatically adjusts to screen size.

Timeline events remain centered and organized on mobile devices.

---

# Replacing Images

Place your images in the same folder as the HTML file.

Example:

```
/WeddingInvitation
│
├── invitation.html
├── opening1.jpg
├── opening2.jpg
├── opening3.jpg
├── hero.jpg
├── countdown.jpg
└── music.mp3
```

Then update the configuration values:

```javascript
openingImage1: "opening1.jpg",
openingImage2: "opening2.jpg",
openingImage3: "opening3.jpg",
heroBackgroundImage: "hero.jpg",
countdownBackgroundImage: "countdown.jpg",
backgroundMusic: "music.mp3",
```

---

# Recommended Image Sizes

Opening Images:

- 1920 × 1080 minimum
- Landscape orientation preferred

Hero Background:

- 1920 × 1080 minimum

Countdown Background:

- 1920 × 1080 minimum

For best quality:

- JPG
- PNG
- WebP

---

# No Coding Experience Required

Most users only need to edit the configuration section.

Typical customization process:

1. Replace names
2. Replace dates
3. Replace location
4. Replace images
5. Replace music
6. Adjust colors
7. Save the file
8. Open in a browser

Done.

---

# Notes

This template was intentionally designed to be:

- Easy to customize
- Easy to maintain
- Mobile friendly
- Elegant
- Self-contained in a single HTML file

You may freely adapt it for:

- Weddings
- Engagement parties
- Anniversaries
- Birthday invitations
- Quinceañeras
- Baby showers
- Corporate events
- Any celebration requiring an interactive invitation

Simply replace the content, images, colors, and music with your own.
