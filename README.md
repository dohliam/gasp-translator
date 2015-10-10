# Global-ASP Translator - Translation system for the Global African Storybook Project

The goal of this project is to build an easy-to-use and accessible translation system to automate the process of translating [African Storybook Project](http://africanstorybook.org/) stories into other languages for [Global-ASP](https://global-asp.github.io).

It has deliberately been kept as minimal as possible to allow translators to focus on the translation with as little distraction as possible.

You can visit the live Translator tool [here](https://global-asp.github.io/translator).

## Usage

To begin translating stories, just click on the "Translate!" button at the bottom of the page. This will open up a story from the [African Storybook Project](http://africanstorybook.org/) collection, with empty space on the right for you to enter your translation.

Make sure to enter your name and the language you are translating into at the top of the page. Your work will be released under the same Creative Commons license as the original story, and you will be credited for attribution using the name you select here. You can edit either field at any time, e.g. if you want to change the way you are attributed or translate into a different language.

Within the main translation area of the page, images from each page of the story will appear on the left side accompanied by the original text of that page. On the far right side is a box where you can input your translation. You can hover over the thumbnails to see larger versions of the images.

If you have completed part of a translation but want to move on to another story or close the window, the text you have entered in each box will be saved automatically on your local machine so you can return to it later. Note that it will __NOT__ be submitted until you click on the "Review Submission" button and then finally click on "Submit Translation" to send it to [Global-ASP](https://global-asp.github.io) for inclusion in the project.

When you click on the "Review Submission" button, a new text box will appear at the bottom of the screen containing the entire text of your translation. If there is anything you would like to add or change you can edit the text in the window before submitting. However, please try to avoid changing the layout or markup (e.g., pagebreaks marked by `##`).

Once you are satisfied with your translation, click on the "Submit Translation" button to send it for inclusion in the [Global-ASP](https://global-asp.github.io) project. You can optionally include your email address in the box above the submit button if you would like to be contacted about your translation.

## Navigation

The "Next" and "Previous" buttons can be used to navigate through the available stories in the collection. All work is saved in local storage, so you can feel free to browse the collection for stories you would like to translate, even if you have partly begun another translation.

Click on the "Random Story" button to visit a random story from the collection. There are over 300 stories in the collection, all of different lengths, styles, and subject matter, so browse around until you see something you would be comfortable translating.

## API

The Translator features a simple API that allows you to link directly to individual stories for translation. Just add `?` and the [index number](https://global-asp.github.io/stories/master.html) of the story at the end of the url, for example:

* `https://global-asp.github.io/translator/?0030`: links to translation template for story #0030


## License

The code portion of this project is released under the MIT license (see LICENSE file for details).

The full text of the original ASP stories is derived from the [asp-source repo](https://github.com/global-asp/asp-source). All stories are Creative Commons licensed, either CC-BY or CC-BY-NC. License information is included with each file, and also displayed in gasp-translator during the translation process.

"Next", "previous", and "random" buttons are courtesy of [Material Design Icons](https://github.com/google/material-design-icons) (CC-BY).

[Tacit CSS](https://github.com/yegor256/tacit/) by Yegor Bugayenko is licensed under MIT.

Submissions are handled by [Formspree](http://formspree.io/).
