# Scratch & See

This is an Objective-C class that helps create a masking effect similar to a scratch card, when swiping on the screen the user can see an image being revealed as he swipes. This is a cool effect that can be applied for a scratch card action or wiping a glass.<br />


<br />

# Update
- Fixed masking progress calculation

# Sample



The project contains an example, but in general it's really simple.
``` objc
MDScratchImageView *scratchImageView = [[MDScratchImageView alloc] initWithFrame:imageView.frame];
scratchImageView.image = image;
```
That's it!

