---
# theme id or package name
# Learn more: https://sli.dev/themes/use.html
theme: 'apple-basic'

# what transition to use
transition: 'fade-out'

# title of your slide, will auto infer from the first header if not specified
title: 'Roland - The User Manual'

# titleTemplate for the webpage, `%s` will be replaced by the page's title
titleTemplate: '%s - Slidev'

# information for your slides, can be a markdown string
info: false

# enable presenter mode, can be boolean, 'dev' or 'build'
presenter: true

# enabled pdf downloading in SPA build, can also be a custom url
download: true

# filename of the export file
exportFilename: 'slides'

# export options
# use export CLI options in camelCase format
# Learn more: https://sli.dev/guide/exporting.html
export:
  format: 'pdf'
  timeout: 30000
  dark: false
  withClicks: true
  withToc: false
  
# syntax highlighter, can be 'prism' or 'shiki'
highlighter: 'prism'

# show line numbers in code blocks
lineNumbers: true

# enable monaco editor, can be boolean, 'dev' or 'build'
monaco: 'dev'

# download remote assets in local using vite-plugin-remote-assets, can be boolean, 'dev' or 'build'
remoteAssets: false

# controls whether texts in slides are selectable
selectable: true

# enable slide recording, can be boolean, 'dev' or 'build'
record: 'dev'

# force color schema for the slides, can be 'auto', 'light', or 'dark'
colorSchema: 'auto'

# router mode for vue-router, can be "history" or "hash"
routerMode: 'history'

# aspect ratio for the slides
aspectRatio: '16/9'

# real width of the canvas, unit in px
canvasWidth: 980

# used for theme customization, will inject root styles as `--slidev-theme-x` for attribute `x`
themeConfig:
  primary: '#5d8392'

# favicon, can be a local file path or URL
favicon: 'https://cdn.jsdelivr.net/gh/slidevjs/slidev/assets/favicon.png'

# URL of PlantUML server used to render diagrams
plantUmlServer: 'https://www.plantuml.com/plantuml'

# fonts will be auto imported from Google fonts
# Learn more: https://sli.dev/custom/fonts
fonts:
  sans: 'Roboto'
  serif: 'Roboto Slab'
  mono: 'Fira Code'

# default frontmatter applies to all slides
defaults:
  layout: 'default'

# drawing options
# Learn more: https://sli.dev/guide/drawing.html
drawings:
  enabled: true
  persist: false
  presenterOnly: false
  syncAll: true
---
---
layout: intro
---

# Roland ...

... The User Manual

<div class="absolute bottom-10">
  <span class="font-700">
    roland@tritsch.email, Jun 2023
  </span>
</div>

---
layout: image-right
image: 'images/roland-tritsch-exec.png'
---

# Why?

* Who is Roland?
* What does Roland like when working together?
* What to do to the most out of Roland?
* How to help Roland, so that he can help you?

---
layout: section
---

# Who is Roland?

---

# About ...

<br>
<div class="flex h-80 justify-center">
  <img src="/images/about.png" class="rounded shadow" />
</div>

---
layout: image-right
image: 'images/craftsman.png'
---

# I am a Software Craftsman

* Build and own/operate functional (minimal) systems, that solve a problem (that needs solving)
* Build with functional programming languages
* Build gardens, not jungles (managable cost of ownership)
* My dad is a craftsman (toolsmith). I learned early in life ...
  * ... that you plan, execute, clean/sharpen the tools, rinse and repeat
  * ... to sign my work (it needs to be beautiful; you need to be proud of it)
  * ... that the quality of the tools and material and the level of the craftmanship determines the quality of what you build

---
layout: image-right
image: 'https://live.staticflickr.com/65535/49768700213_0c23e49354_z.jpg'
---

# I am a Manager

* Building functional teams (were people trust and respect each other)
* Building (remote-first) places where great engineers can do there best work
* Help people to find/discover their superpower (everybody got one) and develop it

---
layout: image-right
image: 'images/manager.png'
---

# I am a Leader

* Find problems that need/deserve solving (make the planet a better place)
* Inspire others to deliver on shared objectives - Jeff Weiner
* Be strong. Be kind. Be happy

---
layout: image-right
image: 'images/family.jpg'
---

# I am a Husband and a Father

* Married to a greek woman (Christina; since 1999)
* She gives him roots. I give him wings (Alexandros; since 2002)
* German, but living in Dublin/Ireland (since 2006)

---
layout: image-right
image: 'images/mbti.png'
---

# I am Princess Leia and Darth Vader

* ENTJ & ESTJ (MBTI)
  * Extroverted (strong)
  * Thinking (strong)
  * Judging (strong)
  * Sensing/Intuition (50/50)
* The Executive & The Supervisor
* Princess Leia & Darth Vader

---

# What I value in people ...

<br>
<div class="flex h-80 justify-center">
  <img src="/images/values.png" class="rounded shadow" />
</div>

---

# What I value in organisations ...

<br>
<div class="flex h-80 justify-center">
  <img src="/images/values.png" class="rounded shadow" />
</div>

---
layout: section
---

# Likes and dis-likes ...

---

# I like ...

... on top of what we have already talked about ...

* ... being on-time (running good meetings)
* ... being effective/efficient (do not waste time, money, energy (unnecessarily))
* ... cameradery (a/the feeling of being in it together; building teams that trust and respect each other)
* ... to be kind (not nice; embrace radical candor and productive friction)
  * Build safe places, where you can (respectfully) disagree with each other (but then also disagree-and-commit)
* ... (wired) headsets (I do not need a headset, I can hear you well)
* ... competence (expertise + experience + intelligence)

---
layout: section
---

# Quotes

---
layout: quote
---

# We are what we repeatedly do. Excellence, then, is not an act, but a habit.
Aristotle

---
layout: quote
---

# Optimism is the essential ingredient for innovation.
Robert Noyce

---
layout: section
---

# Appendix - Demo

---

# Default

* Slide bullet text
* Slide bullet text
* Slide bullet text

---
layout: bullets
---

* Slide bullet text
* Slide bullet text
* Slide bullet text

---
layout: intro
---

# Intro Layout

Presentation subtitle

<div class="absolute bottom-10">
  <span class="font-700">
    Author and Date
  </span>
</div>

---
layout: intro-image
image: 'https://live.staticflickr.com/65535/49768700213_0c23e49354_z.jpg'
---

<div class="absolute top-10">
  <span class="font-700">
    Author and Date
  </span>
</div>

<div class="absolute bottom-10">
  <h1>Intro-Image Layout</h1>
  <p>Presentation subtitle</p>
</div>

---
layout: intro-image-right
image: 'https://live.staticflickr.com/65535/49768700213_0c23e49354_z.jpg'
---

# Intro-Image-Right Layout

## Slide Subtitle

---

---
layout: two-cols
---

# Left

* Slide bullet text
* Slide bullet text
* Slide bullet text

::right::

# Right

* Slide bullet text
* Slide bullet text
* Slide bullet text

---
layout: image-right
image: 'https://live.staticflickr.com/65535/49768700213_0c23e49354_z.jpg'
---

# Image-Right Layout

## Slide Subtitle

* Slide bullet text
* Slide bullet text
* Slide bullet text

---
layout: section
---

# Section Layout

---
layout: statement
---

# Statement Layout

---
layout: fact
---

# Fact Layout
Fact information

---
layout: quote
---

# "Quote Layout"
Attribution

---
layout: 3-images
imageLeft: 'https://live.staticflickr.com/65535/49768700213_0c23e49354_z.jpg'
imageTopRight: 'https://live.staticflickr.com/65535/49768700213_0c23e49354_z.jpg'
imageBottomRight: 'https://live.staticflickr.com/65535/49768700213_0c23e49354_z.jpg'
---

---
layout: image
image: 'https://live.staticflickr.com/65535/49768700213_0c23e49354_z.jpg'
---

---
layout: section
---

# Code Highlighter

---
highlighter: shiki
---

# Code Example

```elixir {5|9-13|all}
defmodule Weather.ApiTest do
  @moduledoc false

  use ExUnit.Case
  use ExVCR.Mock, adapter: ExVCR.Adapter.Hackney

  describe "get_forecast/1" do
    test "success: get weather for (correct) city" do
      use_cassette "api_successful_request" do
        {:ok, forecast} = "Lisbon" |> Weather.Api.get_forecast()
        assert forecast["city"]["name"] == "Lisbon"
        assert forecast["city"]["country"] == "PT"
      end
    end
  end
end

```

---
layout: section
---

# Markdown Syntax

---

# Local image

![working][]

* Slide bullet text
* Slide bullet text
* Slide bullet text
 
![working][]

[working]: /images/working.jpg

---

# Local image tag

<img src="/images/working.jpg" style="float:right; margin:auto" width="20%" hspace="5%" vspace="1%"/>

* Slide bullet text
* Slide bullet text
* Slide bullet text
 
<img src="/images/working.jpg" style="display:block; margin:auto" width="80%" hspace="1%" vspace="1%"/>

---

# Local image tag (II)

<img src="/images/working.jpg" class="m-40 h-40 rounded shadow" />

* Slide bullet text
* Slide bullet text
* Slide bullet text

---

# Presenter Notes

* Slide bullet text
* Slide bullet text
* Slide bullet text

<!--
This is a paragraph.

And this is a bullet list ...

* ???
* ???
* ???
-->

---

# Icons

<mdi-account-circle /> - ??? <br/>
<carbon-badge /> - ??? <br/>
<uim-rocket /> - ??? <br/>
<twemoji-cat-with-tears-of-joy /> - ??? <br/>
<logos-vue /> - ??? <br/>

View more/all [icons][] ... like ...

<mi-circle-add />
<mi-circle-remove />
<mi-circle-check />
<mi-circle-error />
<mi-circle-help />
<mi-circle-information />

[icons]: https://icones.js.org

---

# Diagrams

```mermaid
sequenceDiagram
  Alice->John: Hello John, how are you?
  Note over Alice,John: A typical interaction
```

---

# Diagrams (cont.)

```mermaid {theme: 'neutral', scale: 0.8}
graph TD
B[Text] --> C{Decision}
C -->|One| D[Result 1]
C -->|Two| E[Result 2]
```

---

# Element Transition

<v-clicks>

* Slide bullet text
* Slide bullet text
* Slide bullet text

</v-clicks>
