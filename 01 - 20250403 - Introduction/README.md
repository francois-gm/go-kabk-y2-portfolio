# Introduction

## The “*obligation*” to self-design (15min)

Thinking about one's self-representation online.

1) What do I want to achieve or want out of this? Exposure? Reputation? Work? Income? Legitimacy? Collaboration?
2) Who and where is my audience, and how can I 'reach out' to them (in terms of location, social skills, tone).
3) How shall I 'present my self', language-wise, working out the narrative (the '[obligation to self-design](https://www.e-flux.com/journal/00/68457/the-obligation-to-self-design/)')?
4) What formats can be used to present my self and practice, on which mediums, and on which platforms? (See 1 for hints).

### Options:

- A *website*
- - ... made with a website builder ([webflow](https://webflow.com), [cargo](https://cargo.site), [hotglue](https://hotglue.me), etc) (€–€€).
  - ... made *by hand* using HTML, CSS, and (a bit) of Javascript (?) (€).
  - ... made by someone you commissionned (€€€).

- A *document*
- - ... in the form of an ebook with interactions and hyperlinks.
  - ... or a conventionally (but timelessly) designed .pdf
  - ... hosted online via Dropbox, Google Docs, WeTransfer, etc.
  - ... or a Google Docs / spreadsheet / Github repository?
  - to be sent online by email, to be self-hsoted, to be shared on social medias?
 
- An *online platform presence*
- - ... a social media account (instagram, or what's the flavour of the day?)
  - ... a newsletter (don't forget about user's consent to subscribe to your newsletter)
    
- Being *physical*
  - ... attending cultural events where *peers* are present (be mindful of others – and put your ego aside)
  - ... attending fairs?
  - ... *organizing* events?
  - ... distributing promotional prints (business cards, etc)?

- Or a bit of all that...
 
## Online, a portfolio website

For this workshop, we will think about your online presence in the form of a (traditional) hand-coded website.

### Looking at portfolio websites, some examples (15min)

- (V)
- (V)
- (V)
- (F) [Nicky Tesla](https://nickytes.la)
- (F)
- (F)

### Looking at portfolio websites, your examples (1h, 3min x 20 students)

Think about the questions earlier. Try to answer the following:

1) What they want to achieve?
2) Who is their audience?
3) How they reach out to their audience (which type of language they use, playful, minimal, serious, academic, etc)
4) What do you like about it, and why?
5) What do you don't like about it, and why?
6) Does it work, can you do/find what you were looking for (if the case)?

## Preparing your content (30min)

**Organizing**

1) Create a folder for your (web) project's content.
2) Inside that folder, you can create a folder for each project and name them by their project name.
3) Inside each project folder, you can create a sub-folder named `files`, in this folder you add your images, downloadable documents (like pdfs), videos, etc.
4) Within that project folder, create a `content.txt` (text) file. Inside that text file, add a title and a project description. You can also add additional (textual) information.

**Naming convention**

- **Avoid** the use of special characters in your file names.
- **Avoid** the use of capitalized charaters, as well as spaces. Separate words in your file name by either using a underscore (`my_file.jpg`) or dash (`my-file.jpg`).
- Try to be **descritive** but **concise** in the naming of your files. As an example name your image files by their project names, and what makes them specific (close-up, background view, etc). You can include the date the images were taken as well in the file names. Or the photo credit (who took the picture) in the file name.

**File types**

- Image:
- Video: you can add video files. These need to be .mp4 files. You can compress for web using ().
- Audio: you can add audio files. These need to be .mp3 files. You can compress for web using ().
- Embedded content: you can add videos you've hosted on YouTube, Vimeo, or audio files from SoundCloud.
- Documents: your resume / cv as an example, these can be links to Google Docs or `.pdf` files (exported as *interactive* pdfs and with proper compression).

**Web font resources**

You can use custom fonts in your website.

- Open Foundry **→** [open-foundry.com](https://open-foundry.com/)
- Badass Libre fonts by womxn **→** [design-research.be](https://www.design-research.be/by-womxn/)
- Bye Bye Binary typotheque **→** [typotheque.genderfluid.space](https://typotheque.genderfluid.space)
- Use & Modify **→** [usemodify.com](https://usemodify.com)
- Velvetyne type **→** [velvetyne.fr](https://velvetyne.fr)
- Adobe Typekit **→** [fonts.adobe.com](https://fonts.adobe.com/)
- Google Fonts **→** [fonts.google.com](https://fonts.google.com/)
- Font Squirrel **→** [fontsquirrel.com](https://www.fontsquirrel.com/)

## Preparing media for online use

You will be using lots of media and files on your website from images to videos and fonts. It's important to be **optimal** in terms of **sizes** and **resolutions** to get your website to respond **quickly** and work **properly**.

As a rule of thumbs your website should load under 3000ms (3 seconds).

> "Statistics indicate that **40% of visitors will leave a website** if it takes longer than **three seconds** to load." – [[Source, browserstack](https://www.browserstack.com/guide/how-fast-should-a-website-load)]

Below are some general rules and best practices regarding using media.

### Images

Keep them light, fast and proper.

1. Size: keep your image sizes below **200 kb** (yes that is kilo bytes!)
2. Resolution: don't use images that exceed **1920px width or height**
3. Format: for photos use JPG but for vector images with transparency use either SVG or PNG.
4. GIF: don't use GIF files (use videos on loop instead, .mp4 format).
5. Use browser lazy loading for images: [read more here](https://web.dev/articles/browser-level-image-lazy-loading).* 

\* ... but the **first** visible image on your page should **not** be lazy loaded.

#### How to?

**Compress your .jpg with Photoshop** using the **'Save for Web (Legacy)'** option (under `File->Export`), `[Shift]+[Alt]+[Cmd]+[S]`, with the appropriate image width resizing and the quality setting between **50** and **60** (target under 200kb, the less the better).

If 'Save for Web (Legacy)' is not available, use **'Export As'** (under `File->Export`).

Or, optionally, you can use this mac software called [ImageOptim](https://imageoptim.com/).

### Videos

It's highly recommended to upload your videos to a service such as YouTube or Vimeo because their servers are much faster and they provide good embedding options.

1. Codec: use **H.264** this will reduce file size and keep quality.
2. File format: use **.mp4**
3. Limit the bitrate to preferably **2mb/minute**, but you could go to max 8mb/min if the video is really short.
4. MOV: don't use MOV files.

Tools to convert your video here: [cloudconvert.com/mp4-converter](https://cloudconvert.com/mp4-converter)

**YouTube embedding**

To embed a YouTube video take these steps:

1. Upload video on YouTube
2. Go to video page when it's uploaded
3. Click on the **share** button below video
4. Click on the **embed** button in popup window
5. Copy code
6. Paste in your html document where you want the embedded video (you can change the `width` and `height` parameters to `width="100%"` and `height="auto"`.)

**Vimeo embedding**

To embed a Vimeo video take these steps:

1. Upload video on Vimeo
2. Go to video settings page when it's uploaded
3. Click on **embed** tab on the left navigation panel
4. Click on dark blue **embed code** button (this copies code for you to clipboard)
5. Paste in your html document where you want the embedded video
6. Paste in your html document where you want the embedded video (you can change the `width` and `height` parameters to `width="100%"` and `height="auto"`.)

**How much space do you need?**

**5** **gigabytes** is more than enough. As explained in the using media section below you need to really take care of file size and this will reduce the costs needed for hosting.



## Portfolio inspiration

- [Conversation Taking Place](https://conversation-taking-place.com)
- [Jordy van den Nieuwendijk](https://jordy.studio)
- [Margi Pippi](https://margipippi.com)
- [Nazlı Ercan](https://nazli-ercan.com)
- [Dea Kaker Štrucl](https://deakakerstrucl.com)
- [Anna Cairns](https://annacairns.com)
- [Clara Berger](https://claraberger.net)
- [Studio Bas Koopmans](https://studiobaskoopmans.com/)
- [Studio Pointer*](https://pointer.click/)
- [Sebastian Ly Serena](http://sebastianlyserena.dk)
- [Studio Yannic Poepperling](https://yannicpoepperling.de)
- [Katrin Krumm](https://katrinkrumm.de/)
- [Node](https://node.international/)
- [Michel Egger](https://www.michelegger.ch)
- [Formafantasma](https://formafantasma.com)
- [Parabol Studio](https://parabolstudio.no)
- [Elina Birkehag](https://elinabirkehag.com)
- [Rietlanden Women's Office](https://rietlanden.womensoffice.nl/works.html)
- [Studio Darius Ou](https://dariusou.work)
- [Zeno Beikircher](https://zenobei.com)
- [Büro Vivien Hoffmann](http://www.vivienhoffmann.com)
- [Medusa](https://medusaoffspace.com)
- [Sara Kaaman](https://www.sarakaaman.com)
- [Julijonas Urbonas](https://julijonasurbonas.lt)
- [Studio Remco van Bladel](https://remcovanbladel.nl)
- [Lynne Carty](http://lynnecarty.info)
- [Bram Vanderbeke](https://bramvanderbeke.com)
- [Tom Bubul](https://tombubul.info)
- [Alan Trotter](https://alantrotter.com)
- [Vytautas Kumža](http://vytautaskumza.com)
- [Farah al Qasimi](https://farahalqasimi.com)
- [Ana María Gómez López](https://anamariagomezlopez.info)
- [Lukas Engelhardt](https://lukasengelhardt.net/)
- [Studio Zuzana Kostelanská](https://studiozuzana.xyz)
- [Carmen Dusmet Carrasco](https://www.carmendusmet.net/)
