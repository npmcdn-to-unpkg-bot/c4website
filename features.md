---
layout: page
title: Features
---

<div class="row">
	<div class="col-md-10 col-md-offset-1 text-center">
		<h1 class="headliner">Welcome to C4</h1>
		<h2>Built on top of Swift, C4 puts the power of UIKit and Core Animation at your disposal, allowing you to create inventive digital interactions with far less time and effort. Plus, you get all the interactivity, fun and expressiveness of Swift. Your apps will run lightning-fast.</h2>
		<h2>The API of C4 is simple and streamlined allowing beginners to get into programming very easily. For seasoned developers, C4 can be dropped into any existing project with as little effort as linking any other native framework . With C4, you’ll save a ton of time working with interactions, animation and media.</h2>
	</div>
</div>

<div class="row">
	<div class="col-md-10 col-md-offset-1 text-center">
		<h2>Efficient</h2>
		<p>Spend less time navigating between different frameworks and focus on bringing your ideas to life. C4 combines the power of UIKit and Core Animation into a single set of objects whose APIs are easy to understand and straightforward. And because C4's foundation is built on native frameworks, you’ll be inheriting Swift’s faster code, compile times and optimization for modern hardware.</p>
	</div>
</div>

<div class="row">
	<div class="col-md-10 col-md-offset-1">
		<h3 class="text-center">Expressive</h3>
		<p class="text-center">C4 brings your ideas to life by allowing you to focus on experimenting, designing, visualizing and building rather than on learning low-level technologies. Objects are consistent and intuitive — they all essentially work the same way .  C4's language has been designed to be as simple and expressive as possible.</p>
		<p class="text-center">For example, C4 compresses the access of properties:</p>
	
		<div class="row">
			<div class="col-md-6">
        <h4>C4</h4>
{% highlight swift %}
let m = movie.width 
{% endhighlight %}
            </div>
            
            <div class="col-md-6">
            <h4>UIKit</h4>
{% highlight swift %}
let m = movie.frame.size.width
{% endhighlight %}
          </div>
        </div>
        <div class="row">
          <div class="col-md-12">
            <p class="text-center">Animating both view and property changes in C4 is much cleaner, and looks like this:</p>
            <div class="row">
              <div class="col-md-6">
                <h4>C4</h4> 
{% highlight swift %}
ViewAnimation(duration: 0.5) {
  shape.center = self.canvas.center
  shape.lineWidth = 5
}.animate()
{% endhighlight %}
              </div>
              <div class="col-md-6">
                <h4>UIKit + Core Animation</h4>
{% highlight swift %}
UIView.animateWithDuration(0.5) {
    v.center = self.view.center
}

CATransaction.begin()
CATransaction.setValue(NSNumber(float: 0.5), forKey: kCATransactionAnimationDuration)
if let shapeLayer = v.layer as? CAShapeLayer {
    shapeLayer.lineWidth = 5
}
CATransaction.commit()
{% endhighlight %}
              </div>
            </div>
            <div class="row">
              <div class="col-md-10 col-md-offset-1">
                <p class="text-center">C4 takes advantage of all of Swift’s modernity: closures, tuples, generics, interaction, structs, error handling. And, YES, you can even do this:</p>
              </div>
            </div>
            <div class="row">
            <div class="col-md-12">
{% highlight swift %}
let bananaName = "Jimmy".banana
{% endhighlight %}
                <p class="text-center">Check the <a href="https://developer.apple.com/swift/">Swift Overview</a> for more.</p>
              </div>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-md-10 col-md-offset-1 text-center">
            <h3>Easy To Learn</h3>
            <p>Through both its simplified API and consistent objects, C4 is incredibly easy to learn compared to the frameworks it’s built upon: UIKit, Core Animation, etc. C4’s language has been designed to make it easy for both novice and experienced programmers to pick up and use right away.</p>
            <h3>Well Supported</h3>
            <p>The C4 team has always been highly committed to publishing excellent documentation, examples and tutorials for learning how to program with C4.</p>
            <p>The current release of C4 also includes a full end-to-end tutorial that will walk you through the design, creation and publication of a full-blown app: COSMOS</p>
            <div class="row">
              <div class="col-md-6">
                <a href="https://itunes.apple.com/us/app/c4smos/id985883701?ls=1&mt=8"><img src="images/index/about-app.png" /></a>
                <p><a href="https://itunes.apple.com/us/app/c4smos/id985883701?ls=1&mt=8">Get COSMOS from the App Store</a></p>
              </div>
              <div class="col-md-6">
                <a href="cosmos"><img src="images/index/about-cosmos.png" /></a>
                <p><a href="cosmos">Build COSMOS from start to finish</a></p>
              </div>
            </div>
            <p>We’re currently converting over 200 code examples and 30 tutorials to C4's new modern syntax. These examples and tutorials (coming soon) guide new users through core concepts and provide seasoned developers with the reference they need to keep up the pace.</p>
          </div>
        </div>
        <div class="row">
          <div class="col-md-10 col-md-offset-1 text-center">
            <h3>Powerful</h3>
            <p>Originally based on Objective-C, C4 now takes entire advantage of the Swift programming language — which itself was built to be fast and powerful. Where Swift has been tuned to make intuitive, natural coding perform best, the guts of each component in C4 — every class, every method and every structure –  make that performance sing.</p>
            <p>Through C4 you are able to work with media, animations and interactions in a way that dissolves the differences between the many frameworks you need to create beautiful user experiences. It seamlessly combines many important components of UIKit, Core Animation, Core Graphics, AVFoundation and QuartzCore.</p>
          </div>
        </div>
        <div class="row text-center">
          <div class="col-md-10 col-md-offset-1">
            <h3>Multipurpose</h3>
            <p>C4 is built for anyone who wants to build beautiful user experiences for iOS and has been designed to reach an incredibly broad set of possible uses. This flexibility is one of the most important aspects of C4, demonstrating its strength across a variety of different use cases and disciplines.</p>
            <p>C4 has been used for:
              <ul class="about text-center list-unstyled">
                <li>Prototyping</li>
                <li>Mobile Applications</li>
                <li>Data Visualization</li>
                <li>Interactive Artworks</li>
                <li>Computational Design Education</li>
                <li>Communication Design</li>
                <li>Print Design</li>
              </ul>
            </p>
          </div>
        </div>
        <div class="row text-center">
          <div class="col-md-10 col-md-offset-1">
            <h3>Open Source</h3>
            <p>Sporting the MIT License, C4 is an open-source project whose features and functions can be used freely in educational, artistic and even professional settings. The project is open to anyone who wants to contribute, and the project’s <a href="https://github.com/c4labs/c4ios/">code</a>, <a href="https://github.com/c4labs/c4ios/">documentation</a>, and <a href="https://github.com/c4labs/C4iOS/wiki">process</a> are completely available for you to read through, learn from and take advantage of. Ongoing commitment by our core team and other developers guarantees that C4 will be constantly updated and focused on user’s interests.</p>
            <a href="https://join-c4.herokuapp.com/"><img src="images/index/about-slack.png" /></a>
            <p><a href="https://join-c4.herokuapp.com/">Join our Slack community!</a></p>
          </div>
        </div>
        <div class="row">
          <div class="col-md-10 col-md-offset-1">
            <h3 class="text-center">Simplicity</h3>
            <p class="text-center">Simplicity is a major accomplishment for C4. Across the board, C4 is simple to learn, to use, to read and to adopt. C4 reduces the amount of code you need to the most powerful essentials. </p>
            <p class="text-center">Take movies, for example. Instead of needing to AVQueuePlayer, AVPlayerItem, navigating asset tracks and learning how to load files through NSBundle, you only have to create a movie from its file name and add it to the canvas:</p>
          
          <div class="row">
            <div class="col-md-6">
            <h4>C4</h4>
{% highlight swift %}
func setup() {
  let movie = Movie("halo.mp4")
  canvas.add(movie)
  movie?.play()
}
{% endhighlight %}
          </div>
          <div class="col-md-6">
            <h4>UIKit + AVFoundation</h4>
{% highlight swift %}
func viewDidLoad() {
  guard let url = NSBundle.mainBundle().URLForResource("halo.mp4", withExtension: nil) else {
      fatalError("File not found")
  }

  let asset = AVAsset(URL: url)
  let player = AVQueuePlayer(playerItem: AVPlayerItem(asset: asset))
  player.actionAtItemEnd = .Pause

  let movieLayer = AVPlayerLayer(player: player)
  movieLayer.videoGravity = AVLayerVideoGravityResize

  let tracks = asset.tracksWithMediaType(AVMediaTypeVideo)

  let movieTrack = tracks[0]
  let size = movieTrack.naturalSize

  movieLayer.frame = CGRect(x: 0,y: 0,width: size.width,height: size.height)
  self.view.layer.addSublayer(movieLayer)
  player.play()
}
{% endhighlight %}
           </div>
          </div>
          <div class="docs">
            <p class="text-center">… And a <a href="http://cocoadocs.org/docsets/C4/1.1.0/">whole lot more</a>.</p>
          </div>
        </div>
      </div>
    </div>
  </div>