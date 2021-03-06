<p align="center">
  <a href="https://github.com/nemecek-filip/DynamicType-ReferenceApp">Dynamic Type</a> &bull;
  <a href="https://github.com/nemecek-filip/EKEventKit.Example">Event Kit</a>  &bull;
  <a href="https://github.com/nemecek-filip/QLPreviewController.Example">Quick Look</a> 	&bull;
  <a href="https://github.com/nemecek-filip/App-ideas">App Ideas</a> &bull;
  <a href="https://github.com/nemecek-filip/KeyboardPreview.iOS">Keyboard Preview</a>
  &bull;
  <b>Modern Collection Views</b>
</p>

----

# Modern Collection Views

My playground for trying stuff with compositional collection view layout and diffable data source.

The goal is to showcase different compositional layouts and how to achieve them. Feel free to use any code you can find and if you have interesting layout idea - open PR!

**Check out my blog** for posts about [Compositional Layout](https://nemecek.be/blog/series/compositional-layout) and [Diffable Data Sources](https://nemecek.be/blog/series/diffable) or any other iOS development [topics](https://nemecek.be/blog/swift-and-ios) :-)

For more about `NSCollectionLayoutGroup` which lets you create layouts as shown below, check out [this post](https://nemecek.be/blog/66/detailed-look-at-the-nscollectionlayoutgroup).

![CL-groups-example](https://nemecek.be/media/images/groups-example.png)


### Included examples

The project currently offers these example screens.

* **List layout** - list created with Compositional Layout (CL) for iOS 13+
* **Simple grid** - grid layout with option to change sizing and see it animate the change (see GIF below)
* **Lazy grid example** - this grid starts with 12 items and when you scroll at the end it "loads" more (see GIF below)
* **Background decoration** - this shows how to add background views to section in CL layout. For example you can use this to create layout similar to inset & grouped TableView
* **System list** - quick example of creating list layout with the API available from iOS 14
* **Jokes list** - this is more an example of Diffable Data Source that is used to display random jokes from an API and also favorited ones that are stored using Core Data. This also shows how to add headers to CL and loading effect. There is also context menu on the items and text-to-speech (because why not?)
* **Badges example** - example showcasing adding badges to collection view cells and their positioning
* **Instagram profile screen** - this practical example shows how to build screen similar to Instagram profile with Compositional Layout and Diffable. You can read more on my [blog](https://nemecek.be/blog/72/building-instagram-profile-screen-with-compositional-layout)


Free free to reach out over at [@nemecek_f](https://twitter.com/nemecek_f) with issues, questions or anything else.

## Resizable grid

![Resizable Grid Example](https://nemecek.be/media/images/CDPResizableGrid.gif)

## Lazy loaded grid - ideal for paging

![Lazy Grid](https://nemecek.be/media/images/CDPLazyGrid.gif)

## Jokes list with loading indicators

![Jokes Loading Shimmer](https://nemecek.be/media/images/jokesLoadingShimmer.gif)

## Badges

![Compositional Layout - supplementary views example](https://nemecek.be/media/images/IMG_39B7EA982A23-1.jpeg)