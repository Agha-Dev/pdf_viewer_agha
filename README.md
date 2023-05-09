[//]: # (![FolioReader logo]&#40;https://raw.githubusercontent.com/FolioReader/FolioReaderKit/assets/folioreader.png&#41;)

[//]: # ()
[//]: # ([![Build Status]&#40;https://api.travis-ci.org/FolioReader/FolioReader-Android.svg?branch=master&#41;]&#40;https://travis-ci.org/FolioReader/FolioReader-Android&#41;)

[//]: # ()
[//]: # (FolioReader-Android is an EPUB reader written in Java and Kotlin.)

[//]: # ()
[//]: # (### Features)

[//]: # ()
[//]: # (- [x] Custom Fonts)

[//]: # (- [x] Custom Text Size)

[//]: # (- [x] Themes / Day mode / Night mode)

[//]: # (- [x] Text Highlighting)

[//]: # (- [x] List / Edit / Delete Highlights)

[//]: # (- [x] Handle Internal and External Links)

[//]: # (- [x] Portrait / Landscape)

[//]: # (- [ ] Reading Time Left / Pages left)

[//]: # (- [x] In-App Dictionary)

[//]: # (- [ ] Media Overlays &#40;Sync text rendering with audio playback&#41;)

[//]: # (- [ ] TTS - Text to Speech Support)

[//]: # (- [ ] Parse epub cover image)

[//]: # (- [ ] PDF support)

[//]: # (- [x] Book Search)

[//]: # (- [x] Add Notes to a Highlight)

[//]: # (- [ ] Better Documentation)

[//]: # (- [x] Last Read Locator)

[//]: # (- [x] Horizontal Reading)

[//]: # (- [x] Distraction Free Reading)

[//]: # ()
[//]: # (## Demo)

[//]: # (##### Custom Fonts)

[//]: # (![Custom fonts]&#40;https://cloud.githubusercontent.com/assets/1277242/19012915/0661c7b2-87e0-11e6-81d6-8c71051e1074.gif&#41;)

[//]: # (##### Day and Night Mode)

[//]: # (![Day night mode]&#40;https://cloud.githubusercontent.com/assets/1277242/19012914/f42059c4-87df-11e6-97f8-29e61a79e8aa.gif&#41;)

[//]: # (##### Text Highlighting)

[//]: # (![Highlight]&#40;https://cloud.githubusercontent.com/assets/1277242/19012904/c2700c3a-87df-11e6-97ed-507765b3ddf0.gif&#41;)

[//]: # (##### Media Overlays)

[//]: # (![Media Overlay]&#40;https://cloud.githubusercontent.com/assets/1277242/19012908/d61f3ce2-87df-11e6-8652-d72b6a1ad9a3.gif&#41;)

[//]: # ()
[//]: # (### Gradle)

[//]: # ()
[//]: # (Add following dependency to your root project `build.gradle` file:)

[//]: # ()
[//]: # (```groovy)

[//]: # (allprojects {)

[//]: # (    repositories {)

[//]: # (        ...)

[//]: # (        jcenter&#40;&#41;)

[//]: # (        maven { url "https://jitpack.io" })

[//]: # (        ...)

[//]: # (    })

[//]: # (})

[//]: # (```)

[//]: # ()
[//]: # (Add following dependency to your app module `build.gradle` file:)

[//]: # ()
[//]: # (```groovy)

[//]: # (dependencies {)

[//]: # (    ...)

[//]: # (    implementation "com.folioreader:folioreader:0.5.4")

[//]: # (    ...)

[//]: # (})

[//]: # (```)

[//]: # ()
[//]: # (### Enable Multidex support)

[//]: # ()
[//]: # (Enable Multidex support as explained in this [Android Doc]&#40;https://developer.android.com/studio/build/multidex&#41;)

[//]: # ()
[//]: # (### Usage)

[//]: # ()
[//]: # (Get singleton object of `FolioReader`:)

[//]: # ()
[//]: # (```java)

[//]: # (FolioReader folioReader = FolioReader.get&#40;&#41;;)

[//]: # (```)

[//]: # ()
[//]: # (Call the function `openBook&#40;&#41;`:)

[//]: # ()
[//]: # (##### opening book from assets -)

[//]: # ()
[//]: # (```java)

[//]: # (folioReader.openBook&#40;"file:///android_asset/TheSilverChair.epub"&#41;;)

[//]: # (```)

[//]: # (##### opening book from raw -)

[//]: # ()
[//]: # (```java)

[//]: # (folioReader.openBook&#40;R.raw.accessible_epub_3&#41;;)

[//]: # (```)

[//]: # ()
[//]: # ()
[//]: # (## WIKI)

[//]: # ()
[//]: # (* [Home]&#40;https://github.com/FolioReader/FolioReader-Android/wiki&#41;)

[//]: # (* [Configuration]&#40;https://github.com/FolioReader/FolioReader-Android/wiki/Configuration&#41;)

[//]: # (    * [Custom Configuration]&#40;https://github.com/FolioReader/FolioReader-Android/wiki/Custom-Configuration&#41;)

[//]: # (* [Highlight]&#40;https://github.com/FolioReader/FolioReader-Android/wiki/Highlight&#41;)

[//]: # (    * [Highlight Action]&#40;https://github.com/FolioReader/FolioReader-Android/wiki/Highlight-Action&#41;)

[//]: # (    * [Highlight Event]&#40;https://github.com/FolioReader/FolioReader-Android/wiki/Highlight-Event&#41;)

[//]: # (    * [Providing External Highlight]&#40;https://github.com/FolioReader/FolioReader-Android/wiki/Providing-External-Highlight&#41;)

[//]: # (* [ReadLocator]&#40;https://github.com/FolioReader/FolioReader-Android/wiki/ReadLocator&#41;)

[//]: # (* [Clean up code]&#40;https://github.com/FolioReader/FolioReader-Android/wiki/Clean-up-code&#41;)

[//]: # ()
[//]: # (## Reporting Issue)

[//]: # ()
[//]: # (See [KNOWN_ISSUES]&#40;https://github.com/FolioReader/FolioReader-Android/blob/master/KNOWN_ISSUES.md&#41; and [CHANGELOG]&#40;https://github.com/FolioReader/FolioReader-Android/blob/master/CHANGELOG.md&#41; first before reporting any issue. <br />)

[//]: # (Please follow [Issue Template]&#40;https://github.com/FolioReader/FolioReader-Android/blob/master/.github/ISSUE_TEMPLATE.md&#41; to report any issue.)

[//]: # ()
[//]: # (## Share your application)

[//]: # (If you are using FolioReader in your application, share your application link in [this issue]&#40;https://github.com/FolioReader/FolioReader-Android/issues/291&#41;)

[//]: # ()
[//]: # (### Credits)

[//]: # (1. <a href="https://github.com/daimajia/AndroidSwipeLayout">SwipeLayout</a>)

[//]: # (2. <a href="https://github.com/readium/r2-streamer-kotlin">r2-streamer-kotlin</a>)

[//]: # (3. <a href="http://developer.pearson.com/apis/dictionaries">Pearson Dictionaries</a>)

[//]: # (4. <a href="https://github.com/timdown/rangy">rangy</a>)

[//]: # ()
[//]: # (### Author)

[//]: # ([**Heberti Almeida**]&#40;https://github.com/hebertialmeida&#41;)

[//]: # ()
[//]: # (- Follow me on **Twitter**: [**@hebertialmeida**]&#40;https://twitter.com/hebertialmeida&#41;)

[//]: # (- Contact me on **LinkedIn**: [**hebertialmeida**]&#40;http://linkedin.com/in/hebertialmeida&#41;)

[//]: # ()
[//]: # ([**CodeToArt Technology**]&#40;https://github.com/codetoart&#41;)

[//]: # ()
[//]: # (- Follow us on **Twitter**: [**@codetoart**]&#40;https://twitter.com/codetoart&#41;)

[//]: # (- Contact us on **Website**: [**codetoart**]&#40;http://www.codetoart.com&#41;)

[//]: # ()
[//]: # (## Donations)

[//]: # ()
[//]: # (**This project needs you!** If you would like to support this project's further development, the creator of this project or the continuous maintenance of this project, **feel free to donate**. Your donation is highly appreciated. Thank you!)

[//]: # ()
[//]: # (**PayPal**)

[//]: # ()
[//]: # ( - [**Donate 5 $**]&#40;https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=hebertialmeida%40gmail%2ecom&lc=US&item_name=FolioReader%20Libraries&amount=5%2e00&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donate_SM%2egif%3aNonHosted&#41;: Thank's for creating this project, here's a tea &#40;or some juice&#41; for you!)

[//]: # ( - [**Donate 10 $**]&#40;https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=hebertialmeida%40gmail%2ecom&lc=US&item_name=FolioReader%20Libraries&amount=10%2e00&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donate_SM%2egif%3aNonHosted&#41;: Wow, I am stunned. Let me take you to the movies!)

[//]: # ( - [**Donate 15 $**]&#40;https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=hebertialmeida%40gmail%2ecom&lc=US&item_name=FolioReader%20Libraries&amount=15%2e00&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donate_SM%2egif%3aNonHosted&#41;: I really appreciate your work, let's grab some lunch! )

[//]: # ( - [**Donate 25 $**]&#40;https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=hebertialmeida%40gmail%2ecom&lc=US&item_name=FolioReader%20Libraries&amount=25%2e00&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donate_SM%2egif%3aNonHosted&#41;: That's some awesome stuff you did right there, dinner is on me!)

[//]: # ( - [**Donate 50 $**]&#40;https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=hebertialmeida%40gmail%2ecom&lc=US&item_name=FolioReader%20Libraries&amount=50%2e00&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donate_SM%2egif%3aNonHosted&#41;: I really really want to support this project, great job!)

[//]: # ( - [**Donate 100 $**]&#40;https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=hebertialmeida%40gmail%2ecom&lc=US&item_name=FolioReader%20Libraries&amount=100%2e00&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donate_SM%2egif%3aNonHosted&#41;: You are the man! This project saved me hours &#40;if not days&#41; of struggle and hard work, simply awesome!)

[//]: # ( - Of course, you can also [**choose what you want to donate**]&#40;https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=hebertialmeida%40gmail%2ecom&lc=US&item_name=FolioReader%20Libraries&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donate_SM%2egif%3aNonHosted&#41;, all donations are awesome!)

[//]: # ()
[//]: # (## License)

[//]: # (FolioReaderKit is available under the BSD license. See the [LICENSE]&#40;https://github.com/FolioReader/FolioReader-Android/blob/master/License.md&#41; file.)

[//]: # ()
