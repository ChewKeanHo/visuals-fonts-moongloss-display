# Moongloss Display Font | (Holloway) Chew, Kean Ho's Creative Visuals

[![banner](/Pictures/banner_1200x630.svg)](#)

Moongloss Display is a Latin (ID: `*Latn`) Display font designed by
[The Moongloss Display Project Team](https://moonglossfont.github.io).
Its design is based on monospaced characters to look functionally,
technologically, and reasonably futuristic for date, time, or minor info
display purposes. There are 3 families for specific applications:

* `Moongloss Display` - standard thick styled typeface
* `Moongloss Display Medium` - slightly slimed styled typeface
* `Moongloss Display Thin` - slim styled typeface

This font is ideal for eye-catching general use like poster title, movie title,
movie notice headings, and body headings.




## Verifying Content Integrity

[![banner](/.internals/trademarks/banner_1200x100.svg)](#)

To secure the content from unauthorized modification by anyone down to `0-1` bit
level, all documents and text are cryptographically signed using one or more
cryptography tools such as but not limited to:

* [GnuPG](https://gnupg.org); AND/OR
* [OpenSSL](https://www.openssl.org/).

The public key and the associated certificate are attached. Only I keep and
maintain the private keys. To verify the content's integrity:



### GnuPG

1. Install [GnuPG](https://gnupg.org) software if not present.
2. Download the target file and its detached signature file (the `.asc` file
   with the same filename).
3. Download the public key file (`.gpg`).
4. Place them next to each other in the directory.
5. Open a terminal and execute the following command:

```
$ gpg --no-default-keyring --keyring /path/to/public.gpg --verify /path/to/file.asc
```



### OpenSSL

1. Install [OpenSSL](https://www.openssl.org) software if not present.
2. Download the target file and its detached signature file (the `.sig`/`.sign`
   file with the same filename).
3. Download the public certificate file (`.pem`) containing the public key
   within.
4. Place them next to each other in the directory.
5. Open a terminal and execute the following command:

```
$ openssl dgst -verify /path/to/pubkey.pem -signature /path/to/file.sig /path/to/file
```




## Artificial Intelligence (A.I.) Decrees

[![banner](/.internals/trademarks/banner_1200x100.svg)](#)

> [!CAUTION]
>
> Note to Maintainers: Update each sub-section here matching the project’s
> specifications from time-to-time especially between releases.

This decree defines the project’s policy on the use of Artificial Intelligence.
The following sections list data lifecycle activities and indicate whether A.I.
is deployed. Unless explicitly stated otherwise (e.g. deployment with
specifics), A.I. is not used for these tasks.



### Data Sourcing & Acquisition

> [!Note]
>
> Example activities:
>
> * Performing enhanced web searches due to search engine pollution by A.I.
>   slop contents.
> * Performing completely auto-generated media such as but not limited to
>   images, videos, and audios.

* Multiple Large Language Model (LLM) A.I.s as the search engine for searching
  research materials across the Internet due to massive unwanted A.I publication
  slops.
* One or more LLM A.I.s as the grammar and language corrector and enhancer for
  superpervised improvement against human written content.
* One or more Transformer-based Diffusion Model A.I.s for generative image
  creation.



### Data Processing & Transformation

> [!Note]
>
> Example activities:
>
> * Performing multi-steps process development.
> * Performing data sanitization like data cleaning and data deduplication.
> * Performing data format compatibility conversion.
> * Constructing and optimizing data processing libraries.
> * Upscaling an image with neural network not achievable with conventional
    image manipulation technologies.

* One or more Convolutional Neural Network (CNN) A.I.s used for upscaling one
  or more images for proper editing.



### Data Storage & Security

> [!Note]
>
> Example activities:
>
> * Performing security and threat detection.
> * Performing `Data at Rest` encryption and health monitoring.
> * Performing encryption data storage management.
> * Performing automated data storage house-keeping.
> * Performing data storage devices health monitoring and mitigation.

* No deployment.



### Data Analysis & Insight Generation

> [!Note]
>
> Example activities:
>
> * Performing multi-steps data analytics.
> * Performing pattern detection and recognition.
> * Developing predictive modelling.
> * Developing natural language queries models.
> * Creating artificial intelligence's neural network models based on data
>   feeds.
> * Optimizing artificial intelligence's transfer learning, hyperparameter
>   tuning, etc.

* No deployment.



### Data Quality Validation & Assurances

> [!Note]
>
> Example activities:
>
> * Performing end-user use case simulated testings.
> * Performing automated sanity testings.
> * Performing penetration & security testings.
> * Performing anomaly detection testings.
> * Performing schema validations.
> * Performing automated testing of data pipelines.

* No deployment.



### Data Visualization & Reporting

> [!Note]
>
> Example activities:
>
> * Performing data graphical visualization creation based on data feeds.
> * Performing summarized dashboarding with graphical design and data feeds.
> * Performing report writing.
> * Performing prediction projections.

* No deployment.



### Data Governance & Compliance

> [!Note]
>
> Example activities:
>
> * Performing personal identifiable information (PII) filtration and removal.
> * Performing regulatory compliance checks (e.g., data filtration, censorship,
>   removal as required by law).
> * Performing compliance monitoring and validation.
> * Performing data lineage tracking and analysis.
> * Performing data audit trail analysis.

* No deployment.



### Data Sharing & Publication

> [!Note]
>
> Example activities:
>
> * Performing document's metadata creation.
> * Performing document translation.
> * Processing data publication licensing and management.

* No deployment.




## Maintainers' Notes

[![banner](/.internals/trademarks/banner_1200x100.svg)](#)

1. **Only keep the `git` repository for font metadata and display purposes**.
   * Font files are binary objects which are **unsuitable for `git` commits**.
   * Use `git tag` and `releases` version control strategy instead.
2. **DO NOT use `git-lfs`** due to ambiguous and inconsistent storage allocation
   policies from various git service providers.
   * It will disrupt the work pipeline causing unwanted data losses downstream.
   * Some requires you to pay for storage space.
3. All fonts **MUST be strictly licensed under
   [Open Font License](http://scripts.sil.org/OFL) without any private
   arbitrary terms (e.g. people from country X are prohibited to use,
   not allowed to re-distribute, trademarking font, etc)**.
   * The goal is for downstream to use the font without fear of anything.
   * Some designers modify the license terms without taking its legal
     concequences into account.
   * When you have a slightest doubt, **DO NOT** commit.
4. To naturally monitor conflicting names and IDs between any font families:
   * **Font Filename** - **STRICTLY THE SAME as the font family name**. If it is
     funny looking; leave it. It is the creators' responsibilities to sort of
     conflicting names and proper naming conventions.
   * **Product SKU** - **replace symbols (e.g. `&` into `and`)** for hardware
     scanning compatibility purposes.
   * If any of the above is conflicting with any of our existing registered
     font(s):
     * Comply to Copyright laws: *the oldest (check its license ownership birth
       time) stays; the new ones get updated*. In any case, the default action
       is **drop the new ones**.
     * If you have the resources to drive the brand changes and prepared to
       possibly face any legal reprecussion from any socially undesirable
       creators, you can drive the conversation in a separate accord.
5. When the font is qualified for re-dstribution, please **DO HELP** the
   upstream creators to clean up their license file and marketing pitches.
   License should have:
   1. A `Copyright [YEAR] [ENTITY_FULL_NAME] (OPTIONAL_URL) <OPTIONAL_EMAIL>`
      header.
      * **`[YEAR]`** - the earliest year is suffice. Copyright works on first
        birth; not range or latest.
      * **`[ENTITY_FULL_NAME]`** - the legally reponsible entity's full name.
      * **`[OPTIONAL_URL]`** - the entity's provided URL to contact. The url is
        enclosed with rounded parenthesis (**`( )`**) as defined by programming
        syntax. This is optional if URL is unavailable. However, Copyright
        requires at least 1 contactable channel so ensure the alternatives are
        available.
      * **`[OPTIONAL_EMAIL]`** - the entity's provided email to contact. The
        address is enclosed with angled parenthesis (**`< >`**) as defined by
        programming syntax. This is optional if URL is unavailable. However,
        Copyright requires at least 1 contactable channel so ensure the
        alternatives are available.
   2. Update/remove the collective alias (e.g. `The [PROJECT] Project Authors`)
      definition clause template.
      * **DO remove it if there is an existing project authors alias from
        upstream**.
      * When re-distributing a font, **MAKE SURE you remove it** such a way that
        we **ARE NOT** the creators.
      * **Update the alias and only use it for downstream communications** if
        this is a new creation project.
   3. There should be **2 EMPTY lines** context separator between the copyright
      entities list and the first line of the first clause.
6. Please **ONLY USE AND SUPPORT** the following open source image editing
   software for securing software supply chain from unwanted threats (e.g.
   vendor-locked by any expensive or proprietary software):
   * **Inkscape (https://inkscape.org)** - for vector graphics maintenances and
     exporting SVG plain vector files.
7. For the thumbnail:
   * All known languages are already tabulated accordingly with their
     ISO3166-Alpha2 (e.g. `ZH`) and/or ISO15924 language scripts (e.g.
     `Hans`/`Hant` for `ZH` or entirely `ZH-Hans`/`ZH-Hant`). The layer is
     an object path called `indicator` which will remain the same after the
     font changes.
   * If the language is unsupported with blank or tofu, leave it. That's the
     whole point of demonstrating the font's capabilities.
   * The languages'/scripts' elements are labelled and ID-ed with full english
     identifier using basic latin characters only for programming purposes.
   * The principal canvas **MUST BE SAVED** in `inkscape SVG format` and retain
     all legal attributes (license, copyright, etc). The files **MUST HAVE**
     `inkscape-` prefixes to avoid confusion. They are saved inside
     `Pictures/principal-canvas` directory.
   * The exported svg **MUST BE IN** `Plain SVG format` and retain all legal
     attributes (license, copright, etc). The files **MUST NOT HAVE**
     `inkscape-` prefixes. They are saved inside `/Pictures` directory.
   * The exported svg's text fields **MUST BE** converted into `path` data type
     and then `union` into a single `foreground` path layer. This is to make
     sure end-user can view the sample without needing to pre-setup the font
     files.
8. For artificial intelligence:
  * **ONLY USE** for internal research or Internet searches internally.
  * **Any automated or "vibe" output commitments are STRICTLY PROHIBITED**.
    * This is a simple artifact re-distribution project. **DO NOT LET ANY** A.I.
      near any of your code and files commitment.
    * If you sign-off any A.I. commitment, **YOU WILL BE HELD FULLY LIABLE FOR
      ALL ITS CONCEQUENCES**.
    * Therefore: **STRICTLY HUMAN COMMITMENT**.
  * **Use of passive A.I. (e.g. image upscaling) is allowed**.




## License

[![banner](/.internals/trademarks/banner_1200x100.svg)](#)

* [Agreed GIMP License](.internals/terms-of-services/GimpORG-License.pdf)
* [Agreed GIMP Privacy Policy](.internals/privacy-policy/GimpORG-Privacy-Policy.pdf)
* [Agreed Inkscape License](.internals/terms-of-services/Inkscape-License.pdf)
* [Agreed Inkscape Privacy Policy](.internals/privacy-policy/Inkscape-Privacy-Policy.pdf)
* [Agreed (Holloway) Chew, Kean Ho's Upscaler License](.internals/terms-of-services/Upscaler-LICENSE.txt)
* [Agreed Perchance.org Terms of Service](.internals/terms-of-services/PerchanceORG-Terms-of-Service.pdf)
* [Agreed Perchance.org Privacy Policy](.internals/privacy-policy/PerchanceORG-Privacy-Policy.pdf)

This entire repository is licensed under [SIL Open Font License](LICENSE.txt).
To ensure better understanding of this license, the following sub-sections will
briefly describe how to deploy the content.

For registered non-profit organizations (NGO), you are considered a
`Commercial Entity` the same as any for-profit organization by default. However,
you will be eligible for the NGO disbursement grant and receive exception
privileges from the creator(s).



### Attribution

Attribution is **OPTIONAL**. Whenever required, you **MUST** attribute back to
the creator(s) as follows:

```
Title: Moongloss Display Font
Creators: The Moongloss Display Project Team
Packaged-By: (Holloway) Chew, Kean Ho
Contact: hello@chewkeanho.com
SKU: chewkeanho-visuals-fonts-moongloss-display
UUID: FD02B07D-62A4-4EBC-917D-BD5DF32F531E
License: SIL Open Font License (http://scripts.sil.org/OFL)
Repository Made On: 2026-04-10
Repository Made From: Malaysia, South East Asia
Procure: https://github.com/ChewKeanHo/visuals-fonts-moongloss-display
```



### Ownership - Personal

> [!NOTE]
>
> This targets any customer wanting to own a copy of the content and then only
> he/she is using it without sharing with any 3rd-party entity; AND **WITHOUT**
> any monetary intention such as but not limited to:
>
> * Saving a local copy and then viewing via his/her own mobile device(s); OR
> * Saving a local copy and then viewing via his/her own personal computer; OR
> * Saving a local copy for artificial intelligence data training purposes.

You are **ALLOWED** provided that you **STRICTLY COMPLY** with the license
requirements of:

1. Retaining the same license downsteam for the font files.



### Ownership - Commercial

> [!NOTE]
>
> This targets any customer wanting to own a copy of the content and then only
> he/she is using it without sharing with any 3rd-party entity; AND **WITH** any
> monetary intention such as but not limited to:
>
> * Saving a local copy for enhancing his/her company's procurement list; OR
> * Saving a local copy for commercial artificial intelligence data training
>   purposes.

You are **ALLOWED** provided that you **STRICTLY COMPLY** with the license
requirements of:

1. Retaining the same license downsteam for the font files; AND
2. Gain **ZERO commercial value of any kind from the font files alone
   (e.g. selling the font files)**.



### Reference - Personal & Commercial

> [!NOTE]
>
> This targets any customer wanting to refer or to provide a guide for sourcing
> the original content for any 3rd-party entity **without directly displaying
> any portion of the original content**; **WITHOUT** any monetary intention such
> as but not limited to:
>
> * Academic research and paper writing; OR
> * New content creation linking to the original content **WITHOUT displaying
>   any of the original content** for his/her own streaming platform; OR
> * Content production and collection linking to original content **WITHOUT
>   displaying any of the original content**; OR
> * Web portfolio project linking to the original content **WITHOUT displaying
>   any of the original content**; OR
> * Event materials linking the original content **WITHOUT displaying any of the
>   original content**; OR
> * Meeting materials linking the original content **WITHOUT displaying any of
>   the original content**; OR
> * Advertisement contents linking the original content **WITHOUT displaying any
>   of the original content**.

You are **ALLOWED** provided that you **STRICTLY COMPLY** with the license
requirements of:

1. Retaining the same license downsteam for the font files; AND
2. Gain **ZERO commercial value of any kind from the font files alone
   (e.g. selling the font files)**.



### Integration - Personal

> [!NOTE]
>
> This targets any customer wanting to directly **display portions and NOT ALL**
> of the original content **as it is OR without any composing remixes or
> modifications retaining the original intent, art direction and messages** into
> his/her content creation; **WITHOUT** any monetary intention such as but not
> limited to:
>
> * New content creation with displaying portion(s) of the original content for
>   his/her own streaming platform **without any monetary gain**; OR
> * Content production and collection with displaying portion(s) of the original
>   content **without any monetary gain**; OR
> * Web portfolio project with displaying portion(s) of the original content
>   **without any monetary gain**; OR
> * Event materials with displaying portion(s) of the original content
>   **without any monetary gain**; OR
> * Meeting materials with displaying portion(s) of the original content
>   **without any monetary gain**.

You are **ALLOWED** provided that you **STRICTLY COMPLY** with the license
requirements of:

1. Retaining the same license downsteam for the font files.



### Integration - Commercial

> [!NOTE]
>
> This targets any customer wanting to directly **display portions and NOT ALL**
> of the original content **as it is OR without any composing remixes or
> modifications retaining the original intent, art direction and messages** into
> his/her content creation; **WITH** any monetary intention such as but not
> limited to:
>
> * New content creation with displaying portion(s) of the original content for
>   his/her own streaming platform; OR
> * Content production and collection with displaying portion(s) of the original
>   content; OR
> * Web portfolio project with displaying portion(s) of the original content; OR
> * Event materials with displaying portion(s) of the original content; OR
> * Meeting materials with displaying portion(s) of the original content; OR
> * Advertisement materials with displaying portion(s) of the original content.

You are **ALLOWED** provided that you **STRICTLY COMPLY** with the license
requirements of:

1. Retaining the same license downsteam for the font files; AND
2. Gain **ZERO commercial value of any kind from the font files alone
   (e.g. selling the font files)**; AND
3. Using the font files for commercial integration (e.g. design works) and
   selling the output (not the font files) for commerical gains.



### Composition Remix - Personal

> [!NOTE]
>
> This targets any customer wanting to own and then **modify the original
> content extensively preserving or altering the original intent, art direction,
> or message** for composing his/her new content creation; **WITHOUT** any
> monetary intention such as but not limited to:
>
> * New content creation with digitally modified and processed original content
>   integration for his/her own streaming platform **WITHOUT** any profits
>   including advertisement commission; OR
> * Personal content production and collection with digitally modified and
>   processed original content integration for his/her own streaming platform
>   **WITHOUT** any profits including advertisement commission; OR
> * Personal web portfolio project with digitally modified and processed
>   original content integration for his/her own streaming platform **WITHOUT**
>   any profits including advertisement commission; OR
> * Social media meme content creation with digitally modified and processed
>   original content integration for his/her own streaming platform **WITHOUT**
>   any profits including advertisement commission.

You are **ALLOWED** provided that you **STRICTLY COMPLY** with the license
requirements of:

1. Retaining the same license downsteam for the font files.



### Composition Remix - Commercial

> [!NOTE]
>
> This targets any customer wanting to own and then **modify the original
> content extensively preserving or altering the original intent, art direction,
> or message** for composing his/her new content creation; **WITH** any monetary
> intention such as but not limited to:
>
> * New content creation with digitally modified and processed original content
>   integration for his/her own streaming platform; OR
> * Personal content production and collection with digitally modified and
>   processed original content integration for his/her own streaming platform;
>   OR
> * Personal web portfolio project with digitally modified and processed
>   original content integration for his/her own streaming platform; OR
> * Social media meme content creation with digitally modified and processed
>   original content integration for his/her own streaming platform.

You are **ALLOWED** provided that you **STRICTLY COMPLY** with the license
requirements of:

1. Retaining the same license downsteam for the font files; AND
2. Gain **ZERO commercial value of any kind from the font files alone
   (e.g. selling the original or modified font files)**; AND
3. Using the font files for commercial integration (e.g. design works) and
   selling the output (not the font files) for commerical gains.



### Broadcast or Resell Redistribution - Personal

> [!NOTE]
>
> This targets any customer wanting to share, to broadcast, to re-distribute,
> to sell, or to re-sell the original, **modified, OR derived** content
> **WITHOUT** any monetary intention such as but not limited to:
>
> * Sharing with family members; OR
> * Streaming the content via any streaming platform with private viewer
>   access; OR
> * Displaying the content in his/her gallery with privately invited guests; OR
> * Displaying the content in private, free entry open spaces like living room;
>   OR
> * Owning a copy of the original content and serving it as downloadable content
>   on a website in a private network (e.g. self-hosted home network); OR
> * Sharing the original content across social media or messaging applications
>   like email or instant messenger.

You are **ALLOWED** provided that you **STRICTLY COMPLY** with the license
requirements of:

1. Retaining the same license downsteam for the font files; AND
2. Gain **ZERO commercial value of any kind from the font files alone
   (e.g. selling the original or modified font files)**.



### Broadcast or Resell Redistribution - Commercial

> [!NOTE]
>
> This targets any customer wanting to share, to broadcast, to re-distribute,
> to sell, or to re-sell the original, **modified, OR derived** content
> **WITH** any monetary intention such as but not limited to:
>
> * Streaming the content via any streaming platform with public or private
>   viewer access; OR
> * Displaying the content in any company's public events with free or payable
>   guest invites; OR
> * Displaying the content in any company's internal/private events with free or
>   payable guest invites; OR
> * Owning a copy of the original content and serving it as free OR payable
>   downloadable content on his/her website in any network (Internet, Intranet,
>   or private networks); OR
> * Sharing the original content across social media or messaging applications
>   like email or instant messenger; OR
> * Distributing the original content via multiple profit-earning streaming
>   platforms.

You are **ALLOWED** provided that you **STRICTLY COMPLY** with the license
requirements of:

1. Retaining the same license downsteam for the font files; AND
2. Gain **ZERO commercial value of any kind from the font files alone
   (e.g. selling the original or modified font files)**.
