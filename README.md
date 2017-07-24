# Styleguide Checklist

A checklist of potential things to consider when constructing a styleguide for
a company or project. Currently a work in progress.

In no particular order...

## Brand

### Logo
- [ ] General usage guidelines
- [ ] Logo
- [ ] Logomark 
- [ ] Logotype
- [ ] Clearspace notes
- [ ] Sizing notes
- [ ] Color rules, notes, guides, restrictions
- [ ] Using against 
  - [ ] Background images
  - [ ] Background gradients
  - [ ] Background colors
- [ ] Usage restrictions
- [ ] Appropriate asset usage
- [ ] Assets
  - [ ] .eps
  - [ ] .ai
  - [ ] .sketch
  - [ ] .psd
  - [ ] .svg

## Design Primitives
Base visual styles that can be used for both digital and analog assets.

### Color
  - [ ] General usage guidelines 
  - [ ] Palette
      - [ ] Name
      - [ ] CMYK
      - [ ] PMS 
      - [ ] Hex
      - [ ] rgb
      - [ ] hsl
  - [ ] Combinations of colors for use

### Gradients
  - [ ] General usage guidelines
  - [ ] Combining with text
  - [ ] Color values
  - [ ] Type(s)
  - [ ] Direction

### Typography

#### Typefaces (Font family)
- [ ] Typefaces used
  - [ ] General usage and guidelines
  - [ ] Web
  - [ ] Email
  - [ ] Print

#### Type scale
- [ ] General usage and guidelines
- [ ] Values 
  - [ ] Web
  - [ ] Email
  - [ ] Print

#### Leading / line-height
- [ ] General usage and guidelines
- [ ] Copy
- [ ] Titles / Large font-size
- [ ] Special cases 

#### Tracking / letter-spacing
- [ ] General usage and guidelines
- [ ] Tight value
- [ ] Spaced value

#### Font weights
- [ ] General usage guidelines
- [ ] Define, if any, constraints with font-size
- [ ] Available weights (values)
- [ ] Restriced weight values (if any)

#### Measure (Length of lines of text)
- [ ] General usage notes 
- [ ] Narrow
- [ ] Default
- [ ] Wide

#### Text Alignment
- [ ] Horizontal text alignment value options
  - [ ] Right
  - [ ] Left
  - [ ] Centered
  - [ ] Justified
- [ ] Considerations / guidelines for centering text
- [ ] i18n considerations (Right to Left, Left to Right)
- [ ] Vertical Alignment general usage guidelines

#### Formatting 
- [ ] Dates
- [ ] Time
- [ ] Date range
- [ ] Time range
- [ ] Citations
- [ ] Quotes
- [ ] Author
- [ ] Capitalization 

###  Borders

- [ ] Colors
- [ ] Styles    
- [ ] Size (width)
- [ ] Radii

### Drop & Box Shadows
  - [ ] Colors
  - [ ] Blur
  - [ ] Size
  - [ ] Direction

### Layout
- [ ] Spacing (margins and padding)
- [ ] Breakpoints 
- Grid
  - [ ] Gutters 
  - [ ] Column sizing
  - [ ] Column divisions
- [ ] Component layouts / structure
- [ ] Page layouts
- [ ] Vertical alignment (the whens and hows)

### Graphs and Data Visualizations
- [ ] General usage and guidelines
- [ ] Colors
- [ ] Styles
- [ ] Gradients
- [ ] Labels
  - [ ] Orientation
  - [ ] Capitalization

### Animations
- [ ] Easing functions
- [ ] Timing of animations
- [ ] Animation types i.e Bounce, fade, glow
- [ ] Animated properties

### Icons 
- [ ] General usage guidelines
- [ ] Icon grid system
- [ ] Size API
- [ ] Colors
- [ ] Use w and w/o text
- [ ] Alignment

### Imagery
  - [ ] Photo guidelines
    - [ ] Saliency
    - [ ] Content
    - [ ] Composition
    - [ ] How to combine with text
  - [ ] Illustration styles

### Voice and Tone 
- [ ] General guidelines
- [ ] Marketing
- [ ] App
- [ ] Gender
- [ ] Pronouns
- [ ] Age
- [ ] Vision 
- [ ] Personal attributes
- [ ] Grammar 
  - [ ] Numbers 
  - [ ] Dates
  - [ ] Time
  - [ ] Decimals, Fractions, Percentages
  - [ ] Value ranges 
  - [ ] Money
  - [ ] Telephone numbers
  - [ ] Temperature
  - [ ] Punctuation usage
    - [ ] Colons
    - [ ] Commas
    - [ ] Dashes and hyphens
    - [ ] Ellipses
    - [ ] Periods
    - [ ] Question marks
    - [ ] Exclamation points
    - [ ] Quotation marks
    - [ ] Semicolons
    - [ ] Ampersands
  - [ ] URLS 
  - [ ] Address
  - [ ] States, cities, countries
  - [ ] About company
  - [ ] About other companies
  - [ ] Slang
  - [ ] Internationalization (i18n) notes 
    - [ ] Process
    - [ ] Considerations
  - [ ] Copyright
  - [ ] Trademarks
  - [ ] Wordlist e.g back end vs back-end. Bcc vs BCC

- [ ] Content organization
- [ ] Navigation patterns
- [ ] Notification patterns
- [ ] Error states 
- [ ] Success states 
- [ ] Empty states
- [ ] Loading states
- [ ] Illustration / Graphics guides
- [ ] Photo usage and development
- [ ] Where photos are sourced


### Print collateral
- [ ] General rules and guidelines

### Presentation Assets
- [ ] Slide decks (powerpoint & keynote) 
- [ ] Internal template
- [ ] External template
- [ ] Shared assets
  - [ ] Client / Vendor logo assets

### Marketing materials
- [ ] T-shirts
- [ ] General guidelines
- [ ] T-shirt colors
- [ ] Buttons
- [ ] Pamphlets
- [ ] Posters
- [ ] Booth decals / structure
- [ ] Billboards

### Social media
- Twitter
- [ ] General usage guidelines
- [ ] Avatar
- [ ] Background Image
- Facebook 
- [ ] General usage guidelines
- [ ] Profile photo
- [ ] Background Image
- [ ] Photo albums
- Vimeo / Youtube (Support videos?)
- [ ] Avatar

### TBN
- Existing websites
- New websites and pages 
- Internal tools
- Third party site integrations (zendesk)
- Logged in app

#### Theming
- [ ] Shadows
- [ ] Border radii 
- [ ] Border widths 
- [ ] Border colors
- [ ] Colors
- [ ] Palette
- [ ] Appropriate combinations
- [ ] Constraints for text or background
- [ ] Gradients


#### Icons
- [ ] Collect icon assets
- [ ] Icon 
- [ ] Name
- [ ] Colors
- [ ] Formats for various platforms

#### Design Assets
- [ ] Code 
- [ ] Prototyping templates and resources
  - [ ] React
  - [ ] Vue
  - [ ] Angular
  - [ ] Static HTML
  - [ ] Lodash / handlebars / swig etc.
  - [ ] CSS toolkit
    - [ ] Sass 
    - [ ] Stylus
    - [ ] Less
    - [ ] Postcss
    - [ ] Vanilla

- [ ] Design Templates (XD, Photoshop, Illustrator, Sketch)
- [ ] Icons
- [ ] Typefaces (Actual font files, useful for print design and using apps like photoshop) 


## Style Audit
To understand where we need to go and how we are going to get there, we need to
understand what the current reality is


1. Audit the existing styles for each separate front-end codebase
  - Find intersections of common styles
  - Visualize and compare how values relate to eachother
2. Collect prior print collateral: letterhead, marketing etc. 
3. Collect email screenshots
4. Visualize flows for common patterns
  - Log in
  - Sign up
  - Delete account
  - Lost password reset
  - Change email
  - Change credit card
  - Change address

#### Consuming the styleguide

- Who are all of the people who will consume this?
- What are their biggest needs?
- What needs do they not have that we are assuming they have?
- Onboarding a new designer. What is their process? How can we structure
the styleguide in a way that reduces friction and unknowns for a new teammate or someone collaborating with us?
- Video tutorials
- Written guides and visual examples

#### Common pages
- Landing 
- Error pages
  - 404
  - 500
  - 503
- Help

#### Further Reading

Grid systems 
A pattern language
Strunk and White elements of style
Elements of Typography Style
AMA Manual of Style: http://www.amamanualofstyle.com
ALA Standards Manual
Chicago Manual of Style
